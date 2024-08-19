---
title: "Easy Connection for Double Viewing: Adding a Second Screen in Windows 10"
date: 2024-08-18T19:37:17.650Z
updated: 2024-08-19T19:37:17.650Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Easy Connection for Double Viewing: Adding a Second Screen in Windows 10"
excerpt: "This Article Describes Easy Connection for Double Viewing: Adding a Second Screen in Windows 10"
thumbnail: https://thmb.techidaily.com/a65df42cc8379f3aa4b0bec4cca01f43716f0f93a74b7a32e511a24eeedbecef.jpg
---

## Effective Winsxs Directory Management: Free Up Disk Space on Windows 11 in a Flash

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_59759c33baabd.png)

 This is among the usually asked questions: can I delete WinSxS folder to free up some disk space?

The answer is, no.

 Nor can you delete everything in the WinSxS folder, because some of the files are important for Windows to run and update. Basically, WinSxS folder is where the files needed for your Windows are, as well as backups and/or updates of those files.

 But there are many ways you can use to reduce the size for your WinSxS folder on Windows 10\. In this post, we will be introducing two of them. So you will at least have one option that works.

[**1. Use Disk Cleanup**](https://tools.techidaily.com/drivereasy/download/)

[**2. Use DISM Tool**](https://tools.techidaily.com/drivereasy/download/)

**WARNING** : It is never suggested that you use a third-party tool to cleanup your WinSxS file, since faulty deleting the whole folder or some files in the folder might end up breaking your computer, making it impossible to boot or update.

## **1\. Use Disk Cleanup**

 Disk cleanup is a built-in tool that helps you delete temporary files. To run it, just follow:

 1) On your keyboard, press**Windows logo** button, then type in**disk cleanup** . Then choose**Disk Cleanup** from the list.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b754c83e3.png)

 2) If you haven’t changed the location where you placed your system file, choose**(C:)** and click**OK** . If you have changed the file location before, choose the correct file directory accordingly.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b948ea778.png)

 3) Under**Files to delete** sector, tick the boxes before the files you don’t need anymore and then hit**OK** to delete them. Select to highlight the file name to see more detailed information if you want.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bc59c244b.png)

 4) If you need to free more space, you can also choose**Clean up system files** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf02990e3.png)

 Then you will be prompted to choose which system drive you want to clean up. Choose accordingly and the clean process will start right away.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf68b4ff6.png)

## **2\. Use DISM Tool**

**DISM**  stands for Deployment Image & Servicing Management. It is a tool that allows you to make changes to Windows features, packages, drivers, and international settings. In this case, we will use it to help us clean up our WinSxS folder.

 The process may take a long time. It some cases, it could take up to 30 minutes. Please don’t worry when it’s not finished after a long time. Please be patient until the process finishes.

 1) On your keyboard, press **Windows logo key**   and **X**   at the same time, then choose **Command Prompt (Admin)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1bb42138.png)

 When prompted with the UAC, hit **Yes** to continue.

 2) In DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup

 This command helps you clean up files when your system is not in use.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1fc428ac.png)

 3) Check for possible typo. Then hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c4b394177.png)

 4) In the same DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup /ResetBase

 This command helps you remove all superseded versions of every component in the component store.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c546794f7.png)

 5) Make sure you have made no typo and hit**Enter** . Wait for it to finish.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c55d520c4.png)

 6) Still in the same window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /SPSuperseded

 This command helps you reduce the amount of space used by a Service Pack.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5c8b3c70.png)

7) Make sure that you have made no typo and hit Enter.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5eb65aaf.png)

 If you need more assistance, feel free to leave us comment and we will see what else we can do to help.

Hope your problem solved!

