---
title: How to Successfully Overcome the KB Error Code 0X80070422 on Your Windows 10 PC [Solution]
date: 2025-02-09T20:34:21.237Z
updated: 2025-02-12T05:07:53.153Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes How to Successfully Overcome the KB Error Code 0X80070422 on Your Windows 10 PC [Solution]
excerpt: This Article Describes How to Successfully Overcome the KB Error Code 0X80070422 on Your Windows 10 PC [Solution]
thumbnail: https://thmb.techidaily.com/596dd6315d1559e3cb5b3aa52b6f2b9825ab34a39bbf16416336b018124bf2bc.jpg
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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-advanced-scheduling-with-premium-recording-software/"><u>[New] 2024 Approved Advanced Scheduling with Premium Recording Software</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-downloading-fb-audio-nuggets/"><u>[New] 2024 Approved Downloading FB Audio Nuggets</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-powerful-insights-unlocking-full-potential-with-mobizen-screen-recording/"><u>[New] In 2024, Powerful Insights Unlocking Full Potential with Mobizen Screen Recording</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-up-close-and-personal-tips-for-sharper-videos-on-videoleap/"><u>[Updated] Up Close & Personal Tips for Sharper Videos on Videoleap</u></a></li>
<li><a href="https://technical-tips.techidaily.com/bypassing-the-login-how-to-engage-with-telegram-users-anonymously/"><u>Bypassing the Login: How to Engage with Telegram Users Anonymously</u></a></li>
<li><a href="https://activate-lock.techidaily.com/easy-fixes-how-to-recover-forgotten-icloud-password-on-your-apple-iphone-14-by-drfone-ios/"><u>Easy Fixes How To Recover Forgotten iCloud Password On your Apple iPhone 14</u></a></li>
<li><a href="https://technical-tips.techidaily.com/elite-gadgets-economical-pricing-experience-luxury-with-affordable-tech-picks/"><u>Elite Gadgets, Economical Pricing: Experience Luxury with Affordable Tech Picks</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-change-the-taskbar-color-in-windows-10/"><u>How to Change the Taskbar Color in Windows 10</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/iphone-16-upgrades-with-advanced-image-recognition-features-inspired-by-google-lens-detailed-review-on-apples-latest-tech-breakthrough/"><u>IPhone 16 Upgrades with Advanced Image Recognition Features Inspired by Google Lens - Detailed Review on Apple's Latest Tech Breakthrough</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-the-art-of-distributing-digital-steam-rewards-effectively/"><u>Mastering the Art of Distributing Digital Steam Rewards Effectively</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-your-android-a-guide-to-quick-settings-navigation/"><u>Mastering Your Android: A Guide to Quick Settings Navigation</u></a></li>
<li><a href="https://discover-guides.techidaily.com/maximizing-print-clarity-and-color-accuracy-expert-advice-with-yl-computings-solutions-for-quality-printouts/"><u>Maximizing Print Clarity and Color Accuracy: Expert Advice with YL Computing's Solutions for Quality Printouts</u></a></li>
<li><a href="https://youtube-data.techidaily.com/-overview-of-colour-difference-filming-for-2024/"><u>Quick Overview of Colour Difference Filming for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solving-common-gmail-sync-errors-a-users-handbook/"><u>Solving Common Gmail Sync Errors: A User’s Handbook</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-resetting-a-user-account-password-on-windows/"><u>Step-by-Step Guide: Resetting a User Account Password on Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-tutorial-how-to-get-and-use-az-screen-recorder-on-a-pc/"><u>Ultimate Tutorial: How To Get and Use AZ Screen Recorder On a PC</u></a></li>
<li><a href="https://win-special.techidaily.com/understanding-aomei-backuppers-specific-glossary/"><u>Understanding AOMEI Backupper's Specific Glossary</u></a></li>
<li><a href="https://technical-tips.techidaily.com/what-is-google-hangouts-and-how-did-it-revolutionize-chatting/"><u>What Is Google Hangouts and How Did It Revolutionize Chatting?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/what-to-anticipate-for-google-pixel-fold-2-unveiling-the-potential-pricing-launch-timeframe-and-features/"><u>What to Anticipate for Google Pixel Fold 2 – Unveiling the Potential Pricing, Launch Timeframe & Features</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

