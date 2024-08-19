---
title: "Bluetooth Boost: How To Effortlessly Hook Up Various Speakers To One Device"
date: 2024-08-18T20:48:04.428Z
updated: 2024-08-19T20:48:04.428Z
categories:
  - BestProducts
description: "This Article Describes Bluetooth Boost: How To Effortlessly Hook Up Various Speakers To One Device"
excerpt: "This Article Describes Bluetooth Boost: How To Effortlessly Hook Up Various Speakers To One Device"
thumbnail: https://thmb.techidaily.com/7216cdd0db0d51b9ba6ea43c8d26dd6a0eb4cf5b262743a458e3d7ee3b2754cf.jpeg
---

## Mac Users Rejoice: How to Reset Your DNS Records Effortlessly
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
### What to Know

* You can delete the DNS cache through Terminal. Press**Command** +**Space** to search for it.
* Enter this flush DNS command: **sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder**
* El Capitan and older Mac OS X systems use different commands to clear DNS.

 This article explains how to delete the[DNS cache](https://www.lifewire.com/what-is-a-dns-cache-817514) on a Mac.

## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .
2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.
3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
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
<li><a href="https://youtube-data.techidaily.com/024-approved-strategies-to-avoid-pitfalls-in-designing-youtube-thumbnails/"><u>[New] 2024 Approved  Strategies to Avoid Pitfalls in Designing YouTube Thumbnails</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-synergy-of-social-media-embedding-linktree-in-your-tiktok-bio/"><u>[New] Synergy of Social Media  Embedding Linktree in Your TikTok Bio</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-wave-off-your-insta-footprint-complete-guide-to-permanent-delete-for-2024/"><u>[New] Wave Off Your Insta Footprint  Complete Guide to Permanent Delete for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-masterclass-in-screenshotting-professional-level-techniques-using-mobizen/"><u>[Updated] In 2024, Masterclass in Screenshotting  Professional-Level Techniques Using Mobizen</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-optimal-devices-for-photogrammetric-movies/"><u>2024 Approved  Optimal Devices for Photogrammetric Movies</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/5-quick-methods-to-bypass-nubia-red-magic-8s-pro-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Nubia Red Magic 8S Pro FRP</u></a></li>
<li><a href="https://technical-tips.techidaily.com/8-best-free-driver-updater-tools-july-2024/"><u>8 Best Free Driver Updater Tools (July 2024)</u></a></li>
<li><a href="https://extra-information.techidaily.com/a-beginners-primer-on-virtual-reality-concepts/"><u>A Beginner's Primer on Virtual Reality Concepts</u></a></li>
<li><a href="https://technical-tips.techidaily.com/a-complete-overview-of-what-streaming-gadgets-are-and-how-they-work/"><u>A Complete Overview of What Streaming Gadgets Are and How They Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-productivity-the-essentials-of-using-flow-launcher/"><u>Accelerate Productivity: The Essentials of Using Flow Launcher</u></a></li>
<li><a href="https://technical-tips.techidaily.com/avoiding-regrets-on-social-media-the-process-of-deleting-images-from-facebook/"><u>Avoiding Regrets on Social Media: The Process of Deleting Images From Facebook</u></a></li>
<li><a href="https://win-answers.techidaily.com/diagnosing-and-repairing-the-pc-launch-glitch-in-robocop-rogue-city-video-game/"><u>Diagnosing and Repairing the PC Launch Glitch in RoboCop: Rogue City Video Game</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-top-family-friendly-films-streaming-on-amazon-prime-video-in-july-2024/"><u>Discover the Top Family-Friendly Films Streaming on Amazon Prime Video in July 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/enabling-low-light-modes-for-iphone-displays-complete-tutorial/"><u>Enabling Low Light Modes for iPhone Displays – Complete Tutorial</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722850398032-enhancing-your-furry-friends-portraits-techniques-to-remove-pupil-glare-and-redness/"><u>Enhancing Your Furry Friend's Portraits: Techniques to Remove Pupil Glare and Redness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gain-early-access-the-way-into-windows-11-beta/"><u>Gain Early Access: The Way Into Windows 11 Beta</u></a></li>
<li><a href="https://technical-tips.techidaily.com/gmail-tips-detecting-emails-that-have-been-opened-by-recipients/"><u>Gmail Tips: Detecting Emails That Have Been Opened by Recipients</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-or-bypass-knox-enrollment-service-on-vivo-s18-pro-by-drfone-android/"><u>How To Remove or Bypass Knox Enrollment Service On Vivo S18 Pro</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-your-realme-gt-3-lock-screen-password-by-drfone-android/"><u>How to Reset your Realme GT 3 Lock Screen Password</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-2-ways-to-transfer-text-messages-from-vivo-t2-pro-5g-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 2 Ways to Transfer Text Messages from Vivo T2 Pro 5G to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-into-the-digital-frontier-vr-today-and-tomorrow/"><u>In 2024, Into the Digital Frontier  VR Today & Tomorrow</u></a></li>
<li><a href="https://technical-tips.techidaily.com/inside-the-samsung-galaxy-watch-7-find-out-pricing-release-schedule-and-feature-breakdown/"><u>Inside the Samsung Galaxy Watch 7: Find Out Pricing, Release Schedule, and Feature Breakdown!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/keyboard-trouble-heres-how-you-can-restore-typing-functionality-on-your-pc-or-laptop/"><u>Keyboard Trouble? Here's How You Can Restore Typing Functionality on Your PC or Laptop</u></a></li>
<li><a href="https://technical-tips.techidaily.com/learn-how-to-program-any-device-using-a-universal-remote-made-simple/"><u>Learn How to Program Any Device Using a Universal Remote Made Simple</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-twitter-growth-effective-strategies-for-building-your-audience/"><u>Mastering Twitter Growth: Effective Strategies for Building Your Audience</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigating-the-future-top-smart-frames-of-2024/"><u>Navigating the Future: Top Smart Frames of 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigating-through-the-finest-options-2024s-top-ceiling-audio-innovations/"><u>Navigating Through The Finest Options: 2024'S Top Ceiling Audio Innovations</u></a></li>
<li><a href="https://technical-tips.techidaily.com/remedying-visual-anomalies-in-your-pc-display-expert-tips-and-tricks/"><u>Remedying Visual Anomalies in Your PC Display: Expert Tips & Tricks</u></a></li>
<li><a href="https://technical-tips.techidaily.com/rtx-graphics-cards-are-they-worth-the-upgrade/"><u>RTX Graphics Cards: Are They Worth the Upgrade?</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-oppo-find-n3-flip-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from Oppo Find N3 Flip</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solutions-to-resolve-the-mfplatdll-file-missing-issue/"><u>Solutions to Resolve the 'Mfplat.dll File Missing' Issue</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-tutorial-how-to-recover-stored-usernames-and-passwords-on-macos-devices/"><u>Step-by-Step Tutorial: How to Recover Stored Usernames and Passwords on macOS Devices</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-battle-of-the-console-generation-a-deep-dive-into-ps5-slim-vs-regular-ps5/"><u>The Battle of the Console Generation: A Deep Dive Into PS5 Slim Vs. Regular PS5</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ommand-center-where-you-create-on-youtube/"><u>The Command Center Where You Create on YouTube</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-definitive-guide-to-setting-up-google-meet-calls-on-your-windows-desktop/"><u>The Definitive Guide to Setting Up Google Meet Calls on Your Windows Desktop</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-secret-behind-grok-ai-how-it-works-costing-insights-and-what-elon-musk-unveiled/"><u>The Secret Behind Grok AI: How It Works, Costing Insights, and What Elon Musk Unveiled</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-7-methods-to-boost-your-pcs-performance-swiftly/"><u>Top 7 Methods to Boost Your PC's Performance Swiftly</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ultimate-tutorial-for-syncing-multiple-bluetooth-sound-systems-with-a-lone-gadget/"><u>Ultimate Tutorial for Syncing Multiple Bluetooth Sound Systems With a Lone Gadget</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ultimate-walkthrough-on-how-to-successfully-navigate-pokemon-go/"><u>Ultimate Walkthrough on How to Successfully Navigate 'Pokémon Go'</u></a></li>
</ul></div>
