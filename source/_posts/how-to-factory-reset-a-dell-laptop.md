---
title: How To Factory Reset a Dell Laptop
date: 2025-02-08T03:56:43.621Z
updated: 2025-02-11T16:41:04.054Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes How To Factory Reset a Dell Laptop
excerpt: This Article Describes How To Factory Reset a Dell Laptop
thumbnail: https://thmb.techidaily.com/97473d93769b74152c0b0b04df270598f5aded17925dea70fd12d869a1bbc744.jpg
---

## Error Code 80240020 Deciphered: Easy Steps to Successfully Install Windows 10 without a Glitch

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
<li><a href="https://snapchat-videos.techidaily.com/new-melody-mixin-adding-tracks-to-snapchat-vids/"><u>[New] Melody Mixin' Adding Tracks to Snapchat Vids</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-maximizing-your-time-free-countdown-essentials/"><u>2024 Approved Maximizing Your Time Free Countdown Essentials</u></a></li>
<li><a href="https://data-wizards.techidaily.com/addressing-frame-dropouts-in-h264-videos/"><u>Addressing Frame Dropouts in H.264 Videos</u></a></li>
<li><a href="https://extra-tips.techidaily.com/choosing-between-podcast-and-youtube-for-content-delivery/"><u>Choosing Between Podcast and YouTube for Content Delivery</u></a></li>
<li><a href="https://technical-tips.techidaily.com/easy-steps-for-building-a-portable-wireless-movie-hub-right-in-your-college-room/"><u>Easy Steps for Building a Portable Wireless Movie Hub Right in Your College Room</u></a></li>
<li><a href="https://technical-tips.techidaily.com/effective-methods-for-dealing-with-error-d3dx930dll-missing-on-your-pc/"><u>Effective Methods for Dealing With Error: d3dx9_30.dll Missing on Your PC</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/financial-insights-for-vids-how-much-do-youtubers-earn-per-sponsorship/"><u>Financial Insights for Vids How Much Do YouTubers Earn Per Sponsorship?</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-get-permission-from-trustedinstaller-to-make-changes-to-files/"><u>How to Get Permission From Trustedinstaller to Make Changes to Files</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-videos-from-itel-p55plus-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Videos from Itel P55+ to iPad | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-the-art-of-customizing-windows-photos-app-intertwining-visuals-and-audio/"><u>In 2024, The Art of Customizing Windows Photos App Intertwining Visuals & Audio</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigating-through-iphones-language-and-region-settings-adjustment/"><u>Navigating Through iPhone's Language and Region Settings Adjustment</u></a></li>
<li><a href="https://technical-tips.techidaily.com/overcoming-msxml4dll-file-unavailability-effective-strategies/"><u>Overcoming Msxml4.DLL File Unavailability: Effective Strategies</u></a></li>
<li><a href="https://solve-popular.techidaily.com/resolving-errors-unauthorized-action-attempted-on-non-functional-hard-drive/"><u>Resolving Errors: Unauthorized Action Attempted on Non-Functional Hard Drive</u></a></li>
<li><a href="https://technical-tips.techidaily.com/streamlining-your-inbox-the-ultimate-guide-to-categorizing-emails-with-gmail-labels/"><u>Streamlining Your Inbox: The Ultimate Guide to Categorizing Emails with Gmail Labels</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/top-iso-format-converters-easy-guide-to-change-iso-files-into-popular-video-formats/"><u>Top ISO Format Converters: Easy Guide to Change ISO Files Into Popular Video Formats</u></a></li>
<li><a href="https://technical-tips.techidaily.com/turn-off-unwanted-song-recommendations-from-automatic-playing-in-apple-music/"><u>Turn Off Unwanted Song Recommendations From Automatic Playing in Apple Music</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unraveling-the-mystery-why-have-my-vehicles-speakers-quieted-down/"><u>Unraveling the Mystery: Why Have My Vehicle's Speakers Quieted Down?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/watch-disney-movies-faster-by-linking-disneyplus-to-googles-chromecast-how-to-guide/"><u>Watch Disney Movies Faster by Linking Disney+ to Google's Chromecast – How-To Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/your-comprehensive-source-ps-portable-arrivals-value-insights-in-depth-spec-analysis-and-buying-options/"><u>Your Comprehensive Source: PS Portable Arrivals, Value Insights, In-Depth Spec Analysis & Buying Options</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

