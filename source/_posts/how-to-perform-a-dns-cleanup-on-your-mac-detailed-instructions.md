---
title: How to Perform a DNS Cleanup on Your Mac - Detailed Instructions
date: 2024-09-19T04:18:13.834Z
updated: 2024-09-20T23:50:47.606Z
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

### How to Flush DNS on Mac OS X

 The Mac OS X flush DNS command is different than the one used in modern versions of the operating system. Open Terminal and then enter the command that corresponds with your version:

* **El Capitan** : sudo killall -HUP mDNSResponder
* **Yosemite** : sudo discoveryutil udnsflushcaches
* **Lion, Mountain Lion, and Mavericks** : sudo killall -HUP mDNSResponder
* **Snow Leopard** : sudo dscacheutil -flushcache
* **Leopard** : sudo lookupd -flushcache
* **Tiger** : lookupd -flushcache

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105883/7443" target="_top" id="2105883">
  <img src="//a.impactradius-go.com/display-ad/7443-2105883" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105883/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-blog.techidaily.com/024-approved-navigating-the-world-of-video-editing-for-youtube-creators/"><u>[New] 2024 Approved Navigating the World of Video Editing for YouTube Creators</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-chortlechamps-excellent-platforms-for-hilarious-tones/"><u>[New] ChortleChamps Excellent Platforms for Hilarious Tones</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-gelato-gadgets-step-by-step-screen-capture-for-frozen-snacks/"><u>[Updated] 2024 Approved Gelato Gadgets Step-by-Step Screen Capture for Frozen Snacks</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-6-top-mc-village-home-structures-unveiled/"><u>[Updated] 6 Top MC Village Home Structures Unveiled</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-charting-the-financial-pathway-of-tseries-within-youtube-market-space/"><u>[Updated] In 2024, Charting the Financial Pathway of TSeries Within YouTube Market Space</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-navigating-top-10-affordable-mobile-video-services-for-2024/"><u>[Updated] Navigating Top 10 Affordable Mobile Video Services for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-step-by-step-tutorial-designing-striking-video-thumbnails-for-social-media-success/"><u>[Updated] Step-by-Step Tutorial Designing Striking Video Thumbnails for Social Media Success</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-2-ways-to-monitor-google-pixel-7a-activity-drfone-by-drfone-virtual-android/"><u>In 2024, 2 Ways to Monitor Google Pixel 7a Activity | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigating-the-pre-purchase-process-8-tips-for-choosing-the-right-desktop-pc/"><u>Navigating the Pre-Purchase Process: 8 Tips for Choosing the Right Desktop PC</u></a></li>
<li><a href="https://solve-info.techidaily.com/personalized-marketing-with-cookiebot-technology-integration/"><u>Personalized Marketing with Cookiebot Technology Integration</u></a></li>
<li><a href="https://technical-tips.techidaily.com/resolving-disk-errors-swiftly-how-to-employ-the-chkdsk-utility-in-windows/"><u>Resolving Disk Errors Swiftly: How to Employ the Chkdsk Utility in Windows</u></a></li>
<li><a href="https://technical-tips.techidaily.com/rock-your-ears-8-amazing-free-music-apps-to-install-on-your-iphone-now/"><u>Rock Your Ears: 8 Amazing Free Music Apps to Install on Your iPhone Now</u></a></li>
<li><a href="https://technical-tips.techidaily.com/samsung-unpacked-2025-countdown-event-timeline-new-releases-and-juicy-rumors/"><u>Samsung Unpacked 2025 Countdown: Event Timeline, New Releases, and Juicy Rumors!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-correcting-accidental-reposts-on-tiktok/"><u>Step-by-Step Guide: Correcting Accidental Reposts on TikTok</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unveiling-the-secrets-behind-electric-two-wheeler-functionality/"><u>Unveiling the Secrets Behind Electric Two-Wheeler Functionality</u></a></li>
<li><a href="https://technical-tips.techidaily.com/upcoming-google-pixel-fold-2-pricing-insights-release-forecast-specs-deep-dive-and-rumored-updates/"><u>Upcoming Google Pixel Fold 2: Pricing Insights, Release Forecast, Specs Deep Dive, and Rumored Updates</u></a></li>
</ul></div>

