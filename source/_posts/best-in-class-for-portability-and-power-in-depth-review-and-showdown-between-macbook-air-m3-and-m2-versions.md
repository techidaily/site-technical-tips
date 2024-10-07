---
title: "Best in Class for Portability & Power: In-Depth Review and Showdown Between MacBook Air M3 & M2 Versions"
date: 2024-09-30T20:13:18.027Z
updated: 2024-10-07T17:03:57.696Z
tags:
  - apple
categories:
  - tech
thumbnail: https://thmb.techidaily.com/0c4fe2df3501ab3d12aff4159eef3a635fdab95893a75ab576300b01cddc62fb.jpg
---

## Discover How to Effortlessly Install and Switch Between Ubuntu & macOS with an Unusual Trick !

![xcode-download](https://www.zdnet.com/a/img/resize/72daf9c10a8cbb72018f54fd48d893e5c1fdc697/2024/02/20/72eff26e-8b49-4c53-8f95-e123371d2227/xcode-download.jpg?auto=webp&width=1280)

Screenshot by David Gewirtz/ZDNET

So, you want to install Linux on a Mac? Well, there's more than one way to get that done. Compared to what I'm going to show you below, there's a somewhat easier set of steps that my colleague [Adrian Kingsley-Hughes ran through](https://www.zdnet.com/article/how-to-install-kali-linux-on-apple-silicon-macs/) using an installer on the App Store and Kali Linux.

**Also: [How to install Ubuntu Linux (It's easy!)](https://www.zdnet.com/article/how-to-install-ubuntu-linux/)**

But I'm going full geek. Together, we're going to use Xcode and build our own sample app, which we'll then use to install the full distribution of the [latest Ubuntu release](https://www.zdnet.com/article/ubuntu-desktop-23-10-arrives-a-glimpse-into-ubuntu-linuxs-future/), Noble Numbat.

Once you've done this, you will have considerable bragging rights. There's a lot to cover, so let's dig in. 

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

##  Download these first

You'll need to download these items before you get started setting up Linux: 

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

**Xcode:** You will need to download and install Xcode from the Mac App Store. Xcode is the primary development environment Apple wants developers to use to build Mac applications and mobile apps. It's free. Just open the App Store app and type "xcode" into the search field.

**The latest build of Ubuntu, for 64-bit Arm:** The Arm installer ISO isn't located on the main Ubuntu download site. Instead, point your browser to the [daily build page](https://cdimage.ubuntu.com/daily-live/current/) and scroll down until you see the desktop image for 64-bit ARM (standard download).

Screenshot by David Gewirtz/ZDNET

**GUILinuxVirtualMachineSampleApp:** [This is a sample app](https://developer.apple.com/documentation/virtualization/running%5Fgui%5Flinux%5Fin%5Fa%5Fvirtual%5Fmachine%5Fon%5Fa%5Fmac) that runs the virtual machine inside of Xcode. You'll need to download it and unzip it. 

Screenshot by David Gewirtz/ZDNET

Before you move on to the next step, be sure that Xcode is fully installed, that you have the Ubuntu .iso file, and that you have downloaded and unzipped the sample app. 

**Also: [Ubuntu Desktop 23.10 arrives: A glimpse into Ubuntu Linux's future](https://www.zdnet.com/article/ubuntu-desktop-23-10-arrives-a-glimpse-into-ubuntu-linuxs-future/)**

Once all of that is done, we can move on. 

<!-- affiliate ads begin -->
<span id="1492813">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1492813.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1492813">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1492813.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1492813%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1492813/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Configure the VM hosting app in Xcode

Go ahead and open Xcode. You'll see a starter screen. Tell it to open up an existing project. 

Screenshot by David Gewirtz/ZDNET

From here, navigate inside the folder you created when you extracted the sample application, and look for a file ending in .xcodeproj. Click open. 

Screenshot by David Gewirtz/ZDNET

This will open the sample application. Well, actually, it will warn you that you're opening a project downloaded from the Internet. But since the project comes right off the Apple developer site, I think you're good. 

Screenshot by David Gewirtz/ZDNET

Now, you'll have the project open. You need to do a bit of housekeeping, and then you'll be good. 

In the left-most pane, click the top-level sample app (shown at 1). Then, click the Signing & Capabilities tab (shown at 2), and finally, click the Add Account button at the Team prompt (shown at 3). 

Screenshot by David Gewirtz/ZDNET

This will take you to your Accounts tab, where you'll just set yourself up as a team. 

Screenshot by David Gewirtz/ZDNET

Once you've done this, close the window, and you'll be ready to move on. Here, you can see my app is going to be signed by my personal account. This just tells MacOS that it's my app and I want to allow it to run.

Screenshot by David Gewirtz/ZDNET

You're ready to start running the VM. Hit the little arrow to build and run. 

Screenshot by David Gewirtz/ZDNET

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136618/26400" target="_top" id="2136618">
  <img src="//a.impactradius-go.com/display-ad/26400-2136618" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136618/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Installing Ubuntu

Your Xcode app will open a blank black window and a file chooser. The file chooser (although it doesn't tell you this) is looking for the Ubuntu install .iso file. So navigate to that .iso, click it, and click Open. 

Screenshot by David Gewirtz/ZDNET

Next, GRUB (Grand Unified Bootloader) will show up in that black window. Select Try or Install Ubuntu and hit Enter. 

Screenshot by David Gewirtz/ZDNET

And let the magic commence! Ubuntu is getting settled into your Xcode app: 

Screenshot by David Gewirtz/ZDNET

And here you go. Start configuring your Ubuntu install. 

Screenshot by David Gewirtz/ZDNET

Go ahead and select Install Ubuntu since you're already installing into a VM and not directly onto your computer anyway. 

Screenshot by David Gewirtz/ZDNET

I did the full installation: 

Screenshot by David Gewirtz/ZDNET

**Also: [Fedora Linux now runs on all M-powered Macs - except one](https://www.zdnet.com/article/fedora-linux-now-runs-on-all-m-powered-macs-except-one/)**

Use the default, which is to allow the installer to erase the virtual disk and set up your virtual filesystem: 

Screenshot by David Gewirtz/ZDNET

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134497/18498" target="_top" id="2134497">
  <img src="//a.impactradius-go.com/display-ad/18498-2134497" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134497/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Run Ubuntu

Ubuntu is ready to run. Just click Restart Now and go to town. 

Screenshot by David Gewirtz/ZDNET

Once you restart, you'll be in a standard environment, with a nice little virtual machine you can play with. 

Screenshot by David Gewirtz/ZDNET

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938721/19272" target="_top" id="1938721">
  <img src="//a.impactradius-go.com/display-ad/19272-1938721" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938721/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Final thoughts

During the installation phase, the Virtualization framework generates a GUI Linux VM.bundle package within your home folder. This grows fairly quickly, so if you're space-constrained, you may want to delete it when you're done Ubuntuing. Mine is 68.72GB after only a few hours of tinkering. 

**Also: [Ubuntu 23.10 seems like the usual boring update - until you dig into it](https://www.zdnet.com/article/ubuntu-23-10-seems-like-the-usual-boring-update-until-you-dig-in/)**

While the example application is limited to operating a single VM concurrently, the MacOS virtualization framework itself is capable of handling several VMs at the same time. This is not controlled by the application we built, but developers can use this framework to build more powerful virtualization management consoles. 

What do you think? Did you go ahead and install Ubuntu inside Xcode? Are you going to tattoo "Ubuntu/Xcode Forever" on your shoulder? Are you going to sing glorious songs of your Xcode prowess to all who will listen? I mean, you could. If you're not going to belt out songs of Macs and Linux, perhaps you could leave us a few comments below. 

---

_You can follow my day-to-day project updates on social media. Be sure to subscribe to my weekly update newsletter [on Substack](https://advancedgeekery.substack.com/), and follow me on Twitter at [@DavidGewirtz](https://twitter.com/davidgewirtz), on Facebook at [Facebook.com/DavidGewirtz](https://www.facebook.com/davidgewirtz), on Instagram at [Instagram.com/DavidGewirtz](https://www.instagram.com/DavidGewirtz/), and on YouTube at [YouTube.com/DavidGewirtzTV](https://www.youtube.com/user/DavidGewirtzTV)._

#### Linux

[The best Linux laptops for consumers and developers](https://www.zdnet.com/article/best-linux-laptop/ "The best Linux laptops for consumers and developers")

[Want to save your aging computer? Try these 5 Linux distributions](https://www.zdnet.com/article/want-to-save-your-old-computer-try-these-5-linux-distributions/ "Want to save your aging computer? Try these 5 Linux distributions")

[The best distros for beginners](https://www.zdnet.com/article/best-linux-desktops-for-beginners/ "The best distros for beginners")

[How to enable Linux on your Chromebook (and why you should)](https://www.zdnet.com/article/how-to-enable-linux-on-your-chromebook-and-why-you-should/ "How to enable Linux on your Chromebook (and why you should)")

* [The best Linux laptops for consumers and developers](https://www.zdnet.com/article/best-linux-laptop/ "The best Linux laptops for consumers and developers")
* [Want to save your aging computer? Try these 5 Linux distributions](https://www.zdnet.com/article/want-to-save-your-old-computer-try-these-5-linux-distributions/ "Want to save your aging computer? Try these 5 Linux distributions")
* [The best distros for beginners](https://www.zdnet.com/article/best-linux-desktops-for-beginners/ "The best distros for beginners")
* [How to enable Linux on your Chromebook (and why you should)](https://www.zdnet.com/article/how-to-enable-linux-on-your-chromebook-and-why-you-should/ "How to enable Linux on your Chromebook (and why you should)")

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/024-approved-compiling-chords-and-crafting-a-unique-youtube-playlist/"><u>[New] 2024 Approved Compiling Chords and Crafting a Unique YouTube Playlist</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-groundbreaking-biodegradable-film-technology-advice/"><u>[New] 2024 Approved Groundbreaking Biodegradable Film Technology Advice</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-vimeos-revenue-revolution-strategies-for-successful-advertising-earning/"><u>[New] 2024 Approved Vimeo's Revenue Revolution Strategies for Successful Advertising Earning</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-renderer-resurgence-new-radeon-edition/"><u>[Updated] 2024 Approved Renderer Resurgence New Radeon Edition</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/best-acer-predator-orion-5000-laptop-review-top-value-and-high-end-specs/"><u>Best Acer Predator Orion 5000 Laptop Review: Top Value and High-End Specs</u></a></li>
<li><a href="https://technical-tips.techidaily.com/connecting-and-utilizing-external-storage-with-your-xbox-one-a-step-by-step-guide/"><u>Connecting and Utilizing External Storage with Your Xbox One: A Step-by-Step Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/cost-effective-starter-packs-for-aspiring-home-movie-buffs/"><u>Cost-Effective Starter Packs for Aspiring Home Movie Buffs</u></a></li>
<li><a href="https://technical-tips.techidaily.com/detailed-analysis-of-the-line-messaging-app/"><u>Detailed Analysis of the Line Messaging App</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-ultimate-selection-the-5-star-workout-logging-tools-of-2024/"><u>Discover the Ultimate Selection: The 5 Star Workout Logging Tools of 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/easy-guide-downloading-your-favorite-shows-from-netflix-onto-your-laptop/"><u>Easy Guide: Downloading Your Favorite Shows From Netflix Onto Your Laptop</u></a></li>
<li><a href="https://technical-tips.techidaily.com/guide-integrating-pinterest-features-into-your-facebook-business-profile/"><u>Guide: Integrating Pinterest Features Into Your Facebook Business Profile</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-2-ways-to-transfer-text-messages-from-motorola-edge-40-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 2 Ways to Transfer Text Messages from Motorola Edge 40 to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-lock-on-iphone-11-pro-max-by-drfone-ios/"><u>In 2024, How to Bypass iCloud Lock on iPhone 11 Pro Max</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-sharefake-gps-on-uber-for-vivo-x100-drfone-by-drfone-virtual-android/"><u>In 2024, How to share/fake gps on Uber for Vivo X100 | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-planning-to-use-a-pokemon-go-joystick-on-vivo-s17-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Planning to Use a Pokemon Go Joystick on Vivo S17 Pro? | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-live-activities-in-ios-16-a-comprehensive-guide/"><u>Mastering Live Activities in iOS 16: A Comprehensive Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-made-simple-resolving-issues-with-your-iphone-remote-control-feature/"><u>Troubleshooting Made Simple: Resolving Issues with Your iPhone Remote Control Feature</u></a></li>
</ul></div>

