---
title: Installing and Utilizing the Yay Tool in Arch Linux – A Comprehensive Tutorial
date: 2024-12-20T19:25:43.196Z
updated: 2024-12-26T01:05:37.137Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/hero-1.png
---

## Installing and Utilizing the Yay Tool in Arch Linux – A Comprehensive Tutorial

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [Arch Linux, the Bare-Bones Distro](https://facebook-video-content.techidaily.com/updated-2024-approved-what-to-do-when-you-spot-your-own-face-during-a-call/)
* [The AUR and Why You Need It](https://some-knowledge.techidaily.com/2024-approved-innovative-images-aesthetic-pc-backgrounds/)
* [Checking the Requirements](https://screen-sharing-recording.techidaily.com/the-ultimate-exploration-of-apeaksofts-screen-recorder-for-2024/)
* [Building Yay on Arch Linux](https://article-tips.techidaily.com/drone-motor-choose-the-5-best-motors-for-your-quadcopter/)
* [Using Yay to Install and Uninstall Software](https://desktop-recording.techidaily.com/updated-enjoy-your-old-favorites-top-5-ps1-game-simulators-on-pc-for-2024/)
* [Accessing the Arch User Repository With Yay](https://android-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-samsung-galaxy-a14-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/)

### Key Takeaways

* Arch Linux is a bare-bones distribution, and installing applications is done manually using the package manager, pacman.
* The Arch User Repository (AUR) is a comprehensive collection of Linux software that can be accessed with the help of tools like Yay.
* Surprisingly, Yay is not installed by default in Arch Linux. You can manually install it to easily search, install, and uninstall applications from the AUR. To install Yay, you need to clone its source code repository and build it. Note that you'll need Git and the standard development tools installed to do that.
* To install software with Yay, use "yay package-name." To uninstall software with Yay, use "yay -R package-name."

 Arch Linux's yay command makes using the Arch User Repository very simple. But sadly, Yay isn’t installed by default. We show you how to install and use this must-have Arch Linux tool.

##  Arch Linux, the Bare-Bones Distro

[Arch Linux](https://archlinux.org/) is a widely known and highly regarded Linux distribution. Arch Linux is a strictly bare-bones distribution. Unlike most distros, it doesn’t come preloaded with a collection of typical applications. When you install Arch Linux, you’re installing a minimalist take on Linux. Once you’ve got Arch running on your computer, it's up to you to install any applications you want to use.

 That’s a great way to set your computer up because there’s absolutely no bloatware. The only applications installed are the ones you’ve considered and decided you want. And that bare-bones philosophy is taken seriously. You don’t even get a graphical desktop environment. If you want one, you install it yourself, using the Arch Linux package manager, pacman.

 That’s all fine in theory, but here’s the conundrum. There’s a massive software repository of additional applications that you can select from, called the Arch User Repository, but pacman doesn’t know about it. It can neither search through it nor download anything from it.

##  The AUR and Why You Need It

 The AUR is one of the [largest and most comprehensive collections of Linux software](https://unlock-android.techidaily.com/in-2024-the-ultimate-guide-to-xiaomi-redmi-k70-pro-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/) available anywhere. It’s a community-driven resource, hosting over 85,000 software packages. Or at least, it hosts something called package build files, or PKGBUILDs.

 A PKGBUILD is a shell script that the Arch Linux makepkg tool can read. makepkg follows the instructions in the PKGBUILD file to create the application on your computer. It does this by downloading the appropriate source code to your computer, compiling it, and creating an archive file containing the newly compiled application. It then calls on pacman to install the application from the archive file.

 The AUR is a wonderful resource if you use it with care. You don’t need an AUR helper to use the AUR. There’s a fairly straightforward but long-winded manual process you can use to install software from the AUR. But if you’re installing a lot of applications, you’ll soon want a way to streamline that process. That’s why tools like Yay were developed.

 The trouble is, Yay isn’t included in a standard Arch Linux installation, you need to install it. But pacman can’t do that for you, because Yay is in the AUR and pacman only works with the standard repositories. We can circumvent this [catch-22](https://en.wikipedia.org/wiki/Catch-22%5F%28logic%29) by installing Yay manually.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Checking the Requirements

 Because we’re going to be compiling code, we need to have the standard set of development packages installed, and we’re also going to use [Git to retrieve the source code](https://android-transfer.techidaily.com/in-2024-tips-of-transferring-messages-from-htc-u23-pro-to-iphone-1415-drfone-by-drfone-transfer-from-android-transfer-from-android/) files, so that has to be installed too.

 It only takes a moment to check whether these packages are present.

        `gcc --version  
git --version`
    
![Checking whether the development tools and Git are installed on Arch Linux](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-10.png) 

 If you get an error message instead of a version number, that package isn’t installed. If you need to, you can install the development files with this command:

        `sudo pacman -S base-devel`
    
 If you need to install Git, use:

        `sudo pacman -S git`
    
 If you want to skip a step, this command will install both the development tools and Git, but only if they're not installed:

        `sudo pacman -S --needed base-devel git`
    
##  Building Yay on Arch Linux

 Now that we’re properly equipped to build Yay, we can start the process. The first step is to clone the Git source code repository to your computer. This creates a directory called “yay”, so cd into a directory where you’re happy for this to happen, such as your Downloads directory.

 Once Yay has been installed, you can delete the “yay” directory.

        `cd ~/Downloads  
git clone https://aur.archlinux.org/yay.git`
    
![Cloning the yay Git repository](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-6.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 We need to change into the newly created directory and call makepkg to build Yay for us.

        `cd yay  
makepkg -si`
    
 The -s (sync dependencies) option will try to find and install any missing dependencies. The -i (install) option installs the package for us once it has been compiled. It means the command will be in your command path, and the man pages will be copied to where they need to go.

 You’ll be prompted with a few “Y/n” questions, and you may need to enter your password. When the process has finished, you can check that Yay is installed using its version command.

        `yay --version`
    
![Checking the version of yay](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-7.png) 

##  Using Yay to Install and Uninstall Software

 Using Yay is similar to using any other command-line package manager. You can use it to install, uninstall, and search for applications.

###  Installing Applications on Arch Linux With Yay

 To install an application, we use the -S (sync) option.

 We'll install the Signal desktop messenger.

        `yay -S signal-desktop`
    
 After a few “\[Y/n\]” prompts and a lot of screen output, you’re returned to the command prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

###  Uninstalling Applications With Yay

 Uninstalling is just as easy. We use the -R (remove) option and provide the name of the package we want to have uninstalled.

        `yay -R signal-desktop`
    
 You're asked to confirm the uninstallation, and then Yay does the rest.

###  Searching for Applications With Yay

 If you know at least part of the name of the application you want, provide what you know to Yay as a search clue. Yay responds by searching the AUR and returning a list of results that contain the search clue in their names.

 Let’s install the NordVPN binary. We don’t know what it is called exactly, so we’ll use Yay without any command-line options and provide the part of the name we do know.

        `yay nordvpn`
    
 The results of the search are presented as a numbered list.

![A list of search results returned by yay](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-3.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The one I’m after is the regular binary, which I can see is at number two on the list. To install it, type “2” and hit Enter. The next two prompts can be answered with the Enter key. When you see “Packages to CleanBuild?” and “Diffs to show?”, just hit Enter.

![Installing the selected package using yay](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/10-4.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 When you’re prompted with “Proceed with installation? \[Y/n\]”, you’ll notice the “Y” in the prompt is in uppercase. That means it is the default action, so you can just hit Enter to continue.

 After more scrolling screen output, the installation is completed, and you’re returned to the command prompt.

##  Accessing the Arch User Repository With Yay

 For many people, the AUR is a large part of the attraction of using Arch Linux. With Yay installed, using this enormous collection of applications is as easy as using pacman.

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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-hot-takes-dailys-most-popular-video-tracks/"><u>[New] In 2024, Hot Takes Daily's Most Popular Video Tracks</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-key-to-successful-drone-operation-optimal-lipo-selection/"><u>[Updated] 2024 Approved Key to Successful Drone Operation Optimal LiPo Selection</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-capturing-the-echoes-of-yesteryears-scanning-and-storing-vintage-prints/"><u>[Updated] Capturing the Echoes of Yesteryears Scanning and Storing Vintage Prints</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-make-every-picture-pop-with-these-10-online-photo-fixers/"><u>[Updated] Make Every Picture Pop with These 10 Online Photo Fixers</u></a></li>
<li><a href="https://technical-tips.techidaily.com/exploring-the-12-most-popular-free-internet-calling-apps/"><u>Exploring the 12 Most Popular Free Internet Calling Apps</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/first-timers-insights-into-pixel-density-matters-for-2024/"><u>First-Timer's Insights Into Pixel Density Matters for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-can-i-use-imessage-if-im-not-a-mac-user/"><u>How Can I Use iMessage if I'm Not a Mac User?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-10-fingerprint-lock-apps-to-lock-your-vivo-v29-pro-phone-by-drfone-android/"><u>In 2024, Top 10 Fingerprint Lock Apps to Lock Your Vivo V29 Pro Phone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/steps-to-overcome-not-found-d3dx941dll-errors-a-detailed-walkthrough/"><u>Steps to Overcome Not Found D3dx9_41.dll Errors: A Detailed Walkthrough</u></a></li>
<li><a href="https://technical-tips.techidaily.com/streamline-learning-with-these-6-must-have-apps-for-homework-success/"><u>Streamline Learning with These 6 Must-Have Apps for Homework Success</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-5-essential-factors-to-evaluate-when-purchasing-your-next-smartwatch/"><u>Top 5 Essential Factors to Evaluate When Purchasing Your Next Smartwatch</u></a></li>
<li><a href="https://facebook.techidaily.com/upcoming-trend-young-people-stepping-away-from-insta/"><u>Upcoming Trend: Young People Stepping Away From Insta</u></a></li>
<li><a href="https://technical-tips.techidaily.com/windows-11-pin-withdrawal-procedure-for-enhanced-access/"><u>Windows 11 PIN Withdrawal Procedure for Enhanced Access</u></a></li>
</ul></div>

