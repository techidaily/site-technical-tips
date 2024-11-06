---
title: "Navigating Permissions: Understanding and Working Around the TrustedInstaller in Windows 11"
date: 2024-11-04T17:03:21.772Z
updated: 2024-11-05T22:58:08.574Z
categories:
  - BestProducts
description: "This Article Describes Navigating Permissions: Understanding and Working Around the TrustedInstaller in Windows 11"
excerpt: "This Article Describes Navigating Permissions: Understanding and Working Around the TrustedInstaller in Windows 11"
thumbnail: https://thmb.techidaily.com/3fc4ce39cf32e051d437369f1ad4829a21ac17b8d3ad76e322c0705c64d5daa2.png
---

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Navigating Permissions: Understanding and Working Around the TrustedInstaller in Windows 11
### What to Know

* Use the**TAKEOWN** and**icacls** Command Prompt commands to take ownership of the file or folder.
* Or, right-click the item and go to**Properties** \>**Security** \>**Advanced** to add yourself to the list.
* TrustedInstaller is a built-in user account that owns lots of important system files.

 This article describes two ways to deal with the message in Windows 10 about needing permission from TrustedInstaller to make changes to a file or folder.

## How to Fix the TrustedInstaller Error Using Command Prompt

 There are two really simple[Command Prompt commands](https://www.lifewire.com/list-of-command-prompt-commands-4092302) you can use to bypass the TrustedInstaller permissions prompt. Follow these steps to fix the TrustedInstaller "error" by granting your user account permission to make changes to the file or folder:

1. [Open an elevated Command Prompt](https://www.lifewire.com/how-to-open-an-elevated-command-prompt-2618088) . The quickest way there is to search for it from the Start menu, right-click the result, and choose**Run as administrator** .  
![The Run As Administrator option for the Windows 10 Command Prompt](https://www.lifewire.com/thmb/qK50_I4SdSJ98eEbO9R6yPSN1Vk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/command-prompt-admin-windows-10-45f7ecab69a442f489eaf6a499a353d4.png)
2. Enter**TAKEOWN /F** and then type the file or folder name. Here's an example:  

 `TAKEOWN /F C:\Windows\System32\fr-FR\fms.dll.mui`
3. Press**Enter** to take control of the file. You'll see a success message if the command executed correctly.  
![The TAKEOWN /F command in Windows 10 Command Prompt](https://www.lifewire.com/thmb/nOnoS4n34cd8C2EJEDT2_rLzdhw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/takeown-command-trustsedinstaller-windows-10-267bfffb4f974a29940a0af233ef4a84.png)
4. Enter the following command (replacing our example file with your own) to immediately give your user account permission to delete or change the file or folder:  

 `icacls C:\Windows\System32\fr-FR\fms.dll.mui /grant Administrators:F /T`  
![icacls command executed in Windows 10 Command Prompt](https://www.lifewire.com/thmb/clN3CT0-H0V3QdOSRZWprDCigZ4=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/icacls-command-windows-10-7f562cffaf424cd281b4e58c68b19e25.png)

## Edit the File's Security Options to Fix the TrustedInstaller Error

 If you don't feel comfortable using Command Prompt to take ownership of the folder or file, there is another way. Here's how to use File Explorer to edit the security settings for the data, which will let you delete or modify it as needed.

Make sure you are logged in as an administrator.

1. Locate the item you need permission to change and then right-click it and choose**Properties** .  
![The context menu for a Windows 10 folder ](https://www.lifewire.com/thmb/CSwAkry59uiW_sJ5GzqkO0QrOuk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/context-menu-folder-windows-10-0447423a01764cecad790f8dc6303c59.png)
2. Go to**Security** \>**Advanced** , then select**Change** next to**Owner: TrustedInstaller** .  

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657386/16446" target="_top" id="1657386">
  <img src="//a.impactradius-go.com/display-ad/16446-1657386" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657386/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Properties and Advanced Security Settings options for a Windows 10 folder](https://www.lifewire.com/thmb/823H3LgLGW5GbhyNSwSn1HNUZlk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/advanced-security-settings-windows-10-folder-4eb4fed4cb134eb1ba00993a705f7175.png)
3. Type your username into the text box and then choose**Check Names** \>**OK** .  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902273/19272" target="_top" id="1902273">
  <img src="//a.impactradius-go.com/display-ad/19272-1902273" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902273/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Windows 10 Check Names box with a user account listed](https://www.lifewire.com/thmb/ESMv2bIcNtWxpryKYLlwZFwmyCA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/windows-10-select-user-or-group-880cbe35a52348f19d11206db4d7a0b6.png)
4. Check the box next to**Replace owner on subcontainers and objects** .  
![The replace owner on subcontainers and objects checkbox in Windows 10](https://www.lifewire.com/thmb/n8OW45wPPq3HiSTrW4eQIT_Y0EU=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/replace-owner-windows-10-folder-885ef894881e4e21a60b1b09568ea020.png)
5. Select**OK** at the bottom and then**OK** on the Properties window you opened in Step 1.
6. Open**Properties** \>**Security** \>**Advanced** once more. This time, select**Add** .  
![The Advanced Security Settings for a Windows 10 folder](https://www.lifewire.com/thmb/fEVYPGbUtSiGdO8kZg1RZd6gtIE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/add-button-advanced-security-settings-3ffcde5bc8b942278219bbd9b4663921.png)
7. Choose**Select a principal** and then type your username in the box.

8. Press**Check Names** \>**OK** .  
![A user account listed in the Select User or Group box for a Windows 10 folder](https://www.lifewire.com/thmb/a8Ie_eyPviEwOjytgb9HHofaQgc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/select-user-group-windows-10-security-b2ffe7d116f2424e845a612090d4e932.png)
9. Check the box next to**Full control** , then select**OK** .  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123727/7443" target="_top" id="2123727">
  <img src="//a.impactradius-go.com/display-ad/7443-2123727" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123727/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Full Control permission selected for a folder in Windows 10](https://www.lifewire.com/thmb/cLa_4Jv8moyuFMZaNvHFNWAcllw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/full-control-folder-permissions-b0f31e6f8d7d418e91990e6c32476c30.png)
10. Check the box next to **Replace all child object permission entries with inheritable permission entries from this object** .  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997722/19272" target="_top" id="1997722">
  <img src="//a.impactradius-go.com/display-ad/19272-1997722" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997722/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The checkbox called Replace all child object permission entries in Windows 10](https://www.lifewire.com/thmb/6T2vTKuuRj3ONEWEpCefVrYtszQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/replace-all-child-object-permission-entries-windows-10-fc09040d1d8b4357b5866ced25b79262.png)
11. Select**OK** on the Advanced Security Settings window and then**Yes** on the confirmation prompts. You should now have full permission to make changes to the file or folder, and you can close any other windows you opened to make these changes.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1610918/18409" target="_top" id="1610918">
  <img src="//a.impactradius-go.com/display-ad/18409-1610918" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://coinrule.sjv.io/i/5597632/1610918/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Why Do I Need Permission From TrustedInstaller?

 Provided you're the primary user of your home computer, you might be surprised to find out you need anyone’s permission to deal with files on your own PC.

 All Windows 10 PCs have an in-built Microsoft account known as the TrustedInstaller. This account exists to prevent accidental damage to important system files, so it's given ownership over many important operating system files. For you to be able to take control of these files, you need to make yourself the owner as described above.  

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-direct-recording-tool-for-chrome-os/"><u>[New] 2024 Approved Direct Recording Tool for Chrome OS</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-unrivaled-windows-video-calls-top-8-apps/"><u>[New] 2024 Approved Unrivaled Windows Video Calls Top 8 Apps</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-direct-download-of-youtube-videos/"><u>[New] In 2024, Direct Download of YouTube Videos</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-enriched-viewing-experience-with-these-free-downloader-apps-for-youtubes/"><u>[New] In 2024, Enriched Viewing Experience with These Free Downloader Apps for YouTubes</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-secure-recording-techniques-masking-personal-details-for-2024/"><u>[New] Secure Recording Techniques Masking Personal Details for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-chart-your-course-navigating-the-waters-of-youtube-subscription-surges-for-2024/"><u>[Updated] Chart Your Course Navigating the Waters of YouTube Subscription Surges for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/apple-unveils-the-upgraded-mac-studio-a-matured-version-of-the-classic-mac-mini/"><u>Apple Unveils the Upgraded Mac Studio - A Matured Version of the Classic Mac Mini</u></a></li>
<li><a href="https://technical-tips.techidaily.com/choosing-loyalty-over-upgrades-why-i-remain-committed-to-my-apple-watch-series/"><u>Choosing Loyalty Over Upgrades: Why I Remain Committed to My Apple Watch Series</u></a></li>
<li><a href="https://technical-tips.techidaily.com/college-students-ultimate-hack-setting-up-a-portable-wireless-tv-system-in-shared-spaces/"><u>College Students' Ultimate Hack: Setting Up a Portable Wireless TV System in Shared Spaces</u></a></li>
<li><a href="https://technical-tips.techidaily.com/deciphering-the-next-gen-airpods-what-sets-the-airpods-pro-and-max-apart-according-to-zdnet/"><u>Deciphering the Next-Gen AirPods: What Sets the AirPods Pro & Max Apart According to ZDNET</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-restore-sounds-in-black-ops-cold-war-a-comprehensive-guide-for-windows-players/"><u>How to Restore Sounds in Black Ops Cold War - A Comprehensive Guide for Windows Players</u></a></li>
<li><a href="https://data-wizards.techidaily.com/pioneering-approaches-to-data-rescue-stellar-edition-by-singh/"><u>Pioneering Approaches to Data Rescue: Stellar Edition by Singh</u></a></li>
<li><a href="https://technical-tips.techidaily.com/protecting-against-threats-for-less-a-selection-of-15-recommended-free-bootable-anti-viruses/"><u>Protecting Against Threats for Less: A Selection of 15 Recommended Free Bootable Anti-Viruses</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/top-5-hidden-gems-to-watch-insta-stories-for-2024/"><u>Top 5 Hidden Gems to Watch Insta Stories for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-rated-waterproof-wearables-comprehensive-tests-and-reviews-by-tech-experts-zdnet/"><u>Top-Rated Waterproof Wearables : Comprehensive Tests & Reviews by Tech Experts | ZDNet</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unveiling-the-ultimate-collection-of-professional-video-editors-the-top-5-selections/"><u>Unveiling the Ultimate Collection of Professional Video Editors - The Top 5 Selections</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unveiling-timeline-all-you-need-to-know-about-new-airpods-launch-and-pre-order-info-zdnet-exclusive/"><u>Unveiling Timeline: All You Need To Know About New AirPods Launch & Pre-Order Info - ZDNet Exclusive</u></a></li>
</ul></div>

