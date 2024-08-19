---
title: DIY Solution for A Black and White Screen Error in Windows 10 Systems
date: 2024-08-18T19:33:56.285Z
updated: 2024-08-19T19:33:56.285Z
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
<li><a href="https://desktop-recording.techidaily.com/new-explore-mp4-recording-tools-today-in-2024/"><u>[New] Explore MP4 Recording Tools Today, In 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-precision-capturing-with-apowersofts-latest-screenshot-tool/"><u>[New] In 2024, Precision Capturing with Apowersoft's Latest Screenshot Tool</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ovies-to-watch-instead-7-best-list/"><u>[New] Movies to Watch Instead - #7 Best List</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/evolutionize-your-videos-with-360-degrees-a-step-by-step-guide-for-youtube-enthusiasts-for-2024/"><u>[New] Revolutionize Your Videos with 360 Degrees  A Step-by-Step Guide for YouTube Enthusiasts for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-plex-media-player-centralized-home-entertainment/"><u>[Updated] In 2024, Plex Media Player  Centralized Home Entertainment</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-unlocking-the-secrets-of-flawless-video-calls-screen-sharing-for-2024/"><u>[Updated] Unlocking the Secrets of Flawless Video Calls (Screen Sharing) for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-smart-picklist-top-value-free-livestream-software-and-apps-reviewed-this-year/"><u>2024 Approved  Smart Picklist  Top Value Free Livestream Software & Apps Reviewed This Year</u></a></li>
<li><a href="https://technical-tips.techidaily.com/all-about-the-samsung-galaxy-ring-what-you-need-to-know-cost-estimates-release-schedule-and-specs-update/"><u>All About the Samsung Galaxy Ring: What You Need to Know - Cost Estimates, Release Schedule & Specs Update</u></a></li>
<li><a href="https://technical-tips.techidaily.com/anticipating-the-tesla-phone-launch-discover-potential-price-release-timeline-and-latest-speculations/"><u>Anticipating the Tesla Phone Launch? Discover Potential Price, Release Timeline & Latest Speculations</u></a></li>
<li><a href="https://technical-tips.techidaily.com/complete-tutorial-for-deleting-windows-recover-disk-from-hard-drive/"><u>Complete Tutorial for Deleting Windows Recover Disk From Hard Drive</u></a></li>
<li><a href="https://technical-tips.techidaily.com/connecting-airpods-compatibility-and-steps-with-nintendo-switch/"><u>Connecting AirPods: Compatibility and Steps with Nintendo Switch</u></a></li>
<li><a href="https://technical-tips.techidaily.com/crossing-platform-photograph-storage-transitioning-your-google-images-to-icloud-safely/"><u>Crossing Platform Photograph Storage: Transitioning Your Google Images to iCloud Safely</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-7-most-effective-notetakers-designed-specifically-for-ipad-devices/"><u>Discover the 7 Most Effective Notetakers Designed Specifically for iPad Devices</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722899434075-discover-these-awesome-no-cost-image-manipulation-tools/"><u>Discover These Awesome No-Cost Image Manipulation Tools!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-tips-for-resolving-the-missing-msidll-file-error-on-your-pc/"><u>Expert Tips for Resolving the Missing msi.dll File Error on Your PC</u></a></li>
<li><a href="https://technical-tips.techidaily.com/get-the-latest-on-teslas-innovation-in-transportation-taxi-revolution-with-estimated-price-arrival-date-and-top-notch-specs/"><u>Get the Latest on Tesla's Innovation in Transportation - Taxi Revolution with Estimated Price, Arrival Date and Top-Notch Specs</u></a></li>
<li><a href="https://technical-tips.techidaily.com/harmonizing-hearths-how-to-create-shared-playlists-for-social-music-time-on-spotify/"><u>Harmonizing Hearths: How to Create Shared Playlists for Social Music Time on Spotify</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-can-i-benefit-from-a-lenovo-scholarly-reduction/"><u>How Can I Benefit From a Lenovo Scholarly Reduction?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-fix-a-computer-that-shows-no-sign-of-power/"><u>How to Fix a Computer That Shows No Sign of Power</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-phone-touchscreen-of-vivo-t2-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Phone Touchscreen Of Vivo T2 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-apple-iphone-13-drfone-by-drfone-virtual-ios/"><u>In 2024, Methods to Change GPS Location On Apple iPhone 13 | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-planning-to-use-a-pokemon-go-joystick-on-vivo-s18-drfone-by-drfone-virtual-android/"><u>In 2024, Planning to Use a Pokemon Go Joystick on Vivo S18? | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/in-depth-analysis-the-third-gen-apple-tv-4k-with-3-camera-setup-unveiled/"><u>In-Depth Analysis: The Third Gen Apple TV 4K with 3-Camera Setup Unveiled</u></a></li>
<li><a href="https://technical-tips.techidaily.com/masterclass-on-resolving-the-absent-shelldll-problem/"><u>Masterclass on Resolving the Absent Shell.dll Problem</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-the-use-of-lg-channels-for-optimal-engagement/"><u>Mastering the Use of LG Channels for Optimal Engagement</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-time-lapse-photography-tips-for-iphones-users/"><u>Mastering Time-Lapse Photography: Tips for iPhones Users</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigating-the-decision-9-key-questions-before-buying-an-ev/"><u>Navigating the Decision: 9 Key Questions Before Buying an EV</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigating-the-path-to-blue-checkmark-verification-on-instagram/"><u>Navigating the Path to Blue-Checkmark Verification on Instagram</u></a></li>
<li><a href="https://technical-tips.techidaily.com/resolving-msvbvm50dll-file-not-foundmissing-issues-on-your-computer/"><u>Resolving MSVBVM50.DLL File Not Found/Missing Issues on Your Computer</u></a></li>
<li><a href="https://technical-tips.techidaily.com/stay-informed-on-micromobility-event-schedule-breaking-news-and-expert-gossip-coverage/"><u>Stay Informed on Micromobility: Event Schedule, Breaking News & Expert Gossip Coverage</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-customizing-your-windows-11-taskbars-hue/"><u>Step-by-Step Guide: Customizing Your Windows 11 Taskbar's Hue</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-tutorial-effortlessly-connecting-your-tv-using-the-fire-stick-remote/"><u>Step-by-Step Tutorial: Effortlessly Connecting Your TV Using the Fire Stick Remote</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-guide-solving-connection-issues-with-your-stadia-gaming-headset/"><u>Troubleshooting Guide: Solving Connection Issues with Your Stadia Gaming Headset</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722899589396-unexpected-black-screen-blues-heres-how-to-get-your-computer-showing-again/"><u>Unexpected Black Screen Blues? Here's How To Get Your Computer Showing Again!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unraveling-netflixs-past-insight-into-its-popular-dvd-by-mail-program/"><u>Unraveling Netflix's Past: Insight Into Its Popular DVD-by-Mail Program</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unveiling-bing-the-alternative-search-option-by-microsoft/"><u>Unveiling Bing - The Alternative Search Option by Microsoft</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->