---
title: "Easy Connection for Double Viewing: Adding a Second Screen in Windows 10"
date: 2025-02-04T18:11:42.939Z
updated: 2025-02-11T23:47:29.849Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Easy Connection for Double Viewing: Adding a Second Screen in Windows 10"
excerpt: "This Article Describes Easy Connection for Double Viewing: Adding a Second Screen in Windows 10"
thumbnail: https://thmb.techidaily.com/a65df42cc8379f3aa4b0bec4cca01f43716f0f93a74b7a32e511a24eeedbecef.jpg
---

## Effective Winsxs Directory Management: Free Up Disk Space on Windows 11 in a Flash

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_59759c33baabd.png)

 This is among the usually asked questions: can I delete WinSxS folder to free up some disk space?

The answer is, no.

 Nor can you delete everything in the WinSxS folder, because some of the files are important for Windows to run and update. Basically, WinSxS folder is where the files needed for your Windows are, as well as backups and/or updates of those files.

 But there are many ways you can use to reduce the size for your WinSxS folder on Windows 10\. In this post, we will be introducing two of them. So you will at least have one option that works.

[**1. Use Disk Cleanup**](https://tools.techidaily.com/drivereasy/download/)

[**2. Use DISM Tool**](https://tools.techidaily.com/drivereasy/download/)

**WARNING** : It is never suggested that you use a third-party tool to cleanup your WinSxS file, since faulty deleting the whole folder or some files in the folder might end up breaking your computer, making it impossible to boot or update.

## **1\. Use Disk Cleanup**

 Disk cleanup is a built-in tool that helps you delete temporary files. To run it, just follow:

 1) On your keyboard, press**Windows logo** button, then type in**disk cleanup** . Then choose**Disk Cleanup** from the list.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b754c83e3.png)

 2) If you haven’t changed the location where you placed your system file, choose**(C:)** and click**OK** . If you have changed the file location before, choose the correct file directory accordingly.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b948ea778.png)

 3) Under**Files to delete** sector, tick the boxes before the files you don’t need anymore and then hit**OK** to delete them. Select to highlight the file name to see more detailed information if you want.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bc59c244b.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) If you need to free more space, you can also choose**Clean up system files** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf02990e3.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then you will be prompted to choose which system drive you want to clean up. Choose accordingly and the clean process will start right away.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf68b4ff6.png)

## **2\. Use DISM Tool**

**DISM**  stands for Deployment Image & Servicing Management. It is a tool that allows you to make changes to Windows features, packages, drivers, and international settings. In this case, we will use it to help us clean up our WinSxS folder.

 The process may take a long time. It some cases, it could take up to 30 minutes. Please don’t worry when it’s not finished after a long time. Please be patient until the process finishes.

 1) On your keyboard, press **Windows logo key**   and **X**   at the same time, then choose **Command Prompt (Admin)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1bb42138.png)

 When prompted with the UAC, hit **Yes** to continue.

 2) In DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup

 This command helps you clean up files when your system is not in use.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1fc428ac.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Check for possible typo. Then hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c4b394177.png)

 4) In the same DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup /ResetBase

 This command helps you remove all superseded versions of every component in the component store.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c546794f7.png)

 5) Make sure you have made no typo and hit**Enter** . Wait for it to finish.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c55d520c4.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 6) Still in the same window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /SPSuperseded

 This command helps you reduce the amount of space used by a Service Pack.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5c8b3c70.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7) Make sure that you have made no typo and hit Enter.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5eb65aaf.png)

 If you need more assistance, feel free to leave us comment and we will see what else we can do to help.

Hope your problem solved!

* [system](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-historical-stop-motion-masterpieces-15-essential-viewing/"><u>[New] 2024 Approved Historical Stop-Motion Masterpieces #15 Essential Viewing</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-photo-perfection-best-practices-for-integrating-frames-online/"><u>[Updated] In 2024, Photo Perfection Best Practices for Integrating Frames Online</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-mastering-free-picture-quality-enhancement-techniques/"><u>[Updated] Mastering Free Picture Quality Enhancement Techniques</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-essential-skills-to-develop-for-thumbnail-designers/"><u>2024 Approved Essential Skills to Develop for Thumbnail Designers</u></a></li>
<li><a href="https://technical-tips.techidaily.com/chromebook-stuck-on-ice-discover-8-ways-to-restore-functionality/"><u>Chromebook Stuck on Ice? Discover 8 Ways to Restore Functionality</u></a></li>
<li><a href="https://technical-tips.techidaily.com/decoding-the-term-wi-fi-calling-an-essential-guide/"><u>Decoding the Term 'Wi-Fi Calling' - An Essential Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-tips-on-how-to-determine-your-cars-anti-theft-radio-code/"><u>Expert Tips on How to Determine Your Car's Anti-Theft Radio Code</u></a></li>
<li><a href="https://technical-tips.techidaily.com/fixing-the-unstartable-device-expert-tips-for-dealing-with-code-10-troubleshooting/"><u>Fixing the Unstartable Device: Expert Tips for Dealing with Code 10 Troubleshooting</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-motorola-edge-40-neo-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Motorola Edge 40 Neo Quickly? | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-capturing-moments-right-ideal-perspectives-on-iphone/"><u>In 2024, Capturing Moments Right Ideal Perspectives on iPhone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/reaching-new-heights-counting-the-tiers-of-royal-match-competition/"><u>Reaching New Heights: Counting the Tiers of Royal Match Competition</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/664347-9781846946516-spirit-release/"><u>Spirit Release | Free Book</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-tutorial-syncing-disneyplus-app-with-google-chromecast-for-ultimate-viewing/"><u>Step-by-Step Tutorial: Syncing Disney+ App with Google Chromecast for Ultimate Viewing</u></a></li>
<li><a href="https://technical-tips.techidaily.com/understanding-the-page-cannot-be-displayed-message-a-complete-guide-on-causes-and-solutions/"><u>Understanding the 'Page Cannot Be Displayed' Message: A Complete Guide on Causes and Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlimited-entertainment-streaming-download-movies-and-songs-directly-from-websites/"><u>Unlimited Entertainment Streaming: Download Movies and Songs Directly From Websites</u></a></li>
</ul></div>

