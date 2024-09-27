---
title: How to Perform a DNS Cleanup on Your Mac - Detailed Instructions
date: 2024-09-21T02:56:42.655Z
updated: 2024-09-26T22:26:38.139Z
categories:
  - BestProducts
description: This Article Describes How to Perform a DNS Cleanup on Your Mac - Detailed Instructions
excerpt: This Article Describes How to Perform a DNS Cleanup on Your Mac - Detailed Instructions
thumbnail: https://www.lifewire.com/thmb/zSQcjmrvSKGApZnR2FXBp1D3DC4=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/flushdnsmac-b663b94f43654b76ac53645d7ce1919c.jpg
---

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Perform a DNS Cleanup on Your Mac - Detailed Instructions
### What to Know

* You can delete the DNS cache through Terminal. Press**Command** +**Space** to search for it.
* Enter this flush DNS command: **sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder**
* El Capitan and older Mac OS X systems use different commands to clear DNS.

 This article explains how to delete the[DNS cache](https://www.lifewire.com/what-is-a-dns-cache-817514) on a Mac.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484944/16446" target="_top" id="1484944">
  <img src="//a.impactradius-go.com/display-ad/16446-1484944" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484944/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880976/19272" target="_top" id="1880976">
  <img src="//a.impactradius-go.com/display-ad/19272-1880976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880976/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137211/26400" target="_top" id="2137211">
  <img src="//a.impactradius-go.com/display-ad/26400-2137211" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137211/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123732/7443" target="_top" id="2123732">
  <img src="//a.impactradius-go.com/display-ad/7443-2123732" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123732/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### How to Flush DNS on Mac OS X

 The Mac OS X flush DNS command is different than the one used in modern versions of the operating system. Open Terminal and then enter the command that corresponds with your version:

* **El Capitan** : sudo killall -HUP mDNSResponder
* **Yosemite** : sudo discoveryutil udnsflushcaches
* **Lion, Mountain Lion, and Mavericks** : sudo killall -HUP mDNSResponder
* **Snow Leopard** : sudo dscacheutil -flushcache
* **Leopard** : sudo lookupd -flushcache
* **Tiger** : lookupd -flushcache

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
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-fcps-ultimate-editing-aid-best-10-plug-ins/"><u>[Updated] 2024 Approved FCP's Ultimate Editing Aid Best 10 Plug-Ins</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-synergizing-visual-elements-best-text-plugins-reviewed/"><u>[Updated] 2024 Approved Synergizing Visual Elements Best Text Plugins Reviewed</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-add-personality-to-your-device-a-comprehensively-tailored-sound-and-ringtone-guide-for-android/"><u>2024 Approved Add Personality to Your Device A Comprehensively Tailored Sound & Ringtone Guide for Android</u></a></li>
<li><a href="https://technical-tips.techidaily.com/a-chronological-guide-to-apples-ios-development-discovering-changes-from-version-10-to-180/"><u>A Chronological Guide to Apple's iOS Development: Discovering Changes From Version 1.0 to 18.0</u></a></li>
<li><a href="https://technical-tips.techidaily.com/best-automated-clicking-solutions-on-android-without-rooting/"><u>Best Automated Clicking Solutions on Android Without Rooting</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-realme-c53-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Realme C53 | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/decoding-the-secrets-of-masterful-windows-10-use/"><u>Decoding the Secrets of Masterful WINDOWS 10 Use</u></a></li>
<li><a href="https://technical-tips.techidaily.com/diagnosing-and-repairing-the-disc-drive-not-found-problem-in-steam-installs/"><u>Diagnosing and Repairing the 'Disc Drive Not Found' Problem in Steam Installs</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/discover-your-displays-pixels-effortless-guide-to-determine-screen-resolution/"><u>Discover Your Display's Pixels: Effortless Guide to Determine Screen Resolution</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-screen-lock-pin-on-realme-gt-3-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On Realme GT 3 Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-reset-the-security-questions-of-your-apple-id-from-your-apple-iphone-13-pro-max-by-drfone-ios/"><u>How To Reset the Security Questions of Your Apple ID From Your Apple iPhone 13 Pro Max</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-facebook-story-viewer-view-facebook-stories-anonymously/"><u>In 2024, Facebook Story Viewer View Facebook Stories Anonymously</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-m34-5g-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Samsung Galaxy M34 5G Phone Without Password?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/resolving-lameencdll-issues-in-audacity-an-in-depth-guide/"><u>Resolving lame_enc.dll Issues in Audacity - An In-Depth Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/snapchat-on-windows-or-mac-a-comprehensive-walkthrough-to-enable-mobile-app-usage-on-desktop/"><u>Snapchat on Windows or Mac: A Comprehensive Walkthrough to Enable Mobile App Usage on Desktop</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-essential-tutorial-on-wiping-and-refreshing-bios-memory-for-optimal-performance/"><u>The Essential Tutorial on Wiping and Refreshing BIOS Memory for Optimal Performance</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-and-repairing-missing-d3dx9dll-errors-on-your-computer/"><u>Troubleshooting and Repairing Missing d3dx9_^.dll Errors on Your Computer</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ultimate-guide-the-top-8-travel-planner-apps-to-enhance-your-adventures/"><u>Ultimate Guide: The Top 8 Travel Planner Apps to Enhance Your Adventures</u></a></li>
<li><a href="https://technical-tips.techidaily.com/whats-new-in-windows-insight-on-july-2024-service-packs-and-patches/"><u>What's New in Windows: Insight on July 2024 Service Packs & Patches</u></a></li>
</ul></div>

