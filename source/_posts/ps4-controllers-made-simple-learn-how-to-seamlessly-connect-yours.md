---
title: "PS4 Controllers Made Simple: Learn How to Seamlessly Connect Yours"
date: 2024-10-17T16:12:17.901Z
updated: 2024-10-19T16:01:11.180Z
categories:
  - BestProducts
description: "This Article Describes PS4 Controllers Made Simple: Learn How to Seamlessly Connect Yours"
excerpt: "This Article Describes PS4 Controllers Made Simple: Learn How to Seamlessly Connect Yours"
thumbnail: https://thmb.techidaily.com/71f657792ad13f84286b1544671aaf8455260b87c02f1f22e6d755ac15543040.jpg
---

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Mac Users Rejoice: How to Reset Your DNS Records Effortlessly
### What to Know

* You can delete the DNS cache through Terminal. Press**Command** +**Space** to search for it.
* Enter this flush DNS command: **sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder**
* El Capitan and older Mac OS X systems use different commands to clear DNS.

 This article explains how to delete the[DNS cache](https://www.lifewire.com/what-is-a-dns-cache-817514) on a Mac.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087262/19272" target="_top" id="2087262">
  <img src="//a.impactradius-go.com/display-ad/19272-2087262" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087262/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<span id="1304647">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1304647.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1304647">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1304647.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1304647%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1304647/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118311/7443" target="_top" id="2118311">
  <img src="//a.impactradius-go.com/display-ad/7443-2118311" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118311/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://review-au.sjv.io/c/5597632/2135315/14409" target="_top" id="2135315">
  <img src="//a.impactradius-go.com/display-ad/14409-2135315" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135315/14409" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-best-9-virtual-mic-recorders-to-enhance-remote-sessions-23/"><u>[New] 2024 Approved Best 9 Virtual Mic Recorders to Enhance Remote Sessions ('23)</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-from-monochrome-to-multicolor-grading-journey/"><u>[New] 2024 Approved From Monochrome to Multicolor Grading Journey</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-crafting-conversational-slides-with-powerpoints-speech-features/"><u>[New] Crafting Conversational Slides with PowerPoint's Speech Features</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/wiftly-adjust-video-speeds-a-users-guide-to-youtube-features-for-2024/"><u>[New] Swiftly Adjust Video Speeds A User's Guide to YouTube Features for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-the-ultimate-guide-to-choosing-the-most-effective-9-multimedia-devices-ios-android/"><u>[Updated] In 2024, The Ultimate Guide to Choosing the Most Effective 9 Multimedia Devices (iOS, Android)</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-hits-and-misses-the-photographers-account/"><u>2024 Approved Hits and Misses The Photographer's Account</u></a></li>
<li><a href="https://technical-tips.techidaily.com/banish-code-19-a-comprehensive-walkthrough-for-windows-users/"><u>Banish Code 지오구19: A Comprehensive Walkthrough for Windows Users</u></a></li>
<li><a href="https://extra-hints.techidaily.com/composing-the-unseen-score-trailer-music-magic/"><u>Composing the Unseen Score Trailer Music Magic</u></a></li>
<li><a href="https://technical-tips.techidaily.com/facebook-marketplace-puzzle-solved-reasons-for-inaccessibility-and-how-to-fix-them/"><u>Facebook Marketplace Puzzle Solved: Reasons for Inaccessibility and How to Fix Them</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-long-is-the-validity-of-a-mailcom-email-address/"><u>How Long Is the Validity of a Mail.com Email Address?</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-a-comprehensive-guide-to-mastering-zoom-win10/"><u>In 2024, A Comprehensive Guide to Mastering Zoom (Win10)</u></a></li>
<li><a href="https://technical-tips.techidaily.com/quick-how-to-navigating-and-running-command-prompt-on-windows-111087/"><u>Quick How-To: Navigating and Running Command Prompt on Windows 11/10/8/7</u></a></li>
<li><a href="https://technical-tips.techidaily.com/simple-strategies-for-locating-individuals-on-facebook/"><u>Simple Strategies for Locating Individuals on Facebook</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-securing-emails-with-your-domain-in-mailapp-for-macos/"><u>Step-by-Step Guide: Securing Emails with Your Domain in Mail.app for macOS</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/top-rated-uniden-r3-radar-scanner-a-look-at-its-sturdy-design-and-impressive-sensing-distance/"><u>Top-Rated Uniden R3 Radar Scanner: A Look at Its Sturdy Design and Impressive Sensing Distance</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ultimate-troubleshooting-for-when-winhttpdll-is-absent-or-unlocatable/"><u>Ultimate Troubleshooting for When Winhttp.dll Is Absent or Unlocatable</u></a></li>
</ul></div>

