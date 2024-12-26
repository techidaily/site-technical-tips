---
title: Latest Threat Discovery in Apple Silicon Macintosh Processors Revealed
date: 2024-12-22T05:45:58.266Z
updated: 2024-12-26T02:37:24.176Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/macbook-air.jpg
---

## Latest Threat Discovery in Apple Silicon Macintosh Processors Revealed

If you thought you were immune from a Meltdown or Spectre-like hardware exploit by using laptops with Apple Silicon chips instead of x86 CPUs, you are unfortunately mistaken. A new vulnerability has popped up on Apple silicon-powered Macs, and it could result in performance losses for some workflows as developers try to patch it.

 Researchers have uncovered a significant vulnerability present in Apple's [M-series chips](https://facebook-record-videos.techidaily.com/updated-the-comprehensive-handbook-of-youtube-views-and-financial-growth/) that exposes Macs to potential attacks, allowing malicious actors to extract secret keys during common cryptographic operations. The vulnerability exploits a hardware optimization feature called the Data Memory-dependent Prefetcher (DMP), present only in M-series chips such as the M1 range and the M2 range, as well as Intel's Raptor Lake microarchitecture. While prefetchers are designed to enhance performance by predicting memory addresses, the DMP, unlike classical prefetchers, utilizes both addresses and data values for predictions. This unique behavior can lead to the leakage of sensitive information, such as encryption keys, through cache side channels.

 Dubbed "GoFetch," the attack can be executed with user-level privileges and targets cryptographic processes running on the same CPU cluster. By crafting inputs to manipulate intermediate data, the attacker can trick the DMP into treating sensitive data as memory addresses, thus leaking secrets over time. The attack is effective against various cryptographic algorithms, even those designed to resist chosen-input attacks.

 The worst part of this vulnerability, however, is that there doesn't look like there's an easy fix for it. Mitigating this vulnerability requires additional defenses in cryptographic software, such as constant-time programming and ciphertext blinding, which come with significant performance costs. Running cryptographic processes on specific CPU cores lacking the DMP may also be necessary but could further impact performance. While newer chips like the M3 offer the option to disable the DMP, the potential performance penalties remain unknown.

 Apple has not officially commented on the research findings, but chances are it'll eventually have to come out with a macOS update that severely limits performance for those specific tasks in order to work around this. That's similar to what happened with the [Meltdown and Spectre security exploits](https://technical-tips.techidaily.com/fixing-motherboard-error-codes-and-bios-issues-during-computer-startup/) in 2018—Spectre was also a side-channel attack, and Meltdown allowed a rogue process to read all memory.

 Source: [Ars Technica](https://arstechnica.com/security/2024/03/hackers-can-extract-secret-encryption-keys-from-apples-mac-chips/)

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
<li><a href="https://vp-tips.techidaily.com/new-navigating-snapchats-new-spotlight-functionality-for-2024/"><u>[New] Navigating Snapchat's New Spotlight Functionality for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-skyward-elite-unified-ultra-hd-multi-touch-panels/"><u>[Updated] 2024 Approved Skyward Elite Unified, Ultra HD Multi-Touch Panels</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-step-by-step-establishing-a-signature-persona-on-youtube/"><u>[Updated] Step-by-Step Establishing a Signature Persona on YouTube</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-cloud-keepers-value-deal-economical-mass-storage/"><u>2024 Approved Cloud Keepers' Value Deal Economical Mass Storage</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-tecno-spark-20-pro-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Tecno Spark 20 Pro | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/android-cache-purge-techniques-for-optimal-performance/"><u>Android Cache Purge Techniques for Optimal Performance</u></a></li>
<li><a href="https://extra-information.techidaily.com/develop-meme-art-in-adobe-suite/"><u>Develop Meme Art in Adobe Suite</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-durable-are-electric-car-batteries-against-petrol-powered-cars/"><u>How Durable Are Electric Car Batteries Against Petrol-Powered Cars?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-choose-your-ideal-academic-desktop-pc-a-comprehensive-guide/"><u>How To Choose Your Ideal Academic Desktop PC - A Comprehensive Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-asus-rog-phone-7-ultimate-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Asus ROG Phone 7 Ultimate for Free? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/premium-choices-the-very-best-tripods-for-high-definition-shooting-for-2024/"><u>Premium Choices The Very Best Tripods for High Definition Shooting for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/sequential-enjoyment-how-to-properly-arrange-and-watch-the-matrix-films/"><u>Sequential Enjoyment: How to Properly Arrange and Watch The Matrix Films</u></a></li>
<li><a href="https://technical-tips.techidaily.com/strengthen-your-digital-communication-with-these-5-premier-secure-email-solutions/"><u>Strengthen Your Digital Communication with These 5 Premier Secure Email Solutions</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-perfect-blend-of-tech-joining-airpods-and-your-hp-notebook-seamlessly/"><u>The Perfect Blend of Tech: Joining AirPods and Your HP Notebook Seamlessly</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-value-packages-for-starting-your-movie-experience-at-home/"><u>The Ultimate Value Packages for Starting Your Movie Experience at Home</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-8-search-tools-to-locate-individuals-easily/"><u>Top 8 Search Tools to Locate Individuals Easily</u></a></li>
<li><a href="https://buynow-help.techidaily.com/top-reason-elevate-your-pc-gaming-experience-with-a-controller-the-top-choice-for-gamers/"><u>Top Reason: Elevate Your PC Gaming Experience with a Controller - The Top Choice for Gamers!</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-catch-the-regional-located-pokemon-for-xiaomi-redmi-12-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Catch the Regional-Located Pokemon For Xiaomi Redmi 12 | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/what-exactly-are-memes-in-the-digital-age/"><u>What Exactly Are Memes in the Digital Age?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

