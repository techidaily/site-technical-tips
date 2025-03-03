---
title: "Step-by-Step Guide: Successfully Disabling Safe Mode in Windows 11"
date: 2025-02-25T01:37:17.410Z
updated: 2025-03-03T02:44:09.146Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Step-by-Step Guide: Successfully Disabling Safe Mode in Windows 11"
excerpt: "This Article Describes Step-by-Step Guide: Successfully Disabling Safe Mode in Windows 11"
thumbnail: https://thmb.techidaily.com/8c53194608f8a775260017278f44b51f37022a75b1d4965ad23230242f3d564c.jpg
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
<li><a href="https://remote-screen-capture.techidaily.com/new-from-airwaves-to-files-online-audio-capture-basics/"><u>[New] From Airwaves to Files Online Audio Capture Basics</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-snappy-movement-capturing-blur-with-iphone-photos/"><u>[New] In 2024, Snappy Movement Capturing Blur with iPhone Photos</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-vimeo-recorder-tips-effective-screen-and-camera-capturing-techniques/"><u>[New] Vimeo Recorder Tips Effective Screen & Camera Capturing Techniques</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-the-ultimate-guide-to-time-lapses-with-iphone-for-2024/"><u>[Updated] The Ultimate Guide to Time-Lapses with iPhone for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-expert-tips-on-navigating-the-complex-world-of-instagram-hashtags/"><u>2024 Approved Expert Tips on Navigating the Complex World of Instagram Hashtags</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-the-visual-vault-in-depth-recorder-comparisons/"><u>2024 Approved The Visual Vault In-Depth Recorder Comparisons</u></a></li>
<li><a href="https://technical-tips.techidaily.com/before-purchasing-a-fitness-tracker-the-5-crucial-aspects-everyone-should-know/"><u>Before Purchasing a Fitness Tracker: The 5 Crucial Aspects Everyone Should Know</u></a></li>
<li><a href="https://technical-tips.techidaily.com/download-corsair-k70-mouse-software-and-drivers-get-started/"><u>Download Corsair K70 Mouse Software & Drivers - Get Started</u></a></li>
<li><a href="https://win-ratings.techidaily.com/easy-steps-for-new-users-adding-a-solid-state-drive-to-their-notebook-pc/"><u>Easy Steps for New Users: Adding a Solid-State Drive to Their Notebook PC</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/essential-stardew-enhancements-for-maximum-farming-fun-for-2024/"><u>Essential Stardew Enhancements for Maximum Farming Fun for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/explore-the-top-5-free-alternatives-to-skype-in-2e-e/"><u>Explore the Top 5 Free Alternatives to Skype in 2E! (E)</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-vivo-t2-pro-5g-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Vivo T2 Pro 5G Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://technical-tips.techidaily.com/master-engaging-content-the-definitive-guide-to-the-507-greatest-instagram-captions/"><u>Master Engaging Content: The Definitive Guide to the 507 Greatest Instagram Captions</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-definitive-steps-in-finding-your-dream-smartphone-cover/"><u>The Definitive Steps in Finding Your Dream Smartphone Cover</u></a></li>
</ul></div>

