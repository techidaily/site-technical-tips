---
title: Windows 10 Search Not Working [Solved]
date: 2024-08-18T19:42:41.128Z
updated: 2024-08-19T19:42:41.128Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Windows 10 Search Not Working [Solved]
excerpt: This Article Describes Windows 10 Search Not Working [Solved]
thumbnail: https://thmb.techidaily.com/dd0fbdf5cb36119cb6841081ccc0579ed7b5b44574bcc137517a05ce80e5ff57.jpg
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
<li><a href="https://hardware-help.techidaily.com/new-update-download-the-scansnap-s1100-software-seamlessly/"><u>[NEW UPDATE]: Download the ScanSnap S1100 Software Seamlessly</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-elevated-viewing-larger-youtube-images/"><u>[New] 2024 Approved  Elevated Viewing  Larger YouTube Images</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-ios-android-unite-how-to-download-and-make-your-own-whatsapp-tones/"><u>[Updated] IOS, Android Unite  How to Download and Make Your Own WhatsApp Tones</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2023s-ultimate-toolwiz-photo-suite-analysis-for-2024/"><u>2023'S Ultimate Toolwiz Photo Suite Analysis for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-capture-and-compress-swift-iphone-time-lapse-tactics/"><u>2024 Approved  Capture and Compress  Swift iPhone Time-Lapse Tactics</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-goovision-9000-ultimate-os-snapshotter/"><u>2024 Approved  GooVision 9000  Ultimate OS Snapshotter</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-xiaomi-redmi-k70-pro-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Xiaomi Redmi K70 Pro | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/airpod-compatibility-can-they-be-connected-to-the-nintendo-switch/"><u>AirPod Compatibility: Can They Be Connected to the Nintendo Switch?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/all-you-need-to-know-teslas-rumored-robotaxi-price-launch-date-and-features/"><u>All You Need to Know: Tesla's Rumored Robotaxi Price, Launch Date & Features</u></a></li>
<li><a href="https://extra-hints.techidaily.com/bigger-photos-equal-quality-output-for-2024/"><u>Bigger Photos, Equal Quality Output for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/comprehensive-guide-to-fix-your-pc-when-it-says-bootmgr-is-absent/"><u>Comprehensive Guide to Fix Your PC When It Says 'BOOTMGR Is Absent'</u></a></li>
<li><a href="https://technical-tips.techidaily.com/comprehensive-walkthrough-making-the-most-out-of-google-gemini/"><u>Comprehensive Walkthrough: Making The Most Out Of Google Gemini</u></a></li>
<li><a href="https://technical-tips.techidaily.com/crucial-inquiries-prospective-buyers-should-make-about-evs/"><u>Crucial Inquiries Prospective Buyers Should Make About EVs</u></a></li>
<li><a href="https://technical-tips.techidaily.com/determining-if-its-a-global-issue-is-blizzards-battlenet-down-or-just-your-connection/"><u>Determining If It's a Global Issue: Is Blizzard's Battle.net Down, Or Just Your Connection?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/distinguishing-features-between-roku-express-and-roku-stick-a-comprehensive-guide/"><u>Distinguishing Features Between Roku Express and Roku Stick - A Comprehensive Guide</u></a></li>
<li><a href="https://some-techniques.techidaily.com/expert-tips-for-precise-control-with-xbox-zoom-for-2024/"><u>Expert Tips for Precise Control with Xbox Zoom for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-tips-for-returning-your-lenovo-desktop-or-laptop-back-to-its-original-state/"><u>Expert Tips for Returning Your Lenovo Desktop or Laptop Back to Its Original State</u></a></li>
<li><a href="https://technical-tips.techidaily.com/explore-our-pick-of-the-best-no-cost-system-registry-tools/"><u>Explore Our Pick of the Best No-Cost System Registry Tools .</u></a></li>
<li><a href="https://technical-tips.techidaily.com/free-communication-tools-better-than-skype-best-picks-of-2024/"><u>Free Communication Tools Better Than Skype - Best Picks of 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/future-google-pixel-wrist-device-cost-estimates-availability-date-and-hardware-details-gathering-insights/"><u>Future Google Pixel Wrist Device: Cost Estimates, Availability Date & Hardware Details – Gathering Insights</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/gazegraphic-reviews-synopsis-for-2024/"><u>GazeGraphic Reviews Synopsis for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-long-does-your-mailcom-username-remain-active/"><u>How Long Does Your Mail.com Username Remain Active?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-turn-off-sticky-keys-on-windows/"><u>How to Turn Off Sticky Keys on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/immediate-fix-overcoming-no-battery-detected-issues-swiftly/"><u>Immediate Fix: Overcoming 'No Battery Detected' Issues Swiftly</u></a></li>
<li><a href="https://win-solutions.techidaily.com/improving-gameplay-fluidity-strategies-to-resolve-stutter-and-elevate-fps-on-the-ascent/"><u>Improving Gameplay Fluidity: Strategies to Resolve Stutter & Elevate FPS on 'The Ascent'</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-apple-iphone-13-pro-max-to-ipod-touch-drfone-by-drfone-transfer-from-ios/"><u>In 2024, 4 Ways to Transfer Music from Apple iPhone 13 Pro Max to iPod touch | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-boost-your-like-ratio-tips-for-squaring-up-videos/"><u>In 2024, Boost Your Like Ratio  Tips for Squaring Up Videos</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-capturing-attention-the-power-of-these-top-10-tags/"><u>In 2024, Capturing Attention  The Power of These Top 10 Tags</u></a></li>
<li><a href="https://technical-tips.techidaily.com/inside-scoop-on-android-16s-release-date-no-cost-features-and-cutting-edge-specs-all-the-rumors-you-need/"><u>Inside Scoop on Android 16'S Release Date, No-Cost Features, and Cutting-Edge Specs: All the Rumors You Need!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/iphone-silence-issue-heres-what-you-need-to-know-and-quick-fixes/"><u>IPhone Silence Issue? Here’s What You Need to Know & Quick Fixes</u></a></li>
<li><a href="https://technical-tips.techidaily.com/is-a-lagging-zoom-call-due-to-the-platform-or-your-network-connection/"><u>Is a Lagging Zoom Call Due to the Platform or Your Network Connection?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/lost-your-ipad-passcode-follow-these-simple-steps-to-regain-access/"><u>Lost Your iPad Passcode? Follow These Simple Steps to Regain Access!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mailcom-subscription-details-explored-anticipating-account-expiration-dates/"><u>Mail.com Subscription Details Explored: Anticipating Account Expiration Dates</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/methods-to-transfer-from-apple-iphone-13-pro-max-to-android-drfone-by-drfone-transfer-from-ios/"><u>Methods to Transfer from Apple iPhone 13 Pro Max to Android | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigating-espnplus-explained-a-comprehensive-look-at-how-it-revolutionizes-sports-viewing/"><u>Navigating ESPN+ Explained: A Comprehensive Look at How It Revolutionizes Sports Viewing</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigating-the-switch-key-inquiries-before-committing-to-an-electric-vehicle-purchase/"><u>Navigating the Switch: Key Inquiries Before Committing to an Electric Vehicle Purchase</u></a></li>
<li><a href="https://technical-tips.techidaily.com/overcoming-the-missing-d3dx9n40dll-error-effective-troubleshooting-techniques/"><u>Overcoming the 'Missing d3dx9_n40.dll' Error: Effective Troubleshooting Techniques</u></a></li>
<li><a href="https://technical-tips.techidaily.com/overcoming-viewing-difficulties-paramount-plus-not-working-properly-on-your-fire-stick/"><u>Overcoming Viewing Difficulties: Paramount Plus Not Working Properly on Your Fire Stick?</u></a></li>
<li><a href="https://extra-information.techidaily.com/premium-picks-recommended-portals-for-tapping-snapchat-tunes/"><u>Premium Picks  Recommended Portals for Tapping Snapchat Tunes</u></a></li>
<li><a href="https://technical-tips.techidaily.com/samsung-event-live-broadcasts-the-ultimate-watch-party-guide/"><u>Samsung Event Live Broadcasts - The Ultimate Watch Party Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/should-i-invest-in-a-ps5-top-4-benefits-of-owning-sonys-latest-console/"><u>Should I Invest in a PS5? Top 4 Benefits of Owning Sony's Latest Console</u></a></li>
<li><a href="https://technical-tips.techidaily.com/slack-in-the-office-expert-techniques-for-streamlining-communication-and-task-management/"><u>Slack in the Office: Expert Techniques for Streamlining Communication and Task Management</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722902338124-slash-your-spending-6-unbeatable-online-deal-destinations-revealed/"><u>Slash Your Spending: 6 Unbeatable Online Deal Destinations Revealed!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solving-the-issue-why-isnt-my-wi-fi-appearing-find-out-how/"><u>Solving the Issue: Why Isn't My Wi-Fi Appearing? Find Out How</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-removing-your-windows-recovery-partition/"><u>Step-by-Step Guide: Removing Your Windows Recovery Partition</u></a></li>
<li><a href="https://driver-download.techidaily.com/step-by-step-fresh-installation-of-samsung-960-evo-drive-software-on-windows-machines/"><u>Step-by-Step: Fresh Installation of Samsung 960 EVO Drive Software on Windows Machines</u></a></li>
<li><a href="https://technical-tips.techidaily.com/streamline-your-tech-with-these-amo-best-free-update-tools-a-comprehensive-collection/"><u>Streamline Your Tech with These Amo Best Free Update Tools: A Comprehensive Collection</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-definitive-how-to-guide-removing-or-pausing-facebook-from-your-android-device/"><u>The Definitive How-To Guide: Removing or Pausing Facebook From Your Android Device</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722879415464-the-samsung-galaxy-z-flip-6-a-comprehensive-guide-to-its-market-release-cost-and-unique-features/"><u>The Samsung Galaxy Z Flip 6: A Comprehensive Guide to Its Market Release, Cost and Unique Features</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-guide-timing-and-techniques-for-dropping-followers-on-x/"><u>The Ultimate Guide: Timing & Techniques for Dropping Followers on X</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-trick-to-securely-reconnect-a-fallen-off-key-from-your-notebook/"><u>The Ultimate Trick to Securely Reconnect a Fallen-Off Key From Your Notebook</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-15-best-free-software-uninstallers-you-should-try/"><u>Top 15 Best Free Software Uninstallers You Should Try</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-the-absent-dbghelpdll-error-in-your-system/"><u>Troubleshooting the Absent Dbghelp.dll Error in Your System</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722880361311-ultimate-guide-speeding-up-your-computer-in-just-7-steps/"><u>Ultimate Guide: Speeding up Your Computer in Just 7 Steps</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ultimate-guide-where-to-find-and-enjoy-free-music-streaming/"><u>Ultimate Guide: Where to Find and Enjoy Free Music Streaming</u></a></li>
<li><a href="https://technical-tips.techidaily.com/understanding-tablet-technology-how-does-the-ipad-distinguish-itself/"><u>Understanding Tablet Technology: How Does the iPad Distinguish Itself?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unlock-the-full-potential-of-your-firestick-with-these-expert-remote-pairing-tips/"><u>Unlock the Full Potential of Your Firestick with These Expert Remote Pairing Tips</u></a></li>
<li><a href="https://technical-tips.techidaily.com/untangling-dll-dilemmas-effective-solutions-for-handling-msvcr70dll-disappearance-errors/"><u>Untangling DLL Dilemmas: Effective Solutions for Handling MSVCR70.DLL Disappearance Errors</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-in-2024-demystifying-ai-game-generators/"><u>Updated In 2024, Demystifying AI Game Generators</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-the-top-webm-to-mp3-converters-you-need-to-know-for-2024/"><u>Updated The Top WebM to MP3 Converters You Need to Know for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->