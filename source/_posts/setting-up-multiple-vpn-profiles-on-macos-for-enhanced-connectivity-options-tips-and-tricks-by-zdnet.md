---
title: Setting Up Multiple VPN Profiles on macOS for Enhanced Connectivity Options | Tips & Tricks by ZDNet
date: 2025-01-10T03:13:00.671Z
updated: 2025-01-11T08:52:26.787Z
tags:
  - apple
categories:
  - tech
thumbnail: https://www.zdnet.com/a/img/resize/9d62ebaae5cde110de337e500298a1dd86cc5b2c/2022/07/11/47775a46-83d9-4a0e-a1e0-bac36bb3c798/macos-ventura-apple-hero.jpg?width=278&height=156&fit=crop&auto=webp
---

## Flexible Connection Setup on macOS with Multiple Network Locations - Tips

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to create different network locations in MacOS

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_SbYznUy_zY?si=ThBkP934r3mizi48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Open System Preferences

Click the Apple menu at the top right of your display and select System Preferences from the menu.

## 2\. Open Network

From within System Preferences, click the Network icon to open the Network section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Create a new network location

From the Location drop-down, select Edit Locations. In the resulting pop-up, click + (the plus sign). You will be prompted to name the location, so type a new name and hit Enter on your keyboard, and then click Done.

Creating a new Network Location in MacOS Monterey.

Image: Jack Wallen

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Configure the new location

Make sure to select the new location you created from the Location drop-down. Click Advanced to open the location configuration window, where you can configure the location to meet your specific needs. For example, you can select the network to be used and then configure that network for a static IP address using the Cloudflare DNS servers.

Configuring a network for the new location in MacOS.

Image: Jack Wallen

Once you've configured the location exactly how you need it, click Apply to save everything.

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
<li><a href="https://article-knowledge.techidaily.com/new-affordable-laptop-friendly-software-for-dvd-viewing-for-2024/"><u>[New] Affordable, Laptop-Friendly Software for DVD Viewing for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-avoiding-lost-sequences-with-obs-fixes/"><u>[Updated] 2024 Approved Avoiding Lost Sequences with OBS Fixes</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-digital-fortune-makers-top-earning-youtubers/"><u>[Updated] 2024 Approved Digital Fortune Makers Top Earning YouTubers</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-discovering-the-metaverses-hidden-joys/"><u>[Updated] In 2024, Discovering the Metaverse's Hidden Joys</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-nighttime-novelties-with-vocalists-recommended-guide/"><u>[Updated] Nighttime Novelties with Vocalists Recommended Guide</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-top-10-best-free-facetime-for-android-alternatives-for-2024/"><u>[Updated] Top 10 Best Free FaceTime for Android Alternatives for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-your-apple-iphone-xr-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset Your Apple iPhone XR? | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722890530608-ipad-wont-connect-to-wi-fi-heres-how-you-can-fix-it/"><u>IPad Won't Connect to Wi-Fi? Here’s How You Can Fix It!</u></a></li>
<li><a href="https://fox-glue.techidaily.com/leading-websites-for-acoustic-phone-alerts-for-2024/"><u>Leading Websites for Acoustic Phone Alerts for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/shifting-your-apple-device-location-a-step-by-step-guide/"><u>Shifting Your Apple Device Location: A Step-by-Step Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-guide-properly-referencing-your-conversations-with-chatgpt/"><u>The Ultimate Guide: Properly Referencing Your Conversations with ChatGPT</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-vanishing-wi-fi-dilemamo-tips-for-restoring-your-networks-presence/"><u>The Vanishing Wi-Fi Dilemamo: Tips for Restoring Your Network's Presence</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-picks-favorite-series-to-stream-on-discovery-plus-in-july-2024/"><u>Top Picks: Favorite Series to Stream on Discovery Plus in July 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unveiling-the-secrets-behind-oled-detailed-insights-into-its-workings/"><u>Unveiling the Secrets Behind OLED - Detailed Insights Into Its Workings</u></a></li>
<li><a href="https://technical-tips.techidaily.com/update-your-viewing-experience-how-to-install-a-new-internet-browser-on-your-samsung-tv/"><u>Update Your Viewing Experience: How to Install a New Internet Browser on Your Samsung TV</u></a></li>
</ul></div>

