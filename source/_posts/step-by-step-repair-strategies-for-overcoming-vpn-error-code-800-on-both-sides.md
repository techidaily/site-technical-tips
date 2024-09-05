---
title: Step-by-Step Repair Strategies for Overcoming VPN Error Code 800 on Both Sides
date: 2024-09-04T01:00:39.240Z
updated: 2024-09-05T01:00:39.240Z
categories:
  - BestProducts
description: This Article Describes Step-by-Step Repair Strategies for Overcoming VPN Error Code 800 on Both Sides
excerpt: This Article Describes Step-by-Step Repair Strategies for Overcoming VPN Error Code 800 on Both Sides
thumbnail: https://www.lifewire.com/thmb/VnNd7pg1gKy2XNVGJEMHuSLdsJA=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/GettyImages-451913781-5743e1a93df78c6bb02c9b54.jpg
---

## Error Code 0X80004005 Resolved? Step-by-Step Strategies to Fix It
 Error 0x80004005 is a type of unspecified Windows error code that usually appears as "Error Code 0x80004005\. Unspecified error." Error 0x80004005 may show up on its own or alongside other error messages. Sometimes, additional text may help you narrow down the source of the problem.

 Instructions in this article apply to[Windows 11](https://www.lifewire.com/windows-11-5188930) ,[Windows 10](https://www.lifewire.com/windows-10-2626217) ,[Windows 8](https://www.lifewire.com/windows-8-2626235) ,[Windows 7](https://www.lifewire.com/windows-7-2626265) ,[Windows Vista](https://www.lifewire.com/windows-vista-2626311) , and[Windows XP](https://www.lifewire.com/windows-xp-2626354) .

## What Causes Error Code 0x80004005?

 Error code 0x80004005 typically happens when you access shared folders or drives, use specific programs, or have a problem installing Windows updates. Here are the most common causes of error code 0x80004005:

* Problems with[Windows Update](https://www.lifewire.com/what-is-windows-update-2624597) .
* Moving or renaming files and folders.
* Windows notification issues.
* Problems opening or extracting[compressed files](https://www.lifewire.com/what-is-a-compressed-file-2625829) and folders.

 If you notice the error occurs when you use a specific program, the problem is likely[software](https://www.lifewire.com/what-is-software-4153107) related.

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
<li><a href="https://on-screen-recording.techidaily.com/new-androids-finest-moba-battles-compilation-10-edition/"><u>[New] Android's Finest MOBA Battles Compilation (#10 Edition)</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-directing-youtube-and-twitter-videos-via-whatsapp-messages/"><u>[New] Directing YouTube & Twitter Videos via WhatsApp Messages</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-inventory-of-videography-items-for-exploration/"><u>[New] Inventory of Videography Items for Exploration</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-tailoring-a-unique-identity-a-roadmap-to-more-youtube-followers/"><u>[New] Tailoring a Unique Identity  A Roadmap to More YouTube Followers</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-ultimate-select-masterful-instagram-hlv-artisans/"><u>[New] Ultimate Select  Masterful Instagram HLV Artisans</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-life-written-in-stillness-to-moving-pictures/"><u>[Updated] From Life' Written in Stillness to Moving Pictures</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-hands-on-crafting-unique-movie-closures-for-pennies/"><u>[Updated] In 2024, Hands-On  Crafting Unique Movie Closures for Pennies</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-acid-pro-alternatives-a-comprehensive-guide/"><u>2024 Approved  ACID Pro Alternatives  A Comprehensive Guide</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-simplified-customization-for-your-youtube-channel-url/"><u>2024 Approved  Simplified Customization for Your YouTube Channel URL</u></a></li>
<li><a href="https://blog-min.techidaily.com/1725290604089-mp3ogg4/"><u>最新技術：MP3から高音質OGGへの圧縮無料変換4つの方法</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-poco-m6-pro-4g-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Poco M6 Pro 4G</u></a></li>
<li><a href="https://extra-resources.techidaily.com/audible-brilliance-the-ultimate-mic-guide-for-2024/"><u>Audible Brilliance  The Ultimate Mic Guide for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/beating-the-blues-with-netflix-comprehensive-strategies-for-overcoming-ui-800-3-glitches/"><u>Beating the Blues with Netflix: Comprehensive Strategies for Overcoming UI-800-3 Glitches</u></a></li>
<li><a href="https://technical-tips.techidaily.com/before-you-level-up-check-these-5-must-know-points-when-buying-a-game-console/"><u>Before You Level Up? Check These 5 Must-Know Points When Buying a Game Console</u></a></li>
<li><a href="https://technical-tips.techidaily.com/bring-the-world-of-streaming-into-your-home-cinema-system-with-ease/"><u>Bring the World of Streaming Into Your Home Cinema System with Ease</u></a></li>
<li><a href="https://technical-tips.techidaily.com/common-problems-and-solutions-for-non-working-in-car-radios/"><u>Common Problems and Solutions for Non-Working In-Car Radios</u></a></li>
<li><a href="https://technical-tips.techidaily.com/comprehensive-d-link-default-credentials-the-latest-update-for-july-2024/"><u>Comprehensive D-Link Default Credentials: The Latest Update for July 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/deactivate-critical-messaging-warnings-on-iphones-with-this-simple-tutorial/"><u>Deactivate Critical Messaging Warnings on iPhones with This Simple Tutorial</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-most-enjoyable-free-movies-to-watch-on-youtube-in-july-2024/"><u>Discover the Most Enjoyable Free Movies to Watch on YouTube in July 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/duo-data-integration-seamlessly-combining-columns-in-microsoft-excel/"><u>Duo Data Integration: Seamlessly Combining Columns in Microsoft Excel</u></a></li>
<li><a href="https://technical-tips.techidaily.com/easy-fixes-for-your-tvs-frequent-malfunctions-a-step-by-step-guide/"><u>Easy Fixes for Your TV's Frequent Malfunctions – A Step-by-Step Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/explore-enigmatic-puzzle-worlds-top-apple-device-titles-akin-to-the-room-and-myst/"><u>Explore Enigmatic Puzzle Worlds: Top Apple Device Titles Akin to ‘The Room’ and ‘Myst’</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/exploring-forefront-ais-strengths-over-chatgpt/"><u>Exploring Forefront AI's Strengths Over ChatGPT</u></a></li>
<li><a href="https://driver-install.techidaily.com/get-canon-scan-software-in-minutes-for-pcs/"><u>Get Canon Scan Software in Minutes for PCs</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/get-ready-to-rewind-top-10-slow-motion-video-players/"><u>Get Ready to Rewind Top 10 Slow Motion Video Players</u></a></li>
<li><a href="https://change-location.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-vivo-y27s-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Vivo Y27s? | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-fix-cannot-open-file-error-in-microsoft-word-step-by-step-guide/"><u>How to Fix 'Cannot Open File' Error in Microsoft Word – Step-by-Step Guide</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-se-2022-to-other-iphone-12-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone SE (2022) To Other iPhone 12 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-tecno-pova-6-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Tecno Pova 6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-humorous-highlights-create-with-kapwing-meme-maker/"><u>In 2024, Humorous Highlights  Create with Kapwing Meme Maker</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/g-an-impact-professional-thumbnail-design-for-youtube-for-2024/"><u>Making an Impact  Professional Thumbnail Design for YouTube for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722853325454-mastering-pokemon-go-a-comprehensive-guide/"><u>Mastering 'Pokémon Go': A Comprehensive Guide</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/mastering-content-strategy-after-the-facebook-revamp-for-2024/"><u>Mastering Content Strategy After the Facebook Revamp for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/overcoming-viewing-hurdles-on-netflix-fixing-playback-troubles-easily/"><u>Overcoming Viewing Hurdles on Netflix - Fixing Playback Troubles Easily</u></a></li>
<li><a href="https://technical-tips.techidaily.com/professional-tricks-how-to-insert-customized-lines-in-microsoft-word/"><u>Professional Tricks: How to Insert Customized Lines in Microsoft Word</u></a></li>
<li><a href="https://data-wizards.techidaily.com/reestablishing-high-quality-display-on-win11/"><u>Reestablishing High-Quality Display on Win11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/resolving-code-28-issues-on-your-windows-pc-a-step-by-step-guide/"><u>Resolving 'Code: 28' Issues on Your Windows PC – A Step-by-Step Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/resolving-x3daudiodll-file-absent-issues-a-step-by-step-guide/"><u>Resolving 'X3DAudio.dll' File Absent Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/seamless-streaming-made-simple-how-to-enable-vlc-for-apple-tv-viewing/"><u>Seamless Streaming Made Simple: How to Enable VLC for Apple TV Viewing</u></a></li>
<li><a href="https://technical-tips.techidaily.com/selecting-a-smart-device-pros-and-cons-of-iphones-vs-android-phones/"><u>Selecting a Smart Device: Pros and Cons of iPhones vs Android Phones</u></a></li>
<li><a href="https://blog-min.techidaily.com/story-2-the-myth-of-dormancy-indication/"><u>Story 2: The Myth of Dormancy Indication</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-comprehensive-guide-to-micromobility-timelines-breaking-stories-rumored-trends-and-in-depth-analysis/"><u>The Comprehensive Guide to Micromobility Timelines: Breaking Stories, Rumored Trends & In-Depth Analysis</u></a></li>
<li><a href="https://screen-capture.techidaily.com/the-key-steps-effective-obs-streaming-directly-to-facebook-users-for-2024/"><u>The Key Steps  Effective OBS Streaming Directly to Facebook Users for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-guide-to-overcoming-a-502-bad-gateway-dilemma-online/"><u>The Ultimate Guide to Overcoming a 502 Bad Gateway Dilemma Online</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-8-methods-to-correctly-remove-the-bluish-hue-from-your-television-display/"><u>Top 8 Methods to Correctly Remove the Bluish Hue From Your Television Display</u></a></li>
<li><a href="https://technical-tips.techidaily.com/tricks-to-prevent-auto-sleep-on-macbook-when-you-close-the-lid/"><u>Tricks to Prevent Auto-Sleep on MacBook When You Close the Lid.</u></a></li>
<li><a href="https://technical-tips.techidaily.com/trustworthy-hardware-reviews-and-tips-from-toms-haven/"><u>Trustworthy Hardware Reviews and Tips From Tom's Haven</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ultimate-guide-creating-your-new-x-previously-known-as-twitter-profile/"><u>Ultimate Guide: Creating Your New X (Previously Known as Twitter) Profile</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ultimate-guide-linking-your-samsung-soundbar-with-your-television/"><u>Ultimate Guide: Linking Your Samsung Soundbar with Your Television</u></a></li>
<li><a href="https://technical-tips.techidaily.com/understanding-patch-tuesday-an-essential-guide/"><u>Understanding Patch Tuesday: An Essential Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/universal-access-to-icloud-images-techniques-for-apple-windows-and-android-users/"><u>Universal Access to iCloud Images: Techniques for Apple, Windows, and Android Users</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/unleash-your-youtube-potential-with-easy-techniques-for-2024/"><u>Unleash Your YouTube Potential with Easy Techniques for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unlocking-the-secrets-to-seamlessly-getting-in-and-out-of-iphone-recovery-mode/"><u>Unlocking the Secrets to Seamlessly Getting In and Out of iPhone Recovery Mode</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-video-speed-adjustment-made-easy-in-camtasia/"><u>Updated In 2024, Video Speed Adjustment Made Easy in Camtasia</u></a></li>
<li><a href="https://technical-tips.techidaily.com/watch-the-tokyo-2024-summer-contests-live-from-home-a-complete-guide/"><u>Watch the Tokyo 2024 Summer Contests Live From Home – A Complete Guide</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1531879">
					<video width="540" height="960" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531879.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531879">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531879.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531879%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531879/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->