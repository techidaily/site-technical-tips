---
title: "Complete Tutorial: Unlocking the Full Potential of Your Kindle Fire Through Rooting"
date: 2024-08-20 10:44:29
updated: 2024-08-21 12:20:37
categories:
  - epubor
thumbnail: https://thmb.techidaily.com/b91466317b7eccd6ee21d430979cabf5463805ed441067719a242af16768dcd1.jpg
---

## Complete Tutorial: Unlocking the Full Potential of Your Kindle Fire Through Rooting

## How to Root Kindle Fire

Posted by [Jonny Greenwood](https://plus.google.com/u/0/+JonnyGreenwood999) on 4/15/2020 3:11:13 PM.

3.7 [(32 comments)](http://www.epubor.com/#comment-area) 



![follow](http://www.epubor.com/images/follow.png)

Kindle Fire is one of the most popular tablets at present. Besides great e-book reading experience, the Android OS gives Kindle Fire more playability. As we know, rooting is the first thing you need to do before modifying your own Android system. It makes you become the ultimate administrator of the system. But rooting is not an easy job, especially for the custom Android like Kindle Fire runs. So here comes this article to show you how to root a Kindle Fire in a simple way. Just read it and then root your device!

#### You need to know three things before reading

1 This tutorial is only for the original Kindle Fire. If you want to know how to root Kindle Fire 2nd gen, please view this post: [Rooted Kindle Fire 2nd Generation](http://forum.xda-developers.com/showthread.php?t=2019547).

2 Rooting Kindle Fire is very strict on the system version. This rooting tutorial is for the latest 6.3.x (6.3.1 and 6.3.2). It may be not suitable for the older version. Here is a tutorial for rooting version 6.2.x:[BurritoRoot3 - Kindle Fire Root. Easy root edition](https://forum.xda-developers.com/showthread.php?t=1410223).

3 Some professional terms  
**fbmode**: Fast Boot Mode  
**firefirefire**: A Bootloader  
**twrp**: TeamWin Recovery Project  
 You don't need to understand these professional terms. Just remember they are necessary for rooting. 

### **Step 1 Get rooting tools**

We've packed all the rooting tools together. [Click here](https://forum.xda-developers.com/showthread.php?t=1414832) to download the rooting tools.

### **Step 2 Open CMD and run ADB**

Extract the zip files in step1\. Open the extracted folder, press on "Shift" and right click in the blank. Choose "Open command window here" and CMD window will pop up.

![how to root kindle fire-enter cmd](https://www.epubor.com/images/uppic/1-how to root kindle fire-enter cmd.png)

Type these commands one by one to make your Kindle Fire enter fbmode. Remember to type the next command when the last command has run. Pay attention to the blank space.

**1\. adb push fbmode /data/local/fbmode** 
 **2\. adb shell chmod 755 /data/local/fbmode** 
 **3\. adb shell /data/local/fbmode** 
 **4\. adb reboot**

When you run the 4th command, the Kindle Fire will reboot and stick on the "Kindle Fire" logo. Don't worry. This means your device has entered the fbmode successfully. Now type another commands to install firefirefire and twrp on you Kindle Fire.

**1\. fastboot -i 0x1949 flash bootloader u-boot.bin** 
**2\. fastboot -i 0x1949 flash recovery twrp.img** 
**3\. fastboot -i 0x1949 oem idme bootmode 4000** 
**4\. fastboot -i 0x1949 reboot**

Now your Kindle Fire will reboot. You may find that the boot screen has changed and there is a notice which says "press power button for boot menu" displayed on the bottom of the screen. Long press power button and choose "Recovery". Then Kindle Fire will enter TWRP. Just like this:

![how to root kindle fire-twrp](https://www.epubor.com/images/uppic/2-how to root kindle fire-twrp.jpg)

You don't need do anything on your Kindle Fire. Go on typing commands in CMD:

**1\. adb shell mount system** 
**2\. adb push su /system/xbin/su** 
**3\. adb shell chown 0.0 /system/xbin/su** 
**4\. adb shell chmod 06755 /system/xbin/su**

Now go back to TWRP on you Kindle Fire. Choose 'Reboot" – "System" and your device will reboot. 

### **Step 3 Install superuser**

Transfer the superuser apk file to your Kindle Fire. Install it with ES File Explorer.

![how to root kindle fire-install superuser](https://www.epubor.com/images/uppic/3-how to root kindle fire-install superuser.png)

Now you've got all rooting job done! Every time you run an app which needs some permission, a window will pop up like this:

![how to root kindle fire-superuser warning](https://www.epubor.com/images/uppic/4-how to root kindle fire-superuser warning.jpg)

If you can see this picture on your device, that means you've rooted your Kindle Fire successfully!

![cro buttom](http://www.epubor.com/images/uppic/crobuttom.png)

This guide is written for Kindle Fire users or lovers. A cool trick for you. We also gathered [top 10 kindle fire cool tricks](https://tools.techidaily.com/epubor/products/), see the full list?

Trick 1 [How to Set Wallpaper on Kindle Fire](https://tools.techidaily.com/epubor/products/) 

Trick 2 [How to Root Kindle Fire](https://tools.techidaily.com/epubor/products/) 

Trick 3 [Turn Kindle Fire into Android Tablet](https://tools.techidaily.com/epubor/products/) 

Trick 4 [Cool Apps for Kindle Fire](https://tools.techidaily.com/epubor/products/) 

Trick 5 [Install Flash Player on Kindle Fire](https://tools.techidaily.com/epubor/products/) 

Trick 6 [Sites to Download Free Kindle Books](https://tools.techidaily.com/epubor/products/) 

Trick 7 [Share Kindle Fire Books with Friends](https://tools.techidaily.com/epubor/products/) 

Trick 8 [Print from Kindle Fire](https://tools.techidaily.com/epubor/products/)

Trick 9 [Transfer files to Kindle](https://tools.techidaily.com/epubor/transfer/)

Trick 10 [More Helpful Tips Freebies for Kindle Fire](https://tools.techidaily.com/epubor/products/)

![author](https://www.epubor.com/images/uppic/jonny.png)

[Jonny Greenwood](https://plus.google.com/u/0/+JonnyGreenwood999) joined Epubor since 2011, loves everything about eBooks and eReaders. He seeks the methods to read eBooks more freely and wants to share all he has got with you.

SHARING IS GREAT!

[Tweet](https://twitter.com/share) 

[SAVE PAGE AS PDF](https://tools.techidaily.com/epubor/products/) 



32 Comments

[reply](https://tools.techidaily.com/epubor/products/) 

[reply](https://tools.techidaily.com/epubor/products/) 

Which OS?

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

08/17/2013 14:14:20

What OS are you using to install this? Windows or Ubuntu? Thanks, about to start on this tut. 

[reply](https://tools.techidaily.com/epubor/products/) 

Eddie

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

08/18/2013 19:04:02

I use Windows 7.

[reply](https://tools.techidaily.com/epubor/products/) 

Luísa

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

09/2/2013 16:27:48

In the second command it says that the device was not found

[reply](https://tools.techidaily.com/epubor/products/) 

Hannibal

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

09/8/2013 07:12:22

The file isn't extracting properly for me. I'm using winrar 32-bit and running Windows 8.

 Would it be possible to help me please?

[reply](https://tools.techidaily.com/epubor/products/) 

Eddie

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

09/8/2013 19:25:31

Hi, Hannibal. We've just tested the rar file. It can be extracted indeed. Perhaps it's the system compatibility which cause the extracting error. Or you can try another extracting tool like the 7-zip.

[reply](https://tools.techidaily.com/epubor/products/) 

medic245lccfr

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

09/23/2013 04:57:25

I got through the first 4 steps no problem. Like you said it will reboot and Kindle Fire logo stays on screen but when I entered fastboot -i 0x1949 flash bootloader u-boot.bin it gets stuck and tells me it is "waiting on device". Let it sit for about an hour and nothing. Tried a hard reset and the steps again. Nothing. What do I do next. I have tried KFU but it can't find device,probably because it is not booted up. The driver is also missing in Device Manager now. Running Win8 Pro 64\. Any help would be appreciated.

[reply](https://tools.techidaily.com/epubor/products/) 

Eddie

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

09/23/2013 20:11:14

Hi,medic245lccfr  
 According to your description, I guess it's the usb driver's problem. Try to reinstall the usb driver. Another reason for this may be that you use the Win 8 Pro 64.System incompatibility always causes many unexpected problems.

[reply](https://tools.techidaily.com/epubor/products/) 

Eddie

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

09/23/2013 20:11:19

Hi,medic245lccfr  
 According to your description, I guess it's the usb driver's problem. Try to reinstall the usb driver. Another reason for this may be that you use the Win 8 Pro 64.System incompatibility always causes many unexpected problems.

[reply](https://tools.techidaily.com/epubor/products/) 

BillyJ

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

10/21/2013 05:36:31

Sraight forward, to the point & accurate

[reply](https://tools.techidaily.com/epubor/products/) 

marc marroquin

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

10/25/2013 09:51:00

Thanks for your help, however the first problem I ran into was I have a 64bit machine, that was easy to take care of, i got a 32bit one. Second when I attempted to run the adb programs, I got device not found, and I could not see any hints on this page to correct????????

[reply](https://tools.techidaily.com/epubor/products/) 

garacee

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

11/4/2013 02:15:37

after ive typed this 1\. fastboot -i 0x1949 flash bootloader u-boot.bin the cmd says "waiting for device" while the kindle displays 'kindle fire' on the screen. i cannot type a new command. its been like that for like forever..? how long should i wait?

[reply](https://tools.techidaily.com/epubor/products/) 

Matt

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

11/5/2013 11:38:03

step 3: Install superuser

 Transfer the superuser apk file to your Kindle Fire. Install it with ES File Explorer.

  
 Excuse me, WHAT? BE MORE CLEAR ON THIS.

[reply](https://tools.techidaily.com/epubor/products/) 

pol

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

11/10/2013 20:12:51

Hi, I´ve just tried to run this, but at the first step had "error: device not found".  
 KF is connected, I can see device´s folders as a pendrive. I´m using windows 8.  
 Any idea?

 thanks

[reply](https://tools.techidaily.com/epubor/products/) 

jack

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

11/21/2013 10:39:33

nice.it worked well.

[reply](https://tools.techidaily.com/epubor/products/) 

IsraelCB

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

11/24/2013 20:08:46

My superuser will not ask permissions any help?

[reply](https://tools.techidaily.com/epubor/products/) 

James Bowers

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

01/12/2014 08:44:01

I installed Superuser on kindle fire gen1 through file explorer. was it supposed to in a certain file? i had it as a standalone icon in the local folder when i installed it. i now have an icon on the kindle that when pressed that states no log information and also no apps in list?

 Thanks, James

[reply](https://tools.techidaily.com/epubor/products/) 

Paul

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

01/29/2014 10:48:57

Once I have successfully rooted my Kindle I have heard I should install Jelly Bean. Are there other alternatives? What do you recommend?

 Thanks

[reply](https://tools.techidaily.com/epubor/products/) 

get

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

05/16/2014 18:57:55

You suck  

[reply](https://tools.techidaily.com/epubor/products/) 

raustin

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

07/13/2014 06:49:20

Will this work on 10.4.9 please reply asap 

[reply](https://tools.techidaily.com/epubor/products/) 

Panic!

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

08/4/2014 17:32:18

The command line shows this, couldn't write bp1, panic!  
 How do I fix

[reply](https://tools.techidaily.com/epubor/products/) 

sarah

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

11/29/2014 13:30:26

I have 4.5.1 4th gen. How to root that? No Instructions. 

[reply](https://tools.techidaily.com/epubor/products/) 

The Great

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

03/1/2015 21:58:51

Hi, just wanted to tell you that at the second and the third step, it says "device not found". Please help

[reply](https://tools.techidaily.com/epubor/products/) 

Nutelly

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

05/9/2015 19:45:09

By rebooting will It erase the stuff on my kindle??

[reply](https://tools.techidaily.com/epubor/products/) 

smokiibear

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

06/11/2015 07:55:24

any suggestions for version 7.4.9

[reply](https://tools.techidaily.com/epubor/products/) 

Nick

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

06/14/2015 16:51:38

Bullshit dosnt work

[reply](https://tools.techidaily.com/epubor/products/) 

aarno

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

07/17/2015 14:33:59

first command line: adb out of date, killing...

[reply](https://tools.techidaily.com/epubor/products/) 

jimmy

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

09/16/2015 05:46:21

I want to root kindle fire 3rd generation 

[reply](https://tools.techidaily.com/epubor/products/) 

sky

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

09/18/2015 22:41:36

when i am writting the command it is showing "error no device found"  

[reply](https://tools.techidaily.com/epubor/products/) 

sky

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

09/18/2015 23:23:05

please see and reply how to solve it  

[reply](https://tools.techidaily.com/epubor/products/) 

stephen

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

10/22/2015 09:36:19

hi..  
 how to root 3rd gen version 4.5.5 kindle fire.?  
 can you pls help me..cuz I cant save my coc in google play..pls help..

[reply](https://tools.techidaily.com/epubor/products/) 

Mohamed Faramawy

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

01/9/2016 13:27:54

MyKindleFire stuck at KINDLE FIRE logo screen.  
 and it seemsneed Amazon Fast boot cabel.

[reply](https://tools.techidaily.com/epubor/products/) 

Dave

[Re:How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

01/12/2016 15:02:09

I get this error while excecuting the 3rd line

  
 C:\\Users\\\*\*\*\*\*\\adb&gt;adb shell /data/local/fbmode  
 UÖ?\~e+d: permission denied

  
 Please help

[reply](https://tools.techidaily.com/epubor/products/) 

Leave a comment

| Rating |  |
| ------ |  |

| YourName | \*  1 to 50 chars |
| -------- | ----------------- |

| email | Internet Email |
| ----- | -------------- |

| Comments | UBB Editor |
| -------- | ---------- |

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
