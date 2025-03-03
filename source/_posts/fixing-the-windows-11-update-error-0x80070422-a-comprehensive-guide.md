---
title: "Fixing the Windows 11 Update Error 0X80070422: A Comprehensive Guide"
date: 2025-02-23T18:58:21.696Z
updated: 2025-03-02T19:28:40.026Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Fixing the Windows 11 Update Error 0X80070422: A Comprehensive Guide"
excerpt: "This Article Describes Fixing the Windows 11 Update Error 0X80070422: A Comprehensive Guide"
thumbnail: https://thmb.techidaily.com/b7b45cfdc35344213e5101907c39a4f8622c548d37868126691840befd4a8d38.jpg
---

## Is Your PC's Windows Update Taking Forever? Here's Why and How to Improve It

**Windows update takes so long to complete?** Although it’s very frustrating, you’re definitely not the only person to experience this problem. Many other Windows users have reported the very same issue. More importantly, you should be able to fix this issue pretty easily!

## **Try these fixes**

 Here’s a list of fixes that have resolved this problem for other Windows users. You don’t have to try them all. Just work your way through the list until you find the one that does the trick for you.

1. **[Run Windows Update Troubleshooter](https://tools.techidaily.com/drivereasy/download/)**
2. **[Update your drivers](https://tools.techidaily.com/drivereasy/download/)**
3. **[Reset Windows Update components](https://tools.techidaily.com/drivereasy/download/)**
4. **[Run the DISM tool](https://tools.techidaily.com/drivereasy/download/)**
5. **[Run System File Checker](https://tools.techidaily.com/drivereasy/download/)**
6. **[Download updates from Microsoft Update Catalog manually](https://tools.techidaily.com/drivereasy/download/)**

---

### Fix 1: Run Windows Update Troubleshooter

 This might be one of the easiest fixes to try. Windows**Update troubleshooter** is a built-in tool that can help you analyze and resolve issues related to Windows updates. Try running Windows Update troubleshooter to see if you can resolve this issue. Here is how to do it:

#### Windows 10

 1) On your keyboard, press**the Windows logo key** and type**troubleshoot** . In the list of search results, select**Troubleshoot** .

![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap828.png)

 2) In the pop-up window, select**Windows Update** and click **Run the troubleshooter** . You’ll be prompted for permission. Click**Yes** to run**Windows Update troubleshooter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap829-2.png)

 3) Click**Apply this fix** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap830.png)

4) Follow the on-screen instructions to troubleshoot this issue.

#### Windows 11

 1) On your keyboard, press the**Windows logo + I keys** simultaneously to open Settings.

 2) From the left navigation panel, select**System** , then click**Troubleshoot** from the right.

![](https://images.drivereasy.com/wp-content/uploads/2022/06/win11-System-Troubleshoot-1200x699.jpg)

 3) Click**Other troubleshooters** .

![](https://images.drivereasy.com/wp-content/uploads/2022/06/win11-Other-troubleshooters-1200x699.jpg)

 4) Click on the**Run** button next to**Windows Update** .

![](https://images.drivereasy.com/wp-content/uploads/2023/12/win11-Troubleshooter-Windows-Update-1200x616.jpg)

 When the process is finished, perform a Windows update again to see if it still takes much longer than usual. If this issue persists, try the next fix, below.

### Fix 2: Update your drivers

 **Outdated or corrupted drivers on your PC can also trigger this issue** . For example, if your network driver is outdated or corrupted, it may slow down your download speed, so Windows updates may take much longer than before. To fix this issue, you need to update your drivers.

 There are two ways to update your drivers:**manually** and **automatically** .

**Update your drivers manually** – You can update your drivers manually by going to the official website of your PC manufacturer and searching for the latest driver for each device on your PC.

 Be sure to choose the driver**that’s compatible with your exact PC model** and **your version of Windows** .

**Or**

**Update your drivers automatically** – If you don’t have the time, patience, or computer skills to update your drivers manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.**Driver Easy handles it all** .

**All the drivers in Driver Easy** come straight from**the manufacturer** . They‘re **all certified safe and secure** .

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.

 2) Run Driver Easy and click**Scan Now** . Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/Driver-Easy-Scan-Needed.jpg)

 3) Click**Update** next to any device to download the correct version of its driver, and then you can install it manually. Or click**Update All** to automatically download and install the correct version of _all_ the drivers that are missing or out of date on your system (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click **Update All.**  You get **full support** and a **30-day money back** guarantee).  

