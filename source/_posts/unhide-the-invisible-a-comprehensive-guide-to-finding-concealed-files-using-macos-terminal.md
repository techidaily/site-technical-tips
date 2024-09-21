---
title: "Unhide the Invisible: A Comprehensive Guide to Finding Concealed Files Using macOS Terminal"
date: 2024-09-15T20:00:34.947Z
updated: 2024-09-21T03:17:07.207Z
categories:
  - BestProducts
description: "This Article Describes Unhide the Invisible: A Comprehensive Guide to Finding Concealed Files Using macOS Terminal"
excerpt: "This Article Describes Unhide the Invisible: A Comprehensive Guide to Finding Concealed Files Using macOS Terminal"
thumbnail: https://thmb.techidaily.com/fa466aca4e0117af9ede098ff5beff07b4b780680a77e468de6afed425dad313.jpg
---

## Unhide the Invisible: A Comprehensive Guide to Finding Concealed Files Using macOS Terminal
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

## What Was Hidden Can Now Be Seen

 Now that the Finder is displaying[hidden files](https://www.lifewire.com/what-is-a-hidden-file-2625898) and folders, just what can you see? The answer depends on the specific folder you're looking at, but in just about every folder, you'll see a file named**.DS\_Store** . The DS\_Store file contains information about the current folder, including the icon to use for the folder, the location its window will open in, and other bits of information the system needs.

 More important than the ubiquitous .DS\_Store file are the hidden folders that allow Mac users to access files such as the[Library folder](https://www.lifewire.com/os-x-is-hiding-your-library-folder-2260833) within your[Home folder](https://www.lifewire.com/move-macs-home-folder-new-location-2260157) . The Library folder contains many files and folders that relate to specific apps and services that you use on your Mac. For example, have you ever wondered where your email messages are stored? If you use Mail, you'll find them in the hidden Library folder. Likewise, the Library folder contains your[Calendar](https://www.lifewire.com/back-up-or-move-ical-or-calendar-data-to-new-mac-2260870) , Notes,[Contacts](https://www.lifewire.com/back-up-or-move-contacts-or-address-book-data-2260801) ,[Saved Application States](https://www.lifewire.com/managing-resume-feature-os-x-2259802) , and much more.

 Go ahead and look around the Library folder, but don't make any changes unless you have a specific problem that you're attempting to fix.

 Now that you can see all the hidden folders and files in the Finder, you'll probably want to hide them again, if only because they tend to clutter up Finder windows with extraneous items.

## Hide the Clutter

1. Launch**Terminal** , located at**/Applications/Utilities/** .
2. Type or copy/paste the commands below into the Terminal window, one at a time, pressing**ENTER** after each one.  
 **defaults write com.apple.finder AppleShowAllFiles FALSE**  
**killall Finder**  
![Terminal with ShowAllFiles set to FALSE](https://www.lifewire.com/thmb/7JHA9g9EOKMG8xeydvO7Yp3H_24=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/003_view-hidden-mac-folders-using-terminal-2260776-5c2ea75e46e0fb0001a438c8.jpg)
3. Poof! The hidden files are once again hidden. No hidden folder or file was harmed in the making of this Mac tip.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972670/19272" target="_top" id="1972670">
  <img src="//a.impactradius-go.com/display-ad/19272-1972670" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972670/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-http.techidaily.com/new-from-silence-to-symphony-how-to-set-up-unique-ringtones-and-sounds-for-android-for-2024/"><u>[New] From Silence to Symphony How to Set Up Unique Ringtones & Sounds for Android for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-timing-and-frequency-their-effect-on-youtube-rankings/"><u>[New] In 2024, Timing & Frequency Their Effect on YouTube Rankings</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-endless-memories-free-saving-on-instagram-stories/"><u>[Updated] Endless Memories FREE Saving on Instagram Stories</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-introduction-to-cinematic-graphics-techniques/"><u>[Updated] In 2024, Introduction to Cinematic Graphics Techniques</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-the-insiders-guide-to-recording-games-in-windows-11/"><u>[Updated] The Insider's Guide to Recording Games in Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/achieve-stunning-high-resolution-clarity-with-winxvideo-ai-convert-your-pictures-to-4k-8k-or-10k-quality/"><u>Achieve Stunning High-Resolution Clarity with WinxVideo AI - Convert Your Pictures to 4K, 8K, or 10K Quality</u></a></li>
<li><a href="https://technical-tips.techidaily.com/amazon-firestick-and-fandango-a-match-made-in-heaven-getting-started-with-downloads/"><u>Amazon Firestick and Fandango: A Match Made in Heaven - Getting Started with Downloads</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Oppo A58 4G | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/eliminating-screen-woes-tackling-unwanted-colors-and-visual-bends/"><u>Eliminating Screen Woes: Tackling Unwanted Colors & Visual Bends</u></a></li>
<li><a href="https://some-techniques.techidaily.com/five-easy-steps-to-enhance-photo-hues-for-2024/"><u>Five Easy Steps to Enhance Photo Hues for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-the-art-of-tv-shopping-a-comprehensive-home-entertainment-selection-process/"><u>Mastering the Art of TV Shopping: A Comprehensive Home Entertainment Selection Process</u></a></li>
<li><a href="https://some-skills.techidaily.com/synergy-of-social-media-embedding-linktree-in-your-tiktok-bio-for-2024/"><u>Synergy of Social Media Embedding Linktree in Your TikTok Bio for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/tech-rumors-decoded-unraveling-the-mystery-of-teslas-upcoming-automaton-price-estimates-and-specs-revealed/"><u>Tech Rumors Decoded: Unraveling the Mystery of Tesla's Upcoming Automaton - Price Estimates & Specs Revealed!</u></a></li>
</ul></div>

