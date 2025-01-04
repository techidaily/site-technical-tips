---
title: Enhance Privacy on Your Apple Vision Pro with a Simple VPN Setup - Tips & Reasons to Protect Your Data
date: 2024-12-28T16:37:03.282Z
updated: 2025-01-04T16:44:23.843Z
tags:
  - apple
categories:
  - tech
thumbnail: https://www.zdnet.com/topic/apple/    https://www.zdnet.com/a/img/resize/cc760d300982612be42c1e17c83da22cae881416/2024/04/10/9ee80fb4-2e8f-4c92-adec-d8aceb66329a/speed-app.png?width=170&height=96&fit=crop&format=pjpg&auto=webp
---

## Secure Your Apple Vision Pro with a VPN: Installation Tutorials & Advantages Explained

![cover](https://www.zdnet.com/a/img/resize/2ae9bf524b9cea7e2db4f65c459804299201cd16/2024/04/10/5f3e713a-ccdc-4a7d-a2a1-b36b8f212cc8/cover.jpg?auto=webp&width=1280)

David Gewirtz/ZDNET

One of the killer apps for Apple's Vision Pro headset is using it while traveling, which also happens to be when you most want to use a VPN. I discussed this in a [previous article](https://www.zdnet.com/article/why-youll-need-a-vpn-for-the-vision-pro-and-other-xr-headsets/) \-- before I had access to a Vision Pro -- and did manage to dig around in the emulator and find a setting for VPNs, which boded well for eventual VPN capabilities.

**Also: [Itching to try Vision Pro's Travel Mode? Here's what to expect before you go](https://www.zdnet.com/article/itching-to-try-vision-pros-travel-mode-heres-what-to-expect-before-you-go/)**

Now that I have a headset, I'm happy to report that, yes, installing a VPN on the Vision Pro does work. In this article, I'll take you step by step through installing and configuring a VPN that runs entirely on the Vision Pro device.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

##  Before we begin

Two things are worth noting before we dig in. 

First: The VPN service I'm using is Proton VPN, which I [reviewed last year](https://www.zdnet.com/article/proton-vpn-review/). This article is _not_ a review of Proton VPN. It's an exploration of what's involved in setting up a VPN on the Vision Pro. Of the VPNs available to set up with Apple's headset, Proton was the one with which I was most familiar. So I reached out to their team for a test account.

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

Second: I need to acknowledge and explain the generally low quality of the screenshots. As I discussed in [my article about how to take Vision Pro screenshots](https://www.zdnet.com/article/apple-vision-pro-tricks-how-to-take-perfect-screenshots-and-recordings-and-avoid-weirdness/), the system only provides focused pixels on the small area your eyes are looking at and only takes 1920x1080 pixel images. 

As such, many of the screenshots below are less than stellar. In instances where I wanted you to see a small section of a particular screenshot, I zoomed in tight in Photoshop and used that to illustrate the process. 

Because the screenshot only captures a very small portion of the screen where eyes are focused, I had to take 72 images on the Vision Pro, including many shots of the same screen, in the hopes of getting one that was good enough. I wound up using 21\. Each screenshot in this article has a little expando-square in the upper-right corner. You'll probably want to hit that for most of these screenshots to be able to see the details.

**Also: [Apple Vision Pro tricks: How to take perfect screenshots and recordings (and avoid weirdness)](https://www.zdnet.com/article/apple-vision-pro-tricks-how-to-take-perfect-screenshots-and-recordings-and-avoid-weirdness/)**

I do not care for the Vision Pro's implementation of screenshots. If Apple wants us to tell you folks about how their new invention works, they _really_ need to improve how this is done and let us grab full-frame, full-resolution screenshots. 

With that observation out of the way, let's get started. 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Installing the apps

I'm going to install two apps: Proton's VPN and [Speed Test by Ookla](https://apps.apple.com/us/app/speedtest-by-ookla/id300704847). These are not native Vision Pro apps, but Apple allows developers to designate some of their iPad and iPhone apps as suitable for the Vision Pro. 

**Also: [Why you'll need a VPN for the Vision Pro (and other XR headsets)](https://www.zdnet.com/article/why-youll-need-a-vpn-for-the-vision-pro-and-other-xr-headsets/)**

When you open the App Store on the Vision Pro and do a search, you have the option of looking for VisionOS apps or iPad and iPhone apps. To get both of these apps, I told it to search the available iPad and iPhone apps. 

The speed test is the easiest way to see and prove the VPN is in operation. So that's what I installed first. 

I launched the App Store on the Vision Pro itself and searched for "speed test". 

This says "Open" instead of "Get" because I had already installed it on the Vision Pro in the past, but wanted to show you how it looks in the App Store for this article.

Screenshot by David Gewirtz/ZDNET

Next, I looked for the [Proton VPN app](https://apps.apple.com/us/app/proton-vpn-fast-secure/id1437005085) on the traditional apps side of the Vision Pro app store. Notice that it mentions in-app purchases. I didn't have to deal with this, because I'd already set up my account on my Mac. 

Screenshot by David Gewirtz/ZDNET

Once I hit Get, I had to give the App Store my password (which is not entirely enjoyable without a keyboard on the Vision Pro). I was then presented with a confirmation dialog. I pressed Install. 

Screenshot by David Gewirtz/ZDNET

I was then given one more opportunity to confirm the install by pressing the larger button at the top of the headset. 

Screenshot by David Gewirtz/ZDNET

##  Launching the apps

The Vision Pro has two separate structures for apps. Vision Pro native apps are displayed in the main app launcher. But non-native apps, those built for iPads and iPhones, are stored in their own Compatible Apps folder. 

Screenshot by David Gewirtz/ZDNET

The Proton VPN app is on the first page of the folder. 

The two blurred-out apps are icons for apps from developers who are still working on their projects and don't yet want them to be made public.

Screenshot by David Gewirtz/ZDNET

The Speed Test app was installed on the next page of the Compatible Apps folder. 

Screenshot by David Gewirtz/ZDNET

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6nvb0775GOM?si=peBB_Mo_4zcZFuci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Running a local speed test

Once the two apps were installed, but before the VPN was enabled, I ran a local speed test. I wanted to see a baseline of what we were dealing with. Take a look at the following composite screenshot. There's a lot going on here. I overlayed measurements taken on my iPhone on the left side of the screen. 

Screenshot by David Gewirtz/ZDNET

The area marked (1) indicates the download and upload speed of the Vision Pro. The area marked (2) indicates the download and upload speed of the iPhone. The iPhone was a lot faster. These measurements tell you how long it will take to move a block of data like a file. 

The area marked (3) indicates the ping speeds for the Vision Pro, while the area marked (4) indicates the same thing on the iPhone. Ping speeds tell you how long it takes for a packet to go out and back to the network. You want low ping speeds if you're playing a fast game, because you want your target to still be in the same place by the time the network gets your data. 

**Also: [The best VPN services of 2024: Expert tested](https://www.zdnet.com/article/best-vpn/)**

Keep in mind that all of this is before the VPN had been activated or configured into the network stack of the Vision Pro. I was really quite surprised at how much better my four-year-old iPhone was compared to the brand-new $3,500 Vision Pro. 

And, just in case you're curious, here's what my desktop Mac Studio connected via Ethernet scored. It's a lot faster than Wi-Fi, regardless of which device you're measuring against. 

Screenshot by David Gewirtz/ZDNET

Before we move on to installing and testing the VPN, note that Speed Test correctly identified my location as the Pacific Northwest. I'm in Oregon. 

Screenshot by David Gewirtz/ZDNET

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Installing the VPN

To get started, I went to the Compatible Apps folder and launched Proton VPN. It gave me the option to create an account or log in. 

Screenshot by David Gewirtz/ZDNET

I had previously prepared my account, so I signed in. 

Screenshot by David Gewirtz/ZDNET

Rather than deal with the dreaded floating keyboard, I used the Apple ecosystem's Universal Clipboard feature. I copied the Proton VPN username and password on my Mac, and pasted it on the Vision Pro. (Hint: Hold your thumb and forefinger together to paste.)

**Also: [How to select, copy, and paste on the Apple Vision Pro with hand gestures](https://www.zdnet.com/article/how-to-select-copy-and-paste-on-the-apple-vision-pro-with-hand-gestures/)**

The Proton VPN app gave me the opportunity to save the login information into the iCloud Keychain, which I did. 

Screenshot by David Gewirtz/ZDNET

The first thing I did was hit the Quick Connect button in Proton VPN. Unfortunately, you can't see it in the screenshot all that well because I struggle to get the Vision Pro to focus on items near the bottom of the screen. I'm still exploring why that is; it could have something to do with the shape of my eyes. 

Screenshot by David Gewirtz/ZDNET

As soon as I did that, the Vision Pro dropped out of the virtual environment and put me in passthrough mode, giving me this dialog: 

Yep, that's my Roku TV behind there.

Screenshot by David Gewirtz/ZDNET

This is the meat of the VPN. This is when Proton VPN is actually asking to hook into the Vision Pro's VPN subsystem. It's also showing in Settings, where the VPN is installed and enabled. 

Screenshot by David Gewirtz/ZDNET

You can control whether the VPN activates on demand, or only when you enable it by clicking the Info button. You can also uninstall the VPN using the same interface. 

Screenshot by David Gewirtz/ZDNET

And there you go. There's now a VPN on the Vision Pro. I've been testing using Proton VPN, but because these interfaces are part of VisionOS, it's fair to assume that any VPN app you use, if written properly, should install onto the Vision Pro in roughly the same way. 

**Also: [The best VPNs for iPhone and iPad: Expert tested](https://www.zdnet.com/article/best-iphone-vpn/)**

Next, let's check it out and see if it works.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Testing the VPN

I'm on the West Coast of the United States, so it makes sense that Quick Connect dropped me into Los Angeles. 

Screenshot by David Gewirtz/ZDNET

When looking at the Speed Test results (it's difficult to see because of how the screenshots blur) and with a bit of resizing and Photoshop magic, you can see where the map says "City of Los Angeles," proving that Speed Test thinks the device being used is in LA, which confirms the VPN is running. 

Screenshot by David Gewirtz/ZDNET

The speed results themselves aren't breathtaking, but they're reasonable. The VPN did cost the network some performance, but at least with these tests, there's still more than enough bandwidth for video streaming. 

**Also: [What is a VPN and why do you need one? All your virtual private network questions answered](https://www.zdnet.com/article/what-is-a-vpn-and-why-do-you-need-one-all-your-virtual-private-network-questions-answered/)**

I did one more test, connecting to London. In Proton VPN, I searched for and found a London-based server. 

Screenshot by David Gewirtz/ZDNET

From there, I established a London connection. 

Screenshot by David Gewirtz/ZDNET

Interestingly, the performance connecting from Oregon to London was better than the connection from Oregon to LA, but not by much. 

Screenshot by David Gewirtz/ZDNET

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What does it all mean?

One of the more interesting observations comes from this screenshot, showing which machine Speed Test thinks is running its app. 

Screenshot by David Gewirtz/ZDNET

Notice? Speed Test thinks the Apple Vision Pro is an 11-inch 3rd-generation iPad Pro, a tablet sold by Apple from May 2021 through October 2022\. Apps that don't yet know about the Vision Pro as a device seem to see the headset as an iPad. This is why we can run many existing iPad apps, unchanged, on the Vision Pro. 

In any case, the bottom line is that a VPN does, indeed, work on the Vision Pro. Proton VPN works well enough now, and will probably improve once the company optimizes it for the new hardware. 

**Also: [Proton VPN review: A very solid VPN with robust leak protection](https://www.zdnet.com/article/proton-vpn-review/)**

The door is definitely open for VPN use on the Vision Pro. For those using it while traveling, this is a very important capability indeed. 

Do you plan on traveling with your Vision Pro? Have you tried to use a VPN with it yet? Does this article help ease your concerns about being able to protect your data when traveling with a Vision Pro? Let us know in the comments below. 

---

_You can follow my day-to-day project updates on social media. Be sure to subscribe to [my weekly update newsletter](https://advancedgeekery.substack.com/), and follow me on Twitter/X at [@DavidGewirtz](https://twitter.com/davidgewirtz), on Facebook at [Facebook.com/DavidGewirtz](https://www.facebook.com/davidgewirtz), on Instagram at [Instagram.com/DavidGewirtz](https://www.instagram.com/DavidGewirtz/), and on YouTube at [YouTube.com/DavidGewirtzTV](https://www.youtube.com/user/DavidGewirtzTV)._

#### AR + VR

[I replaced my boring workouts with Meta Quest's Supernatural app, and can't imagine going back](https://www.zdnet.com/article/supernatural-on-meta-quest-hands-on/ "I replaced my boring workouts with Meta Quest's Supernatural app, and can't imagine going back")

[This Finnish startup's new VR headset rivals Apple's Vision Pro - and business users will love it](https://www.zdnet.com/article/this-finnish-startups-new-vr-headset-rivals-apples-vision-pro-and-business-users-will-love-it/ "This Finnish startup's new VR headset rivals Apple's Vision Pro - and business users will love it")

[Meta's $500 Quest 3 is the mainstream VR headset I've been waiting for, and it delivers](https://www.zdnet.com/article/meta-quest-3-review/ "Meta's $500 Quest 3 is the mainstream VR headset I've been waiting for, and it delivers")

[I tried Apple Vision Pro and it's far ahead of where I expected](https://www.zdnet.com/article/i-tried-apple-vision-pro-and-its-far-ahead-of-where-i-expected/ "I tried Apple Vision Pro and it's far ahead of where I expected")

[The best VR headsets right now (and they're not just from Meta)](https://www.zdnet.com/article/best-vr-headset/ "The best VR headsets right now (and they're not just from Meta)")

* [I replaced my boring workouts with Meta Quest's Supernatural app, and can't imagine going back](https://www.zdnet.com/article/supernatural-on-meta-quest-hands-on/ "I replaced my boring workouts with Meta Quest's Supernatural app, and can't imagine going back")
* [This Finnish startup's new VR headset rivals Apple's Vision Pro - and business users will love it](https://www.zdnet.com/article/this-finnish-startups-new-vr-headset-rivals-apples-vision-pro-and-business-users-will-love-it/ "This Finnish startup's new VR headset rivals Apple's Vision Pro - and business users will love it")
* [Meta's $500 Quest 3 is the mainstream VR headset I've been waiting for, and it delivers](https://www.zdnet.com/article/meta-quest-3-review/ "Meta's $500 Quest 3 is the mainstream VR headset I've been waiting for, and it delivers")
* [I tried Apple Vision Pro and it's far ahead of where I expected](https://www.zdnet.com/article/i-tried-apple-vision-pro-and-its-far-ahead-of-where-i-expected/ "I tried Apple Vision Pro and it's far ahead of where I expected")
* [The best VR headsets right now (and they're not just from Meta)](https://www.zdnet.com/article/best-vr-headset/ "The best VR headsets right now (and they're not just from Meta)")

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
<li><a href="https://some-techniques.techidaily.com/new-ideal-ringtones-picks-high-quality-destinations/"><u>[New] Ideal Ringtones Picks High-Quality Destinations</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-first-timers-guide-to-zoom-segregation-rooms/"><u>[Updated] 2024 Approved First-Timer's Guide to Zoom Segregation Rooms</u></a></li>
<li><a href="https://technical-tips.techidaily.com/automattics-strategic-move-taking-over-beeper-with-future-messaging-innovations-insights-from-zdnet/"><u>Automattic's Strategic Move: Taking Over Beeper with Future Messaging Innovations - Insights From ZDNet</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-honor-90-pro-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Honor 90 Pro Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/comprehensive-list-of-apple-watch-compatible-with-watchos-11-updates-and-exclusions/"><u>Comprehensive List of Apple Watch Compatible with WatchOS 11 – Updates and Exclusions</u></a></li>
<li><a href="https://technical-tips.techidaily.com/confirmation-received-how-to-check-if-your-text-has-been-read/"><u>Confirmation Received? How to Check if Your Text Has Been Read</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-xiaomi-redmi-note-12-4g-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Xiaomi Redmi Note 12 4G in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/efficiently-deleting-cache-from-your-android-smartphone-or-tablet/"><u>Efficiently Deleting Cache From Your Android Smartphone or Tablet</u></a></li>
<li><a href="https://technical-tips.techidaily.com/get-ahead-of-the-curve-with-rumored-insights-into-new-android-16-features-costs-and-launch-date-surprises/"><u>Get Ahead of the Curve with Rumored Insights Into New Android 16 Features, Costs and Launch Date Surprises</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-3-ways-to-fake-gps-without-root-on-vivo-y100a-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Fake GPS Without Root On Vivo Y100A | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-vivo-x100-to-mac-drfone-by-drfone-android/"><u>In 2024, How to Mirror Vivo X100 to Mac? | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-no-fuss-guide-to-recording-virtual-classes-on-windowsmacos/"><u>In 2024, No-Fuss Guide to Recording Virtual Classes on Windows/macOS</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-optimal-activities-coexisting-with-listening-podcasts/"><u>In 2024, Optimal Activities Coexisting with Listening Podcasts</u></a></li>
<li><a href="https://technical-tips.techidaily.com/maximizing-savings-on-apples-ipad-pro-before-prime-day-why-this-is-a-smart-move-according-to-zdnet-experts/"><u>Maximizing Savings on Apple's iPad Pro Before Prime Day – Why This Is a Smart Move, According to ZDNet Experts</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigating-impulse-purchases-on-prime-day-how-the-allure-of-affordable-apple-earpods-with-usb-c-led-to-my-spontaneous-acquisition-insights-from-zdnet/"><u>Navigating Impulse Purchases on Prime Day: How the Allure of Affordable Apple EarPods with USB-C Led to My Spontaneous Acquisition | Insights From ZDNET</u></a></li>
<li><a href="https://technical-tips.techidaily.com/protecting-against-mercenary-malware-what-apples-latest-warning-means-for-iphone-owners-zdnet-insights/"><u>Protecting Against Mercenary Malware: What Apple's Latest Warning Means for iPhone Owners | ZDNET Insights</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/rethink-your-youtube-videos-with-these-non-youtube-edits-for-2024/"><u>Rethink Your YouTube Videos with These Non-Youtube Edits for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unleash-potential-discovering-free-onlineoffline-animations/"><u>Unleash Potential Discovering Free Online/Offline Animations</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unlocking-simplicity-and-style-the-ultimate-smart-lock-app-for-your-iphone-beyond-the-ordinary-look/"><u>Unlocking Simplicity & Style: The Ultimate Smart Lock App for Your iPhone, Beyond the Ordinary Look</u></a></li>
</ul></div>

