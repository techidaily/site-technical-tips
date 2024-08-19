---
title: Top 13 Must-Listen True Crime Podcast Episodes
date: 2024-08-18T20:50:13.312Z
updated: 2024-08-19T20:50:13.312Z
categories:
  - BestProducts
description: This Article Describes Top 13 Must-Listen True Crime Podcast Episodes
excerpt: This Article Describes Top 13 Must-Listen True Crime Podcast Episodes
thumbnail: https://www.lifewire.com/thmb/zkbFe6fSEIJ3l6ilOk3yxBweE7Y=/540x405/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/accident-barrier-caution-923681-5b0d7e5a1d64040037626584.jpg
---

## Step-by-Step Fix for Stop Code 0X0000007B – No More Blue Screen Woes
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
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
<li><a href="https://vp-tips.techidaily.com/new-the-art-of-color-transformation-an-expert-written-by-dr-jane-smith/"><u>[New] The Art of Color Transformation  An Expert' Written by Dr. Jane Smith</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-download-youtube-audio-safely-and-legally-in-3-ways/"><u>[Updated] Download Youtube Audio  Safely & Legally in 3 Ways</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-how-to-transition-your-facebook-vids-into-stellar-hd-for-2024/"><u>[Updated] How to Transition Your Facebook Vids Into Stellar HD for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-master-video-cropping-for-unique-instagram-visuals/"><u>[Updated] In 2024, Master Video Cropping for Unique Instagram Visuals</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-optimal-low-price-nintendo-simulations/"><u>[Updated] In 2024, Optimal Low-Price Nintendo Simulations</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-winning-game-recording-guide-for-w11-users-for-2024/"><u>[Updated] Winning Game Recording Guide for W11 Users for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/a-closer-look-at-aim-everything-you-need-to-know-about-aols-chat-giant/"><u>A Closer Look at AIM: Everything You Need to Know About AOL's Chat Giant</u></a></li>
<li><a href="https://win-answers.techidaily.com/beat-the-load-effective-strategies-for-getting-past-sea-of-thieves-starting-hurdle/"><u>Beat the Load: Effective Strategies for Getting Past Sea of Thieves' Starting Hurdle</u></a></li>
<li><a href="https://technical-tips.techidaily.com/choosing-a-motherboard-with-confidence-analyzing-7-determining-factors/"><u>Choosing a Motherboard with Confidence: Analyzing 7 Determining Factors</u></a></li>
<li><a href="https://technical-tips.techidaily.com/connecting-your-airpods-seamlessly-with-your-macbook-air-a-detailed-walkthrough/"><u>Connecting Your AirPods Seamlessly with Your MacBook Air - A Detailed Walkthrough</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/corrected-screen-tilt-in-netbook-fix/"><u>Corrected Screen Tilt in Netbook Fix</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-ultimate-selection-the-top-11-inspiring-film-gems-for-viewers/"><u>Discover the Ultimate Selection: The Top 11 Inspiring Film Gems for Viewers</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discovering-aether-unveiling-its-nature-and-secrets-of-membership/"><u>Discovering Aether: Unveiling Its Nature & Secrets of Membership</u></a></li>
<li><a href="https://technical-tips.techidaily.com/exclusive-insight-whats-coming-with-the-newly-announced-samsung-galaxy-z-flip-gen3-predicted-cost-and-release-schedule-included/"><u>Exclusive Insight: What's Coming with the Newly Announced Samsung Galaxy Z Flip Gen3 – Predicted Cost and Release Schedule Included!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/exploring-biometrics-insightful-definitions-and-applications/"><u>Exploring Biometrics: Insightful Definitions and Applications</u></a></li>
<li><a href="https://technical-tips.techidaily.com/fix-your-computers-fm2dll-error-quickly-and-easily/"><u>Fix Your Computer's Fm2#.dll Error Quickly and Easily</u></a></li>
<li><a href="https://technical-tips.techidaily.com/from-sweet-sixteen-to-championship-glory-catch-every-dribble-of-mens-college-hoops-on-air/"><u>From Sweet Sixteen to Championship Glory: Catch Every Dribble of Men's College Hoops on Air!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-long-does-your-mailcom-username-remain-active/"><u>How Long Does Your Mail.com Username Remain Active?</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-apple-iphone-14-pro-location-is-wrong-drfone-by-drfone-virtual-ios/"><u>How to Fix My Apple iPhone 14 Pro Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-in-depth-analysis-of-gradual-audio-lowering-with-lumafusion/"><u>In 2024, In-Depth Analysis of Gradual Audio Lowering with Lumafusion</u></a></li>
<li><a href="https://technical-tips.techidaily.com/is-a-lagging-zoom-call-due-to-the-platform-or-your-network-connection/"><u>Is a Lagging Zoom Call Due to the Platform or Your Network Connection?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/is-it-time-to-upgrade-to-a-blu-ray-player-or-stick-with-streaming-options/"><u>Is It Time to Upgrade to a Blu-Ray Player or Stick with Streaming Options?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722851559708-keyboard-malfunctions-heres-how-to-get-it-back-in-working-order/"><u>Keyboard Malfunctions? Here's How to Get It Back in Working Order</u></a></li>
<li><a href="https://technical-tips.techidaily.com/master-healthy-eating-with-these-6-recommended-diet-tracking-mobile-apps/"><u>Master Healthy Eating with These 6 Recommended Diet Tracking Mobile Apps</u></a></li>
<li><a href="https://technical-tips.techidaily.com/nintendo-switch-online-outage-server-issues-or-connection-woes/"><u>Nintendo Switch Online Outage: Server Issues or Connection Woes?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/quick-installation-tutorial-for-microsoft-office-365-apps-on-pc/"><u>Quick Installation Tutorial for Microsoft Office 365 Apps on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-the-explorer-view-for-better-management/"><u>Resetting the Explorer View for Better Management</u></a></li>
<li><a href="https://technical-tips.techidaily.com/roblox-server-status-checking-if-the-game-is-down-or-your-connection-is-weak/"><u>Roblox Server Status: Checking if the Game Is Down or Your Connection Is Weak</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722878440012-rumored-apple-ring-info-leaked-insights-into-price-points-release-schedule-and-features-awaiting-confirmation/"><u>Rumored Apple Ring Info Leaked: Insights Into Price Points, Release Schedule & Features Awaiting Confirmation</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solutions-to-resolve-mfc71dll-file-cannot-be-found-issues/"><u>Solutions to Resolve 'MFC71.DLL File Cannot Be Found' Issues</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-clearing-your-macs-dns-cache/"><u>Step-by-Step Guide: Clearing Your Mac's DNS Cache</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-linking-your-nintendo-switch-console-with-your-television/"><u>Step-by-Step Guide: Linking Your Nintendo Switch Console with Your Television</u></a></li>
<li><a href="https://technical-tips.techidaily.com/streamline-your-studies-discover-the-9-indispensable-technology-essentials-for-learners/"><u>Streamline Your Studies: Discover the 9 Indispensable Technology Essentials for Learners</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/streamlining-skype-calls-with-advanced-zoom-use/"><u>Streamlining Skype Calls with Advanced Zoom Use</u></a></li>
<li><a href="https://technical-tips.techidaily.com/tech-guide-keep-your-macbook-awake-even-with-closed-lid-step-by-step/"><u>Tech Guide: Keep Your MacBook Awake Even with Closed Lid – Step-by-Step</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-selection-of-8-leading-edtech-apps/"><u>The Ultimate Selection of 8 Leading EdTech Apps</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722842901524-troubleshooting-missing-rockaldlldll-errors-in-your-system-expert-advice/"><u>Troubleshooting Missing rockaldll.dll Errors in Your System – Expert Advice</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-the-absent-dbghelpdll-error-in-your-system/"><u>Troubleshooting the Absent Dbghelp.dll Error in Your System</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-tips-for-finding-or-fixing-mfc7edll-errors/"><u>Troubleshooting Tips for Finding or Fixing Mfc7e.dll Errors</u></a></li>
<li><a href="https://technical-tips.techidaily.com/understanding-lg-channels-key-information-explained-simply/"><u>Understanding LG Channels: Key Information Explained Simply</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unlocking-success-dominating-apple-tv-with-higher-rankings-and-viewers/"><u>Unlocking Success: Dominating Apple TV with Higher Rankings and Viewers</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unlocking-tutorial-removing-a-pin-from-windows-10-login-screen/"><u>Unlocking Tutorial: Removing a PIN From Windows 10 Login Screen</u></a></li>
<li><a href="https://common-error.techidaily.com/1723203161909-unstuck-the-infinite-waiting-screen-of-valorant-with-proven-fixes/"><u>Unstuck the Infinite Waiting Screen of Valorant with Proven Fixes.</u></a></li>
<li><a href="https://technical-tips.techidaily.com/untangling-dll-dilemmas-effective-solutions-for-handling-msvcr70dll-disappearance-errors/"><u>Untangling DLL Dilemmas: Effective Solutions for Handling MSVCR70.DLL Disappearance Errors</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-power-of-familiarity-top-7-reasons-why-you-love-win10/"><u>Unveiling the Power of Familiarity: Top 7 Reasons Why You Love Win10</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-fcp-x-visual-effects-how-to-create-seamless-green-screen-composites/"><u>Updated 2024 Approved FCP X Visual Effects How to Create Seamless Green Screen Composites</u></a></li>
</ul></div>
