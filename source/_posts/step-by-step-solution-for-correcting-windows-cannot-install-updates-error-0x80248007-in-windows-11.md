---
title: Step-by-Step Solution for Correcting 'Windows Cannot Install Updates' Error (0X80248007) in Windows 11
date: 2025-02-26T01:29:46.405Z
updated: 2025-03-02T18:09:59.442Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Step-by-Step Solution for Correcting 'Windows Cannot Install Updates' Error (0X80248007) in Windows 11
excerpt: This Article Describes Step-by-Step Solution for Correcting 'Windows Cannot Install Updates' Error (0X80248007) in Windows 11
thumbnail: https://thmb.techidaily.com/d03c6bda0db9e446c0d9464753859ee1c2f12f38d94da77b1f5b8b2204a1d875.jpg
---

## Resolving Windows 10 Installation Issue - Fix Error Code 80 #

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
<li><a href="https://vp-tips.techidaily.com/new-essential-tips-for-ordering-photos-on-iphone-with-icloud-backup-for-2024/"><u>[New] Essential Tips for Ordering Photos on iPhone, With iCloud Backup for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-explore-these-non-periscope-video-platforms-for-iphones-and-androids-for-2024/"><u>[New] Explore These Non-Periscope Video Platforms for iPhones & Androids for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-realme-gt-neo-5-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Realme GT Neo 5 | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/dual-display-dominance-top-videographer-verdict/"><u>Dual Display Dominance Top Videographer Verdict</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-conversion-of-m2ts-files-to-avi-a-step-by-step-tutorial-at-no-charge/"><u>Effortless Conversion of M2TS Files to AVI - A Step-by-Step Tutorial at No Charge</u></a></li>
<li><a href="https://technical-tips.techidaily.com/master-the-setup-wireless-linking-of-your-ps4-controllers-easily/"><u>Master the Setup: Wireless Linking of Your PS4 Controllers Easily</u></a></li>
<li><a href="https://technical-tips.techidaily.com/missing-file-alert-how-to-restore-your-lost-d3dx926dll-library/"><u>Missing File Alert! How to Restore Your Lost d3dx9_26.dll Library</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigate-through-the-top-6-must-play-super-mario-games-for-personal-computers/"><u>Navigate Through the Top 6 Must-Play Super Mario Games for Personal Computers</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-world-of-computer-hardware-with-tom-an-in-depth-analysis/"><u>Navigating the World of Computer Hardware with Tom - An In-Depth Analysis</u></a></li>
<li><a href="https://technical-tips.techidaily.com/price-predictions-and-technical-details-your-guide-to-the-latest-on-the-google-pixel-smartwatch/"><u>Price Predictions & Technical Details - Your Guide to the Latest on the Google Pixel Smartwatch</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210932890-9781912230587-the-coronavirus-pandemic/"><u>The Coronavirus Pandemic | Free Book</u></a></li>
<li><a href="https://program-issues.techidaily.com/1723007958056-trouble-with-apex-legends-solve-common-engine-issues-now/"><u>Trouble with Apex Legends? Solve Common Engine Issues Now</u></a></li>
</ul></div>