![](https://images.drivereasy.com/wp-content/uploads/2017/03/Driver-Easy-Update-All.jpg)

 You can do it for free if you like, but it’s partly manual.

 If you need assistance, please contact**Driver Easy’s support team** at **[support@drivereasy.com](https://tools.techidaily.com/drivereasy/download/) .**

### Fix 3: Reset Windows Update components

 This issue may occur if there’s something wrong with Windows Update components. If Windows Update components are corrupted, Windows Update may not work properly. In this case, try resetting Windows Update components. Here is how to do it:

 1) On your keyboard, press**the Windows logo key** and **R** at the same time to open the Run dialog. Type **cmd** and press**Ctrl** , **Shift** and **Enter** at the same time to **run Command Prompt as administrator** . You’ll be prompted for permission. Click **Yes** to open the Command Prompt.

![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap468.png)

 2) In Command Prompt, type the command lines below and press**Enter** on your keyboard **after typing each** :

**net stop bits**  
**net stop wuauserv**  
**net stop appidsvc**  
**net stop cryptsvc**

**net stop bits** **net stop wuauserv** **net stop appidsvc** **net stop cryptsvc**

 The Windows Update related system services will be stopped after executing the command lines above.

 3) In Command Prompt, type the following command lines and press**Enter** after typing each:

**ren %systemroot%\SoftwareDistribution SoftwareDistribution.old**
**ren %systemroot%\system32\catroot2 catroot2.old**

 You will**rename** the**SoftwareDistribution and catroot2** folder as **SoftwareDistribution.old and catroot2.old** after you run these two command lines. These two folders are used by Windows Update to save temporary update files.

 By renaming these two folders, **Windows will think these two folders are missing, and Windows will create new ones to store Windows update files.** By doing that, you can avoid many Windows Update issues caused by the old corrupted temporary files in these two folders.

 4) In Command Prompt, type the following command lines and press**Enter** after each:

**net start bits**  
**net start wuauserv**  
**net start appidsvc**  
**net start cryptsvc**

 After executing the command lines above, you start the Windows Update related system services.

 Check to see if this resolves your Windows Update problem. Hopefully, it did. But if not, try the next fix, below.

### Fix 4: Run the DISM tool

 This issue is probably caused by the corrupted Windows update files. In this case, running   **the Deployment Image Servicing and Management (DISM) tool** may resolve this issue. Just follow the step-by-step instructions to run the DISM tool:

 1) On your keyboard, press**the Windows Logo Key** and **R** at the same time to open the Run dialog. Type**cmd**  and then press**Ctrl** , **Shift** , and **Enter**  on your keyboard at the same time to **run the Command Prompt as administrator** . You will be prompted for permission. Click **Yes** to run**Command Prompt** .  

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap245.jpg)

 2) On your keyboard, type the command lines below one by one and press**Enter** .

**Dism /Online /Cleanup-Image /ScanHealth**

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap1-2.jpg)

 When you run the command mentioned above, the DISM tool will scan all the system files and compare them with official system files. The function of this command line is to see if the system file on your PC is consistent with its official source or not. This command line doesn’t fix the corruption. It may take several minutes for this command operation to be completed.

**Dism /Online /Cleanup-Image /CheckHealth**

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap2-5.jpg)

 When you run the command line **Dism /Online /Cleanup-Image /CheckHealth** , the DISM tool will check whether your Windows 10 image has corruptions or not. This command line also doesn’t repair the corrupted files. It may take several minutes for this command operation to be completed.

**Dism /Online /Cleanup-Image /RestoreHealth**

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap3-4.jpg)

 The command line**Dism /Online /Cleanup-Image /RestoreHealth** tells the DISM tool to try to repair the corrupted files detected. It will replace the corrupted files with the files from official sources online. It may take several minutes for this command operation to be completed.

 It may take several minutes for this command operation to be completed.

3) Close the Command Prompt when the restore operation is completed.

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap4-6.jpg)

 Try performing a Windows update to see if this fix works. If this issue persists, try running the System File Checker.

### Fix 5: Run System File Checker

**System File Checker** can scan for corruptions in Windows system files and restore corrupted files. If Windows update takes so long to complete, it may be caused by some corruption error. In this case, running System File Checker may help you resolve this issue.

 1) On your keyboard, press**the Windows Logo Key** and**R** at the same time to open the Run dialog. Type**cmd** and press**Ctrl** ,**Shift** and**Enter** at the same time to**run Command Prompt as administrator** . You’ll be prompted for permission. Click**Yes** to open the Command Prompt.

![](https://images.drivereasy.com/wp-content/uploads/2018/12/snap000138.png)

 2) On your keyboard, type the following command and press**Enter** .

**sfc /scannow**  

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap1-3.jpg)

It may take some time for the command operation to be completed.

 3) When this command operation is completed, close**Command Prompt** .

 Perform a Windows update to check whether this fix works or not. If you still fail to install updates for your Windows system, try the next fix, below.

### Fix 6: Download updates from Microsoft Update Catalog manually

