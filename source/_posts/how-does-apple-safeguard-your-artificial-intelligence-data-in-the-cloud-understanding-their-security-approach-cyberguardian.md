---
title: How Does Apple Safeguard Your Artificial Intelligence Data in the Cloud? Understanding Their Security Approach | CyberGuardian
date: 2024-09-26T03:45:50.823Z
updated: 2024-10-02T04:02:15.814Z
tags:
  - apple
categories:
  - tech
thumbnail: https://www.zdnet.com/topic/apple/    https://www.zdnet.com/a/img/resize/558d488df9aecc96023a99260f424024eaba4ac1/2023/09/12/cd73fe16-07f4-41f0-baf2-1937f9131fec/mac-pro-apple-store.jpg?width=170&height=96&fit=crop&auto=webp
---

## To Buy or Not to Buy the iPhone 16: Evaluating Apple’s Artificial Intelligence Tech | Perspectives

![iPhone 15 Pro surrounded by other phones](https://www.zdnet.com/a/img/resize/4600c96a1f15564c700a1496407215dd662fa474/2024/04/09/0a0be5c9-bdeb-4ab8-a8b5-56af04e0ee93/iphone-15-pro-with-android-phones-in-the-background.jpg?auto=webp&precrop=3317,1864,x259,y259&width=1280)

Prakhar Khanna/ZDNET

In a recent ZDNET article, my friend and colleague David Gewirtz explained why he considers the [upcoming iPhone 16](https://www.zdnet.com/article/apple-confirms-iphone-16-event-date-and-its-glowtime-according-to-the-company/), with its focus on iOS 18 and Apple Intelligence, [an essential upgrade](https://www.zdnet.com/article/6-reasons-why-ios-18-makes-the-iphone-16-a-must-upgrade-for-me/). While I value David's perspective, I have a different take.

**Also: [The iOS 18 public beta is available for iPhone right now. How to download it](https://www.zdnet.com/article/the-ios-18-public-beta-is-available-for-iphone-right-now-heres-how-to-download-it-and-which-models-support-it/)**

David argues that the incorporation of [artificial intelligence](https://www.zdnet.com/article/what-is-ai-heres-everything-you-need-to-know-about-artificial-intelligence/) (AI) in [iOS 18](https://www.zdnet.com/article/the-best-ios-18-features-that-will-make-updating-your-iphone-worthwhile/) makes the iPhone 16 a necessary upgrade, emphasizing the potential of [Apple Intelligence](https://www.zdnet.com/article/what-is-apple-intelligence-everything-to-know-about-ai-features-coming-to-iphones-macs-and-ipads/) to revolutionize our interaction with devices. While I agree that Apple Intelligence has long-term potential, I'm not convinced that its first iteration will deliver the game-changing usability that many anticipate.

If anything, the latest iOS 18.1 betas with Apple Intelligence features have been underwhelming at best.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## The annual upgrade ritual

Every year, my wife and I eagerly await the release of the new iPhones. Being part of [Apple's Upgrade Program](https://apple.sjv.io/c/159047/435031/7613?&sharedid=zdnet&partnerpropertyid=1980086&u=https%3A%2F%2Fwww.apple.com%2Fshop%2Fiphone%2Fiphone-upgrade-program&subId1=zd-%5F%5FCOM%5FCLICK%5FID%5F%5F-dtp), we return our devices, reset our loan with Citizens Bank, and acquire the latest model. Over the past few years, I have opted for the [Pro Max](https://apple.sjv.io/c/159047/435031/7613?&sharedid=zdnet&partnerpropertyid=1980086&u=https%3A%2F%2Fwww.apple.com%2Fiphone-15-pro%2F&subId1=zd-%5F%5FCOM%5FCLICK%5FID%5F%5F-dtp), and my wife has chosen the [base model](https://apple.sjv.io/c/159047/435031/7613?&sharedid=zdnet&partnerpropertyid=1980086&u=https%3A%2F%2Fwww.apple.com%2Fiphone-15%2F&subId1=zd-%5F%5FCOM%5FCLICK%5FID%5F%5F-dtp). The expected annual improvements have been incremental but appreciated. 

Despite the buzz around the [iPhone 16's new features](https://www.zdnet.com/article/im-an-android-user-but-these-three-iphone-16-features-would-win-me-over/) and the integration of Apple Intelligence, however, several concerns dampen my enthusiasm for upgrading this year.

## Apple Intelligence: A significant, yet incomplete, leap forward

Apple Intelligence represents a significant leap in on-device AI capabilities, directly bringing advanced machine learning and natural language processing to our phones. Unlike typical iOS or MacOS feature upgrades, Apple Intelligence loads a downsized version of Apple's Foundation Models, [a home-grown large language model (LLM)](https://www.zdnet.com/article/apple-claims-its-on-device-ai-system-realm-substantially-outperforms-gpt-4/) with approximately 3 billion parameters. While impressive, this is tiny compared to models like [GPT-3.5 and GPT-4](https://www.zdnet.com/article/what-does-gpt-stand-for-understanding-gpt-3-5-gpt-4-and-more/), which boast hundreds of billions of parameters. Even Meta's open source Llama 3, which you can run on a desktop computer, has 8 billion parameters. 

**Also: [I broke Meta's Llama 3.1 405B with one question (which GPT-4o gets right)](https://www.zdnet.com/article/i-broke-metas-llama-3-1-405b-with-one-question-which-gpt-4o-gets-right/)**

The [iOS 18.1 Developer Beta](https://www.zdnet.com/article/apple-intelligence-arrives-in-ios-18-1-developer-beta-heres-whats-new-for-iphone/), released at the end of July, introduced the first Apple Intelligence features, but they've been modest so far. These include Writing Tools, which allow users to rewrite emails, texts, or letters in different tones, proofread content, and summarize or format it with tables or bullet points. Another feature provides webpage, email, or text summaries -- a time-saver that cuts straight to the content. Users can also ask the Photo app to search for specific images, such as those showing someone holding a phone.

However, the integration of Apple Intelligence is not without challenges. The model, when running, may occupy between 750MB and 2GB of RAM, depending on how effective Apple's memory compression technology is. This substantial allocation of memory to a core OS function that won't always be used means that parts must be dynamically loaded in and out of memory as required, introducing new system constraints and potentially putting additional stress on the CPU.

**Also:** [**How to run dozens of AI models on your Mac or PC - no third-party cloud needed**](https://www.zdnet.com/article/how-to-run-dozens-of-ai-models-on-your-mac-or-pc-no-third-party-cloud-needed/)

More advanced AI features, such as [Genmoji](https://www.zdnet.com/article/apples-new-ai-generated-genmoji-solve-a-problem-weve-all-had-before/) for creating custom emoji, the [Image Playground](https://www.zdnet.com/article/forget-dall-e-apples-new-ai-image-generator-runs-on-device-and-works-like-magic/) for on-device image creation, and ChatGPT integration, have yet to be included in the beta. Siri has received a minor UI update and a more conversational tone, but significant improvements are expected later this year. [According to Bloomberg's Mark Gurman](https://www.bloomberg.com/news/newsletters/2024-07-07/apple-watch-series-10-ultra-3-details-bigger-screens-blood-pressure-challenge-lybjqp0q), additional Apple Intelligence features will be introduced in upcoming iOS 18.1 Beta releases, with the stable version possibly arriving in October.

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

<!-- affiliate ads begin -->
<span id="1743243">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1743243.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19272-1743243">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1743243.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Faligracehair.sjv.io%2Fc%2F5597632%2F1743243%2F19272'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1743243/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## New hardware leaks: what to expect from the iPhone 16

Earlier, I discussed how older -- as well as current generation -- iOS devices [aren't powerful enough to handle on-device Generative AI tasks](https://www.zdnet.com/article/the-expensive-reason-why-apples-upcoming-ai-features-arent-coming-to-your-older-iphone/). The [base iPhone 15](https://www.zdnet.com/article/iphone-15-plus-review/), which has only 6GB of RAM, would struggle to meet the demands of Apple Intelligence as it evolves and becomes more integrated into iOS, core Apple applications, and developer applications. Older iPhones have [6GB of RAM or less](https://iosref.com/ram-processor), and are not eligible to run Apple Intelligence in current iOS 18.1 builds. 

Due to their 8GB of onboard RAM, only the iPhone 15 Pro and the iPhone 15 Pro Max can run Apple Intelligence, and it is strictly a beta feature that can be enabled or disabled at user preference within Settings.

**Also: [iOS 18.1 update: Every iPhone model that will support Apple's new AI features (for now)](https://www.zdnet.com/article/ios-18-1-update-every-iphone-model-that-will-support-apples-new-ai-features-for-now/)**

Recent leaks have [spilled the specifications](https://www.tomsguide.com/phones/iphones/iphone-16-leak-just-spilled-the-specs-and-prices-on-all-four-models) of the iPhone 16 lineup, providing a clearer picture of what to expect. The base iPhone 16 is expected to feature the A18 processor with 8GB of RAM, while the iPhone 16 Pro models might sport the A18 Pro with up to 12GB of RAM, although [recent rumors indicate this may be rolled out for iPhone 17 instead](https://www.macrumors.com/2024/08/28/iphone-17-feature-12gb-ram-up-from-8gb/). This increase in memory is crucial, considering the demanding nature of Apple Intelligence features. However, whether it will fully address performance concerns remains to be seen.

Interestingly, despite these hardware upgrades, Apple appears to be keeping prices similar to those of the iPhone 15 series, with the base iPhone 16 starting at $799\. The iPhone 16 Pro, however, is rumored to start at $1,099, a $100 increase from its predecessor, likely due to the additional storage and upgraded components. The Pro models are also expected to introduce Wi-Fi 7 connectivity, a new telephoto lens, and larger screens -- 6.3 inches for the Pro and 6.9 inches for the Pro Max.

**Also: [Apple Intelligence will improve Siri in 2024, but don't expect most updates until 2025](https://www.zdnet.com/article/apple-intelligence-will-improve-siri-in-2024-but-dont-expect-most-updates-until-2025/)**

Despite these upgrades, the iPhone 16 may still face challenges due to design cycles that didn't fully account for the scope of Apple Intelligence's capabilities. As a result, users may experience suboptimal performance and a less seamless user experience, especially as more AI features roll out in subsequent updates.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997717/19272" target="_top" id="1997717">
  <img src="//a.impactradius-go.com/display-ad/19272-1997717" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997717/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Why you shouldn't buy the iPhone 16 for Apple Intelligence

Besides memory concerns, AI processing demands a lot of power and additional computing resources. Without significant advancements in battery and power management technology, users might have to charge their phones more often. This can lead to increased battery drain, reduced battery lifespan, and potential performance issues. The extra processing power needed to run on-device LLMs could strain the CPU, causing the device to heat up and affecting its overall performance and reliability.

**Also: [How iOS 18 changes the way you charge your iPhone](https://www.zdnet.com/article/how-ios-18-changes-the-way-you-charge-your-iphone/)**

For these reasons, I see the iPhone 16 (and potentially even the iPhone 17) as a transitional product in Apple's journey toward on-device AI. 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134221/18498" target="_top" id="2134221">
  <img src="//a.impactradius-go.com/display-ad/18498-2134221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134221/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How Apple Intelligence will likely evolve

Apple's AI capabilities are expected to improve significantly in the coming years. By 2025, we may see more advanced and dependable integration of Apple Intelligence not only in mobile devices and Macs, but also in products like the Apple Watch, HomePod, Apple TV, and a [consumer-oriented version of the Vision headset](https://www.zdnet.com/article/to-rescue-the-vision-pro-apple-must-do-these-3-things/).

To extend Apple Intelligence to these less powerful devices, as the company is doing with its "Private Cloud Compute" by running [secure Darwin-based servers in their data centers](https://www.zdnet.com/article/apple-is-building-a-high-security-os-to-run-its-ai-data-centers-heres-what-we-know-so-far/) for more advanced LLM processing, Apple might leverage cloud-based resources for these less-powerful systems through fully developed data center capabilities and partnerships with companies like OpenAI or Google.

**Also: [To rescue the Vision Pro, Apple must do these 3 things](https://www.zdnet.com/article/to-rescue-the-vision-pro-apple-must-do-these-3-things/)**

Alternatively, Apple could consider a distributed or "mesh" AI processing system, where idle devices within a household or enterprise can assist less powerful ones with LLM queries.

Apple could achieve this by equipping MacOS, iOS, and iPadOS with Apple Intelligence and the on-device LLM as planned. Subsequent changes could enable all devices to communicate their generative AI capabilities and idle processing state. This would allow them to act as proxies for each other's Apple Intelligence requests. 

Enterprises may also employ a mobile device management solution to facilitate access to on-device LLMs with business Macs. Additionally, iPhones or Macs could be used as proxies for Apple Watch or HomePod requests for mobile users. We may also see a more powerful Apple TV with more onboard memory and processing to act as an Apple Intelligence "hub" for every Apple device in a household.

Imagine your iPhone using the unused processing power of your Mac or iPad, all equipped with on-device LLMs, to tackle complex AI tasks. This would increase the accessibility of AI features across Apple's product range.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036472/19272" target="_top" id="2036472">
  <img src="//a.impactradius-go.com/display-ad/19272-2036472" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036472/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## I'm still optimistic

Despite the hype around Apple Intelligence, there are many other reasons to consider upgrading to the iPhone 16, like improvements in camera quality, display, and overall performance. The iPhone 16 will likely feature better sensors, enhanced computational photography, and superior video capabilities. The display might also see improvements in brightness, color accuracy, and refresh rate, making it a better device for media consumption and gaming. 

**Also: [Apple may be cooking something big with its new Game Mode. Here are 3 things we know](https://www.zdnet.com/article/apple-may-be-cooking-something-big-with-its-new-game-mode-here-are-3-things-we-know/)**

If, however, you're considering the iPhone 16 solely for its AI capabilities -- which are still evolving and unlikely to deliver the expected performance touted in Apple's WWDC 2024 keynote -- you might want to manage your expectations.

_This article was originally published on June 28, 2024, and updated on August 27, 2024\._ 

#### Apple

[Every iPhone model that will be updated to Apple's iOS 18 (and which ones can't)](https://www.zdnet.com/article/every-iphone-model-compatible-with-apples-ios-18-and-which-ones-arent/ "Every iPhone model that will be updated to Apple's iOS 18 (and which ones can't)")

[M3 MacBook Air vs. M2 MacBook Air: Which Apple laptop should you buy?](https://www.zdnet.com/article/m3-macbook-air-vs-m2-macbook-air/ "M3 MacBook Air vs. M2 MacBook Air: Which Apple laptop should you buy?")

[Why you shouldn't buy the iPhone 16 for Apple Intelligence](https://www.zdnet.com/article/why-you-shouldnt-buy-the-iphone-16-for-apple-intelligence/ "Why you shouldn't buy the iPhone 16 for Apple Intelligence")

[I uncovered 8 cool ways to use LiDAR on an iPhone and iPad](https://www.zdnet.com/article/i-uncovered-8-cool-ways-to-use-lidar-on-an-iphone-and-ipad/ "I uncovered 8 cool ways to use LiDAR on an iPhone and iPad")

* [Every iPhone model that will be updated to Apple's iOS 18 (and which ones can't)](https://www.zdnet.com/article/every-iphone-model-compatible-with-apples-ios-18-and-which-ones-arent/ "Every iPhone model that will be updated to Apple's iOS 18 (and which ones can't)")
* [M3 MacBook Air vs. M2 MacBook Air: Which Apple laptop should you buy?](https://www.zdnet.com/article/m3-macbook-air-vs-m2-macbook-air/ "M3 MacBook Air vs. M2 MacBook Air: Which Apple laptop should you buy?")
* [Why you shouldn't buy the iPhone 16 for Apple Intelligence](https://www.zdnet.com/article/why-you-shouldnt-buy-the-iphone-16-for-apple-intelligence/ "Why you shouldn't buy the iPhone 16 for Apple Intelligence")
* [I uncovered 8 cool ways to use LiDAR on an iPhone and iPad](https://www.zdnet.com/article/i-uncovered-8-cool-ways-to-use-lidar-on-an-iphone-and-ipad/ "I uncovered 8 cool ways to use LiDAR on an iPhone and iPad")

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
<li><a href="https://extra-lessons.techidaily.com/ar-merging-physical-and-fictional-worlds-for-2024/"><u>AR Merging Physical and Fictional Worlds for 2024</u></a></li>
<li><a href="https://fox-within.techidaily.com/configuring-app-v-5-essential-guide-to-managing-folder-settings/"><u>Configuring App-V 5: Essential Guide to Managing Folder Settings</u></a></li>
<li><a href="https://facebook.techidaily.com/duplicitous-dms-verify-user-authenticity/"><u>Duplicitous DMs: Verify User Authenticity</u></a></li>
<li><a href="https://technical-tips.techidaily.com/follow-mens-ncaa-tournament-on-the-airwaves-with-comprehensive-coverage-of-march-madness-and-final-four-games/"><u>Follow Men's NCAA Tournament on the Airwaves with Comprehensive Coverage of March Madness and Final Four Games</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-efficiently-upload-and-render-youtube-videos-with-precision/"><u>In 2024, Efficiently Upload and Render YouTube Videos with Precision</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-change-oneplus-nord-ce-3-5g-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change OnePlus Nord CE 3 5G Lock Screen Password?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-movie-magic-adjusting-netflix-speed/"><u>In 2024, Mastering Movie Magic Adjusting Netflix Speed</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-top-rated-flv-editor-for-windows-8-edit-videos-like-a-pro/"><u>New In 2024, Top-Rated FLV Editor for Windows 8 Edit Videos Like a Pro</u></a></li>
<li><a href="https://location-social.techidaily.com/simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-realme-gt-3-drfone-by-drfone-virtual-android/"><u>Simple and Effective Ways to Change Your Country on YouTube App Of your Realme GT 3 | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-basics-of-bass-management-technology-explained/"><u>The Basics of Bass Management Technology Explained</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-foremost-8-mobile-game-experiences-for-gamers-on-the-go/"><u>The Foremost 8 Mobile Game Experiences for Gamers On-the-Go</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-importance-of-b-roll-diversity-in-filmmaking-for-2024/"><u>The Importance of B-Roll Diversity in Filmmaking for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-guide-to-parent-friendly-online-protection-top-8-apps-and-services/"><u>The Ultimate Guide to Parent-Friendly Online Protection: Top 8 Apps and Services</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-tips-when-you-cant-find-dnscryptdll-on-your-computer/"><u>Troubleshooting Tips When You Can't Find DNSCrypt.dll on Your Computer</u></a></li>
</ul></div>

