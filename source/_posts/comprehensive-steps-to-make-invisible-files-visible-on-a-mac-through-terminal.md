---
title: Comprehensive Steps to Make Invisible Files Visible on a Mac Through Terminal
date: 2024-09-29T21:04:45.475Z
updated: 2024-10-02T09:39:48.085Z
categories:
  - BestProducts
description: This Article Describes Comprehensive Steps to Make Invisible Files Visible on a Mac Through Terminal
excerpt: This Article Describes Comprehensive Steps to Make Invisible Files Visible on a Mac Through Terminal
thumbnail: https://www.lifewire.com/thmb/klGzkHFGCUaqiWyKpafLJvoSONc=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/ScreenShot2019-01-03at3.13.16PM-5c2ea61c46e0fb0001abc508.jpg
---

## Comprehensive Steps to Make Invisible Files Visible on a Mac Through Terminal
 Your Mac has a few secrets, hidden folders, and files that are invisible to you. You may not even realize how much hidden data there is on your Mac, from basic things, such as preference files for user data and apps, to core system data that your Mac needs to run correctly. Apple hides these files and folders to prevent you from accidentally changing or deleting important data that your Mac needs.

 Apple's reasoning is good, but there are times when you may need to view these out-of-the-way corners of your Mac's file system. You'll find that accessing these hidden corners of your Mac is one of the steps in many Mac troubleshooting guides, as well as guides for backing up important data, such as[mail messages](https://www.lifewire.com/transfer-apple-mail-to-new-mac-2260915) or[Safari bookmarks](https://www.lifewire.com/back-up-or-move-safari-bookmarks-to-new-mac-2260891) . Fortunately, Apple includes ways to access these hidden goodies in[OS X](https://www.lifewire.com/install-mac-os-on-pc-5075590) and the more recent[macOS](https://www.lifewire.com/what-is-macos-4691239) . This guide concentrate on using the Terminal app, which provides a command line-like interface to many of the Mac's core functions.

