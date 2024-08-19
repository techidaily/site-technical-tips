---
title: Step-by-Step Solution for Correcting 'Windows Cannot Install Updates' Error (0X80248007) in Windows 11
date: 2024-08-18T19:37:33.816Z
updated: 2024-08-19T19:37:33.816Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Step-by-Step Solution for Correcting 'Windows Cannot Install Updates' Error (0X80248007) in Windows 11
excerpt: This Article Describes Step-by-Step Solution for Correcting 'Windows Cannot Install Updates' Error (0X80248007) in Windows 11
thumbnail: https://thmb.techidaily.com/d03c6bda0db9e446c0d9464753859ee1c2f12f38d94da77b1f5b8b2204a1d875.jpg
---

## Resolving Windows 10 Installation Issue - Fix Error Code 80 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-facebook-vault-convert-videos-to-mp4-in-seconds/"><u>[New] 2024 Approved  Facebook Vault  Convert Videos to MP4 in Seconds</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-video-magic-quick-angular-and-joint-editing-on-android/"><u>[New] 2024 Approved  Video Magic  Quick Angular and Joint Editing on Android</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-youtube-channel-art-make-banners-icons-and-thumbnails/"><u>[New] 2024 Approved  YouTube Channel Art - Make Banners, Icons, and Thumbnails</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-beneath-the-surface-assessing-huawei-p10-writability-features-for-2024/"><u>[New] Beneath the Surface  Assessing Huawei P10' Writability Features for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-instatales-order-your-pictures-rightly/"><u>[New] In 2024, InstaTales  Order Your Pictures Rightly</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-mellow-playtime-10-top-rated-stress-erasers/"><u>[New] Mellow Playtime  10 Top-Rated Stress Erasers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-tech-gear-review-vr-treadmills-showdown-for-2024/"><u>[New] Tech Gear Review  VR Treadmills Showdown for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-transform-your-screen-recording-process-using-aiseesoft-tools-for-2024/"><u>[New] Transform Your Screen Recording Process Using Aiseesoft Tools for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-securing-your-snapchat-footage-a-step-by-step-process/"><u>[Updated] In 2024, Securing Your Snapchat Footage  A Step-by-Step Process</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-the-art-of-increasing-indoor-ambiance-via-sunlight/"><u>[Updated] In 2024, The Art of Increasing Indoor Ambiance via Sunlight</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-uncluttered-desktop-recorder-w10/"><u>[Updated] Uncluttered Desktop Recorder W10</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-discover-how-to-change-your-characters-voice-and-sound-presence-naturally-expert-tips-for-free/"><u>2024 Approved  Discover How to Change Your Character's Voice and Sound Presence Naturally  Expert Tips for FREE</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-from-zero-to-hero-steps-to-construct-your-channels-backlinks/"><u>2024 Approved  From Zero to Hero  Steps to Construct Your Channel's Backlinks</u></a></li>
<li><a href="https://win11.techidaily.com/4-early-stages-of-pc-failure-know-when-to-act/"><u>4 Early Stages of PC Failure, Know When To Act</u></a></li>
<li><a href="https://technical-tips.techidaily.com/apples-upcoming-household-automation-companion-insights-on-anticipated-cost-and-launch-timeline/"><u>Apple's Upcoming Household Automation Companion: Insights on Anticipated Cost & Launch Timeline</u></a></li>
<li><a href="https://technical-tips.techidaily.com/artifice-intelligences-influence-on-future-progress/"><u>Artifice Intelligence's Influence on Future Progress</u></a></li>
<li><a href="https://technical-tips.techidaily.com/complete-tutorial-enabling-cookie-functionality-on-browsers/"><u>Complete Tutorial: Enabling Cookie Functionality on Browsers</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/comprehensive-guide-free-and-paid-tools-for-noise-reduction-for-2024/"><u>Comprehensive Guide  Free & Paid Tools for Noise Reduction for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/crafting-a-stellar-visual-identity-the-ultimate-guide-to-yt-design-for-2024/"><u>Crafting a Stellar Visual Identity  The Ultimate Guide to YT Design for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/d3dx930dll-error-resolution-essential-tips-and-tricks/"><u>D3dx9_30.dll Error Resolution: Essential Tips and Tricks</u></a></li>
<li><a href="https://technical-tips.techidaily.com/decode-the-mystery-a-detailed-look-at-all-blue-screen-stop-messages/"><u>Decode the Mystery: A Detailed Look at All Blue Screen 'STOP' Messages</u></a></li>
<li><a href="https://technical-tips.techidaily.com/decoding-royal-match-understanding-its-multi-level-composition/"><u>Decoding Royal Match: Understanding Its Multi-Level Composition</u></a></li>
<li><a href="https://technical-tips.techidaily.com/decoding-tech-terms-the-clear-difference-between-ar-vr-mr-and-xr/"><u>Decoding Tech Terms: The Clear Difference Between AR, VR, MR & XR</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-ultimate-list-of-7-free-musical-delights-for-your-mobile-devices/"><u>Discover the Ultimate List of 7 Free Musical Delights for Your Mobile Devices</u></a></li>
<li><a href="https://technical-tips.techidaily.com/easy-fixes-for-when-your-surface-pro-wont-connect-to-the-internet/"><u>Easy Fixes for When Your Surface Pro Won't Connect to the Internet</u></a></li>
<li><a href="https://technical-tips.techidaily.com/faster-sound-playback-tips-overcoming-chromecast-audio-buffering-problems/"><u>Faster Sound Playback Tips: Overcoming Chromecast Audio Buffering Problems</u></a></li>
<li><a href="https://technical-tips.techidaily.com/free-onscreen-entertainment-browse-movies-and-series-on-crackle-for-zero-dollars/"><u>Free Onscreen Entertainment: Browse Movies & Series on Crackle for Zero Dollars</u></a></li>
<li><a href="https://technical-tips.techidaily.com/galaxy-z-fold-6-arrives-explore-the-price-tag-release-timeline-and-comprehensive-specifications/"><u>Galaxy Z Fold 6 Arrives - Explore the Price Tag, Release Timeline & Comprehensive Specifications</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-to-correcting-device-misconfiguration-error-code-1-solution/"><u>Guide to Correcting Device Misconfiguration Error - Code 1 Solution</u></a></li>
<li><a href="https://technical-tips.techidaily.com/guide-successfully-adding-domains-to-safe-lists-on-macos-mail/"><u>Guide: Successfully Adding Domains to Safe Lists on macOS Mail</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/how-does-the-samsung-q60r-series-stack-up-an-in-depth-review-of-a-4k-smart-gaming-tv/"><u>How Does the Samsung Q60R Series Stack Up? An In-Depth Review of a 4K Smart Gaming TV</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-change-the-sound-of-new-mail-alerts-in-your-gmail-account-the-ultimate-tutorial/"><u>How to Change the Sound of New Mail Alerts in Your Gmail Account: The Ultimate Tutorial</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-correct-cygwin1dll-not-found-bugs-successfully/"><u>How to Correct 'cygwin1.dll Not Found' Bugs Successfully</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-correctly-address-the-not-found-msvcr71dll-system-error/"><u>How To Correctly Address The Not Found: msvcr71.dll System Error</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-ensure-safe-whitelisting-of-your-personal-or-business-email-addresses/"><u>How to Ensure Safe Whitelisting of Your Personal or Business Email Addresses</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-pictures-from-nubia-by-fonelab-android-recover-pictures/"><u>How to Rescue Lost Pictures from Nubia ?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/important-aspects-to-check-out-before-investing-in-a-new-smartwatch-a-comprehensive-guide/"><u>Important Aspects to Check Out Before Investing in a New Smartwatch: A Comprehensive Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-nokia-105-classic-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Nokia 105 Classic to Roku | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-screen-to-samsung-galaxy-s23-phones-drfone-by-drfone-android/"><u>In 2024, How to Mirror PC Screen to Samsung Galaxy S23 Phones? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-open-your-iphone-15-plus-without-a-home-button-drfone-by-drfone-ios/"><u>In 2024, How To Open Your iPhone 15 Plus Without a Home Button | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-gmail-password-on-oppo-find-x7-devices-by-drfone-android/"><u>In 2024, How to Reset Gmail Password on Oppo Find X7 Devices</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-vivo-v27-pro-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Vivo V27 Pro to PC? | Dr.fone</u></a></li>
<li><a href="https://fox-that.techidaily.com/iphone-photo-collection-made-simple-uncover-8-proven-strategies-and-insights-to-fix-camera-roll-challenges/"><u>IPhone Photo Collection Made Simple: Uncover 8 Proven Strategies & Insights to Fix Camera Roll Challenges</u></a></li>
<li><a href="https://technical-tips.techidaily.com/is-a-digital-to-analog-converter-dac-necessary-in-your-setup/"><u>Is a Digital-to-Analog Converter (DAC) Necessary in Your Setup?</u></a></li>
<li><a href="https://youtube-help.techidaily.com/joke-junctions-brainstorming-7-hilarious-youtube-storylines-for-2024/"><u>Joke Junctions  Brainstorming 7 Hilarious YouTube Storylines for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/july-2024s-must-watch-free-films-from-youtube-find-your-next-viewing-pleasure/"><u>July 2024'S Must-Watch FREE Films From YouTube - Find Your Next Viewing Pleasure!</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/leading-the-pack-in-instagram-content-crafting-puzzle-feeds/"><u>Leading the Pack in Instagram Content  Crafting Puzzle Feeds</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-the-battle-against-a-lynel-in-the-legend-of-zelda-breath-of-the-wild/"><u>Mastering the Battle Against a Lynel in The Legend of Zelda: Breath of the Wild</u></a></li>
<li><a href="https://technical-tips.techidaily.com/playstation-5-compact-version-detailed-breakdown-of-price-point-release-schedule-and-feature-set/"><u>PlayStation 5 Compact Version: Detailed Breakdown of Price Point, Release Schedule & Feature Set</u></a></li>
<li><a href="https://technical-tips.techidaily.com/powerpoint-audio-repair-tips-addressing-and-resolving-soundplay-problems-in-your-slideshow/"><u>PowerPoint Audio Repair Tips: Addressing and Resolving Soundplay Problems in Your Slideshow</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/professional-selfies-elevating-your-online-presence/"><u>Professional Selfies  Elevating Your Online Presence</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/quick-tips-addressing-thread-exception-not-handled-errors-effortlessly/"><u>Quick Tips: Addressing 'Thread Exception Not Handled' Errors Effortlessly</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-edge-browser-crash-issues-on-windows-11-systems/"><u>Resolving Edge Browser Crash Issues on Windows 11 Systems</u></a></li>
<li><a href="https://technical-tips.techidaily.com/resolving-the-msvbvm50dll-error-comprehensive-troubleshooting-guide/"><u>Resolving the msvbvm50.dll Error: Comprehensive Troubleshooting Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/rumors-of-the-next-pixel-wrist-device-estimated-price-tag-release-forecast-and-speculative-hardware-reviewed/"><u>Rumors of the Next Pixel Wrist Device – Estimated Price Tag, Release Forecast, and Speculative Hardware Reviewed</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solving-d3d9dll-file-missing-issues-a-comprehensive-guide/"><u>Solving d3d9.dll File Missing Issues: A Comprehensive Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solving-your-ps5-dualsense-charger-issues-expert-advice-and-tips/"><u>Solving Your PS5 DualSense Charger Issues: Expert Advice & Tips</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-instructions-on-how-to-binge-watch-the-indiana-jones-franchise-properly/"><u>Step-by-Step Instructions on How to Binge Watch the Indiana Jones Franchise Properly</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-tips-on-how-to-engage-in-a-twitter-discussion/"><u>Step-by-Step Tips on How To Engage In A Twitter Discussion</u></a></li>
<li><a href="https://facebook.techidaily.com/streamlining-social-media-integration-a-step-by-step-guide/"><u>Streamlining Social Media Integration: A Step-by-Step Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/streamlining-your-social-circle-remove-groups-of-contacts-quickly-from-snapchat/"><u>Streamlining Your Social Circle: Remove Groups of Contacts Quickly From Snapchat</u></a></li>
<li><a href="https://extra-hints.techidaily.com/synchronized-intro-editing-across-all-your-devices-this-year/"><u>Synchronized Intro Editing Across All Your Devices This Year</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-art-of-creating-awkward-potions-in-minecraft-expert-tips-and-techniques/"><u>The Art of Creating Awkward Potions in Minecraft - Expert Tips and Techniques</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/the-art-of-repeated-imagery-in-instagram-videos-for-2024/"><u>The Art of Repeated Imagery in Instagram Videos for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-best-spy-watches-for-your-xiaomi-civi-3-drfone-by-drfone-virtual-android/"><u>Top 10 Best Spy Watches For your Xiaomi Civi 3 | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-12-best-free-online-calling-applications-in-2-new-trends-the-best-12-free-voip-services/"><u>Top 12 Best Free Online Calling Applications in 2# New Trends: The Best 12 Free VoIP Services</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-2024-picks-ultimate-guide-to-choosing-a-durable-waterproof-smartphone-case/"><u>Top 2024 Picks: Ultimate Guide to Choosing a Durable Waterproof Smartphone Case</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-steps-for-elden-ring-when-multiplayer-stops-responding/"><u>Troubleshooting Steps for Elden Ring When Multiplayer Stops Responding</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-tips-getting-your-amazon-echo-online-again/"><u>Troubleshooting Tips: Getting Your Amazon Echo Online Again</u></a></li>
<li><a href="https://technical-tips.techidaily.com/uber-vs-taxi-a-cost-comparison-which-is-more-budget-friendly/"><u>Uber Vs. Taxi: A Cost Comparison - Which Is More Budget-Friendly?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/understanding-dacs-why-you-should-consider-adding-this-device-for-superior-sound-quality/"><u>Understanding DACs: Why You Should Consider Adding This Device for Superior Sound Quality</u></a></li>
<li><a href="https://technical-tips.techidaily.com/what-comes-with-the-nintendo-switch/"><u>What Comes With the Nintendo Switch?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/whats-next-for-sony-in-vr-price-insights-and-release-timeline-revealed/"><u>What's Next for Sony in VR? Price Insights and Release Timeline Revealed</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-apple-iphone-14-drfone-by-drfone-virtual-ios/"><u>Why Your WhatsApp Live Location is Not Updating and How to Fix on your Apple iPhone 14 | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->