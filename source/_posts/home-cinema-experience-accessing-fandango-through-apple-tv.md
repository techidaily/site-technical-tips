---
title: "Home Cinema Experience: Accessing Fandango Through Apple TV"
date: 2024-08-20T10:18:32.891Z
updated: 2024-08-21T10:18:32.891Z
categories:
  - BestProducts
description: "This Article Describes Home Cinema Experience: Accessing Fandango Through Apple TV"
excerpt: "This Article Describes Home Cinema Experience: Accessing Fandango Through Apple TV"
thumbnail: https://thmb.techidaily.com/0d31f5646fe3a9a749251ddb64d10288427198f92e87a603dc09ffcf334ba8c5.jpg
---

## Experience Lightning-Fast Browsing: Flush Your Mac's DNS Data Today
### What to Know

* You can delete the DNS cache through Terminal. Press**Command** +**Space** to search for it.
* Enter this flush DNS command: **sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder**
* El Capitan and older Mac OS X systems use different commands to clear DNS.

 This article explains how to delete the[DNS cache](https://www.lifewire.com/what-is-a-dns-cache-817514) on a Mac.

## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .
2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.
3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
### How to Flush DNS on Mac OS X

 The Mac OS X flush DNS command is different than the one used in modern versions of the operating system. Open Terminal and then enter the command that corresponds with your version:

* **El Capitan** : sudo killall -HUP mDNSResponder
* **Yosemite** : sudo discoveryutil udnsflushcaches
* **Lion, Mountain Lion, and Mavericks** : sudo killall -HUP mDNSResponder
* **Snow Leopard** : sudo dscacheutil -flushcache
* **Leopard** : sudo lookupd -flushcache
* **Tiger** : lookupd -flushcache

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## What Does Flushing DNS Do?

 Each time you access a website in your web browser, the URL you enter is sent to a[DNS server](https://www.lifewire.com/what-is-a-dns-server-2625854) for translation into an[IP address](https://www.lifewire.com/what-is-an-ip-address-2625920) . This information is stored in a cache on your Mac for easy retrieval in the future, hence the term_DNS cache_ .

 When you try to access a website you’ve been to recently, your Mac uses its DNS cache instead of checking with an actual DNS server. The web browser doesn’t have to go through the extra step of communicating with a remote DNS server, which results in less time between entering a website address and the website loading.

 If the local DNS cache is corrupt or outdated, it’s kind of like trying to use an old phone book that's been vandalized. Your web browser checks the cache to find an IP address for the website you’re trying to visit, and it finds either the wrong address or an unusable one. This can slow the process down or prevent websites or specific web page elements, like videos, from loading.

 When you flush your DNS cache, you instruct your Mac to delete its local DNS records. This in turn forces your web browser to check with a DNS server for fresh information. You should always flush your DNS cache after[changing the DNS servers on your Mac](https://www.lifewire.com/network-preference-pane-change-macs-dns-settings-2260394) . It can also be helpful if you’re having connectivity problems.  

 FAQ

* How do I check the DNS cache on a Mac?  
 Open the built-in Console log-viewer app on your Mac and type**any:mdnsresponder** into the search bar. Then, launch Terminal, type in**sudo killall –INFO mDNSResponder** , and press**Enter** or**Return** . Back in the Console app, you can view a list of cached DNS records.
* How do I clear the DNS cache on Windows 10?  
 To[clear the DNS cache on Windows 10](https://www.lifewire.com/flush-and-clear-windows-dns-cache-5095298) , open the Run dialog box, type in**ipconfig /flushdns** , and click**OK** . You can also use the same command in the Windows command prompt if you want more information on the process.
* What is DNS cache poisoning?  
 DNS cache poisoning, also known as DNS spoofing, is when someone deliberately enters false or incorrect information into a DNS cache. After the false information is input, future DNS queries will return incorrect responses and direct users to the wrong websites.

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
<li><a href="https://youtube-webster.techidaily.com/024-approved-transforming-your-footage-into-shareable-youtube-stories/"><u>[New] 2024 Approved  Transforming Your Footage Into Shareable YouTube Stories</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-game-recorder-mastery-top-5-techniques-for-windows-11/"><u>[New] Game Recorder Mastery  Top 5 Techniques for Windows 11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solved-windows-11-widgets-not-working/"><u>[SOLVED] Windows 11 Widgets Not Working</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-deciding-on-ideal-vimeo-subscription-plan/"><u>[Updated] 2024 Approved  Deciding on Ideal Vimeo Subscription Plan</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-how-to-stream-a-pre-recorded-video-live-on-facebook-for-2024/"><u>[Updated] How to Stream A Pre-Recorded Video Live on Facebook for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-the-future-of-video-on-facebook-focusing-on-shorter-formats/"><u>[Updated] The Future of Video on Facebook  Focusing on Shorter Formats</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-infinix-smart-8-plus-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Infinix Smart 8 Plus Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-vivo-v27-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Vivo V27 | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/demystifying-superfetch-essentials-you-must-understand-today/"><u>Demystifying SuperFetch: Essentials You Must Understand Today</u></a></li>
<li><a href="https://technical-tips.techidaily.com/doubling-your-digital-space-connect-and-configure-an-extra-monitor-with-windows-10/"><u>Doubling Your Digital Space: Connect and Configure an Extra Monitor with Windows 10</u></a></li>
<li><a href="https://technical-tips.techidaily.com/easy-steps-for-installing-and-configuring-a-vpn-in-windows-11-comprehensive-instructional-article/"><u>Easy Steps for Installing and Configuring a VPN in Windows 11 – Comprehensive Instructional Article</u></a></li>
<li><a href="https://technical-tips.techidaily.com/eliminate-printer-problems-remove-your-device-efficiently-from-windows-os/"><u>Eliminate Printer Problems: Remove Your Device Efficiently From Windows OS</u></a></li>
<li><a href="https://technical-tips.techidaily.com/enable-built-in-administrator-account-in-windows-10-7-and-8-step-by-step/"><u>Enable Built-In Administrator Account in Windows 10, 7 & 8 (Step by Step)</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-advice-when-to-update-plus-how-to-protect-yourself-during-a-bios-overhaul/"><u>Expert Advice: When to Update + How to Protect Yourself During a BIOS Overhaul</u></a></li>
<li><a href="https://technical-tips.techidaily.com/fix-install-realtek-hd-audio-driver-failure-easily/"><u>Fix Install Realtek HD Audio Driver Failure. Easily!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/fixing-undetected-sd-cards-tips-and-tricks-for-quick-solutions/"><u>Fixing Undetected SD Cards - Tips and Tricks for Quick Solutions</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-connect-windows-10-to-wifi/"><u>How to Connect Windows 10 to WiFi</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-create-a-batch-file-the-easy-way/"><u>How to Create a Batch File? The Easy Way!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-do-private-browsing-in-chrome-step-by-step-guide/"><u>How to Do Private Browsing in Chrome [Step-by-Step Guide]</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-set-up-dual-monitors-on-windows-11/"><u>How to Set Up Dual Monitors on Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-infinix-smart-8-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Infinix Smart 8 Phone Hassle-Free</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unveiling-the-secrets-of-vr-filmmaking-with-advanced-techniques-using-adobe-premiere-pro/"><u>In 2024, Unveiling the Secrets of VR Filmmaking with Advanced Techniques Using Adobe Premiere Pro</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/iphone-is-disabled-here-is-the-way-to-unlock-disabled-iphone-se-2020-by-drfone-ios/"><u>iPhone Is Disabled? Here Is The Way To Unlock Disabled iPhone SE (2020)</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-oppo-a18-drfone-by-drfone-virtual-android/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Oppo A18 | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/logitech-c922-stuck-expert-tips-for-getting-your-high-definition-streaming-camera-back-online/"><u>Logitech C922 Stuck? Expert Tips for Getting Your High-Definition Streaming Camera Back Online</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-your-pc-specs-easily-check-ram-on-windows-devices-today/"><u>Mastering Your PC Specs: Easily Check RAM on Windows Devices Today</u></a></li>
<li><a href="https://technical-tips.techidaily.com/maximizing-frame-rates-effective-strategies-to-enhance-fps-in-the-game-rust/"><u>Maximizing Frame Rates: Effective Strategies to Enhance FPS in the Game 'Rust'</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/new-2024-approved-becoming-a-pro-in-tiktok-live-shopping-your-complete-guide/"><u>New 2024 Approved Becoming a Pro in TikTok Live Shopping Your Complete Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/pairing-bluetooth-earbuds-with-sony-ps4-detailed-instructions-and-visual-aids-included/"><u>Pairing Bluetooth Earbuds with Sony PS4 - Detailed Instructions and Visual Aids Included</u></a></li>
<li><a href="https://technical-tips.techidaily.com/quick-guide-opening-the-windows-10-boot-menu/"><u>Quick Guide: Opening the Windows 10 Boot Menu</u></a></li>
<li><a href="https://technical-tips.techidaily.com/say-goodbye-to-sticky-windows-keyboard-keys-with-this-step-by-step-solution/"><u>Say Goodbye to Sticky Windows Keyboard Keys with This Step-by-Step Solution</u></a></li>
<li><a href="https://technical-tips.techidaily.com/simple-steps-removing-the-windows-10-anniversary-update-without-a-hitch/"><u>Simple Steps: Removing the Windows 10 Anniversary Update Without a Hitch</u></a></li>
<li><a href="https://technical-tips.techidaily.com/skype-call-failed-on-windows-10-7-solved/"><u>Skype: Call Failed on Windows 10 / 7 [Solved]</u></a></li>
<li><a href="https://technical-tips.techidaily.com/speeding-up-your-game-time-expert-tips-to-enhance-battlenet-download-velocity-in-n-2024/"><u>Speeding Up Your Game Time: Expert Tips to Enhance Battle.net Download Velocity in N 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-quickly-accessing-the-control-panel-on-your-windows-8-pc/"><u>Step-by-Step Guide: Quickly Accessing the Control Panel on Your Windows 8 PC</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-tutorial-on-customizing-display-options-for-windows-11-users/"><u>Step-by-Step Tutorial on Customizing Display Options for Windows 11 Users</u></a></li>
<li><a href="https://tech-revival.techidaily.com/strategies-for-incorporating-gpt-mention-techniques-into-interactive-chatbot-dialogues/"><u>Strategies for Incorporating GPT Mention Techniques Into Interactive Chatbot Dialogues</u></a></li>
<li><a href="https://technical-tips.techidaily.com/tech-savvy-guide-effortless-screen-shots-with-your-toshiba-laptop-explained/"><u>Tech Savvy Guide: Effortless Screen Shots with Your Toshiba Laptop Explained</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-5-characteristics-of-high-performance-game-mice/"><u>The Ultimate 5 Characteristics of High-Performance Game Mice</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-5-vpn-services-ideal-for-enhanced-privacy-on-youtube/"><u>Top 5 VPN Services Ideal for Enhanced Privacy on YouTube</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-skype-not-connecting-in-windows-10-top-5-easy-to-follow-fixes/"><u>Troubleshooting Skype Not Connecting in Windows 10: Top 5 Easy-to-Follow Fixes</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-tips-to-revive-and-restart-your-frozen-computer-in-windows-10/"><u>Troubleshooting Tips to Revive and Restart Your Frozen Computer in Windows 10</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ultimate-guide-step-by-step-instructions-to-remove-programs-on-windows-11/"><u>Ultimate Guide: Step-by-Step Instructions to Remove Programs on Windows 11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unlocking-your-pcs-secrets-a-user-friendly-way-to-check-bios-version-under-windows-11/"><u>Unlocking Your PC's Secrets: A User-Friendly Way to Check BIOS Version Under Windows 11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/windows-11-blocks-desktop-programs-win32-apps-points-to-windows-store/"><u>Windows 11 Blocks Desktop Programs (Win32 Apps), Points to Windows Store</u></a></li>
<li><a href="https://technical-tips.techidaily.com/windows-store-not-working-on-windows-11-fixed/"><u>Windows Store Not Working on Windows 11 [Fixed]</u></a></li>
<li><a href="https://technical-tips.techidaily.com/winning-the-battle-against-windows-10-high-ram-drain-tips-and-tricks/"><u>Winning the Battle Against Windows 10 High RAM Drain - Tips and Tricks</u></a></li>
</ul></div>
