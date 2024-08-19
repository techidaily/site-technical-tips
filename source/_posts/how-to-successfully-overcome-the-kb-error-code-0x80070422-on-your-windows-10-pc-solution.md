---
title: How to Successfully Overcome the KB Error Code 0X80070422 on Your Windows 10 PC [Solution]
date: 2024-08-18T19:35:15.031Z
updated: 2024-08-19T19:35:15.031Z
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
<li><a href="https://digital-screen-recording.techidaily.com/new-first-time-user-steps-for-effortless-vrecorder-setup-for-2024/"><u>[New] First-Time User Steps for Effortless VRecorder Setup for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-skyrocketing-to-million-dollar-views-best-hashtags/"><u>[New] Skyrocketing to Million-Dollar Views  Best Hashtags</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-2024-elite-camcorders-best-buy-guide/"><u>[New] The 2024 Elite Camcorders - Best Buy Guide</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-amp-up-the-sound-beat-downloads-on-fb/"><u>[Updated] In 2024, Amp Up the Sound  Beat Downloads on FB</u></a></li>
<li><a href="https://technical-tips.techidaily.com/(3-made-simple-a-beginners-tutorial-for-creating-hearts-on-keyboards/"><u><3 Made Simple: A Beginner's Tutorial for Creating Hearts on Keyboards</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-step-into-new-dimensions-with-jaunt-vr-review/"><u>2024 Approved  Step Into New Dimensions with Jaunt VR Review</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/analytics-tools-for-an-improved-tracking-of-your-instagram-metrics-for-2024/"><u>Analytics Tools For an Improved Tracking of Your Instagram Metrics for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/choosing-the-perfect-iphone-for-serious-gamers-a-comprehensive-guide/"><u>Choosing the Perfect iPhone for Serious Gamers: A Comprehensive Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/comprehensive-strategies-to-troubleshoot-and-solve-the-500-error-code/"><u>Comprehensive Strategies to Troubleshoot and Solve the 500 Error Code</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-best-iphone-gps-navigation-apps-top-5-picks/"><u>Discover the Best iPhone GPS Navigation Apps (Top 5 Picks)</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ending-your-paramount-streaming-service-account-a-how-to-walkthrough/"><u>Ending Your Paramount Streaming Service Account - A How-To Walkthrough</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/fixed-rtwlanesys-blue-screen-error/"><u>Fixed: rtwlane.sys Blue Screen Error</u></a></li>
<li><a href="https://technical-tips.techidaily.com/get-ready-playstation-portable-launches-with-detailed-info-on-costs-and-features-find-retailers-near-you/"><u>Get Ready: PlayStation Portable Launches with Detailed Info on Costs & Features - Find Retailers Near You!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/guide-to-uninstalling-bundled-software-on-ios-devices/"><u>Guide to Uninstalling Bundled Software on iOS Devices</u></a></li>
<li><a href="https://technical-tips.techidaily.com/highly-recommended-applications-for-virtual-group-meetings-and-calls/"><u>Highly Recommended Applications for Virtual Group Meetings and Calls</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-correctly-address-mfc71dll-not-detected-error-on-your-pc/"><u>How to Correctly Address 'mfc71.dll Not Detected' Error on Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-freshen-up-your-windows-11-experience-with-a-reset-or-refresh/"><u>How to Freshen Up Your Windows 11 Experience with a Reset or Refresh</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722897012241-huge-ipad-deals-await-limited-time-only-to-grab-yours/"><u>Huge iPad Deals Await – Limited Time Only to Grab Yours!</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-meizu-21-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Meizu 21 Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-iphone-se-2020-icloud-activation-lock-bypass-by-drfone-ios/"><u>In 2024, iPhone SE (2020) iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://technical-tips.techidaily.com/learn-to-record-and-send-voice-messages-on-your-ios-device-with-ease/"><u>Learn to Record & Send Voice Messages on Your iOS Device with Ease</u></a></li>
<li><a href="https://technical-tips.techidaily.com/leveraging-ai-reshaping-our-world-for-a-better-future/"><u>Leveraging AI: Reshaping Our World for a Better Future</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-discord-bot-integration-tips-and-techniques/"><u>Mastering Discord Bot Integration - Tips and Techniques</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-the-art-of-instagram-verification-proven-strategies-to-earn-your-blue-badge/"><u>Mastering the Art of Instagram Verification: Proven Strategies to Earn Your Blue Badge</u></a></li>
<li><a href="https://screen-recording.techidaily.com/mastering-youtube-live-recording-on-every-gadget/"><u>Mastering YouTube Live Recording on Every Gadget</u></a></li>
<li><a href="https://technical-tips.techidaily.com/maximize-your-screen-time-how-to-enjoy-netflix-content-without-financial-commitment/"><u>Maximize Your Screen Time: How to Enjoy Netflix Content Without Financial Commitment</u></a></li>
<li><a href="https://program-issues.techidaily.com/no-more-waiting-around-solve-your-madden-nfl-22-initial-load-screen-problem-now/"><u>No More Waiting Around! Solve Your Madden Nfl 22 Initial Load Screen Problem Now</u></a></li>
<li><a href="https://program-issues.techidaily.com/smooth-gaming-ahead-quick-fixes-to-stop-titanfall-2-from-crashing/"><u>Smooth Gaming Ahead: Quick Fixes to Stop Titanfall 2 From Crashing</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-solutions-for-correcting-the-hulu-rununk13-problem/"><u>Step-by-Step Solutions for Correcting the Hulu RUNUNK13 Problem</u></a></li>
<li><a href="https://technical-tips.techidaily.com/steps-to-correct-missing-mss32dll-errors-in-windows/"><u>Steps to Correct Missing mss32.dll Errors in Windows</u></a></li>
<li><a href="https://program-issues.techidaily.com/stop-war-thunder-from-crashing-with-these-proven-fixes/"><u>Stop War Thunder From Crashing with These Proven Fixes</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-best-5-gps-applications-for-your-iphone-experience/"><u>The Best 5 GPS Applications for Your iPhone Experience</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-definitive-fix-guide-for-overcoming-hulus-rununk13-problem/"><u>The Definitive Fix Guide for Overcoming Hulu's RUNUNK13 Problem</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-mac-masterclass-eliminating-stale-dns-records-effectively/"><u>The Mac Masterclass: Eliminating Stale DNS Records Effectively</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722870163512-top-15-free-windows-11-skins-and-themes-get-your-pc-revamped/"><u>Top 15 FREE Windows 11 Skins & Themes - Get Your PC Revamped!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unveiling-the-future-of-transportation-insights-on-teslas-autonomous-taxi-service-and-its-anticipated-cost/"><u>Unveiling the Future of Transportation: Insights on Tesla's Autonomous Taxi Service & Its Anticipated Cost</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->