---
title: Setting Up Multiple VPN Profiles on macOS for Enhanced Connectivity Options | Tips & Tricks by ZDNet
date: 2024-12-02T04:45:34.544Z
updated: 2024-12-05T04:01:45.777Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **ZDNET** Recommends

[The best Macs Apple's Mac lineup can be confusing as the company transitions from Intel processors to its own Apple Silicon processors. But we're here to help.  Read now](https://www.zdnet.com/article/best-mac/)

For the general-purpose network, I can just have MacOS accept an IP address from the DHCP server. However, for the container network, I prefer assigning a static IP address.

Is this possible?

It certainly is. With the help of MacOS Network Locations, you can assign specific configurations for specific networks (or locations) and even define a particular network you want to connect to within a location.

Let me show you how it works.

**Also:** [**How to manage SSH connections on MacOS with Termius**](https://www.zdnet.com/article/how-to-manage-ssh-connections-on-macos-with-termius/) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to create different network locations in MacOS

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

## 1\. Open System Preferences

Click the Apple menu at the top right of your display and select System Preferences from the menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Open Network

From within System Preferences, click the Network icon to open the Network section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-the-finest-global-virtual-learning-hubs-outside-udemy/"><u>[New] 2024 Approved The Finest Global Virtual Learning Hubs Outside Udemy</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-streamlining-online-meetings-zoom-and-gmail-sync-strategies-for-2024/"><u>[New] Streamlining Online Meetings Zoom & Gmail Sync Strategies for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-unleash-your-full-potential-in-the-metaverse/"><u>[Updated] 2024 Approved Unleash Your Full Potential in the Metaverse</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-unveiling-superior-screen-recording-obs-vs-fraps-face-off/"><u>[Updated] Unveiling Superior Screen Recording OBS vs Fraps Face-Off</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-best-professional-drones-an-in-depth-pilots-list/"><u>2024 Approved Best Professional Drones – An In-Depth Pilot’s List</u></a></li>
<li><a href="https://network-issues.techidaily.com/correct-video-glitches-on-monitors/"><u>Correct Video Glitches on Monitors</u></a></li>
<li><a href="https://technical-tips.techidaily.com/deciding-on-your-next-wrist-companion-googles-pixel-watch-against-apples-latest-series-8-techcomparison-blog/"><u>Deciding on Your Next Wrist Companion: Google's Pixel Watch Against Apple's Latest Series 8 | TechComparison Blog</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-25-prime-festive-season-ipad-discounts-your-ultimate-guide-to-saving-big-powered-by-zdnet/"><u>Discover 25 Prime Festive Season iPad Discounts - Your Ultimate Guide to Saving Big, Powered by ZDNet</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-solutions-to-the-msxml4dll-not-found-problem/"><u>Expert Solutions to the Msxml4.dll Not Found Problem</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-honor-100-pro-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Honor 100 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-optimal-ways-to-preserve-android-records/"><u>In 2024, Optimal Ways to Preserve Android Records</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Realme V30T | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigating-your-first-home-audio-setup-a-comprehensive-beginners-guide/"><u>Navigating Your First Home Audio Setup - A Comprehensive Beginners Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/seamless-transition-strategies-upgrading-to-your-new-iphone-with-ease-insights/"><u>Seamless Transition Strategies: Upgrading to Your New iPhone with Ease - Insights</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solve-your-apple-vision-pro-envy-with-budget-friendly-xr-glasses-how-i-did-it/"><u>Solve Your Apple Vision Pro Envy with Budget-Friendly XR Glasses - How I Did It</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-guide-to-using-craft-on-your-mac-enhance-your-document-handling-skills-with-expert-advice-from-zdnet/"><u>The Ultimate Guide to Using Craft on Your Mac: Enhance Your Document Handling Skills with Expert Advice From ZDNET</u></a></li>
</ul></div>

