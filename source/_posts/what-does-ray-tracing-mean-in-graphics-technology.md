---
title: What Does Ray Tracing Mean in Graphics Technology?
date: 2024-08-18T20:53:42.453Z
updated: 2024-08-19T20:53:42.453Z
categories:
  - BestProducts
description: This Article Describes What Does Ray Tracing Mean in Graphics Technology?
excerpt: This Article Describes What Does Ray Tracing Mean in Graphics Technology?
thumbnail: https://www.lifewire.com/thmb/1-Yp1JIoL4O5iudaQ-YSTZFzypk=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/raytracingstarwars-b548b699b36b4bb8b4334d66a964ede9.jpg
---

## Effortless Typography Tweaks in Windows 11 – Learn How to Change Fonts Easily
### What to Know

* Go to**Settings** \>**Personalization** \>**Fonts** to find the name of the font you want to use throughout Windows 11.
* Then, create a REG file using that name to replace the current system font. Open the REG file to change the font.
* Not all Windows fonts will change, but some do. It's easy to restore the default font if you change your mind.

 This article teaches you how to change the Windows 11 system font so that various areas of the OS will use the font type you prefer. It also covers how to undo these steps to restore the default font.

## How to Change the System Font in Windows 11

 The quickest way to change the Windows 11 font is through a Windows Registry edit, which we'll do by creating a[REG file](https://www.lifewire.com/how-to-create-edit-and-use-reg-files-2622817) .

