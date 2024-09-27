---
title: "Mastering the Nohup Command: A Comprehensive Guide for Continuous Processes on Linux"
date: 2024-08-30T13:33:34.925Z
updated: 2024-08-31T13:33:34.925Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/446c2c83401a2bf43df1ddd12db668c5d64cb21efbb35cbfda2026996e2400a4.jpg
---

## Mastering the Nohup Command: A Comprehensive Guide for Continuous Processes on Linux

### Quick Links

* [HUP and SIGHUP](https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-realme-c51-drfone-by-drfone-virtual-android/)
* [The nohup Command](https://smart-video-editing.techidaily.com/new-unleash-your-creativity-top-free-video-editing-software-for-32-bit-windows-for-2024/)
* [Using nohup](https://video-capture.techidaily.com/in-2024-best-free-desktop-recorders/)

 The Linux `nohup` command lets important processes carry on running even when the terminal window that launched them is closed. We show you how to use this venerable command on today's Linux.

##  HUP and SIGHUP

[Unix](https://vimeo-videos.techidaily.com/2024-approved-elevate-your-visuals-music-integration-for-vimeo-films/), the ancestor of Linux, was created before the PC was invented. Computers were large, expensive pieces of equipment. People interacted with them over serial lines either locally within the same building or remotely over slow modem connections. Originally, they typed their instructions on [teleprinters that were gradually replaced by dumb terminals](https://video-screen-grab.techidaily.com/in-2024-how-to-record-perfect-videos-in-total-quietude/).

 They were called dumb because the processing power was in the computer you were connected to, not the terminal you were typing on. The programs were running on the computer---where ever that may have been located---and not on the device on your desk.

 If something happened that broke the connection between your terminal and the computer, the computer detected the line drop and sent a `HUP `or hang up signal to the programs you'd been running. The programs ceased execution when they received the signal.

 That functionality lives on in Linux today. On your PC, a [terminal window](https://facebook-clips.techidaily.com/downloading-facebook-gifs-pc-android-and-ios-guide/) is an emulation of a physical terminal. If you have processes running that were launched from that terminal window and you close that window the SIGHUP

 signal is sent to the programs so that they're informed of the HUP and know they should [terminate](https://games-able.techidaily.com/the-perfect-gloss-a-ps5-sanitation-guide/).

 There's a cascade effect that takes place. If the processes have launched any child processes the SIGHUP is passed down the line to them too so that they know they ought to terminate.

 The `nohup` command launches child processes but refuses to pass SIGHUP signals to them. That might sound like a problem, but it's actually a useful function.

##  The nohup Command

 If you want to have a process continue even if the terminal window it was launched from is closed, you need a way to intercept the SIGHUP so that the program never receives it. (Actually, the terminal window doesn't launch processes, they're launched by the shell session inside the terminal window.) The simple and elegant solution to that problem is to place another process between the shell session and the program, and have that middle-layer program never pass on the SIGHUP signal.

 That's what `nohup` does. It launches programs for you so that they are a child process of `nohup`, not a child process of the shell. Because they're not a child process of the shell, they won't directly receive a SIGHUP from the shell. And if `nohup` doesn't pass on the SIGHUP to its children, the program won't receive SIGHUP at all.

 This is useful when, for example, you have a long-running process that you need to let run to completion. If you accidentally close the terminal window and its shell, you'll terminate the process too. Using `nohup` to launch the process isolates the process from the `nohup` signal. If you're working remotely on a computer [over SSH](https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-vivo-y78t-drfone-by-drfone-fix-android-problems-fix-android-problems/) and you don't want a sensitive process to terminate if the remote connection fails, you'd start the process on the remote computer with `nohup` .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Using nohup

 We created a program that doesn't do anything useful, but it will run and run until it is terminated. It prints the time to the terminal window every three seconds. It's called long-proc for "long process."

./long-proc

![The long-proc program running a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/1-2.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
 If this was a program that did something useful and we wanted it to continue to run even if the terminal window and shell are closed, we'd launch it with `nohup`.

nohup ./long-proc

![launching the the long-proc program from nohup](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/2-3.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
 The process is decoupled from `stdin` and `stdout` so it can neither receive any input nor write to the terminal window. Also, because it is still running, you're not returned to the command prompt. All that `nohup` does is make the process impervious to the terminal closing down. It doesn't [turn the process into a background task](https://buynow-help.techidaily.com/compact-wonder-the-theta-sc2s-portable-vr-journey/).

 Do you now have to [reboot](https://data-wizards.techidaily.com/formatting-your-macs-storage-simplified-an-instructional-video/) just to terminate the process? No. To stop a `nohup` process you haven't launched as a background process, hit the Ctrl+C key combination.

![Halting the long-proc process with Ctrl+C](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/3-2.png) 

 The output from the program has been captured for us in a file called "nohup.out." We can review it with less.

less nohup.out

![Opening the nohup.out file in less](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/4-2.png) 

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
 Anything that would usually be sent to the terminal window is captured in the file. Subsequent runs of `nohup` will be appended to the existing "nohup.out" file.

![The output from long-proc written tot he nohup.out file, displayed in less](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/5-2.png) 

 A more useful way to run the process is to launch it with `nohup` so that it withstands the terminal window being closed, and to make it a [background task](https://buynow-help.techidaily.com/compact-wonder-the-theta-sc2s-portable-vr-journey/) at the same time. To do this we add an ampersand "`&`" to the end of the command line.

nohup ./long-proc &

![luanching the long-proc program with nohup and making it a background task](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/6-2.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You'll need to hit "Enter" once more to return to command prompt. We're told the job number of the process is 1---the number in brackets "`[]`"--- and that the process ID is 13115.

 We can use either of these to terminate the process. "Ctrl+C" won't work now because the program doesn't have any association with either the terminal window or the shell.

 If you forget what the job number is, you can use the `jobs` command to list the background tasks that have been launched from that terminal window.

jobs

![Listing the background tasks that have ben launched from a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/7-2.png) 

 To kill our task we can use the `kill` command and the job number, preceded by a percentage sign "`%`", like this:

kill %1

 If you've closed the terminal window you'll need to find the process ID and use that with the `kill` command. The `pgrep` command will find the process ID for processes that match the search clue you provide. We'll search for the process name.

pgrep long-proc

![Finding the process ID of a process by name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/8-2.png) 

 Now we can use the process ID to terminate the process.

kill 13115

![Using the kill command and process ID to terminate a process](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/9-2.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
 The next time you hit "Enter" you're informed that the process has been terminated.

 Now let's look at what doesn't terminate the process. We'll relaunch it, and then close the terminal window.

nohup ./long-proc

![Closing the terminal window with a process running](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/10-2.png) 

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
 If we open a new terminal window and search for our process with `pgrep`, we see it is still running. Closing the terminal window that launched the process has had no effect.

pgrep long-proc

![Using pgrep to search for a process by name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/11-2.png) 

 It is possible to pass multiple commands to `nohup`, but it is usually better to launch them separately. It makes it easier to manipulate them as background jobs. The commands won't run at the same time, they'll be executed one after the other. The execution is not concurrent, it's sequential. To have them run concurrently you need to launch them separately.

 Having said that, to [launch several processes at once](https://fox-http.techidaily.com/in-2024-nikon-d500-review-breaking-boundaries-in-4k/), use `nohup` to launch a Bash shell and use the `-c` (commands) option with the string of commands. Use single quote marks "`'`" to wrap the command list and double ampersands "`&&`" to separate the commands.

nohup bash -c 'ls /bin && ls /sbin'

![Launching two process with nohup](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/12-1.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
 If you [use less](https://win-amazing.techidaily.com/hp-scanjet-driver-updates-available-install-now-for-enhanced-performance-on-windows-systems/) to look through the "nohup.out" file, you'll see the output from the first process, then the output from the second process.

less nohup.out

![Opening the nohup.out file in less](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/13-1.png) 

 The output from both commands has been captured in the "nohup.out" file. It is not intertwined, the output from the second process only starts once the first process has terminated.

![The contents of the nohup.out file in less](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/14-1.png) 

 If you want to use a file of your own instead of "nohup.out", you can [redirect the command](https://location-social.techidaily.com/in-2024-how-to-change-your-gionee-f3-pro-location-on-twitter-drfone-by-drfone-virtual-android/) into the file of your choice.

nohup bash -c 'ls /bin && ls /sbin' > myfile.txt

![redirecting the output from the processes to a user-provided file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/15-1.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
 Note that the message no longer says "appending output to nohupo.out", it says "redirecting stderr to stdout" and we're redirecting stdout to our "myfile.txt" file.

 We can look inside "myfile.txt" file with less.

less myfile.txt

![Opening the myfile.txt file in less](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/16-1.png) 

 As before, it contains the output from both commands.

![The output of the commands captured in the user-specified file myfile.txt in less](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/17.png) 

---

 It's funny how the history of a utility can sometimes make it seem as though it had no relevance to modern times. The `nohup` [command](https://buynow-help.techidaily.com/misinterpretation-of-gram-staining-results-can-lead-to-incorrect-identification-affecting-treatment-decisions-in-clinical-settings/) is one of those. Something that was created to cope with disconnects on serial lines is still useful to today's Linux users on incredibly powerful machines.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>


