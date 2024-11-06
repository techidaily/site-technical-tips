---
title: Mac Users Unite! Learn How to Refresh Your DNS Records Effortlessly
date: 2024-10-31T21:43:10.300Z
updated: 2024-11-05T16:09:48.647Z
categories:
  - BestProducts
description: This Article Describes Mac Users Unite! Learn How to Refresh Your DNS Records Effortlessly
excerpt: This Article Describes Mac Users Unite! Learn How to Refresh Your DNS Records Effortlessly
thumbnail: https://www.lifewire.com/thmb/zSQcjmrvSKGApZnR2FXBp1D3DC4=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/flushdnsmac-b663b94f43654b76ac53645d7ce1919c.jpg
---

## Mac Users Rejoice: How to Reset Your DNS Records Effortlessly
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137214/26400" target="_top" id="2137214">
  <img src="//a.impactradius-go.com/display-ad/26400-2137214" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137214/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135398/19272" target="_top" id="2135398">
  <img src="//a.impactradius-go.com/display-ad/19272-2135398" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135398/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135354/19272" target="_top" id="2135354">
  <img src="//a.impactradius-go.com/display-ad/19272-2135354" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135354/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluetties.sjv.io/c/5597632/2141688/17094" target="_top" id="2141688">
  <img src="//a.impactradius-go.com/display-ad/17094-2141688" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluetties.sjv.io/i/5597632/2141688/17094" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-web.techidaily.com/erfecting-your-youtube-videos-for-igtv-integration-for-2024/"><u>[New] Perfecting Your Youtube Videos for IGTV Integration for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-unlocking-iphone-x-secrets-restoring-face-id-functionality/"><u>[Updated] In 2024, Unlocking iPhone X Secrets Restoring Face ID Functionality</u></a></li>
<li><a href="https://video-capture.techidaily.com/dvdandroid/"><u>「DVD映像再生手順：Androidスマートテーブル端末で実行する方法」</u></a></li>
<li><a href="https://technical-tips.techidaily.com/choosing-between-apples-latest-innovations-ultra-or-series-8-a-comprehensive-guide/"><u>Choosing Between Apple's Latest Innovations: Ultra or Series 8? A Comprehensive Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/exploring-apples-vision-the-introduction-of-a-domestic-robot-helper-a-glimpse-into-tomorrow/"><u>Exploring Apple's Vision: The Introduction of a Domestic Robot Helper - A Glimpse Into Tomorrow</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-how-to-make-a-private-story-on-snapchat-a-complete-guide/"><u>In 2024, How to Make a Private Story on Snapchat A Complete Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/making-the-move-to-iphone-16-expert-analysis-team-on-why-you-should-or-shouldnt-upgrade/"><u>Making the Move to iPhone 16: Expert Analysis Team on Why You Should or Shouldn't Upgrade</u></a></li>
<li><a href="https://technical-tips.techidaily.com/professional-video-production-on-the-go-with-apples-new-final-cut-update-for-iphones-insights/"><u>Professional Video Production On-the-Go with Apple's New FINAL CUT Update for iPhones - Insights</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/setting-up-your-youtube-standings-from-beginner-to-beneficial-businesses-for-2024/"><u>Setting Up Your YouTube Standings From Beginner to Beneficial Businesses for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-5-mobile-gaming-devices-the-ultimate-list/"><u>Top 5 Mobile Gaming Devices : The Ultimate List</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ultimate-guide-to-apples-new-studio-display-key-specifications-and-innovative-features/"><u>Ultimate Guide to Apple's New Studio Display - Key Specifications & Innovative Features</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/understanding-wi-fi-call-technology-and-its-impact-on-communication/"><u>Understanding Wi-Fi Call Technology and Its Impact on Communication</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-condense-your-clips-a-beginners-guide-to-creating-time-lapse-videos/"><u>Updated Condense Your Clips A Beginners Guide to Creating Time Lapse Videos</u></a></li>
</ul></div>

