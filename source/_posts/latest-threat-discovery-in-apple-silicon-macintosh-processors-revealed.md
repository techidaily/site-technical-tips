---
title: Latest Threat Discovery in Apple Silicon Macintosh Processors Revealed
date: 2024-08-30T13:33:32.471Z
updated: 2024-08-31T13:33:32.471Z
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
<li><a href="https://facebook-video-files.techidaily.com/new-elevate-your-fb-video-game-11-winning-strategies/"><u>[New] Elevate Your FB Video Game  11 Winning Strategies</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-affordable-recorder-apps-for-older-computers/"><u>[New] In 2024, Affordable Recorder Apps For Older Computers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-tips-for-finding-trending-videos-on-facebook/"><u>[New] In 2024, Tips for Finding Trending Videos on Facebook</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-unraveling-the-secrets-of-recording-hulu-across-computersmobile/"><u>[New] In 2024, Unraveling the Secrets of Recording Hulu Across Computers/Mobile</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-innovative-setup-essentials-for-game-streaming/"><u>[Updated] 2024 Approved  Innovative Setup Essentials for Game Streaming</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-insta-self-portraits-are-they-truly-accurate/"><u>[Updated] 2024 Approved  Insta Self-Portraits  Are They Truly Accurate?</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-the-ultimate-guide-for-ps3-playback-recording/"><u>[Updated] In 2024, The Ultimate Guide for PS3 Playback Recording</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-leading-virtual-reality-titles-for-your-smartphone/"><u>[Updated] The Leading Virtual Reality Titles for Your Smartphone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-masterpieces-in-editing-filmoras-loved-features/"><u>2024 Approved  Masterpieces in Editing - Filmora's Loved Features</u></a></li>
<li><a href="https://technical-tips.techidaily.com/2024s-comprehensive-list-of-free-voip-services-that-outshine-skype/"><u>2024'S Comprehensive List of Free VoIP Services That Outshine Skype</u></a></li>
<li><a href="https://technical-tips.techidaily.com/avoiding-pitfalls-essential-tips-for-a-smooth-bios-power-on-self-test/"><u>Avoiding Pitfalls: Essential Tips for a Smooth BIOS Power On Self Test</u></a></li>
<li><a href="https://technical-tips.techidaily.com/comprehensive-tutorial-on-hooking-up-a-firestick-with-a-projector/"><u>Comprehensive Tutorial on Hooking Up a Firestick with a Projector</u></a></li>
<li><a href="https://technical-tips.techidaily.com/connect-on-the-go-mastering-roku-in-hotels-and-dorms/"><u>Connect on the Go: Mastering Roku in Hotels and Dorms</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/ddpai-mini3-review-dashcams-arent-usually-this-fun/"><u>DDpai Mini3 Review: Dashcams Aren’t Usually This Fun</u></a></li>
<li><a href="https://technical-tips.techidaily.com/everything-you-need-to-know-about-the-upcoming-samsung-z-fold-4-price-release-date-and-specs-included/"><u>Everything You Need to Know About the Upcoming Samsung Z Fold 4 - Price, Release Date & Specs Included</u></a></li>
<li><a href="https://technical-tips.techidaily.com/experience-excellence-with-these-10-fantastic-free-email-options/"><u>Experience Excellence with These 10 Fantastic FREE Email Options</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-tips-for-fixing-not-found-advapi32dll-system-errors-on-your-pc/"><u>Expert Tips for Fixing 'Not Found: Advapi32.dll' System Errors on Your PC</u></a></li>
<li><a href="https://technical-tips.techidaily.com/explore-the-upcoming-galaxy-z-fold-6-cost-guide-release-timeline-detailed-specs-and-news-update/"><u>Explore the Upcoming Galaxy Z Fold 6: Cost Guide, Release Timeline, Detailed Specs & News Update</u></a></li>
<li><a href="https://technical-tips.techidaily.com/exploring-reasons-behind-youtubes-occasional-performance-glitches/"><u>Exploring Reasons Behind YouTube's Occasional Performance Glitches</u></a></li>
<li><a href="https://technical-tips.techidaily.com/fix-the-d3dx92edll-is-absent-problem-expert-tips-and-tricks/"><u>Fix the 'd3dx9_2e.dll Is Absent' Problem: Expert Tips and Tricks</u></a></li>
<li><a href="https://technical-tips.techidaily.com/future-proof-interviews-the-top-9-skype-techniques-of-2e4/"><u>Future-Proof Interviews: The Top 9 Skype Techniques of 2E4</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-videos-from-y28-5g-by-fonelab-android-recover-video/"><u>How to retrieve erased videos from Y28 5G</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-tecno-spark-20-proplus-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Tecno Spark 20 Pro+ to Outlook | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/ignite-your-networking-join-the-1k-club-on-instagram-regularly/"><u>Ignite Your Networking  Join the 1K Club on Instagram Regularly</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-realme-v30t-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Realme V30T | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-charting-course-videos-as-catalysts-in-teaching/"><u>In 2024, Charting Course  Videos as Catalysts in Teaching</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-premier-free-android-recording-apps-no-ads/"><u>In 2024, Premier Free Android Recording Apps (No Ads)</u></a></li>
<li><a href="https://technical-tips.techidaily.com/insta-insight-how-to-keep-essential-conversations-highlighted-with-a-pin-feature/"><u>Insta Insight: How to Keep Essential Conversations Highlighted with a Pin Feature</u></a></li>
<li><a href="https://technical-tips.techidaily.com/is-there-an-xbox-online-service-disruption-or-are-you-just-experiencing-technical-issues/"><u>Is There an Xbox Online Service Disruption? Or Are You Just Experiencing Technical Issues?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-the-art-of-tweeting-etiquette-knowing-when-to-disconnect-from-x-users/"><u>Mastering the Art of Tweeting Etiquette: Knowing When to Disconnect From X Users</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-tiktok-exposure-the-ultimate-10-point-plan-for-virality/"><u>Mastering TikTok Exposure: The Ultimate 10-Point Plan for Virality</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-poco-x6-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Poco X6 Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/resolve-the-missing-d3dx9n34dll-file-issue-quickly-and-easily/"><u>Resolve the 'Missing' d3dx9_n34.dll File Issue Quickly and Easily</u></a></li>
<li><a href="https://technical-tips.techidaily.com/securing-your-fb-profile-again-without-standard-contact-info/"><u>Securing Your FB Profile Again Without Standard Contact Info</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solving-ac1st16dll-not-found-expert-tips-and-tricks/"><u>Solving 'ac1st16.dll Not Found': Expert Tips and Tricks</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-pairing-your-airpods-with-macos-on-macbook-air/"><u>Step-by-Step Guide: Pairing Your AirPods with macOS on MacBook Air</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-streaming-and-sharing-your-favorite-movies-on-netflix/"><u>Step-by-Step Guide: Streaming and Sharing Your Favorite Movies on Netflix</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-tutorial-how-to-repair-your-pcs-bsod-issues/"><u>Step-by-Step Tutorial: How to Repair Your PC's BSOD Issues</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/strategizing-live-broadcasts-turn-your-recordings-into-facebook-hits-for-2024/"><u>Strategizing Live Broadcasts  Turn Your Recordings Into Facebook Hits for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-update-problem-code-0x800f0922/"><u>Tackling Windows Update Problem - Code 0X800f0922</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/the-ultimate-path-to-perfecting-adobe-capture-screen-recordings/"><u>The Ultimate Path to Perfecting Adobe Capture Screen Recordings</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-5-iphone-gps-navigation-apps-you-cant-live-without/"><u>Top 5 iPhone GPS Navigation Apps You Can't Live Without</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-the-d3dx924dll-file-not-found-issue/"><u>Troubleshooting the d3dx9_24.dll File Not Found Issue</u></a></li>
<li><a href="https://technical-tips.techidaily.com/two-factor-fortified-learn-to-implement-advanced-authentication-on-gmail-today/"><u>Two-Factor Fortified: Learn to Implement Advanced Authentication on Gmail Today!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/understanding-pre-purchase-considerations-a-list-of-5-crucial-elements-in-selecting-a-smartwatch/"><u>Understanding Pre-Purchase Considerations: A List of 5 Crucial Elements in Selecting a Smartwatch</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->