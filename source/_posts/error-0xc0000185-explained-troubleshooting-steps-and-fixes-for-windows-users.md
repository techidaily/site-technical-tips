---
title: "Error 0Xc0000185 Explained: Troubleshooting Steps and Fixes for Windows Users"
date: 2024-08-12T02:54:37.376Z
updated: 2024-08-13T02:54:37.376Z
categories:
  - BestProducts
description: "This Article Describes Error 0Xc0000185 Explained: Troubleshooting Steps and Fixes for Windows Users"
excerpt: "This Article Describes Error 0Xc0000185 Explained: Troubleshooting Steps and Fixes for Windows Users"
thumbnail: https://thmb.techidaily.com/95333bd91bfdee977e890c3d99a260180b34b4ad300f9b943b40a4dfe4ccda73.jpg
---

## Error Code 0X80004005 Explained: Tips and Solutions to Fix It Now
 Error 0x80004005 is a type of unspecified Windows error code that usually appears as "Error Code 0x80004005\. Unspecified error." Error 0x80004005 may show up on its own or alongside other error messages. Sometimes, additional text may help you narrow down the source of the problem.

 Instructions in this article apply to[Windows 11](https://www.lifewire.com/windows-11-5188930) ,[Windows 10](https://www.lifewire.com/windows-10-2626217) ,[Windows 8](https://www.lifewire.com/windows-8-2626235) ,[Windows 7](https://www.lifewire.com/windows-7-2626265) ,[Windows Vista](https://www.lifewire.com/windows-vista-2626311) , and[Windows XP](https://www.lifewire.com/windows-xp-2626354) .

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## What Causes Error Code 0x80004005?

 Error code 0x80004005 typically happens when you access shared folders or drives, use specific programs, or have a problem installing Windows updates. Here are the most common causes of error code 0x80004005:

* Problems with[Windows Update](https://www.lifewire.com/what-is-windows-update-2624597) .
* Moving or renaming files and folders.
* Windows notification issues.
* Problems opening or extracting[compressed files](https://www.lifewire.com/what-is-a-compressed-file-2625829) and folders.

 If you notice the error occurs when you use a specific program, the problem is likely[software](https://www.lifewire.com/what-is-software-4153107) related.

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Fix Error Code 0x80004005

 Follow these steps in the order presented to troubleshoot error code 0x80004005:

1. [Run the Windows Update troubleshooter](https://support.microsoft.com/help/4027322/windows-update-troubleshooter) . The error can happen when an automatic Windows Update fails, or when files downloaded by Windows Update are corrupted. On Windows 7 or later, the easiest[way to fix problems with Windows updates](https://www.lifewire.com/how-to-fix-problems-caused-by-windows-updates-2625775) is to run the built-in automatic troubleshooter.
2. Delete everything in the Windows Update download folder. If the automatic troubleshooter does not fix the problem, open Windows[File Explorer](https://www.lifewire.com/what-is-a-file-manager-4589189) and navigate to**C:\\Windows\\SoftwareDistribution** , for Windows 11 or**C:\\Windows\\SoftwareDistribution\\Download** for earlier Windows versions, then delete everything inside the folder.
3. [Run Windows Update](https://www.lifewire.com/how-to-check-for-install-windows-updates-2624596) . If the problem is related to Windows Update, you may have to finish downloading and installing updates. After running the troubleshooter and manually deleting the files in the Windows Update folder, run Windows Update again.
4. [Delete temporary files](https://www.lifewire.com/how-to-delete-temporary-files-in-windows-2624709) . In some cases, a corrupt temporary file can cause error 0x80004005\. Use the Windows Disk Cleanup tool or type**%temp%** in the Windows search bar to find the**Temp** folder and delete everything inside it.
5. [Disable Outlook mail notifications](https://www.lifewire.com/configure-outlook-email-notifications-1173647) . The error code can occur when[Microsoft Outlook](https://www.lifewire.com/microsoft-outlook-4164620) attempts to notify you of new messages. If disabling this feature fixes the problem, then try[starting Outlook in Safe Mode](https://www.lifewire.com/outlook-safe-mode-4164302) . If that works, a simple re-install might fix your problem.
6. [Disable Windows Defender](https://www.lifewire.com/turn-off-windows-defender-4165378) . In some cases,[antivirus](https://www.lifewire.com/what-is-antivirus-software-152947) software can detect a false positive in connection with the Microsoft Outlook app. If you experience error code 0x80004005 when using Microsoft Outlook, and disabling notifications did not help, turning off antivirus software may fix the problem. Also,[disable Norton Antivirus](https://www.lifewire.com/disable-norton-antivirus-4589389) and other third-party antivirus programs you use.  
 Disabling antivirus software leaves the system vulnerable to malware. Try different[free antivirus programs](https://www.lifewire.com/best-free-antivirus-software-4151895) to find one that doesn't conflict with the applications you use.
7. [Use a different unzip program](https://www.lifewire.com/free-unzip-programs-1356643) . If you see the error code when extracting or opening compressed files (like[.zip](https://www.lifewire.com/zip-file-2622675) or[.rar](https://www.lifewire.com/rar-file-2622216) files), use a different extraction tool.
8. Re-register jdscript.dll and vbscript.dll. If you still see error 0x80004005 after trying to unzip files with other extraction tools, then re-registering these two[dynamic link libraries](https://www.lifewire.com/what-is-a-dll-file-2625852) (DLLs) may help.  
[Open the Command Prompt](https://www.lifewire.com/how-to-open-command-prompt-2618089) as an administrator, type**regsvr32 jscript.dll** , then press the**Enter** key. Then, type**regsvr32 vbscript.dll** and press**Enter** .
9. [Add a key to the Windows Registry](https://www.lifewire.com/how-to-add-change-delete-registry-keys-values-2625145) . If you suspect error 0x80004005 in conjunction with copying or moving files,[open the Windows Registry Editor](https://www.lifewire.com/how-to-open-registry-editor-2625150) and go to **HKLM\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** .  
   * On a[32-bit](https://www.lifewire.com/32-bit-64-bit-2624554) system, create a new**DWORD** [registry value](https://www.lifewire.com/what-is-a-registry-value-2626042) called**LocalAccountTokenFilterPolicy** .  
   * On a 64-bit system, create a**QWORD** registry value called**LocalAccountTokenFilterPolicy** .  
 In both cases, set the value to**numeric 1** (on), then select**OK** . After that,[restart the Windows PC](https://www.lifewire.com/how-to-reboot-a-computer-2624568) to see if the problem is fixed.  
<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![A screenshot of Windows Registry with the Numerical Value and OK button highlighted](https://www.lifewire.com/thmb/OqNevLWWV50Z3qSb36MeYz61-8Y=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/001-how-to-fix-error-code-0x80004005-4689559-7b5e14fd0ef942718355465faefbcb77.jpg)  
 Don't delete or change anything in the Windows registry unless you know what you're doing.
10. Contact support. If none of these fixes work, or if you don't want to make changes to the Windows Registry, contact customer support for your Windows PC. The manufacturer may have potential solutions.

[8 Things to Consider Before Buying a Desktop PC](https://www.lifewire.com/best-desktop-pcs-4045927)

 FAQ

* How do I fix error code ws-37398-0?  
 Error code ws-37398-0 is a PS5 error code that occurs during PlayStation network server outages. Because the error stems from PlayStation, there's nothing you can do to fix it. You must wait until the network outage resolves.
* How do I fix error code 4b538e50 2k21?  
 This error occurs in the games_NBA 2K21_ and_NBA 2K22_ . It usually means your game files are outdated, and there's a pending file download or patch. To fix it, check to see if your computer or console still has game files to download, and wait for the downloading process to complete.
* How do I fix a code 10 error in Windows?  
 To[fix code 10 errors](https://www.lifewire.com/how-to-fix-code-10-errors-2623181) , which indicate that Device Manager can't start a hardware device, first try restarting your computer. If you recently installed a device, try uninstalling and reinstalling its drivers, or see if there are driver updates to install. You can also try installing the latest Windows update.

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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-facebooks-best-picture-enhancers-top-11-tools-ranked/"><u>[New] 2024 Approved  Facebook's Best Picture Enhancers  Top 11 Tools Ranked</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-cutting-edge-gear-for-aspiring-youtube-stars/"><u>[New] In 2024, Cutting-Edge Gear for Aspiring YouTube Stars</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-top-20-tiktok-anthems-discovering-todays-hip-hop-stars-for-2024/"><u>[New] Top 20 TikTok Anthems  Discovering Today’s Hip-Hop Stars for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-unveiling-advanced-methods-to-harness-screencapture-tools-for-2024/"><u>[New] Unveiling Advanced Methods to Harness ScreenCapture Tools for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-excellent-quality-hd-screen-recorders-for-2024/"><u>[Updated] Excellent Quality HD Screen Recorders for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-pinpointing-premium-hdr-camera-brands/"><u>[Updated] Pinpointing Premium HDR Camera Brands</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-transforming-video-makeup-through-color-alignment/"><u>[Updated] Transforming Video Makeup Through Color Alignment</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-the-art-of-crafting-an-engaging-facebook-biography-in-under-157-characters/"><u>2024 Approved  The Art of Crafting an Engaging Facebook Biography in Under 157 Characters</u></a></li>
<li><a href="https://technical-tips.techidaily.com/anticipated-launch-of-oneplus-10-insights-on-cost-schedule-characteristics-and-hype/"><u>Anticipated Launch of OnePlus 10: Insights on Cost, Schedule, Characteristics & Hype</u></a></li>
<li><a href="https://technical-tips.techidaily.com/beginners-roadmap-to-establishing-a-presence-in-playstation-network/"><u>Beginner’s Roadmap to Establishing a Presence in PlayStation Network</u></a></li>
<li><a href="https://technical-tips.techidaily.com/capturing-perfect-shots-with-an-iphone-camera-timer-a-step-by-step-approach/"><u>Capturing Perfect Shots with an iPhone Camera Timer – A Step-by-Step Approach</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/el-conversion-secrets-yt-vs-igtv-for-2024/"><u>Channel Conversion Secrets  YT Vs IGTV for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-secrets-of-retrieving-wireless-network-key-in-windows-11-easily/"><u>Discover the Secrets of Retrieving Wireless Network Key in Windows 11 Easily</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/elite-mac-options-surpassing-bandicams-video-capabilities-for-2024/"><u>Elite Mac Options  Surpassing Bandicam's Video Capabilities for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/essential-checklist-key-points-to-review-prior-to-investing-in-a-smart-tv/"><u>Essential Checklist: Key Points to Review Prior to Investing in a Smart TV</u></a></li>
<li><a href="https://technical-tips.techidaily.com/guide-to-resolving-the-problem-of-an-apple-watch-that-ignores-stand-detection/"><u>Guide To Resolving The Problem Of An Apple Watch That Ignores Stand Detection</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-quickly-fix-connectivity-problems-with-a-wireless-router-or-access-point/"><u>How to Quickly Fix Connectivity Problems with a Wireless Router or Access Point</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-realme-narzo-n53-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Realme Narzo N53 Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-share-several-photos-at-once-on-your-facebook-timeline/"><u>How to Share Several Photos at Once on Your Facebook Timeline</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-solve-rockaldlldll-could-not-be-located-problem-effectively/"><u>How to Solve 'rockaldll.dll Could Not Be Located' Problem Effectively</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-digital-experts-5-favorite-video-recorders/"><u>In 2024, Digital Experts' 5 Favorite Video Recorders</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-xiaomi-redmi-a2plus-drfone-by-drfone-virtual-android/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Xiaomi Redmi A2+? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-samsung-galaxy-f04-drfone-by-drfone-virtual-android/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Samsung Galaxy F04? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-lost-legacies-found-revelations-from-the-canon-of-classical-works/"><u>In 2024, Lost Legacies Found  Revelations From the Canon of Classical Works</u></a></li>
<li><a href="https://technical-tips.techidaily.com/july-2024-hotlist-top-kids-movies-to-watch-on-disney-plus/"><u>July 2024 Hotlist: Top Kids Movies to Watch on Disney Plus!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/master-photography-edits-remedying-pets-eyeball-appearances-seamlessly/"><u>Master Photography Edits: Remedying Pets' Eyeball Appearances Seamlessly</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-gameplay-problems-and-crashes-in-hearts-of-iron-4/"><u>Overcoming Gameplay Problems and Crashes in Hearts of Iron 4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steps-to-obtain-trustee-access-from-trustedinstaller-for-file-modification/"><u>Steps to Obtain Trustee Access From TrustedInstaller for File Modification</u></a></li>
<li><a href="https://technical-tips.techidaily.com/tackling-windows-code-28/"><u>Tackling Windows Code 지표 28에서 열견되는 문제 해결기</u></a></li>
<li><a href="https://technical-tips.techidaily.com/tech-deals-for-learners-how-to-qualify-and-save-with-microsoft-store-offers/"><u>Tech Deals for Learners: How to Qualify and Save with Microsoft Store Offers</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-meta-quest-3-lite-an-inside-look-at-potential-pricing-release-schedule-and-speculated-technical-specifications/"><u>The Meta Quest 3 Lite: An Inside Look at Potential Pricing, Release Schedule, and Speculated Technical Specifications</u></a></li>
<li><a href="https://technical-tips.techidaily.com/tips-for-addressing-and-repairing-kernel-data-mishaps/"><u>Tips for Addressing and Repairing Kernel Data Mishaps</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/top-5-essential-factors-to-assess-when-selecting-your-ideal-fitness-tracker/"><u>Top 5 Essential Factors to Assess When Selecting Your Ideal Fitness Tracker</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-guide-resolving-the-notorious-code-19-issues-on-your-windows-pc/"><u>Troubleshooting Guide: Resolving the Notorious 'Code 19' Issues on Your Windows PC</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ultimate-selection-of-wi-fi-expansion-devices-for-the-year-2024/"><u>Ultimate Selection of Wi-Fi Expansion Devices for the Year 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unlocking-the-mystery-of-authenticity-how-to-get-that-verified-checkmark-on-instagram/"><u>Unlocking the Mystery of Authenticity: How To Get That Verified Checkmark on Instagram</u></a></li>
<li><a href="https://technical-tips.techidaily.com/worth-the-price-tag-assessing-the-impact-of-wi-fi-mesh-networks-on-connectivity/"><u>Worth the Price Tag? Assessing the Impact of Wi-Fi Mesh Networks on Connectivity</u></a></li>
<li><a href="https://technical-tips.techidaily.com/yahoo-mail-termination-process-a-comprehensive-guide-for-eternal-deletion/"><u>Yahoo Mail Termination Process: A Comprehensive Guide for Eternal Deletion</u></a></li>
</ul></div>