**[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)**  offers updates for Windows 2000 SP3 and later versions of Windows operating system. If None of the fixes above works for you, you can try downloading the updates you failed to install from the Microsoft Update Catalog and install them manually. Here is how to do it:

 1) On your keyboard, press **the Windows logo key** and type **windows update** , then press **Enter** to open **Windows Update** .

 2) Click**View update history** to check the updates you failed to install. For example, if you fail to install update KB3006137, you can download that update and install it manually.

![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap470.png)

 3) Before you download updates, you need to**check the system type** of your Windows OS. If you don’t know how to do it, follow the instructions below to view your system type:

 i. On your keyboard, press**the Windows Logo key** and **R** at the same time to open the Run dialog. Type **cmd** and press **Enter** to open Command Prompt.

![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap471.png)

 ii. Type the command line**systeminfo** and press **Enter** to view your system type.

![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap472.png)

 “**X64-based PC** ” indicates that your Windows OS is **64-bit** ; “**X86-based PC** ” means that your Windows OS is **32-bit** .

 4) Visit[**Microsoft Update Catalog**](https://www.catalog.update.microsoft.com/home.aspx) .

 5) Type the update number that you want to download. In this example, type KB3006137 and then click**Search** .

![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap473.png)

 6) In the list of search results, select the correct update for your operating system and click**Download** .

 If your**Windows OS is 64-bit** , you should download the update whose name contains “**x64-based** ”.

![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap474.png)

7) In the pop-up window, click the link to start downloading the updates.

![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap475.png)

 8)**Double-click** the downloaded file and follow the on-screen instructions to install the update.

Restart your PC to see if this issue persists. If not, congratulations!

 If you have any questions or suggestions, please leave your comments below.

* [Windows Update](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://visual-screen-recording.techidaily.com/new-sword-and-shield-the-ultimate-10-game-collection/"><u>[New] Sword and Shield The Ultimate 10-Game Collection</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-unraveling-the-benefits-of-rapid-youtube-subscription/"><u>[Updated] In 2024, Unraveling the Benefits of Rapid YouTube Subscription</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-above-and-beyond-the-ultimate-guide-to-mavic-pro/"><u>2024 Approved Above and Beyond - The Ultimate Guide to Mavic Pro</u></a></li>
<li><a href="https://technical-tips.techidaily.com/a-step-by-step-guide-implementing-family-safe-settings-on-discord/"><u>A Step-by-Step Guide: Implementing Family Safe Settings on Discord</u></a></li>
<li><a href="https://technical-tips.techidaily.com/complete-guide-to-enabling-domain-safelist-feature-in-macos-mail-client/"><u>Complete Guide to Enabling Domain Safelist Feature in macOS Mail Client</u></a></li>
<li><a href="https://technical-tips.techidaily.com/effortless-steps-to-update-the-time-on-your-kindle-paperwhite-device/"><u>Effortless Steps to Update the Time on Your Kindle Paperwhite Device</u></a></li>
<li><a href="https://games-able.techidaily.com/from-novice-to-pro-streamlining-steam-games-with-meta-quest/"><u>From Novice to Pro: Streamlining Steam Games with Meta Quest</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-migrate-android-data-from-realme-c33-2023-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Migrate Android Data From Realme C33 2023 to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-xiaomi-civi-3-drfone-by-drfone-virtual-android/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On Xiaomi Civi 3 | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-hassle-free-techniques-record-your-dell-screen-easily/"><u>In 2024, Hassle-Free Techniques Record Your Dell Screen Easily</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-perfecting-pics-on-pc-our-top-5-snipping-apps-unveiled/"><u>In 2024, Perfecting Pics on PC Our Top 5 Snipping Apps Unveiled</u></a></li>
<li><a href="https://win-blog.techidaily.com/master-the-fix-dealing-with-finals-error-code-tfla0002-successfully/"><u>Master the Fix: Dealing with Finals Error Code TFLA0002 Successfully</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solving-surface-pro-display-issues-tips-to-stop-screen-vibrations-and-flickers/"><u>Solving Surface Pro Display Issues: Tips to Stop Screen Vibrations & Flickers</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-solution-dealing-with-opengl32dll-errors-on-your-pc/"><u>Step-by-Step Solution: Dealing with OpenGL32.dll Errors on Your PC</u></a></li>
<li><a href="https://technical-tips.techidaily.com/streamers-handbook-demystifying-common-confusions-on-twitch-chat-for-rookies/"><u>Streamer's Handbook: Demystifying Common Confusions on Twitch Chat for Rookies</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-premier-selection-of-android-friendly-wristwear-application-suite/"><u>The Premier Selection of Android-Friendly Wristwear Application Suite</u></a></li>
</ul></div>

