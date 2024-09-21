---
title: How to Resolve Windows 'Problem During Startup' Or Reset Error
date: 2024-09-19T20:51:16.403Z
updated: 2024-09-21T01:04:19.010Z
categories:
  - BestProducts
description: This Article Describes How to Resolve Windows 'Problem During Startup' Or Reset Error
excerpt: This Article Describes How to Resolve Windows 'Problem During Startup' Or Reset Error
thumbnail: https://www.lifewire.com/thmb/RTWozXNfuDskFcnTHBCFbtVSHlU=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/there-was-a-problem-resetting-your-pc-86e596e364114dc2bacc19e1295c4ce4.png
---

## Fixing Windows Boot Failures: Resolve Your 'Resetting PC' Error Today
 If you have a problem with Windows that’s too complicated to fix manually, you might try using[Reset This PC](https://www.lifewire.com/reset-this-pc-2626216) . It’s supposed to completely reinstall Windows with just a few clicks, and can be extremely helpful...if it works.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is the 'There Was a Problem Resetting Your PC' Error?

 If Reset This PC fails to run, you’ll probably get this message, or one like it:  

 `There was a problem resetting your PC`
`No changes were made.`

![There was a problem resetting your pc error](https://www.lifewire.com/thmb/5tOAYiPdaTDXVWTynoE4PdeoMxQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/there-was-a-problem-resetting-your-pc-86e596e364114dc2bacc19e1295c4ce4.png)

## Why This Happens

_Why_ you're getting the error is simple: Reset This PC didn't work. You're clearly trying to solve another problem with a reset,_but the reset tool itself doesn’t even work!_ Without much more to go on than a simple failure to launch, it’s hard to know exactly why Reset This PC didn’t start properly.

 There isn't a single solution to this error, but there are a few things you can try.

 Reset This PC errors can happen in[Windows 11](https://www.lifewire.com/windows-11-5188930) ,[Windows 10](https://www.lifewire.com/windows-10-2626217) , and[Windows 8](https://www.lifewire.com/windows-8-2626235) . The directions below apply to both operating systems.

## How to Fix the 'There Was a Problem Resetting Your PC' Error

 Follow these steps in the order they're presented to try the simpler fixes first:

1. [Restart your computer](https://www.lifewire.com/how-to-reboot-a-computer-2624568) and try again ([reset is different from restart](https://www.lifewire.com/reboot-vs-reset-4157868) ).  
 A simple restart is easy to try and[often fixes unexplained problems](https://www.lifewire.com/why-does-restarting-seem-to-fix-most-computer-problems-2624569) . This might be all you need to do.
2. Run Startup Repair from the[Advanced Startup Options (ASO)](https://www.lifewire.com/advanced-startup-options-2625805) menu. This will attempt to fix problems that are preventing Windows from loading, which might be why Reset This PC won’t start.  
![Startup Repair in Advanced Options menu](https://www.lifewire.com/thmb/EjCM25AXeApJ95fLxmCvw-bZ9uU=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/advanced-options-startup-repair-d8c55ed0c58e406b8073335d1a15270d.png)  
 To complete this step, you’ll need to[access the ASO menu](https://www.lifewire.com/how-to-access-advanced-startup-options-in-windows-10-or-8-2626229) . Once you’re there, go to**Troubleshoot** \>**Advanced options** \>**Startup Repair** .
3. [Repair system files with the sfc /scannow command](https://www.lifewire.com/how-to-use-sfc-scannow-to-repair-windows-system-files-2626161) . Reset This PC might be trying to use some important Windows files that are corrupt, which is why you’re seeing this error.  
![sfc scannow command in Command Prompt](https://www.lifewire.com/thmb/rCEGFztnnEGe2OokQxLPfPKG6Po=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/sfc-scannow-a32db075f41b417d9f9116107fdc6c2b.png)  
 You’ll need to run a command to do this, which you can do in an[elevated Command Prompt](https://www.lifewire.com/how-to-open-an-elevated-command-prompt-2618088) from within Windows. If you can’t get as far as your desktop, use the Command Prompt in the ASO menu. Instructions for both methods are available in that link above.
4. [Run System Restore](https://www.lifewire.com/how-to-use-system-restore-in-windows-2626131) . This will undo any changes made to Windows files that might be the cause for the “_There was a problem resetting your PC_ ” error. Just be sure to restore your computer to a point before the error starting occurring.  
![Windows 10 System Restore screen](https://www.lifewire.com/thmb/YNdyS4A1lLE09hn7V9RJ3Rm-Kc8=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/restore-point-windows-10-ecd60e49098a45c7ad8687986904d818.png)  
 If you can’t log in to Windows to run[System Restore](https://www.lifewire.com/what-is-system-restore-2626022) , you can also do it from the ASO menu via**Troubleshoot** \>**System Restore** or from bootable installation media (see the last step below).
5. Repair Windows Recovery Environment. If the WinRE image is, for whatever reason, missing or corrupt, it might be throwing the “_There was a problem resetting your PC_ ” error.  
 To repair it, open an elevated Command Prompt and enter this command:  
 `reagentc /disable`  
![reagentc disable command in Command Prompt](https://www.lifewire.com/thmb/d5zO43p4ZIJfMESMS8Q9H8kNBPU=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/reagentc-disable-command-2ad577ae139f435da2305cc3d34dfd5b.png)  
 Reboot your computer, open Command Prompt again, and enter this command:  
 `reagentc /enable`  
 This fix is only relevant for a very specific situation, which might be unrelated to what's causing the problem. Be sure to complete the other steps above before moving on to this one.
6. If after trying all of these suggestions, you’ve still been unable to fix the error, you can bypass it entirely by[installing Windows from a disc or a flash drive](https://www.lifewire.com/how-to-clean-install-windows-2624904) . Since your goal from the beginning was to wipe the whole drive and reinstall Windows, you can do so from installation media.  
 For this task, you’ll need to have Windows 11, 10, or 8 on a disc or a flash drive. You’ll be booting to that instead of the hard drive so that you can use the software installed there to reinstall Windows.  
 If you're unfamiliar with the boot process, learn[how to boot from a disc](https://www.lifewire.com/how-to-boot-from-a-cd-dvd-or-bd-disc-2626090) or[how to boot from a USB device](https://www.lifewire.com/how-to-boot-from-a-usb-device-2626091) .

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
<li><a href="https://youtube-lab.techidaily.com/n-2024-best-iphone-and-android-photo-and-video-capture-applications-reviewed/"><u>[New] In 2024, Best iPhone & Android Photo & Video Capture Applications Reviewed</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-unleash-the-potential-elevating-your-tiktok-unboxing-contents-like-count/"><u>[Updated] Unleash the Potential Elevating Your TikTok Unboxing Content's Like Count</u></a></li>
<li><a href="https://technical-tips.techidaily.com/clearing-out-multiple-connections-a-tutorial-for-managing-friends-on-snapchat/"><u>Clearing Out Multiple Connections: A Tutorial for Managing Friends on Snapchat</u></a></li>
<li><a href="https://technical-tips.techidaily.com/connect-the-trio-of-sound-a-step-by-step-guide-for-linking-multiple-bluetooth-speakers/"><u>Connect the Trio of Sound: A Step-by-Step Guide for Linking Multiple Bluetooth Speakers</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-easy-ways-to-change-location-on-youtube-tv-on-itel-a60s-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Easy Ways to Change Location on YouTube TV On Itel A60s | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-asus-rog-phone-8-pro-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-samsung-galaxy-a25-5g-without-him-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Two Ways to Track My Boyfriends Samsung Galaxy A25 5G without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/incorporate-primary-keywords-naturally-within-the-content-without-keyword-stuffing-ensure-each-section-of-your-article-addresses-different-aspects-of-how-qu85/"><u>Incorporate Primary Keywords Naturally Within the Content without Keyword Stuffing. Ensure Each Section of Your Article Addresses Different Aspects of How Quantum Computing Can Revolutionize AI.</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-bluetooth-pairing-a-detailed-walkthrough-for-bose-soundlink-users/"><u>Mastering Bluetooth Pairing: A Detailed Walkthrough for Bose Soundlink Users</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-tutorial-for-keeping-your-contact-details-private-in-the-android-world/"><u>The Ultimate Tutorial for Keeping Your Contact Details Private in the Android World</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-picks-for-seamless-and-feature-rich-video-conferencing-groups/"><u>Top Picks for Seamless and Feature-Rich Video Conferencing Groups</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925544/19272" target="_top" id="1925544">
  <img src="//a.impactradius-go.com/display-ad/19272-1925544" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925544/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

