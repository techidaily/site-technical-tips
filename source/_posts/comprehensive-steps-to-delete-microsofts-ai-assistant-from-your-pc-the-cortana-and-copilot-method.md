---
title: "Comprehensive Steps to Delete Microsoft's AI Assistant From Your PC: The Cortana and Copilot Method"
date: 2024-08-30T13:45:52.874Z
updated: 2024-08-31T13:45:52.874Z
categories:
  - BestProducts
description: "This Article Describes Comprehensive Steps to Delete Microsoft's AI Assistant From Your PC: The Cortana and Copilot Method"
excerpt: "This Article Describes Comprehensive Steps to Delete Microsoft's AI Assistant From Your PC: The Cortana and Copilot Method"
thumbnail: https://thmb.techidaily.com/98f34ca3fe8cce60e4b7bdc2a18ea2c36cd4a116d1b350a14d170a43db0a71bd.jpg
---

## The Critical Point at \(S=-1\) Could Be Asymptotically Stable or Unstable Depending on Further Details About the System Dynamics Not Provided Here
 The error will always appear on a STOP message, more commonly called a[Blue Screen of Death (BSOD)](https://www.lifewire.com/blue-screen-of-death-bsod-2625816) .  

## How to Fix STOP 0x0000007B Errors

 Some of these steps may require you to[access Windows via Safe Mode](https://www.lifewire.com/how-do-i-start-windows-in-safe-mode-2624480) . Just skip those steps if that's not possible.

1. [Restart your computer](https://www.lifewire.com/how-to-reboot-a-computer-2624568) if you haven't already done so. The STOP 0x0000007B blue screen error might be a fluke.  
![Restart Windows 10 PC](https://www.lifewire.com/thmb/6CTZiV6xDkGZI7BTsLaucfk5k0g=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/restartWindows10-7722f41a53714d9ba98b4d59e1614b6c.jpg)
2. Did you just install or make a change to a hard drive controller? If so, there's a good chance that the change you made caused the STOP 0x0000007B error. Undo the change and test for the 0x7B blue screen error.  
 Depending on what changes you made, some solutions might include:  
   * Removing or reconfiguring the newly installed hard drive controller  
   * [Starting up with Last Known Good Configuration](https://www.lifewire.com/how-to-start-windows-7-using-last-known-good-configuration-2626308) to undo related[registry](https://www.lifewire.com/windows-registry-2625992) and driver changes  
   * [Using System Restore](https://www.lifewire.com/how-to-use-system-restore-in-windows-2626131) to undo recent changes  
   * [Rolling back the hard drive controller device driver](https://www.lifewire.com/how-to-roll-back-a-driver-in-windows-2619217) to the version prior to your driver update
3. [Verify that the SCSI chain is correctly terminated](https://web.archive.org/web/20181208051243/http://www.pcguide.com/ref/hdd/if/scsi/cablesTermination-c.html) , assuming you're using[SCSI](https://www.lifewire.com/small-computer-system-interface-scsi-2626002) hard drives in your computer. Incorrect SCSI termination has been known to cause STOP 0x0000007B errors.  
 Most home computers don't utilize SCSI hard drives but instead[PATA](https://www.lifewire.com/parallel-ata-pata-2625957) or[SATA](https://www.lifewire.com/serial-ata-sata-2626009) .
4. Verify that the hard drive is properly installed. An improperly installed hard drive could cause this error and other issues.
5. [Verify that the hard drive is configured properly in BIOS](https://web.archive.org/web/20181212064707/http://www.pcguide.com/ref/hdd/bios/biosSettings-c.html) . The STOP 0x0000007B error could occur if the hard drive settings in[BIOS](https://www.lifewire.com/bios-basic-input-output-system-2625820) are incorrect.
6. [Scan your computer for viruses](https://www.lifewire.com/properly-scan-your-computer-for-viruses-and-other-malware-2624526) . Certain malware that infects the[master boot record](https://www.lifewire.com/what-is-a-master-boot-record-mbr-2625936) (MBR) or[boot sector](https://www.lifewire.com/what-is-a-boot-sector-2625815) can cause STOP 0x0000007B errors.  
 Make sure your virus scanning software is updated and configured to scan the MBR and boot sector. See our[Best Free Antivirus Software](https://www.lifewire.com/best-free-antivirus-software-4151895) list if you don't already have one.
7. [Update the drivers for your hard drive controller](https://www.lifewire.com/how-to-update-drivers-in-windows-2619214) . If the drivers to your hard drive controller are outdated, incorrect, or corrupted, the STOP 0x0000007B error will likely occur.  
 If the error occurs during the Windows setup process and you suspect that the reason is driver related, be sure to install the latest hard drive controller driver from the manufacturer for use during the installation of the[operating system](https://www.lifewire.com/operating-systems-2625912) .  
 This is a likely solution if the second[hexadecimal number](https://www.lifewire.com/what-is-hexadecimal-2625897) _after_ the STOP code is 0xC0000034.
8. Change the SATA mode in BIOS to[IDE](https://www.lifewire.com/what-is-an-ide-cable-2625908) mode. Disabling some of the advanced features of SATA drives in BIOS could stop the STOP 0x0000007B error from showing up, especially if you're seeing it in Windows XP or during a Windows XP installation.  
 Depending on your BIOS make and version, SATA mode may be referred to as_AHCI mode_ and IDE mode may be referred to as either_Legacy_ ,_ATA_ , or_Compatibility Mode_ .  
 While not a common solution, you might also want to try the reverse: see if IDE mode is selected in BIOS and if so, change it to AHCI, especially if you see the STOP 0x0000007B error in Windows 10, 8, 7, or Vista.  
 If you see this STOP error_after making the BIOS change_ on a Windows 7 or Vista computer, you might need to enable the AHCI disk driver. See [Microsoft's instructions](https://support.microsoft.com/en-us/help/922976/error-message-occurs-after-you-change-the-sata-mode-of-the-boot-drive) on making that change in Windows Registry.
9. [Run chkdsk on your hard drive](https://www.lifewire.com/chkdsk-command-2625838) . If the boot volume is corrupted, the chkdsk command might repair the corruption.  
 You'll likely have to run chkdsk from the[Recovery Console](https://www.lifewire.com/recovery-console-2625991) .  
 This will likely be the solution if the second hexadecimal number_after_ the STOP code is 0xC0000032.
10. [Perform an extensive test of your hard drive](https://www.lifewire.com/free-hard-drive-testing-programs-2626183) . If your hard drive has a physical problem, one very likely situation is the STOP 0x0000007B error you're seeing.  
[Replace the hard drive](https://www.lifewire.com/how-to-replace-a-hard-drive-2626200) if the diagnostics you complete suggest that there is a hardware problem with the drive.
11. [Run the fixmbr command](https://www.lifewire.com/fixmbr-command-2625887) to create a new master boot record. A corrupted master boot record might be causing your STOP 0x0000007B error.  
 This will likely be the solution if the second hexadecimal number_after_ the STOP code is 0xC000000E.
12. [Clear the CMOS](https://www.lifewire.com/how-to-clear-cmos-2624545) . Sometimes the STOP 0x0000007B error is caused by a BIOS memory issue. Clearing the CMOS could solve that problem.
13. [Update your BIOS](https://www.lifewire.com/how-to-update-bios-4783238) . In some situations, an outdated BIOS could cause this error due to incompatibilities with a hard drive controller.
14. Update the hard drive controller's[firmware](https://www.lifewire.com/what-is-firmware-2625881) if possible. Just as with the BIOS in the previous step, an incompatibility could be causing the 0x7B error and a firmware update from the manufacturer may correct the problem.
15. [Repair your Windows installation](https://www.lifewire.com/how-do-i-automatically-repair-windows-problems-2624907) . If you've just replaced the[motherboard](https://www.lifewire.com/motherboards-system-boards-and-mainboards-2618154) in a computer without reinstalling Windows then this will likely fix your problem.  
![Repair Windows screen](https://www.lifewire.com/thmb/F11Jk0jxq6MD66N_WFyvaIvuTag=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/repairwindows-5ddd983ddbee4fa5ab34fe8d57eb61ec.jpg)  
 Sometimes a Windows repair will not fix a STOP 0x0000007B error. In those cases, a[clean installation of Windows](https://www.lifewire.com/how-to-clean-install-windows-2624904) should do the trick.  
 If you haven't just replaced your motherboard, a Windows reinstall probably_will not_ fix your STOP 0x7B issue.
16. [Perform basic STOP error troubleshooting](https://www.lifewire.com/how-to-fix-a-blue-screen-of-death-2624518) . If none of the specific steps above help fix the STOP 0x0000007B error you're seeing, take a look at this general STOP error troubleshooting guide. Since most STOP errors are similarly caused, some of the suggestions might help.

## Need More Help?

 If you're not interested in fixing this problem yourself, see[How Do I Get My Computer Fixed?](https://www.lifewire.com/how-do-i-get-my-computer-fixed-2625167) for a full list of your support options, plus help with everything along the way like figuring out repair costs, getting your files off, choosing a repair service, and a whole lot more.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Causes of the STOP 0x0000007B Errors

 One of the errors below, or a combination of both errors, might display on the STOP message:

 STOP: 0x0000007BINACCESSIBLE\_BOOT\_DEVICE  

 The STOP 0x0000007B error may also be abbreviated as STOP 0x7B, but the full[STOP code](https://www.lifewire.com/what-is-a-stop-code-2625685) will always be what's displayed on the blue screen STOP message.

 If Windows is able to start after the STOP 0x7B error, you might be prompted with a_Windows has recovered from an unexpected shutdown_ message that shows:

 Problem Event Name: BlueScreenBCCode: 7b  

 STOP 0x0000007B errors are caused by[device driver](https://www.lifewire.com/what-is-a-device-driver-2625796) issues (especially those related to[hard drive](https://www.lifewire.com/what-is-a-hard-disk-drive-2618152) and other storage controllers), viruses, data corruption, and sometimes even[hardware](https://www.lifewire.com/computer-hardware-2625895) failures.

 Any of Microsoft's Windows NT based operating systems could experience this error. This includes[Windows 10](https://www.lifewire.com/windows-10-2626217) ,[Windows 8](https://www.lifewire.com/windows-8-2626235) ,[Windows 7](https://www.lifewire.com/windows-7-2626265) ,[Windows Vista](https://www.lifewire.com/windows-vista-2626311) ,[Windows XP](https://www.lifewire.com/windows-xp-2626354) , Windows 2000, and Windows NT.

 If STOP 0x0000007B isn't the exact STOP code you're seeing or INACCESSIBLE\_BOOT\_DEVICE isn't the exact message, check our[Complete List of STOP Error Codes](https://www.lifewire.com/blue-screen-error-codes-4065576) and reference the troubleshooting information for the STOP message that you are seeing.

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
<li><a href="https://article-files.techidaily.com/new-2024-approved-diy-build-custom-google-cardboard-virtual-reality/"><u>[New] 2024 Approved  DIY Build  Custom Google Cardboard Virtual Reality</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-expert-review-of-the-leading-no-cost-cam-software-options/"><u>[New] 2024 Approved  Expert Review of the Leading No-Cost Cam Software Options</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-boost-your-channel-game-essential-video-editing-advice-for-2024/"><u>[New] Boost Your Channel Game  Essential Video Editing Advice for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-top-tips-for-maximizing-iphone-xs-cinematic-shots/"><u>[New] Top Tips for Maximizing iPhone X's Cinematic Shots</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solved-headphones-not-detecting-working-on-laptop-windows-11/"><u>[SOLVED] Headphones Not Detecting/ Working on Laptop Windows 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-mastering-the-self-play-feature-in-facebook-videos/"><u>[Updated] Mastering the Self-Play Feature in Facebook Videos</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-most-popular-iphone-podcast-soundshare/"><u>2024 Approved  Most Popular iPhone Podcast Soundshare</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-sonic-streamline-the-playlist-conveyor-belt-trick/"><u>2024 Approved  Sonic Streamline  The Playlist Conveyor Belt Trick</u></a></li>
<li><a href="https://technical-tips.techidaily.com/accelerate-windows-11-boot-times-with-these-tips/"><u>Accelerate Windows 11 Boot Times with These Tips</u></a></li>
<li><a href="https://extra-resources.techidaily.com/advanced-8-visual-boosts-for-online-broadcasts/"><u>Advanced 8 Visual Boosts for Online Broadcasts</u></a></li>
<li><a href="https://technical-tips.techidaily.com/beat-chrome-barriers-unblock-websites-with-these-simple-tips/"><u>Beat Chrome Barriers: Unblock Websites with These Simple Tips</u></a></li>
<li><a href="https://technical-tips.techidaily.com/biologic-agents-like-rituximab-may-be-used-in-refractory-cases-where-standard-treatments-have-failed/"><u>Biologic Agents Like Rituximab May Be Used in Refractory Cases Where Standard Treatments Have Failed.</u></a></li>
<li><a href="https://technical-tips.techidaily.com/boost-your-fortnite-performance-top-2024-strategies/"><u>Boost Your Fortnite Performance: Top 2024 Strategies</u></a></li>
<li><a href="https://technical-tips.techidaily.com/boost-your-listening-experience-on-windows-10-with-professional-sound-equalization-techniques/"><u>Boost Your Listening Experience on Windows 10 with Professional Sound Equalization Techniques</u></a></li>
<li><a href="https://win-able.techidaily.com/concurrent-catastrophes-in-computing-navigating-through-multiple-pc-malfunctions-at-once/"><u>Concurrent Catastrophes in Computing: Navigating Through Multiple PC Malfunctions at Once</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/digital-pathway-learn-lithuanian-effectively/"><u>Digital Pathway: Learn Lithuanian Effectively</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-leading-game-torrent-platforms-a-ranking-guide/"><u>Discover the Leading Game Torrent Platforms: A Ranking Guide</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/discover-the-ultimate-64-bit-video-editor-for-windows/"><u>Discover the Ultimate 64-Bit Video Editor for Windows</u></a></li>
<li><a href="https://technical-tips.techidaily.com/easy-steps-to-recover-and-reset-your-email-password-with-two-factor-authentication-in-gmail/"><u>Easy Steps to Recover and Reset Your Email Password with Two-Factor Authentication in Gmail</u></a></li>
<li><a href="https://technical-tips.techidaily.com/easy-tutorial-configuring-and-enabling-remote-desktop-feature-in-windows-11/"><u>Easy Tutorial: Configuring and Enabling Remote Desktop Feature in Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/elevate-your-online-safety-activating-two-step-verification-for-a-more-secure-gmail-experience/"><u>Elevate Your Online Safety – Activating Two-Step Verification for a More Secure Gmail Experience</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/embracing-the-past-present-mondly/"><u>Embracing the Past, Present Mondly</u></a></li>
<li><a href="https://technical-tips.techidaily.com/enabling-offline-mode-a-step-by-step-guide-to-playing-steam-games-without-internet/"><u>Enabling Offline Mode: A Step-by-Step Guide to Playing Steam Games Without Internet</u></a></li>
<li><a href="https://technical-tips.techidaily.com/enhance-your-windows-11-audio-experience-with-the-top-equalizer-settings/"><u>Enhance Your Windows 11 Audio Experience with the Top Equalizer Settings</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-tips-reactivating-a-broken-or-dead-oculus-controller/"><u>Expert Tips: Reactivating a Broken or Dead Oculus Controller</u></a></li>
<li><a href="https://hardware-help.techidaily.com/fixes-for-common-issues-in-pci-crypto-controller-driver-software/"><u>Fixes for Common Issues in PCI Crypto Controller Driver Software</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-honor-magic5-ultimate-lock-screen-password-by-drfone-android/"><u>How To Change Honor Magic5 Ultimate Lock Screen Password?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-download-epson-scanner-drivers-for-windows-10/"><u>How to Download Epson Scanner Drivers for Windows 10</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-play-fortnite-on-pc-easy-guide-for-beginners/"><u>How to Play Fortnite on PC — Easy Guide for Beginners!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-remove-password-in-windows-11-easily/"><u>How to Remove Password in Windows 11. Easily</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-rotate-screen-in-windows-11-easy-guide/"><u>How to Rotate Screen in Windows 11 [Easy Guide]</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-successfully-revoke-nvidia-drivers-in-windows-10-system/"><u>How To Successfully Revoke Nvidia Drivers in Windows 10 System</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-turn-off-and-on-hibernate-feature-in-windows-10/"><u>How to Turn Off and On Hibernate Feature in Windows 10</u></a></li>
<li><a href="https://technical-tips.techidaily.com/immediate-action-a-fast-way-to-modify-your-facebook-sign-in-key/"><u>Immediate Action: A Fast Way to Modify Your FaceBook Sign-In Key</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1723807898710-immediate-fixes-for-the-camera-not-found-issue-on-your-pc-guide-updated/"><u>Immediate Fixes for the 'Camera Not Found' Issue on Your PC – Guide Updated!</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-vivo-y200-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Vivo Y200</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/leading-5-high-quality-webcams-with-audio-support/"><u>Leading 5 High-Quality Webcams with Audio Support</u></a></li>
<li><a href="https://technical-tips.techidaily.com/maximize-productivity-using-your-laptop-as-an-additional-screen/"><u>Maximize Productivity: Using Your Laptop as an Additional Screen</u></a></li>
<li><a href="https://technical-tips.techidaily.com/quick-start-directx-downloads-for-windows-11-and-10-user-friendly-guide-inside/"><u>Quick-Start DirectX Downloads for Windows 11 & 10 - User-Friendly Guide Inside!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/reactivate-realtek-high-definition-sound-adapter-in-windows-11-with-easy-steps/"><u>Reactivate Realtek High Definition Sound Adapter in Windows 11 with Easy Steps</u></a></li>
<li><a href="https://technical-tips.techidaily.com/reviving-a-stalled-computer-expert-tips-to-fix-freezes-on-windows-11-machines/"><u>Reviving a Stalled Computer: Expert Tips to Fix Freezes on Windows 11 Machines</u></a></li>
<li><a href="https://technical-tips.techidaily.com/simple-guide-switching-your-pcs-operating-system-language-in-windows-10/"><u>Simple Guide: Switching Your PC's Operating System Language in Windows 10</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solving-the-issue-how-to-get-your-teams-webcam-functioning-again-on-windows-11-10-and-7/"><u>Solving the Issue: How to Get Your Team's Webcam Functioning Again on Windows 11, 10 & 7</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-removing-nvidia-graphics-card-drivers-from-your-pc/"><u>Step-by-Step Guide: Removing Nvidia Graphics Card Drivers From Your PC</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-removing-windows-10-updates-effectively/"><u>Step-by-Step Guide: Removing Windows 10 Updates Effectively</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-setting-up-a-vpn-on-your-netgear-router-with-illustrated-steps/"><u>Step-by-Step Guide: Setting Up a VPN on Your Netgear Router with Illustrated Steps</u></a></li>
<li><a href="https://technical-tips.techidaily.com/tips-to-start-outlook-in-safe-mode-on-windows-10-with-pictures/"><u>Tips to Start Outlook in Safe Mode on Windows 10 [with Pictures]</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-low-fps-in-godfall-strategies-for-a-smoother-playthrough/"><u>Troubleshooting Low FPS in Godfall: Strategies for a Smoother Playthrough</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ultimate-guide-enhancing-low-end-audio-on-windows-11/"><u>Ultimate Guide: Enhancing Low-End Audio on Windows 11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unleashing-graphic-power-step-by-step-tutorial-on-gpu-overclocking-for-novices/"><u>Unleashing Graphic Power: Step-by-Step Tutorial on GPU Overclocking for Novices</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1723808201902-usb-selective-suspend-everything-you-need-to-know-about-it/"><u>USB Selective Suspend – Everything You Need to Know About It!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/windows-10-snipping-tool-tutorial-easy-way-to-take-and-edit-screenshots/"><u>Windows 10 Snipping Tool Tutorial: Easy Way to Take and Edit Screenshots</u></a></li>
<li><a href="https://technical-tips.techidaily.com/windows-11-troubleshooting-finding-your-way-to-the-boot-options/"><u>Windows 11 Troubleshooting: Finding Your Way to the Boot Options</u></a></li>
<li><a href="https://technical-tips.techidaily.com/winning-the-race-against-time-how-to-speed-up-windows-1ns-initial-boot-sequence/"><u>Winning the Race Against Time: How to Speed Up Windows 1N's Initial Boot Sequence</u></a></li>
<li><a href="https://extra-resources.techidaily.com/your-first-encounter-with-snapseed-image-editing/"><u>Your First Encounter with Snapseed Image Editing</u></a></li>
</ul></div>
