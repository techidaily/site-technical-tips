---
title: DIY Solution for A Black and White Screen Error in Windows 10 Systems
date: 2025-02-10T03:04:23.890Z
updated: 2025-02-11T20:37:47.519Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes DIY Solution for A Black and White Screen Error in Windows 10 Systems
excerpt: This Article Describes DIY Solution for A Black and White Screen Error in Windows 10 Systems
thumbnail: https://thmb.techidaily.com/1a08c8dedd48664d90b507bda304483e40c9a1d2dac0696255a8394fc453f16e.jpg
---

## Error Code 80240020: Comprehensive Troubleshooting Steps for Windows 10 Installation Issues Resolved

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://screen-recording.techidaily.com/new-4-simplified-ways-to-screen-record-lenovo-for-2024/"><u>[New] 4 Simplified Ways to Screen Record Lenovo for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-pixelplay-review-system/"><u>[Updated] 2024 Approved PixelPlay Review System</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-unrivaled-adventures-a-chronicle-of-the-greatest-action-adventure-games-top-10/"><u>[Updated] In 2024, Unrivaled Adventures A Chronicle of the Greatest Action-Adventure Games (Top 10)</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-stream-freedom-on-the-go-download-your-favorite-youtube-tracks-ios/"><u>[Updated] Stream Freedom on the Go Download Your Favorite YouTube Tracks iOS</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-melodic-moments-to-augment-your-status/"><u>2024 Approved Melodic Moments to Augment Your Status</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/choosing-your-console-compare-the-features-of-nintendos-switch-lite-and-oled-editions/"><u>Choosing Your Console? Compare the Features of Nintendo's Switch Lite & OLED Editions</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722890621182-effective-strategies-to-address-and-mend-missing-dynamic-link-library-problems/"><u>Effective Strategies to Address and Mend Missing Dynamic Link Library Problems</u></a></li>
<li><a href="https://technical-tips.techidaily.com/enjoy-endless-entertainment-streaming-hulu-on-lg-smart-tvs-easily/"><u>Enjoy Endless Entertainment: Streaming Hulu on LG Smart TVs Easily</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fix-for-lenovos-inoperative-touch-interface/"><u>Fix for Lenovo's Inoperative Touch Interface</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-get-the-latest-drivers-for-your-lenovo-x1-carbon-on-windows-117-with-ease/"><u>How to Get the Latest Drivers for Your Lenovo X1 Carbon on Windows 11/7 with Ease</u></a></li>
<li><a href="https://technical-tips.techidaily.com/journey-through-time-key-milestones-in-the-development-of-electric-vehicles/"><u>Journey Through Time: Key Milestones in the Development of Electric Vehicles</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-android-troubleshooting-a-step-by-nstep-guide-to-call-recovery/"><u>Mastering Android Troubleshooting: A Step-by-nStep Guide to Call Recovery</u></a></li>
<li><a href="https://technical-tips.techidaily.com/open-iphone-sim-card-panel-without-ejector-pin-tips-and-tricks/"><u>Open iPhone Sim Card Panel without Ejector Pin – Tips & Tricks</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722853065573-step-by-step-guide-to-reversing-videos-on-snapchat-learn-how-today/"><u>Step-by-Step Guide to Reversing Videos on Snapchat - Learn How Today</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-beginners-path-to-broadcasting-your-gaming-adventures-on-ps4/"><u>The Beginner's Path to Broadcasting Your Gaming Adventures on PS4</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ultimate-guide-resolving-dll-cannot-be-found-mistakes/"><u>Ultimate Guide: Resolving 'DLL Cannot Be Found' Mistakes</u></a></li>
<li><a href="https://discover-forum.techidaily.com/yl-software-tips-easily-modify-your-control-panels-color-scheme/"><u>YL Software Tips: Easily Modify Your Control Panel's Color Scheme!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

