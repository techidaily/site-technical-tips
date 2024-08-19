---
title: How To Factory Reset a Dell Laptop
date: 2024-08-18T19:35:57.477Z
updated: 2024-08-19T19:35:57.477Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes How To Factory Reset a Dell Laptop
excerpt: This Article Describes How To Factory Reset a Dell Laptop
thumbnail: https://thmb.techidaily.com/97473d93769b74152c0b0b04df270598f5aded17925dea70fd12d869a1bbc744.jpg
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
<li><a href="https://facebook-record-videos.techidaily.com/new-efficiently-incorporate-youtube-playlists-for-engaging-pages-for-2024/"><u>[New] Efficiently Incorporate YouTube Playlists for Engaging Pages for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-expert-tips-for-skype-calls-best-recording-techniques-freepaid-for-2024/"><u>[Updated] Expert Tips for Skype Calls  Best Recording Techniques (Free/Paid) for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-from-ordinary-to-outstanding-crafting-unique-shorts-thumbnails-for-2024/"><u>[Updated] From Ordinary to Outstanding  Crafting Unique Shorts Thumbnails for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-pc-hdr-optimization-made-simple-for-2024/"><u>[Updated] PC HDR Optimization Made Simple for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/an-ultimate-overview-of-polarr-photo-editor-for-2024/"><u>An Ultimate Overview of Polarr Photo Editor for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/call-of-duty-wwii-on-windows-and-the-notorious-black-screen-issue-complete-fixes-revealed/"><u>Call of Duty WWII on Windows and the Notorious Black Screen Issue: Complete Fixes Revealed</u></a></li>
<li><a href="https://technical-tips.techidaily.com/d3dx939dll-not-found-heres-how-to-correctly-resolve-the-issue/"><u>D3dx9_39.dll Not Found? Here’s How to Correctly Resolve the Issue</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-leading-8-ebook-reader-apps-we-love/"><u>Discover the Leading 8 eBook Reader Apps We Love</u></a></li>
<li><a href="https://technical-tips.techidaily.com/enhancing-security-how-to-set-up-trusted-domain-whitelisting-on-macos-mail/"><u>Enhancing Security: How to Set Up Trusted Domain Whitelisting on macOS Mail</u></a></li>
<li><a href="https://technical-tips.techidaily.com/essential-guide-fixing-common-skype-connection-issues/"><u>Essential Guide: Fixing Common Skype Connection Issues</u></a></li>
<li><a href="https://technical-tips.techidaily.com/experience-cinematic-magic-at-home-with-our-top-pick-of-15-dolby-atmos-movies/"><u>Experience Cinematic Magic at Home with Our Top Pick of 15 Dolby Atmos Movies</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-advice-seamlessly-project-content-from-a-mac-laptopdesktop-to-your-television-screen-using-airplay-technology/"><u>Expert Advice: Seamlessly Project Content From a Mac Laptop/Desktop to Your Television Screen Using AirPlay Technology</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-techniques-for-merging-data-between-columns-in-microsoft-excel/"><u>Expert Techniques for Merging Data Between Columns in Microsoft Excel</u></a></li>
<li><a href="https://technical-tips.techidaily.com/exploring-conversational-agents-what-does-chatgpt-mean/"><u>Exploring Conversational Agents: What Does ChatGPT Mean?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/get-ahead-of-the-curve-early-info-on-samsungs-upcoming-galaxy-watch-7/"><u>Get Ahead of the Curve: Early Info on Samsung's Upcoming Galaxy Watch 7</u></a></li>
<li><a href="https://technical-tips.techidaily.com/guide-switching-your-samsung-smart-tvs-default-web-browser/"><u>Guide: Switching Your Samsung Smart TV's Default Web Browser</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-address-missing-xinput-13-dll-files-in-windows-systems/"><u>How to Address Missing XInput 1.3 DLL Files in Windows Systems</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-erase-your-presence-on-tiktok-a-comprehensive-walkthrough/"><u>How To Erase Your Presence on TikTok – A Comprehensive Walkthrough</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-locate-and-restore-the-missing-d3dx9-39dll-component-on-windows/"><u>How to Locate and Restore the Missing D3dx9_ 39.dll Component on Windows</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-restore-power-to-your-airpods-a-step-by-step-troubleshooting-guide/"><u>How to Restore Power to Your AirPods: A Step-by-Step Troubleshooting Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-poco-c65-drfone-by-drfone-virtual-android/"><u>In 2024, Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Poco C65? | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/inside-look-at-samsung-unpacked-2025-all-upcoming-devices-rumors-and-breakthrough-tech-news-covered/"><u>Inside Look at Samsung Unpacked 2025 - All Upcoming Devices, Rumors, and Breakthrough Tech News Covered</u></a></li>
<li><a href="https://technical-tips.techidaily.com/is-buying-a-ps5-worthwhile-explore-4-convincing-arguments-for-joining-the-playstation-revolution/"><u>Is Buying a PS5 Worthwhile? Explore 4 Convincing Arguments for Joining the PlayStation Revolution</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-windows-telnet-a-comprehensive-guide/"><u>Mastering Windows Telnet: A Comprehensive Guide</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/maximizing-your-macbook-camera-a-recording-handbook/"><u>Maximizing Your MacBook Camera  A Recording Handbook</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigating-the-dilemma-of-assembling-vs-buying-pre-built-desktopslaptops-which-fits-your-lifestyle/"><u>Navigating the Dilemma of Assembling Vs. Buying Pre-Built Desktops/Laptops – Which Fits Your Lifestyle?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/overcoming-the-challenge-addressing-and-repairing-missing-msvcrtdll-errors/"><u>Overcoming the Challenge: Addressing and Repairing Missing MSVCRT.DLL Errors</u></a></li>
<li><a href="https://technical-tips.techidaily.com/reusing-old-receivers-syncing-them-to-a-different-logitech-mouse/"><u>Reusing Old Receivers: Syncing Them to a Different Logitech Mouse</u></a></li>
<li><a href="https://technical-tips.techidaily.com/samsung-unpacked-2025-the-comprehensive-guide-to-whats-new-and-rumored-for-the-next-gen-gadgets/"><u>Samsung Unpacked 2025: The Comprehensive Guide to What’s New and Rumored for the Next Gen Gadgets</u></a></li>
<li><a href="https://technical-tips.techidaily.com/simple-steps-for-deleting-photos-off-your-facebook-page/"><u>Simple Steps for Deleting Photos Off Your Facebook Page</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solving-the-puzzle-comprehensive-insight-into-blue-screen-issues-and-fixes/"><u>Solving the Puzzle: Comprehensive Insight Into Blue Screen Issues and Fixes</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-instructions-for-navigating-and-using-the-wayback-machine-effectively/"><u>Step-by-Step Instructions for Navigating and Using the Wayback Machine Effectively</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-troubleshooting-curing-your-facetime-black-display-problem/"><u>Step-by-Step Troubleshooting: Curing Your FaceTime Black Display Problem</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-tutorial-for-turning-off-urgent-safety-alarms-on-iphone/"><u>Step-by-Step Tutorial for Turning Off Urgent Safety Alarms on iPhone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722853079059-steps-to-follow-handling-an-instagram-account-suspension-or-deactivation/"><u>Steps to Follow: Handling an Instagram Account Suspension or Deactivation</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-complete-guide-to-repair-missing-mingwm10dll-files-on-your-pc/"><u>The Complete Guide to Repair Missing Mingwm10.dll Files on Your PC</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-viewing-guide-superman-film-series-sequential-playlist/"><u>The Ultimate Viewing Guide: Superman Film Series Sequential Playlist</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-walkthrough-for-permanently-removing-your-yahoo-mail-account/"><u>The Ultimate Walkthrough for Permanently Removing Your Yahoo Mail Account</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-steps-for-your-vizio-smart-tv-when-wi-fi-keeps-disconnecting/"><u>Troubleshooting Steps for Your Vizio Smart TV When Wi-Fi Keeps Disconnecting</u></a></li>
<li><a href="https://technical-tips.techidaily.com/whats-the-newest-macbook/"><u>What’s the Newest MacBook?</u></a></li>
<li><a href="https://driver-install.techidaily.com/1720062041045-windows-hub-reconciliation-fixed/"><u>Windows Hub Reconciliation - Fixed</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->