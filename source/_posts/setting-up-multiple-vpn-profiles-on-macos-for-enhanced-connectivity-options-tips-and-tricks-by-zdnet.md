---
title: Setting Up Multiple VPN Profiles on macOS for Enhanced Connectivity Options | Tips & Tricks by ZDNet
date: 2024-12-22T04:52:58.747Z
updated: 2024-12-25T16:58:19.237Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/OFDHJnZLwTA?si=WThcb2h76AnZDzcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to create different network locations in MacOS

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Open System Preferences

Click the Apple menu at the top right of your display and select System Preferences from the menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Open Network

From within System Preferences, click the Network icon to open the Network section.

## 3\. Create a new network location

From the Location drop-down, select Edit Locations. In the resulting pop-up, click + (the plus sign). You will be prompted to name the location, so type a new name and hit Enter on your keyboard, and then click Done.

Creating a new Network Location in MacOS Monterey.

Image: Jack Wallen

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Configure the new location

Make sure to select the new location you created from the Location drop-down. Click Advanced to open the location configuration window, where you can configure the location to meet your specific needs. For example, you can select the network to be used and then configure that network for a static IP address using the Cloudflare DNS servers.

Configuring a network for the new location in MacOS.

Image: Jack Wallen

Once you've configured the location exactly how you need it, click Apply to save everything.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-the-ultimate-instagram-photography-guide-for-crafting-perfect-covers/"><u>[New] 2024 Approved The Ultimate Instagram Photography Guide for Crafting Perfect Covers</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-hashing-it-out-best-tags-to-transform-views-and-profit/"><u>[New] Hashing It Out Best Tags to Transform Views & Profit</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1726227468912-aif-wav-movavi/"><u>「AIF-WAV変換無料: スムーズなオンラインコンバート - Movavi」</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-no-cost-conversion-elevate-your-facebook-videos-to-mp4-and-hd-quality/"><u>2024 Approved No-Cost Conversion Elevate Your Facebook Videos to MP4 & HD Quality</u></a></li>
<li><a href="https://fox-zero.techidaily.com/5-proven-solutions-for-restoring-music-on-your-iphones-lock-screen-ios-16-17-and-18/"><u>5 Proven Solutions for Restoring Music on Your iPhone's Lock Screen (iOS 16, 17 & 18)</u></a></li>
<li><a href="https://technical-tips.techidaily.com/descargar-e-imprimir-de-forma-gratuita-convertidor-de-archivos-raw-cr2-al-formato-jpegbmp/"><u>Descargar E Imprimir De Forma Gratuita: Convertidor De Archivos RAW (CR2) Al Formato JPEG/BMP</u></a></li>
<li><a href="https://technical-tips.techidaily.com/downloads-gratuit-transformer-un-fichier-trp-en-video-mp4-avec-movavi/"><u>Downloads Gratuit : Transformer Un Fichier TRP en Vidéo MP4 Avec Movavi</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-open-swf-files-in-windows-systems-windows-11-10-8-and-e/"><u>How to Open SWF Files in Windows Systems: Windows 11, 10, 8 & E</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-open-your-apple-iphone-6s-without-a-home-button-drfone-by-drfone-ios/"><u>In 2024, How To Open Your Apple iPhone 6s Without a Home Button | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-honor-x50-drfone-by-drfone-virtual-android/"><u>In 2024, How to Watch Hulu Outside US On Honor X50 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-realme-11-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Realme 11 Pro+ | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-failed-validation-with-credit-card-issues/"><u>Overcoming Failed Validation with Credit Card Issues</u></a></li>
<li><a href="https://technical-tips.techidaily.com/quick-and-simple-flv-to-avi-file-transformation-use-movavis-free-online-tool-now/"><u>Quick & Simple FLV to AVI File Transformation - Use Movavi's Free Online Tool Now!</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/step-by-step-tutorial-on-downloading-and-installing-latest-amd-radeon-hd-7870-drivers-for-windows-11/"><u>Step-by-Step Tutorial on Downloading and Installing Latest AMD Radeon HD 7870 Drivers for Windows 11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/topo-12-os-maiores-software-de-captura-de-tela-livres-para-sistema-windows-8-da-moveavi/"><u>Topo 12: Os Maiores Software De Captura De Tela Livres Para Sistema Windows 8 Da Moveávi</u></a></li>
<li><a href="https://technical-tips.techidaily.com/transformador-digital-av-cambiar-mp4-por-aac-o-aac-para-mp4/"><u>Transformador Digital AV: Cambiar MP4 Por AAC O AAC Para MP4</u></a></li>
</ul></div>