1. Open Settings, then select**Personalization** on the left, followed by**Fonts** on the right. Another way to get there is through the Run command:**ms-settings:fonts** .  
![The Personalization settings in Windows 11](https://www.lifewire.com/thmb/SJdYi81a1Rm29jJ6p7V24JP49ss=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/personalization-settings-windows-11-83afd8d0867d4d39a1b87dff59dd8fae.png)
2. Scroll down to**Available fonts** , and find and select the font you're interested in using.  
 If you don't see the font you want, you can take this time to download it. Lots of websites have free fonts, but you can also[buy fonts online](https://www.lifewire.com/buy-fonts-for-desktop-publishing-1077714) . Then, return to this area of Settings to see it. Our[How to Install Fonts in Windows 11](https://www.lifewire.com/install-fonts-in-windows-11-5192443) guide can help if you need it.
3. Locate the**Full name** line in the**Metadata** section, and write it down exactly as it's written. In our example, we recorded**Franklin Gothic Medium** .  
![Full Name and Franklin Gothic Medium highlighted in Windows 11 font settings](https://www.lifewire.com/thmb/TLWCZLK0sdGg9XBIj1y4Ma1EuAA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/001_how-to-change-the-font-in-windows-11-6827640-97099a55349a45e392459345af24caf1.jpg)
4. Open Notepad, or a[different text editor](https://www.lifewire.com/best-free-text-editors-4155819) if you prefer, and paste the following:  
 `Windows Registry Editor Version 5.00`  
`[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Fonts]`  
`"Segoe UI (TrueType)"=""`  
`"Segoe UI Bold (TrueType)"=""`  
`"Segoe UI Bold Italic (TrueType)"=""`  
`"Segoe UI Italic (TrueType)"=""`  
`"Segoe UI Light (TrueType)"=""`  
`"Segoe UI Semibold (TrueType)"=""`  
`"Segoe UI Symbol (TrueType)"=""`  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\FontSubstitutes]`  
`"Segoe UI"="Franklin Gothic Medium"`
5. In the last line of the document, replace**Franklin Gothic Medium** with the name of the font you recorded in Step 3 (keep the quotes around the name).  
![Franklin Gothic Medium highlighted in Windows Notepad with REG file contents](https://www.lifewire.com/thmb/5UM6sKcUZ5_xlc9vkHeFpUtlwpk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/002_how-to-change-the-font-in-windows-11-6827640-babf346069c14d8caa00e4c43d7992b6.jpg)
6. If you're using Notepad, go to**File** \>**Save as** , and type a name in the**File name** box.
7. Choose**All files** from the**Save as type** menu.
8. Type**.reg** at the end of the file name. Our example reads**Franklin Gothic.reg** , but yours can be called whatever you want; just make sure it ends with that file extension.
9. Choose a folder on your computer to save the file (the Desktop folder works), and then select**Save** .  
![FranklinGothic.reg and Save highlighted in a Notepad document with REG file extension](https://www.lifewire.com/thmb/4p0dmSoOCDSVSqxK6o9QnPtNX1U=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/003_how-to-change-the-font-in-windows-11-6827640-9563197f19ae4d848482def07b741adc.jpg)
10. Close the text editor, and then double-click or double-tap the REG file from the folder you just saved it to.
11. Press**Yes** on the User Account Control window, then**Yes** again on the Registry Editor prompt (pictured below), and finally**OK** on the success message.  
![Yes highlighted in the Registry Editor prompt in Windows 11](https://www.lifewire.com/thmb/tViUCj2SD1eHRKNxSY2gP3-IusQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/004_how-to-change-the-font-in-windows-11-6827640-acbf618a85854ff58bb4ca6f3a0d7384.jpg)
12. [Reboot your computer](https://www.lifewire.com/how-to-reboot-a-computer-2624568) to see the font changes. The quickest method is to right-click the Start button and go to**Shut down or sign out** \>**Restart** .

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
## What Does Changing the System Font Do?

 Changing the computer font in Windows 11 will switch up the way text looks throughout the operating system. Desktop icon text and the links in Control Panel are a couple of examples, but it's most obvious in other areas, such as the Run dialog box.

![Windows 11 font type change in Run and Control Panel](https://www.lifewire.com/thmb/eN6m7hD9Mgh_sWhJB-Jl9QOeR2c=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/windows-11-changed-font-type-control-panel-run-desktop-365bc4a2e315498f96aa4115713f7d59.png)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
 However, not every part of Windows will change to the new font. All the text within Settings, Start menu, Clock, Quick Settings, and numerous other areas aren't affected.

[Troubleshooting Installed Fonts That Won't Work](https://www.lifewire.com/cant-use-installed-fonts-1074154)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Restore the Default Font in Windows 11

 The best way to get the original Windows 11 font back is to reverse the registry tweak that changed it in the first place. To do that, repeat the steps from above, but replace the Notepad text with different code.

 You can do this one of two ways. This first method is easiest only if you still have the original REG file:

1. Right-click the REG file from wherever you saved it during Step 9, and select**Edit in Notepad** .
2. Highlight all the text that's in there, and replace it with this:  
 `Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Fonts]`  
`"Segoe UI (TrueType)"="segoeui.ttf"`  
`"Segoe UI Black (TrueType)"="seguibl.ttf"`  
`"Segoe UI Black Italic (TrueType)"="seguibli.ttf"`  
`"Segoe UI Bold (TrueType)"="segoeuib.ttf"`  
`"Segoe UI Bold Italic (TrueType)"="segoeuiz.ttf"`  
`"Segoe UI Emoji (TrueType)"="seguiemj.ttf"`  
`"Segoe UI Historic (TrueType)"="seguihis.ttf"`  
`"Segoe UI Italic (TrueType)"="segoeuii.ttf"`  
`"Segoe UI Light (TrueType)"="segoeuil.ttf"`  
`"Segoe UI Light Italic (TrueType)"="seguili.ttf"`  
`"Segoe UI Semibold (TrueType)"="seguisb.ttf"`  
`"Segoe UI Semibold Italic (TrueType)"="seguisbi.ttf"`  
`"Segoe UI Semilight (TrueType)"="segoeuisl.ttf"`  
`"Segoe UI Semilight Italic (TrueType)"="seguisli.ttf"`  
`"Segoe UI Symbol (TrueType)"="seguisym.ttf"`  
`"Segoe MDL2 Assets (TrueType)"="segmdl2.ttf"`  
`"Segoe Print (TrueType)"="segoepr.ttf"`  
`"Segoe Print Bold (TrueType)"="segoeprb.ttf"`  
`"Segoe Script (TrueType)"="segoesc.ttf"`  
`"Segoe Script Bold (TrueType)"="segoescb.ttf"`  
`[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\WindowsNT\CurrentVersion\FontSubstitutes]`  
`"Segoe UI"=-`
3. Save the file.
4. Exit Notepad, and then open the REG file. Accept all the prompts to edit the registry.
5. If the changes don't take effect immediately (they did for us), reboot your computer.

 If you don't have the original REG file readily available to edit, just repeat the steps at the top of this page. When you get to the part about pasting the code into Notepad, use the modified code from Step 2 above, and don't make any changes to it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Changing Other Fonts in Windows 11

 The method outlined in this article isn't how it typically works when you want to use a new font in Windows. The directions explained above are unique for two reasons: Windows doesn't have a built-in way to change the system font, and you're changing the_system_ font, not just the font type for a single app.

 Most programs have their own font settings so you can make changes that apply to just that one program. And doing it is extremely easy because Windows 11_does_ provide a way to easily install a font that can be used by any of your software.

 For example, if you've downloaded a font you'd like to use in Microsoft Word,[install the font to your computer](https://www.lifewire.com/install-fonts-in-windows-11-5192443) , and it'll be available the next time you open Word. That's usually how it works: install the fonts to your computer to give all your programs access to them.

 You can, for instance, change the default font and size in Outlook by choosing an installed font. The same applies when you[pick a new default font for Thunderbird emails](https://www.lifewire.com/change-default-font-thunderbird-1173143) . Online apps need separate instructions since they don't typically access local fonts:[here's how to edit Gmail's default font options](https://www.lifewire.com/change-the-default-compose-font-face-and-color-in-gmail-1171898) in your browser.

 With some programs, there's a special folder in the app's installation directory that's used to load fonts for that one piece of software. This is how you[install fonts just for Photoshop](https://www.lifewire.com/installing-fonts-for-photoshop-only-1702271) .

[How to Manage Your Fonts in Windows](https://www.lifewire.com/too-many-windows-fonts-1077817)

 FAQ

* How do I change the font size on my Windows desktop icons?  
 To change the default text size in Windows 11, go to**Start** \>**Settings** \>**Accessibility** \>**Text size** . Use the slider to adjust the preview text size and select**Apply** .
* What font is used in Windows?  
 The default system font for Windows 11 is called Segoe UI. Pronounced “see-go,” this is the standard font for all Microsoft products.
* How do I change the default font in Microsoft Office?  
 You can[change the default font in Microsoft Office](https://www.lifewire.com/change-default-font-in-microsoft-office-2511891) apps by creating a template. For example, in Microsoft Word, create a new template and go to the**Home** tab, then right-click any style. Select**Modify** , then choose a font under**Formatting** . Make sure**New documents based on this template** is selected, then select**OK** .

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
<li><a href="https://extra-approaches.techidaily.com/new-mastering-the-art-of-editing-with-final-cut-pro/"><u>[New] Mastering the Art of Editing with Final Cut Pro</u></a></li>
<li><a href="https://screen-recording.techidaily.com/1716069094339-updated-2024-approved-next-gen-online-meeting-apps-azoom-no-more/"><u>[Updated] 2024 Approved  Next-Gen Online Meeting Apps  Azoom No More!</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-ps5-ssd-and-hdd-wonders-top-10-exteriors/"><u>[Updated] 2024 Approved  PS5 SSD & HDD Wonders  Top 10 Exteriors</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-small-companys-guide-to-the-safest-online-chat-services/"><u>[Updated] 2024 Approved  Small Company's Guide to the Safest Online Chat Services</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-top-5-efficient-mac-snippers-for-quick-captures/"><u>[Updated] 2024 Approved  Top 5 Efficient Mac Snippers for Quick Captures</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-stabilized-mobile-shooting-with-precision-mounts/"><u>[Updated] Stabilized Mobile Shooting with Precision Mounts</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-the-ultimate-compilation-of-html5s-best-video-tools-for-2024/"><u>[Updated] The Ultimate Compilation of HTML5's Best Video Tools for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-advanced-zoom-practices-for-chromebook-users/"><u>2024 Approved  Advanced Zoom Practices for Chromebook Users</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-the-best-of-the-best-essential-tablet-sketching-tools/"><u>2024 Approved  The Best of the Best  Essential Tablet Sketching Tools</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-winning-gameplay-capture-with-fbx/"><u>2024 Approved  Winning Gameplay Capture with FBX</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/a-beginners-guide-to-using-the-chat-feature-on-mozilla-thunderbird/"><u>A Beginner's Guide to Using the Chat Feature on Mozilla Thunderbird</u></a></li>
<li><a href="https://technical-tips.techidaily.com/blocking-anonymous-incoming-calls-iphone-users-handbook-for-privacy-protection/"><u>Blocking Anonymous Incoming Calls: IPhone User's Handbook for Privacy Protection</u></a></li>
<li><a href="https://technical-tips.techidaily.com/comprehensive-guide-diagnosing-and-repairing-504-network-issues-efficiently/"><u>Comprehensive Guide: Diagnosing and Repairing 504 Network Issues Efficiently</u></a></li>
<li><a href="https://technical-tips.techidaily.com/detailed-tips-for-addressing-missing-d3dx924dll-files-on-your-pc/"><u>Detailed Tips for Addressing Missing d3dx9_24.dll Files on Your PC</u></a></li>
<li><a href="https://technical-tips.techidaily.com/easy-methods-for-taking-screen-shots-on-hp-computers/"><u>Easy Methods for Taking Screen Shots on HP Computers</u></a></li>
<li><a href="https://fox-access.techidaily.com/exclusive-roundup-30-leading-free-vectr-and-illustration-sites-online-for-2024/"><u>Exclusive Roundup  30 Leading Free Vectr and Illustration Sites Online for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-tips-fixing-the-persistent-504-error-on-your-website/"><u>Expert Tips: Fixing the Persistent 504 Error on Your Website</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722873680783-explore-8-fantastic-no-cost-music-apps-on-your-iphone-today/"><u>Explore 8 Fantastic No-Cost Music Apps on Your iPhone Today!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/free-ipados-version-18-launch-details-dates-costs-and-innovative-features/"><u>Free IPadOS Version 18 Launch Details: Dates, Costs & Innovative Features</u></a></li>
<li><a href="https://technical-tips.techidaily.com/guide-prevent-unknown-numbers-from-disturbing-you-on-iphone-devices/"><u>Guide: Prevent Unknown Numbers From Disturbing You on iPhone Devices</u></a></li>
<li><a href="https://technical-tips.techidaily.com/guide-switching-to-another-internet-browser-on-samsung-smarttvs/"><u>Guide: Switching to Another Internet Browser on Samsung SmartTVs</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-it-poco-m6-5g-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix It Poco M6 5G Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-missing-tabs-in-windows-11-file-explorer/"><u>How to Fix Missing Tabs in Windows 11 File Explorer</u></a></li>
<li><a href="https://technical-tips.techidaily.com/immerse-yourself-in-3d-movie-magic-the-best-ways-to-use-fandangos-online-services/"><u>Immerse Yourself in 3D Movie Magic – The Best Ways to Use Fandango's Online Services</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-samsung-galaxy-a54-5g-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Samsung Galaxy A54 5G Location Settings | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-vivo-s18e-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Vivo S18e | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-to-enter-the-ispoofer-discord-server-on-apple-iphone-12-mini-drfone-by-drfone-virtual-ios/"><u>In 2024, How to enter the iSpoofer discord server On Apple iPhone 12 mini | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-your-account-has-been-disabled-in-the-app-store-and-itunes-on-apple-iphone-14-by-drfone-ios/"><u>In 2024, Your Account Has Been Disabled in the App Store and iTunes On Apple iPhone 14?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/inside-look-at-samsung-galaxy-ring-specs-release-timeline-and-more-insights/"><u>Inside Look at Samsung Galaxy Ring: Specs, Release Timeline, and More Insights</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/interactive-steps-towards-fluency-in-spanish/"><u>Interactive Steps Towards Fluency in Spanish</u></a></li>
<li><a href="https://technical-tips.techidaily.com/marchs-ultimate-guide-to-scoring-great-apple-watch-discounts/"><u>March's Ultimate Guide to Scoring Great Apple Watch Discounts</u></a></li>
<li><a href="https://technical-tips.techidaily.com/resolving-missing-python24dll-a-step-by-step-guide/"><u>Resolving 'Missing python24.dll': A Step-by-Step Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-correcting-the-msodlldll-error-message/"><u>Step-by-Step Guide: Correcting the MSODLL.DLL Error Message</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-fixing-haldll-missing-errors-in-windows-xp-operating-system/"><u>Step-by-Step Guide: Fixing Hal.dll Missing Errors in Windows XP Operating System</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-solution-overcoming-the-netflix-error-ui-800-3/"><u>Step-by-Step Solution: Overcoming the Netflix Error (UI-800-3)</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-tutorial-connecting-apple-airpods-with-your-nintendo-switch/"><u>Step-by-Step Tutorial: Connecting Apple AirPods with Your Nintendo Switch</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-9-fantastic-sites-for-free-preschool-learning-fun/"><u>Top 9 Fantastic Sites for Free Preschool Learning Fun</u></a></li>
<li><a href="https://technical-tips.techidaily.com/transforming-your-windows-11-taskbar-a-step-by-step-guide-to-personalizing-its-color/"><u>Transforming Your Windows 11 Taskbar: A Step-by-Step Guide to Personalizing Its Color</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-tips-for-resolving-wii-disc-playback-errors/"><u>Troubleshooting Tips for Resolving Wii Disc Playback Errors</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ultimate-selection-leading-ceiling-audio-units-for-the-year-2024/"><u>Ultimate Selection: Leading Ceiling Audio Units for the Year 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/understanding-and-repairing-the-halinitializationfailed-bug-how-to-deal-with-stop-code-0x0000005c-successfully/"><u>Understanding and Repairing the HAL_INITIALIZATION_FAILED Bug: How to Deal with Stop Code 0X0000005C Successfully</u></a></li>
<li><a href="https://technical-tips.techidaily.com/understanding-chatgpt-an-overview-of-its-functionality/"><u>Understanding ChatGPT: An Overview of Its Functionality</u></a></li>
<li><a href="https://technical-tips.techidaily.com/upcoming-launch-of-google-pixel-tablet-exciting-specs-and-announcement-details-revealed/"><u>Upcoming Launch of Google Pixel Tablet: Exciting Specs & Announcement Details Revealed</u></a></li>
</ul></div>