![macOS Terminal with hidden files in a Finder window superimposed](https://www.lifewire.com/thmb/0GxCNfM-Nwq84X9L67jj4gSEqP4=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/ScreenShot2019-01-03at3.13.16PM-5c2ea61c46e0fb0001abc508-fb8027cc5efa44e2a3c858234aac1ae3.jpg)

 With Terminal, a simple command is all it takes to get your Mac to spill its secrets.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Use Terminal

1. Launch**Terminal** , located at**/Applications/Utilities/** .  
![Terminal application in macOS Finder Utilities folder](https://www.lifewire.com/thmb/MlM5SU4iQfZRMK1iLmULOs4OewA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/001_view-hidden-mac-folders-using-terminal-2260776-5c2ea70b46e0fb000123c164.jpg)
2. Type or copy and paste the commands below into the Terminal window, one at a time, pressing**ENTER** after each one.  
 **defaults write com.apple.finder AppleShowAllFiles TRUE**  
**killall Finder**  
![Terminal window with commands inline](https://www.lifewire.com/thmb/z9u9E5cQZxfSmppiqZSimKAfX_s=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/002_view-hidden-mac-folders-using-terminal-2260776-5c2ea73546e0fb0001415cda.jpg)
3. Entering the two lines above into Terminal allows you to use the[Finder](https://www.lifewire.com/use-mac-finder-2260739) to display all the hidden files on your Mac. The first line tells the Finder to display all files, regardless of how the hidden flag is set. The second line stops and restarts the Finder, so the changes can take effect. You may see your desktop disappear and reappear when you execute these commands; this is normal.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144280/7443" target="_top" id="2144280">
  <img src="//a.impactradius-go.com/display-ad/7443-2144280" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144280/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What Was Hidden Can Now Be Seen

 Now that the Finder is displaying[hidden files](https://www.lifewire.com/what-is-a-hidden-file-2625898) and folders, just what can you see? The answer depends on the specific folder you're looking at, but in just about every folder, you'll see a file named**.DS\_Store** . The DS\_Store file contains information about the current folder, including the icon to use for the folder, the location its window will open in, and other bits of information the system needs.

 More important than the ubiquitous .DS\_Store file are the hidden folders that allow Mac users to access files such as the[Library folder](https://www.lifewire.com/os-x-is-hiding-your-library-folder-2260833) within your[Home folder](https://www.lifewire.com/move-macs-home-folder-new-location-2260157) . The Library folder contains many files and folders that relate to specific apps and services that you use on your Mac. For example, have you ever wondered where your email messages are stored? If you use Mail, you'll find them in the hidden Library folder. Likewise, the Library folder contains your[Calendar](https://www.lifewire.com/back-up-or-move-ical-or-calendar-data-to-new-mac-2260870) , Notes,[Contacts](https://www.lifewire.com/back-up-or-move-contacts-or-address-book-data-2260801) ,[Saved Application States](https://www.lifewire.com/managing-resume-feature-os-x-2259802) , and much more.

 Go ahead and look around the Library folder, but don't make any changes unless you have a specific problem that you're attempting to fix.

 Now that you can see all the hidden folders and files in the Finder, you'll probably want to hide them again, if only because they tend to clutter up Finder windows with extraneous items.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139114/17108" target="_top" id="2139114">
  <img src="//a.impactradius-go.com/display-ad/17108-2139114" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139114/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Hide the Clutter

1. Launch**Terminal** , located at**/Applications/Utilities/** .
2. Type or copy/paste the commands below into the Terminal window, one at a time, pressing**ENTER** after each one.  
 **defaults write com.apple.finder AppleShowAllFiles FALSE**  
**killall Finder**  
![Terminal with ShowAllFiles set to FALSE](https://www.lifewire.com/thmb/7JHA9g9EOKMG8xeydvO7Yp3H_24=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/003_view-hidden-mac-folders-using-terminal-2260776-5c2ea75e46e0fb0001a438c8.jpg)
3. Poof! The hidden files are once again hidden. No hidden folder or file was harmed in the making of this Mac tip.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135359/19272" target="_top" id="2135359">
  <img src="//a.impactradius-go.com/display-ad/19272-2135359" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135359/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://jalbum-affiliate-program.sjv.io/c/5597632/1838960/17916" target="_top" id="1838960">
  <img src="//a.impactradius-go.com/display-ad/17916-1838960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://jalbum-affiliate-program.sjv.io/i/5597632/1838960/17916" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## More About Terminal

 If the power of the Terminal app intrigues you, you can find out more about what secrets Terminal can uncover in this guide:[Use the Terminal Application to Access Hidden Features](https://www.lifewire.com/mac-terminal-commands-4774997) .

Was this page helpful?

Thanks for letting us know!

 Get the Latest Tech News Delivered Every Day

[Subscribe](https://www.lifewire.com/#)

Tell us why!

 Other  Not enough details  Hard to understand

 Submit

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
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-nailing-the-perfect-capture-mac-tips-for-screencasting-streamed-video/"><u>[New] In 2024, Nailing the Perfect Capture Mac Tips for Screencasting Streamed Video</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-game-capture-without-xboxs-intrusive-game-bar/"><u>[Updated] 2024 Approved Game Capture without Xbox’s Intrusive Game Bar</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-the-definitive-guide-to-capturing-your-streams-netflix-mac-edition/"><u>[Updated] In 2024, The Definitive Guide to Capturing Your Streams Netflix Mac Edition</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-unlocking-the-secrets-of-successful-tiktok-hashtags/"><u>[Updated] In 2024, Unlocking the Secrets of Successful TikTok Hashtags</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/best-3-realme-c51-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>Best 3 Realme C51 Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/best-iphone-email-clients-of-2024-our-picks/"><u>Best iPhone Email Clients of 2024: Our Picks</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-advice-resolving-the-rununk13-error-for-smooth-hulu-viewing/"><u>Expert Advice: Resolving the Rununk13 Error for Smooth Hulu Viewing</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-beyond-the-basics-non-inshot-pc-video-tools/"><u>In 2024, Beyond the Basics Non-Inshot PC Video Tools</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-maximizing-your-reach-with-youtube-shorts-templates/"><u>In 2024, Maximizing Your Reach with YouTube Shorts Templates</u></a></li>
<li><a href="https://technical-tips.techidaily.com/in-depth-look-at-what-you-should-know-about-samsungs-tv-app-ecosystem/"><u>In-Depth Look at What You Should Know About Samsung's TV App Ecosystem</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mac-mastery-steps-to-reboot-network-preferences-and-fix-connectivity-issues/"><u>Mac Mastery: Steps to Reboot Network Preferences and Fix Connectivity Issues</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722862707017-overcoming-stop-0x0000005c-halinitializationfailed-error-on-your-computer/"><u>Overcoming STOP 0X0000005C (HAL_INITIALIZATION_FAILED) Error on Your Computer</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-picks-where-to-watch-movies-online-without-paying-a-dime/"><u>Top Picks: Where to Watch Movies Online Without Paying a Dime</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/transform-your-digital-artistry-with-the-premium-huion-inspiroy-g10-t-series-tablet-a-detailed-performance-and-build-analysis/"><u>Transform Your Digital Artistry with the Premium Huion Inspiroy G10 T-Series Tablet - A Detailed Performance and Build Analysis</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-final-cut-pro-tutorial-adding-picture-in-picture-effects-to-your-videos/"><u>Updated Final Cut Pro Tutorial Adding Picture-in-Picture Effects to Your Videos</u></a></li>
</ul></div>