* [system](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-elevate-social-media-engagement-cutting-edge-fb-ad-techniques/"><u>[New] 2024 Approved  Elevate Social Media Engagement  Cutting-Edge FB Ad Techniques</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-how-to-respond-to-unexpected-content-rejections-by-fb-platform/"><u>[New] How to Respond to Unexpected Content Rejections by FB Platform</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-unlocking-success-with-youtube-on-facebook/"><u>[New] In 2024, Unlocking Success with YouTube on Facebook</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-top-youtube-concepts-for-channel-motivation-and-creativity/"><u>[New] Top YouTube Concepts for Channel Motivation and Creativity</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-5-high-quality-displays-for-unparalleled-games/"><u>[Updated] 5 High-Quality Displays for Unparalleled Games</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-for-students-discover-the-top-10-historical-youtube-channels-now/"><u>[Updated] For Students, Discover the Top 10 Historical YouTube Channels Now</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-the-dynamics-of-home-security-manycam-vs-single-camera-tech/"><u>[Updated] In 2024, The Dynamics of Home Security  ManyCam Vs. Single-Camera Tech</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-superior-5-digital-capture-devices-for-2024/"><u>[Updated] Superior 5 Digital Capture Devices for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-your-ultimate-guide-to-perfectly-recorded-lol-gaming/"><u>[Updated] Your Ultimate Guide to Perfectly Recorded LOL Gaming</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-countdown-creation-in-obs-step-by-step-guide/"><u>2024 Approved  Countdown Creation in OBS  Step-by-Step Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-detailed-app-analysis-the-ultimate-az-recorder-guide/"><u>2024 Approved  Detailed App Analysis - The Ultimate AZ Recorder Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-influencing-the-masses-powerful-tags-for-daily-engagement/"><u>2024 Approved  Influencing the Masses  Powerful Tags for Daily Engagement</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-the-definitive-guide-to-affordable-video-calls-online/"><u>2024 Approved  The Definitive Guide to Affordable Video Calls Online</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/affordable-entertainment-alert-dive-into-sing-along-bliss-with-karaoke-usa-for-less-than-150/"><u>Affordable Entertainment Alert: Dive Into Sing-Along Bliss with Karaoke USA for Less than $150</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/an-insightful-critique-how-watch-dogs-legon-revolutionizes-its-franchise-with-a-fresh-backdrop/"><u>An Insightful Critique: How Watch Dogs: Legon Revolutionizes Its Franchise with a Fresh Backdrop</u></a></li>
<li><a href="https://fox-info.techidaily.com/become-a-close-up-connoisseur-advanced-roleplay-tips/"><u>Become a Close-Up Connoisseur  Advanced Roleplay Tips</u></a></li>
<li><a href="https://technical-tips.techidaily.com/decoding-the-buzz-around-tesla-robotaxi-price-estimates-expected-release-dates-and-technical-innovations-revealed/"><u>Decoding the Buzz Around Tesla Robotaxi: Price Estimates, Expected Release Dates and Technical Innovations Revealed</u></a></li>
<li><a href="https://technical-tips.techidaily.com/dell-laptop-maintenance-made-easy-ultimate-tips-for-effective-cleaning/"><u>Dell Laptop Mainten#ance Made Easy: Ultimate Tips for Effective Cleaning</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/digital-companion-fb-stories-collector/"><u>Digital Companion - FB Stories Collector</u></a></li>
<li><a href="https://technical-tips.techidaily.com/effective-fixes-for-overcoming-mfc42dll-not-found-issues-in-windows/"><u>Effective Fixes for Overcoming 'mfc42.dll Not Found' Issues in Windows</u></a></li>
<li><a href="https://technical-tips.techidaily.com/effortless-guide-setting-up-and-managing-bots-on-a-discord-server/"><u>Effortless Guide: Setting Up and Managing Bots on a Discord Server</u></a></li>
<li><a href="https://technical-tips.techidaily.com/eight-expert-recommended-tools-for-successful-online-person-tracking/"><u>Eight Expert-Recommended Tools for Successful Online Person Tracking</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ensuring-email-privacy-how-to-mark-a-domain-as-trusted-in-macos-mail-application/"><u>Ensuring Email Privacy: How to Mark a Domain as Trusted in macOS Mail Application</u></a></li>
<li><a href="https://technical-tips.techidaily.com/evolution-of-apples-ios-a-comprehensive-journey-from-version-10-to-180/"><u>Evolution of Apple's iOS: A Comprehensive Journey From Version 1.0 to 18.0</u></a></li>
<li><a href="https://technical-tips.techidaily.com/find-your-perfect-match-with-these-easy-to-use-free-digital-planners/"><u>Find Your Perfect Match With These Easy to Use, Free Digital Planners</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/fixing-missing-dbghelpdll-file-errors-easy-solutions-for-windows-users/"><u>Fixing Missing dBghelp.dll File Errors: Easy Solutions for Windows Users</u></a></li>
<li><a href="https://some-techniques.techidaily.com/generate-laughter-kapwings-meme-creator-for-2024/"><u>Generate Laughter  Kapwing's Meme Creator for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-canon-mf4500-printer-drivers-for-seamless-printing/"><u>Get the Latest Canon MF4500 Printer Drivers for Seamless Printing</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-compile-multiple-jpegs-together-into-one-consolidated-pdf-format/"><u>How to Compile Multiple JPEGs Together Into One Consolidated PDF Format</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-tell-if-your-device-is-a-true-ipad-or-just-a-regular-tablet/"><u>How to Tell if Your Device Is a True iPad or Just a Regular Tablet</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-activation-lock-from-the-apple-iphone-xs-max-without-previous-owner-by-drfone-ios/"><u>In 2024, How to Remove Activation Lock From the Apple iPhone XS Max Without Previous Owner?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-remove-forgotten-pin-of-your-honor-magic-6-by-drfone-android/"><u>In 2024, How to Remove Forgotten PIN Of Your Honor Magic 6</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Reasons why Pokémon GPS does not Work On Vivo Y100 5G? | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/integrating-pinterest-tabs-into-your-facebook-page-a-comprehensive-guide/"><u>Integrating Pinterest Tabs Into Your Facebook Page: A Comprehensive Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/introduction-to-aether-an-exploration-of-its-essence-and-entry-methods/"><u>Introduction to Aether - An Exploration of Its Essence and Entry Methods</u></a></li>
<li><a href="https://technical-tips.techidaily.com/macbook-air-locked-up-follow-these-techniques-for-quick-unfreeze-solutions/"><u>MacBook Air Locked Up? Follow These Techniques for Quick Unfreeze Solutions</u></a></li>
<li><a href="https://technical-tips.techidaily.com/master-the-art-of-purging-your-apple-devices-dns-cache-a-complete-tutorial/"><u>Master the Art of Purging Your Apple Device's DNS Cache - A Complete Tutorial</u></a></li>
<li><a href="https://technical-tips.techidaily.com/master-the-art-of-putting-keys-back-on-your-damaged-laptop-keyboard-learn-how-now/"><u>Master the Art of Putting Keys Back on Your Damaged Laptop Keyboard - Learn How Now</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-mobile-reading-secrets-to-buying-and-enjoying-ebooks-on-ios-equipment-via-apples-digital-library/"><u>Mastering Mobile Reading: Secrets to Buying and Enjoying eBooks on iOS Equipment via Apple's Digital Library</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigating-the-return-policy-how-to-get-money-back-for-steam-games/"><u>Navigating the Return Policy: How to Get Money Back for Steam Games</u></a></li>
<li><a href="https://technical-tips.techidaily.com/overcoming-delay-problems-optimizing-connection-for-chromecast-and-phone-systems/"><u>Overcoming Delay Problems: Optimizing Connection for Chromecast and Phone Systems</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ps5-controller-power-problems-heres-how-to-get-it-charging-again/"><u>PS5 Controller Power Problems? Here's How to Get It Charging Again!</u></a></li>
<li><a href="https://win-answers.techidaily.com/rainbow-six-siege-connections-woes-heres-how-you-can-repair-them/"><u>Rainbow Six Siege Connections Woes? Here's How You Can Repair Them</u></a></li>
<li><a href="https://technical-tips.techidaily.com/roku-free-ways-to-access-and-enjoy-content-on-the-roku-channel/"><u>Roku-Free Ways to Access and Enjoy Content on The Roku Channel</u></a></li>
<li><a href="https://facebook.techidaily.com/social-medias-new-controvernial-approach-to-advertising/"><u>Social Media's New Controvernial Approach to Advertising?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-combining-your-fortnite-usernames/"><u>Step-by-Step Guide: Combining Your Fortnite Usernames</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-windows-11-transparent-taskbar-creation/"><u>Steps for Windows 11 Transparent Taskbar Creation</u></a></li>
<li><a href="https://technical-tips.techidaily.com/steps-to-enhance-instagram-content-with-background-music/"><u>Steps to Enhance Instagram Content with Background Music</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-noise-problem-heres-what-to-do-when-your-computer-fan-is-alarmingly-loud/"><u>The Noise Problem? Here’s What to Do When Your Computer Fan Is Alarmingly Loud</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-list-of-9-amazing-sites-for-gratis-pre-k-game-fun/"><u>The Ultimate List of 9 Amazing Sites for Gratis Pre-K Game Fun</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-list-12-premium-voip-tools-no-cost-involved/"><u>The Ultimate List: 12 Premium VoIP Tools , No Cost Involved!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-missing-ac1st16dll-files-on-your-pc/"><u>Troubleshooting 'Missing' ac1st16.dll Files on Your PC</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-steam-disk-write-mishaps-effectively/"><u>Troubleshooting Steam Disk Write Mishaps Effectively</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-steps-for-resolving-cant-find-dll-error-messages/"><u>Troubleshooting Steps for Resolving 'Can't Find DLL' Error Messages</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-pictures-from-htc-u23-pro-by-fonelab-android-recover-pictures/"><u>Undelete lost pictures from HTC U23 Pro.</u></a></li>
<li><a href="https://technical-tips.techidaily.com/understanding-and-rectifying-the-401-unauthorized-http-response-problems/"><u>Understanding & Rectifying the 401 Unauthorized HTTP Response Problems</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->