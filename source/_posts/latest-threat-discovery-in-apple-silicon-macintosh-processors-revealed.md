---
title: Latest Threat Discovery in Apple Silicon Macintosh Processors Revealed
date: 2024-08-26 17:14:58
updated: 2024-08-29 12:47:31
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/macbook-air.jpg
---

## Latest Threat Discovery in Apple Silicon Macintosh Processors Revealed

If you thought you were immune from a Meltdown or Spectre-like hardware exploit by using laptops with Apple Silicon chips instead of x86 CPUs, you are unfortunately mistaken. A new vulnerability has popped up on Apple silicon-powered Macs, and it could result in performance losses for some workflows as developers try to patch it.

 Researchers have uncovered a significant vulnerability present in Apple's [M-series chips](https://facebook-record-videos.techidaily.com/updated-the-comprehensive-handbook-of-youtube-views-and-financial-growth/) that exposes Macs to potential attacks, allowing malicious actors to extract secret keys during common cryptographic operations. The vulnerability exploits a hardware optimization feature called the Data Memory-dependent Prefetcher (DMP), present only in M-series chips such as the M1 range and the M2 range, as well as Intel's Raptor Lake microarchitecture. While prefetchers are designed to enhance performance by predicting memory addresses, the DMP, unlike classical prefetchers, utilizes both addresses and data values for predictions. This unique behavior can lead to the leakage of sensitive information, such as encryption keys, through cache side channels.

 Dubbed "GoFetch," the attack can be executed with user-level privileges and targets cryptographic processes running on the same CPU cluster. By crafting inputs to manipulate intermediate data, the attacker can trick the DMP into treating sensitive data as memory addresses, thus leaking secrets over time. The attack is effective against various cryptographic algorithms, even those designed to resist chosen-input attacks.

 The worst part of this vulnerability, however, is that there doesn't look like there's an easy fix for it. Mitigating this vulnerability requires additional defenses in cryptographic software, such as constant-time programming and ciphertext blinding, which come with significant performance costs. Running cryptographic processes on specific CPU cores lacking the DMP may also be necessary but could further impact performance. While newer chips like the M3 offer the option to disable the DMP, the potential performance penalties remain unknown.

 Apple has not officially commented on the research findings, but chances are it'll eventually have to come out with a macOS update that severely limits performance for those specific tasks in order to work around this. That's similar to what happened with the [Meltdown and Spectre security exploits](https://technical-tips.techidaily.com/fixing-motherboard-error-codes-and-bios-issues-during-computer-startup/) in 2018—Spectre was also a side-channel attack, and Meltdown allowed a rogue process to read all memory.

 Source: [Ars Technica](https://arstechnica.com/security/2024/03/hackers-can-extract-secret-encryption-keys-from-apples-mac-chips/)

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
