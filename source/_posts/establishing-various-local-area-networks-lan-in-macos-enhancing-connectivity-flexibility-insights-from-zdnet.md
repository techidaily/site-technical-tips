---
title: "Establishing Various Local Area Networks (LAN) in macOS: Enhancing Connectivity Flexibility - Insights From ZDNet"
date: 2024-09-30T08:51:02.827Z
updated: 2024-10-02T05:02:40.990Z
tags:
  - apple
categories:
  - tech
thumbnail: https://thmb.techidaily.com/efe03172267db8e41dde950b174798601940a22588399da557fc77a3f3ce0d36.jpeg
---

## Enhancing Your macOS Connectivity by Configuring Various Network Places | Expert Advice

![MacOS Ventura](https://www.zdnet.com/a/img/resize/f9b803b11abf24ef89a80e3eab2b456c1d35293a/2022/07/11/47775a46-83d9-4a0e-a1e0-bac36bb3c798/macos-ventura-apple-hero.jpg?auto=webp&width=1280)

Apple

I connect to a lot of different networks. At home, I have three different LANs to choose from, which I use depending on my needs. For example, I have a general-purpose network and one that I use for the deployment of containers and the like. 

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### **ZDNET** Recommends

[The best Macs Apple's Mac lineup can be confusing as the company transitions from Intel processors to its own Apple Silicon processors. But we're here to help.  Read now](https://www.zdnet.com/article/best-mac/)

For the general-purpose network, I can just have MacOS accept an IP address from the DHCP server. However, for the container network, I prefer assigning a static IP address.

Is this possible?

It certainly is. With the help of MacOS Network Locations, you can assign specific configurations for specific networks (or locations) and even define a particular network you want to connect to within a location.

Let me show you how it works.

**Also:** [**How to manage SSH connections on MacOS with Termius**](https://www.zdnet.com/article/how-to-manage-ssh-connections-on-macos-with-termius/) 

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137973/21526" target="_top" id="2137973">
  <img src="//a.impactradius-go.com/display-ad/21526-2137973" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137973/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to create different network locations in MacOS

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135367/19272" target="_top" id="2135367">
  <img src="//a.impactradius-go.com/display-ad/19272-2135367" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135367/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Open System Preferences

Click the Apple menu at the top right of your display and select System Preferences from the menu.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123749/7443" target="_top" id="2123749">
  <img src="//a.impactradius-go.com/display-ad/7443-2123749" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123749/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Open Network

From within System Preferences, click the Network icon to open the Network section.

## 3\. Create a new network location

From the Location drop-down, select Edit Locations. In the resulting pop-up, click + (the plus sign). You will be prompted to name the location, so type a new name and hit Enter on your keyboard, and then click Done.

Creating a new Network Location in MacOS Monterey.

Image: Jack Wallen

## 4\. Configure the new location

Make sure to select the new location you created from the Location drop-down. Click Advanced to open the location configuration window, where you can configure the location to meet your specific needs. For example, you can select the network to be used and then configure that network for a static IP address using the Cloudflare DNS servers.

Configuring a network for the new location in MacOS.

Image: Jack Wallen

Once you've configured the location exactly how you need it, click Apply to save everything.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948876/19272" target="_top" id="1948876">
  <img src="//a.impactradius-go.com/display-ad/19272-1948876" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948876/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Switching to a different Network Location

After you've created all of the network locations you need, MacOS makes it very easy to switch between them. All you have to do is click the Apple menu > Location > \[Location name\] (select the name of the location you want to use).

Switching between network locations is a few mouse clicks away.

Image: Jack Wallen

And that's all there is to creating and using network locations in MacOS. If you need to get specific with how your MacOS device interacts with a network, this is a great way to go. Just remember, however, if you move from the current location, you'll want to select another. For example, if you have [one location for home and one for work](https://www.zdnet.com/article/hybrid-workers-dont-want-to-return-to-the-office-but-soon-they-might-have-to/), your machine might have trouble connecting to that work LAN with the home settings.

  
Fortunately, you are now empowered to more easily make that switch.

#### Jack Wallen: Here's how to...

[How to get true window snapping in MacOS](https://www.zdnet.com/article/how-to-get-true-window-snapping-in-macos/ "How to get true window snapping in MacOS")

[The AGM 5 Pro might be the loudest Android phone ever](https://www.zdnet.com/article/the-agm-5-pro-might-be-the-loudest-android-phone-ever/ "The AGM 5 Pro might be the loudest Android phone ever")

[Nitrux 2.4 Linux distro shows promise](https://www.zdnet.com/article/nitrux-2-4-linux-distribution-shows-promise-but-seems-rough-around-the-edges/ "Nitrux 2.4 Linux distro shows promise")

[Tired of being tracked online? DuckDuckGo's Email Protection can help](https://www.zdnet.com/article/tired-of-being-tracked-online-duckduckgos-email-protection-can-help/ "Tired of being tracked online? DuckDuckGo's Email Protection can help")

* [How to get true window snapping in MacOS](https://www.zdnet.com/article/how-to-get-true-window-snapping-in-macos/ "How to get true window snapping in MacOS")
* [The AGM 5 Pro might be the loudest Android phone ever](https://www.zdnet.com/article/the-agm-5-pro-might-be-the-loudest-android-phone-ever/ "The AGM 5 Pro might be the loudest Android phone ever")
* [Nitrux 2.4 Linux distro shows promise](https://www.zdnet.com/article/nitrux-2-4-linux-distribution-shows-promise-but-seems-rough-around-the-edges/ "Nitrux 2.4 Linux distro shows promise")
* [Tired of being tracked online? DuckDuckGo's Email Protection can help](https://www.zdnet.com/article/tired-of-being-tracked-online-duckduckgos-email-protection-can-help/ "Tired of being tracked online? DuckDuckGo's Email Protection can help")

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
<li><a href="https://snapchat-videos.techidaily.com/new-crafting-artistry-your-ultimate-companion-for-boomerangs/"><u>[New] Crafting Artistry Your Ultimate Companion for Boomerangs</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-full-spectrum-kinetics-examination/"><u>[New] Full Spectrum Kinetics Examination</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-profit-from-youtube-monetize-youtube-shorts-and-boost-your-income-for-2024/"><u>[Updated] Profit From YouTube Monetize YouTube Shorts and Boost Your Income for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/8-dall-e-3-prompts-for-your-next-image/"><u>8 DALL-E 3 Prompts for Your Next Image</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-xiaomi-14-ultra-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On Xiaomi 14 Ultra | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/effective-solutions-to-correct-osetupdll-errors-on-your-computer/"><u>Effective Solutions to Correct Osetup.dll Errors on Your Computer</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-gemini-inside-googles-latest-artificve-intelligence-endeavor/"><u>Exploring Gemini: Inside Google's Latest Artificve Intelligence Endeavor</u></a></li>
<li><a href="https://technical-tips.techidaily.com/guide-to-repair-the-jscriptdll-cannot-be-found-mistake/"><u>Guide to Repair the 'JScript.dll' Cannot Be Found Mistake</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-fix-issues-with-microsoft-word-file-openness/"><u>How To Fix Issues With Microsoft Word File Openness</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-can-we-unlock-our-honor-100-pro-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our Honor 100 Pro Phone Screen?</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/premium-free-switch-console-emulators-for-2024/"><u>Premium Free Switch Console Emulators for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/smartwatch-essentials-a-comprehensive-guide-to-features-and-capabilities/"><u>Smartwatch Essentials: A Comprehensive Guide to Features & Capabilities</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-tips-for-organizing-a-memorable-in-house-karaoke-gathering/"><u>Step-by-Step Tips for Organizing a Memorable In-House Karaoke Gathering</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-insights-and-reviews/"><u>Tom's Tech Insights and Reviews</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unveiling-the-technique-to-monitor-location-via-iphone-technology/"><u>Unveiling the Technique to Monitor Location via iPhone Technology</u></a></li>
<li><a href="https://technical-tips.techidaily.com/watch-every-superman-movie-in-their-official-storyline-order/"><u>Watch Every Superman Movie - In Their Official Storyline Order</u></a></li>
</ul></div>

