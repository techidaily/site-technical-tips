---
title: "How to Overcome the 0X80070005 Error: Successful Windows Updates Without Access Issues"
date: 2025-02-10T03:27:28.563Z
updated: 2025-02-12T03:29:40.642Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes How to Overcome the 0X80070005 Error: Successful Windows Updates Without Access Issues"
excerpt: "This Article Describes How to Overcome the 0X80070005 Error: Successful Windows Updates Without Access Issues"
thumbnail: https://thmb.techidaily.com/aefba9f0ac6f593076f657b0dfeebc66593ffd1b9ade996e1956601a5424d0a8.jpg
---

## Error Code 80240020 Deciphered: Easy Steps to Successfully Install Windows 10 without a Glitch

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
<li><a href="https://article-knowledge.techidaily.com/updated-innovative-features-of-the-latest-win11-release/"><u>[Updated] Innovative Features of the Latest Win11 Release</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-quick-quirks-of-professional-photo-editing/"><u>[Updated] Quick Quirks of Professional Photo Editing</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-survive-and-thrive-top-8-zombie-game-experiences/"><u>[Updated] Survive and Thrive Top 8 Zombie Game Experiences</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-digital-filmmaking-recording-video-across-various-platforms/"><u>2024 Approved Digital Filmmaking Recording Video Across Various Platforms</u></a></li>
<li><a href="https://extra-hints.techidaily.com/clarity-catalysts-selecting-online-video-aids-for-2024/"><u>Clarity Catalysts Selecting Online Video Aids for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/identify-malfunctioning-drivers-with-windows-device-manager-on-windows-7-by-drivereasy-guide/"><u>Identify malfunctioning drivers with Windows Device Manager on Windows 7</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-sharefake-gps-on-uber-for-oppo-a78-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to share/fake gps on Uber for Oppo A78 5G | Dr.fone</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/innovating-action-filming-yi-4ks-impact-on-cinema-for-2024/"><u>Innovating Action Filming Yi 4K's Impact on Cinema for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigating-time-on-the-internet-tips-and-tricks-for-using-the-wayback-machine/"><u>Navigating Time on the Internet: Tips and Tricks for Using the Wayback Machine</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/pursuing-profits-the-path-to-fiscal-gains-through-videography/"><u>Pursuing Profits The Path to Fiscal Gains Through Videography</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solutions-for-correcting-color-imbalances-and-image-warping-in-display-screens/"><u>Solutions for Correcting Color Imbalances and Image Warping in Display Screens</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-essential-guide-to-acquiring-ai-knowledge-for-free-by-learning-at-your-own-speed-with-lifewire/"><u>The Essential Guide to Acquiring AI Knowledge for Free by Learning at Your Own Speed with Lifewire</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-steps-for-repairing-a-cmos-error-summation-discrepancy/"><u>Troubleshooting Steps for Repairing a CMOS Error Summation Discrepancy</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unveiling-the-advantages-of-evs-over-gas-powered-cars/"><u>Unveiling the Advantages of EVs Over Gas-Powered Cars</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

