---
title: "IPhone Pro-Tips: How To Effortlessly Record and Send Voice Messages"
date: 2024-08-18T20:47:26.012Z
updated: 2024-08-19T20:47:26.012Z
categories:
  - BestProducts
description: "This Article Describes IPhone Pro-Tips: How To Effortlessly Record and Send Voice Messages"
excerpt: "This Article Describes IPhone Pro-Tips: How To Effortlessly Record and Send Voice Messages"
thumbnail: https://thmb.techidaily.com/0004bab4ed76fb3b0e7b5e78faee5c8cd34739a5594338591ba06831ec971383.jpg
---

## Mac Users Rejoice: How to Reset Your DNS Records Effortlessly
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
### What to Know

* You can delete the DNS cache through Terminal. Press**Command** +**Space** to search for it.
* Enter this flush DNS command: **sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder**
* El Capitan and older Mac OS X systems use different commands to clear DNS.

 This article explains how to delete the[DNS cache](https://www.lifewire.com/what-is-a-dns-cache-817514) on a Mac.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .
2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.
3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

### How to Flush DNS on Mac OS X

 The Mac OS X flush DNS command is different than the one used in modern versions of the operating system. Open Terminal and then enter the command that corresponds with your version:

* **El Capitan** : sudo killall -HUP mDNSResponder
* **Yosemite** : sudo discoveryutil udnsflushcaches
* **Lion, Mountain Lion, and Mavericks** : sudo killall -HUP mDNSResponder
* **Snow Leopard** : sudo dscacheutil -flushcache
* **Leopard** : sudo lookupd -flushcache
* **Tiger** : lookupd -flushcache

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
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
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-finest-accessible-switch-replicas/"><u>[New] In 2024, Finest Accessible Switch Replicas</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-spark-to-the-past-djis-mavic-air-reimagines-gameplay/"><u>[New] Spark to the Past? DJI's Mavic Air Reimagines Gameplay</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-realme-c53-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Realme C53 Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/7-must-have-shared-digital-calendars-simplifying-planning-for-busy-parenting-units/"><u>7 Must-Have Shared Digital Calendars: Simplifying Planning for Busy Parenting Units</u></a></li>
<li><a href="https://hardware-help.techidaily.com/analysis-of-hahron-spices-market-share-in-the-chemical-industry/"><u>Analysis of HAHRON SPICE's Market Share in the Chemical Industry</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-from-your-apple-iphone-6s-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code From your Apple iPhone 6s</u></a></li>
<li><a href="https://technical-tips.techidaily.com/dealing-with-dll-disappearances-how-to-address-missing-wmvcoredll-errors-successfully/"><u>Dealing with DLL Disappearances: How to Address Missing Wmvcore.dll Errors Successfully</u></a></li>
<li><a href="https://technical-tips.techidaily.com/diagnosing-and-fixing-your-xbox-series-xs-headset-when-it-stops-working-a-comprehensive-guide/"><u>Diagnosing and Fixing Your Xbox Series X/S Headset When It Stops Working: A Comprehensive Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/efficient-message-sending-techniques-to-reduce-data-consumption-in-texts/"><u>Efficient Message Sending: Techniques to Reduce Data Consumption in Texts</u></a></li>
<li><a href="https://technical-tips.techidaily.com/evaluating-performance-and-features-of-apples-top-devices-ipad-pro-m1-vs-macbook-air-m1/"><u>Evaluating Performance & Features of Apple's Top Devices: IPad Pro M1 Vs. MacBook Air M1</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-inability-to-connect-error-for-malwarebytes-on-win11/"><u>Fixing the Inability to Connect Error for Malwarebytes on Win11</u></a></li>
<li><a href="https://tech-haven.techidaily.com/foremost-20-github-sourced-chatgpt-conversation-ideas/"><u>Foremost 20 Github-Sourced ChatGPT Conversation Ideas</u></a></li>
<li><a href="https://technical-tips.techidaily.com/future-tech-showdown-the-leading-consoles-of-2024-decoded/"><u>Future Tech Showdown: The Leading Consoles of 2024 Decoded</u></a></li>
<li><a href="https://technical-tips.techidaily.com/guide-to-fixing-absence-of-smsmms-on-your-android-phone/"><u>Guide to Fixing Absence of SMS/MMS on Your Android Phone</u></a></li>
<li><a href="https://os-tips.techidaily.com/how-to-cast-your-android-device-on-tv-pc-or-mac-a-comprehensive-guide/"><u>How to Cast Your Android Device on TV, PC, or Mac: A Comprehensive Guide</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-sony-xperia-10-v-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Sony Xperia 10 V to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ipad-wont-connect-to-wi-fi-heres-how-you-can-fix-it/"><u>IPad Won't Connect to Wi-Fi? Here’s How You Can Fix It</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-the-fix-for-msvcrtdll-not-found-essential-steps-unveiled/"><u>Mastering the Fix for 'Msvcrt.dll Not Found' - Essential Steps Unveiled</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-in-2024-harmonizing-soundscape-a-comprehensive-guide-to-eq-adjustments/"><u>New In 2024, Harmonizing Soundscape A Comprehensive Guide to EQ Adjustments</u></a></li>
<li><a href="https://technical-tips.techidaily.com/overcoming-the-challenge-of-missing-wpcpatdll-files-on-your-computer/"><u>Overcoming the Challenge of Missing WPCPAT.DLL Files on Your Computer</u></a></li>
<li><a href="https://technical-tips.techidaily.com/recovering-vanished-texts-ultimate-methods-for-every-device/"><u>Recovering Vanished Texts: Ultimate Methods for Every Device</u></a></li>
<li><a href="https://technical-tips.techidaily.com/resolving-mfplatdll-not-detected-or-absent-issues-a-step-by-step-guide/"><u>Resolving mfplat.dll Not Detected or Absent Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/retrieve-wi-fi-security-codes-effortlessly-for-windows-11-users/"><u>Retrieve Wi-Fi Security Codes Effortlessly for Windows 11 Users</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solutions-to-fix-mozilla-thunderbird-failure-to-open-correctly/"><u>Solutions to Fix Mozilla Thunderbird Failure to Open Correctly</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solving-the-xinput13dll-error-comprehensive-guide/"><u>Solving the xinput1_3.dll Error: Comprehensive Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-tutorial-changing-the-theme-of-your-windows-10-taskbar-for-a-fresh-look/"><u>Step-by-Step Tutorial: Changing the Theme of Your Windows 10 Taskbar for a Fresh Look</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-definitive-selection-of-top-tier-80s-movie-classics-for-modern-audiences/"><u>The Definitive Selection of Top-Tier '80S Movie Classics for Modern Audiences</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-ultimate-guide-to-capturing-youtube-videos-subtitles-in-srt-format-for-2024/"><u>The Ultimate Guide to Capturing YouTube Videos' Subtitles in SRT Format for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-7-no-cost-web-based-faxing-solutions/"><u>Top 7 No-Cost Web-Based Faxing Solutions</u></a></li>
<li><a href="https://win-answers.techidaily.com/ultimate-guide-to-overcoming-minecraft-pc-crashes-and-freezes-expert-advice-for-gamers-updated/"><u>Ultimate Guide to Overcoming Minecraft PC Crashes and Freezes - Expert Advice for Gamers (Updated )</u></a></li>
<li><a href="https://technical-tips.techidaily.com/understanding-aim-the-rise-and-fall-of-aols-chat-phenomenon/"><u>Understanding AIM: The Rise and Fall of AOL's Chat Phenomenon</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unlocking-history-a-beginners-tutorial-to-using-the-wayback-machine/"><u>Unlocking History: A Beginner’s Tutorial to Using the Wayback Machine</u></a></li>
</ul></div>
