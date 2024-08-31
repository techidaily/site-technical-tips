---
title: Understanding LLMs - The Key to Advanced Conversational AI
date: 2024-08-30T13:35:51.773Z
updated: 2024-08-31T13:35:51.773Z
tags:
  - cutting-edge
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/33-2.png
---

## Understanding LLMs - The Key to Advanced Conversational AI

### Key Takeaways

* Large Language Models (LLMs) power AI chatbots like ChatGPT and Google Bard, allowing them to process requests and provide responses.
* LLMs rely on pre-training on vast amounts of data and a set of parameters to determine how they produce text and respond to prompts.
* LLMs, such as AI chatbots, have diverse applications, including providing facts, translating text, generating ideas, and enhancing search engine results.

 While AI chatbots like ChatGPT are now incredibly popular, many of us still don't understand how they work. These chatbots are powered by LLMs, and it's this technology that holds a lot of potential for the future. So, what is an LLM, and how does it allow AI to hold conversations with humans?

##  What Is an LLM?

 The term "LLM" is short for Large Language Model. A large language model provides the framework for AI chatbots like [ChatGPT and Google Bard](https://driver-error.techidaily.com/ethernet-controller-bug-in-win11-realtek-solution/), allowing them to process requests and provide responses.

 The concept of conversational computers was around long before the first example of this technology was put into practice. Back in the 1930s, the idea of a conversational computer arose, but remained entirely theoretical. Decades later, in 1967, the world's first chatbot, ELIZA, was created. Developed by MIT's Joseph Weizenbaum, ELIZA was a text-based program that used a tactic known as "pattern matching" to talk to users, and used a stock of conversational scripts from which it could pull responses.

 The New Jersey Institute of Technology still [provides a web-based version of ELIZA](https://web.njit.edu/~ronkowit/eliza.html) that can be interacted with today.

![Screenshot of ELIZA simulated chatbot conversation on desktop.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/eliza-chat-1.jpg) 

New Jersey Institute of Technology/Joseph Weizenbaum

 As you can see, ELIZA isn't great at interpreting language and providing useful information. But as a 1960s invention, this chatbot was groundbreaking, as it was able to respond to prompts in a relatively human way, while also having the ability to continue a conversation. Above, we told ELIZA that we were sad, and it was able to ask us to tell it more, and question how long we'd been feeling that way.

 While ELIZA was an innovative invention, it wasn't an LLM. In fact, it took another 47 years for a technology close to today's LLMs to be achieved.

 In 2013, an algorithm known as [word2vec](https://www.tensorflow.org/text/tutorials/word2vec) became the LLM's most recent ancestor. Word2vec is a natural language processing (NLP) algorithm used to take one word and convert it into an array of numbers known as a vector. This may seem basic on the surface, but what was amazing about word2vec is that it could create semantic connections between different words after vectorizing them. This ability to create association between words was a huge step towards modern LLMs.

 While many associate OpenAI and its chatbot, ChatGPT, with having fathered LLMs, this isn't the case. The first LLM breakthrough was made by Google in 2017 with its Bidirectional Encoder Representations from Transformers (BERT). BERT was developed in order to improve Google's search engine algorithm, so that user searches can be better interpreted, therefore providing improved search results.

 Prior to BERT's release, several Google researchers wrote and published a paper titled [_Attention Is All You Need_](https://research.google/pubs/attention-is-all-you-need/). This paper set the stage for transformers, as it introduced this technology to the world. We'll get a little more into how transformers work later on.

 In 2022, LLMs hit the mainstream when AI chatbots like ChatGPT, [Claude](https://instagram-video-files.techidaily.com/updated-2024-approved-enhance-your-video-impact-with-slow-motion-on-ig/), and Google Bard became all the rage. The release of OpenAI's ChatGPT-3.5 was the catalyst for this new trend, as the chatbot offered a very impressive conversational AI tool that could very effectively process human language. Since then, LLMs have become a hot topic of conversation, and more LLM-based tools are being released every week.

 So, what's behind this impressive technology?

<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
##  How Do LLMs Work?

 A crucial element that a lot of popular LLMs need is pre-training. Before an LLM is put to work processing language, it needs to be trained on a vast amount of data, as well as a set of parameters.

 Take OpenAI's GPT-3.5, for example. This LLM was trained on all kinds of text-based data, including books, articles, academic journals, web pages, online posts, and more. On top of this, billions of variables, known as "parameters", are set in place to determine how GPT-3.5 produces text and responds to prompts. GPT-3.5's training also involved two other aspects, known as "reinforcement" and "next-word prediction."

 However, other kinds of LLMs go through a different preliminary process, such as multimodal and fine-tuning. OpenAI's DALL-E, for instance, is used to generate images based on prompts, and uses a multimodal approach to take a text-based response, and provide a pixel-based image in return (i.e. one form of input media is converted to another form of output media).

 Google's BERT, on the other hand, goes through a preliminary process known as fine-tuning, which is less focused on producing natural language responses, and more focused on responding to more specific tasks like text classification and question answering (which improves the quality of search results).

 LLMs also rely on a neural network to function, and the most common type used is known as a transformer. Below is a basic diagram depicting the process of a transformer, but we'll delve into more detail to better understand how it works.

![Diagram of an LLM transformer model](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/transformer-diagram-1.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
Katie Rees

 Transformer neural networks play a crucial role in allowing the system to predict what words are coming next, and the importance and context of each word in a given sentence. Within the transformer model, there is an encoder step and a decoder step, each of which consists of multiple layers. First, text-based data reaches the encoder, and is then converted to numbers.

 These individual numerical units are also known as tokens, which is why you may hear the term "token limit" when AI chatbots are being discussed.

 These tokens are then categorized by the transformer, creating a map of the significance of each token, and how one token relates to another. In short, the transformer uses the numerical map it's created to understand the context around the data, and how one token is connected to another. This process is also known as transformer self-attention, or multi-head attention.

 Self-attention involves the transformer performing multiple calculations at once while comparing various input tokens to each other. From this, an output attention score is calculated for each token, or word. The more attention a word gets, the more heavily it is considered when creating an output (or response).

 Now, it's time to decode the numerical data into a text-based response. In this process, the encoded input tokens are converted to text-based output tokens, which forms the LLM's reply to a prompt.

 Without the transformer, the context, nuances, and relationship between words could not be determined, rendering the LLM effectively useless, as its responses would be ineffective or even nonsensical.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Where Are LLMs Used?

![The ChatGPT Official App logo on the sign in page on an iPhone.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/52927928199_a5604dfb49_o.jpg) 

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
Hannah Stryker / How-To Geek

 There are a few major LLMs out there today, including Claude, LaMDA, LLaMA, Cohere, [GPT-3.5, and GPT-4](https://pokemon-go-android.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-honor-x50i-drfone-by-drfone-virtual-android/). A lot of these LLMs were developed by well-known tech giants, such as Google and Meta, though others are the product of AI-focused companies like OpenAI and Anthropic.

 The most well-known examples of LLMs in action are AI chatbots, such as Bard, ChatGPT, Claude, and Bing Chat. These nifty tools began rising in popularity in late 2022, after OpenAI released GPT-3.5\. Since then, the application scope of LLMs has widened vastly, but AI chatbots remain very popular.

 This is because AI chatbots can offer users a myriad of services. You can ask these tools to provide facts, translate text, generate ideas, tell jokes, write poems and songs, and much more. The versatility of AI chatbots makes them useful in all walks of life, and companies are continuously working on improving their AI chatbots for an even better experience.

 But things don't stop with AI chatbots. Some very well-known LLMs are used outside of chatbot environments. For instance, Google's BERT is used to enhance the quality of search engine results, and was around years before chatbot-based LLMs became popular.

 Given how new LLM technology is, there are also a lot of prospective uses that may be applied in the future. LLMs can prove useful in the healthcare industry, specifically in research analysis, patient scenario simulations, discharge summaries, and medical queries. However, the most recent iterations of LLMs still struggle with factual inaccuracies, training data limitations, and [AI hallucinations](https://audio-shaping.techidaily.com/strategies-for-minimizing-large-scale-video-and-audio-data/), so they may not yet be suited for medical use.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
##  LLMs Are an Exciting New Technology

 LLMs are still in their infancy, having only been officially invented in 2017\. But the potential of this language processing method is truly astounding, with LLM-based tools already offering capabilities that were once impossible for computers. In the near future, we may see LLMs advance even further, with more and more industries adopting the technology.

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
<li><a href="https://technical-tips.techidaily.com/spider-man-no-way-home-the-best-sites-for-legal-viewings/"><u>'Spider-Man: No Way Home': The Best Sites for Legal Viewings</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-discovering-the-benefits-of-personalized-asmr-sounds/"><u>[New] 2024 Approved  Discovering the Benefits of Personalized ASMR Sounds</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-key-tips-for-optimal-live-sports-content-capture/"><u>[New] 2024 Approved  Key Tips for Optimal LIVE Sports Content Capture</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-benq-sw320-monitor-reveal-a-spectacle-in-4k-technology/"><u>[Updated] In 2024, BenQ SW320 Monitor Reveal  A Spectacle in 4K Technology</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-premier-selection-10-premium-image-replace-kits/"><u>[Updated] Premier Selection  10 Premium Image Replace Kits</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-metacores-finest-vr-headsets-and-eyewear-guide/"><u>2024 Approved  Metacore's Finest VR Headsets and Eyewear Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/a-beginners-guide-to-starting-chats-within-the-mozilla-thunderbird-email-client/"><u>A Beginner's Guide to Starting Chats Within the Mozilla Thunderbird Email Client</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-unlock-from-iphone-8-plus-how-to-fix-it-by-drfone-ios/"><u>Apple ID Unlock From iPhone 8 Plus? How to Fix it?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/best-practices-for-addressing-stop-0x0n0000003d-errors-in-microsoft-operating-systems/"><u>Best Practices for Addressing STOP 0X0n0000003D Errors in Microsoft Operating Systems</u></a></li>
<li><a href="https://technical-tips.techidaily.com/comprehensive-d-link-default-creds-compilation-july-2024-update/"><u>Comprehensive D-Link Default Creds Compilation: July 2024 Update</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-best-foodie-tv-programs-available-on-netflix-today/"><u>Discover the Best Foodie TV Programs Available on Netflix Today!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/effective-solutions-for-fixing-wifi-authentication-failures-on-android-phones/"><u>Effective Solutions for Fixing Wifi Authentication Failures on Android Phones</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-strategies-how-to-harness-google-maps-for-electric-car-charger-locations/"><u>Expert Strategies: How to Harness Google Maps for Electric Car Charger Locations</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-vivo-y28-5g-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/gmail-hacks-revealed-the-comprehensive-guide-to-establishing-an-email-aka/"><u>Gmail Hacks Revealed: The Comprehensive Guide to Establishing an Email AKA</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-address-and-repair-the-mfc42ddll-missing-error-message/"><u>How to Address and Repair the Mfc42d.dll Missing Error Message</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-asus-rog-phone-7-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Asus ROG Phone 7 to Outlook | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-earning-a-living-with-social-media-snaps/"><u>In 2024, Earning a Living with Social Media Snaps</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-lava-yuva-2-pro-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Lava Yuva 2 Pro ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/insight-into-cellular-operators-and-how-they-work/"><u>Insight Into Cellular Operators and How They Work</u></a></li>
<li><a href="https://technical-tips.techidaily.com/instagrams-hottest-trending-hashtags-for-a-viral-reach/"><u>Instagram's Hottest Trending Hashtags for a Viral Reach</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/netflix-subscription-is-it-a-smart-spending-decision/"><u>Netflix Subscription: Is It a Smart Spending Decision?</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-poco-c55-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Poco C55 Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/reconnecting-guide-restoring-internet-access-on-your-vizio-television/"><u>Reconnecting Guide: Restoring Internet Access on Your Vizio Television</u></a></li>
<li><a href="https://technical-tips.techidaily.com/rectifying-the-absent-python-dll-a-step-by-step-solution-for-python-24dll-not-found/"><u>Rectifying the Absent Python DLL – A Step-by-Step Solution for Python 24.dll Not Found</u></a></li>
<li><a href="https://article-posts.techidaily.com/reimagined-analysis-new-developments-in-sonys-s6500-bdhd-for-2024/"><u>Reimagined Analysis  New Developments in Sony's S6500 BD/HD for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722869413560-samsung-galaxy-ring-2021-price-breakdown-release-schedule-tech-specs-and-current-releases/"><u>Samsung Galaxy Ring 2021: Price Breakdown, Release Schedule, Tech Specs & Current Releases</u></a></li>
<li><a href="https://fox-http.techidaily.com/simplifying-the-process-of-creating-a-high-quality-rss-feed/"><u>Simplifying the Process of Creating a High-Quality RSS Feed</u></a></li>
<li><a href="https://win-blog.techidaily.com/solved-call-of-duty-black-ops-4-not-launching/"><u>SOLVED: Call of Duty Black Ops 4 Not Launching</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-to-correct-a-non-responsive-mozilla-thunderbird-launcher/"><u>Step-by-Step Guide to Correct a Non-Responsive Mozilla Thunderbird Launcher</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-creating-your-new-x-by-formerly-twitter-profile/"><u>Step-by-Step Guide: Creating Your New X by Formerly Twitter Profile</u></a></li>
<li><a href="https://technical-tips.techidaily.com/student-savings-strike-how-to-cut-costs-and-jam-out-on-spotify-for-less-than-half-the-price/"><u>Student Savings Strike: How to Cut Costs and Jam Out on Spotify for Less Than Half the Price</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-collection-of-507-creative-instagram-captions-for-the-year-2024/"><u>The Ultimate Collection of 507 Creative Instagram Captions for the Year 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-guide-to-expanding-your-instagram-followers-effectively/"><u>The Ultimate Guide to Expanding Your Instagram Followers Effectively</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-tutorial-for-hooking-up-apple-homepod-to-your-tv-screen/"><u>The Ultimate Tutorial for Hooking Up Apple HomePod to Your TV Screen</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unlock-affordable-precision-with-elegoo-neptune-4-pro-a-comprehensive-review/"><u>Unlock Affordable Precision with Elegoo Neptune 4 Pro - A Comprehensive Review</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unveiling-the-future-what-to-expect-from-the-upcoming-m4-mac-mini-price-estimates-and-release-dates-awaiting-confirmation/"><u>Unveiling the Future: What to Expect From the Upcoming M4 Mac Mini - Price Estimates and Release Dates Awaiting Confirmation</u></a></li>
<li><a href="https://technical-tips.techidaily.com/wireless-screen-projection-how-to-project-content-from-your-phone-or-tablet-onto-an-lg-television/"><u>Wireless Screen Projection: How to Project Content From Your Phone or Tablet Onto an LG Television</u></a></li>
</ul></div>
