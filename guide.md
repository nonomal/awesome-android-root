---
label: Guide
layout: default
icon: log
order: 90
---

- [What is Root Access](#what-is-root-access)
- [Should I root](#should-i-root)
  - [Benefits of Rooting](#benefits-of-rooting)
  - [Risks and Limitations](#risks-and-limitations)
  - [Community Perspectives](#community-perspectives)
- [Root Solutions](#root-solutions)
  - [How to root](#how-to-root)
  - [Common Methods](#common-methods)
    - [Magisk](#magisk)
    - [KernelSU](#kernelsu)
    - [APatch](#apatch)
  - [Which solution should I use](#which-solution-should-i-use)
- [Framework Solutions](#framework-solutions)
  - [LSPosed](#lsposed)
  - [LSPosed Fork](#lsposed-fork)
- [Frequently Asked Questions](#frequently-asked-questions)
  - [General Questions](#general-questions)
  - [Safety \& Security](#safety--security)
  - [Troubleshooting](#troubleshooting)
## What is Root Access
Android rooting is the process of gaining privileged control (known as root access) over various Android subsystems. 

Rooting allows overcoming limitations that carriers and hardware manufacturers put on some devices, resulting in the ability to alter or replace system applications and settings, run specialized apps that require administrator-level permissions, or perform other operations that are otherwise inaccessible to a normal Android user.

## Should I root
Now to the main question. Should i root?
First, let's view disadvantages then advantages.

### Benefits of Rooting
- You can grant apps, Su and they'll do a great job for you.
- You can tweak kernel= great performance for games.
- You can ban ads from your device completely.
- You can uninstall unnecessary apps, i.e., system apps.
- You can perform much more super enjoying tasks, they all can't be listed here.

### Risks and Limitations
- As a root user, if you ever mess up, it's all your responsibility to fix it.
- Personally i never faced it, even though i messed up the device to the worst condition. People usually say your device may hard brick.
- Banking apps won't work. Recently, some apps are detecting root even with Magisk (there are workarounds for most of them).
- Rooting process if messed, Although it can be fixed, it can be tough for beginners.

### Community Perspectives
- Here is the [reddit thread](https://www.reddit.com/r/AndroidQuestions/comments/1c69h3q/is_rooting_still_something_you_would_do_in_2024/) Debating if its worth it rooting in 2024 (but in my opinion its worth every penny).

## Root Solutions
### How to root
It really depends upon your device; it's recommended to check the XDA forum for your device, which usually has a good guide for your devices. Another option is telegram groups for your devices, as they have specific communities related to your device.
Generally, the following steps are common:
- Unlock the boot loader.
- Get a custom recovery installed.
- Flash your preferred method of rooting solutions from below.
- Enjoy the ultimate power of a rooted device.
### Common Methods
#### Magisk
**[Magisk](https://github.com/topjohnwu/Magisk)** is the most popular and powerful tool for Android power users, providing root access, boot scripts, and a module system for customizing Android devices systemlessly. It's actively maintained and regularly updated. `FOSS`

#### KernelSU
**[KernelSU](https://github.com/tiann/KernelSU)** is a kernel-based root solution for Android devices. It provides a root method that works by modifying the kernel, offering an alternative to Magisk for some devices and use cases. KernelSU is gaining popularity, especially on newer devices. `FOSS`

#### APatch
**[APatch](https://github.com/bmax121/APatch)** uses patching of Android kernel and Android system to gain root access based on [Kernel Patch](https://github.com/bmax121/KernelPatch/). `FOSS`

### Which solution should I use
If you are a newbie or don't know much about rooting, I'd  recommend going with Magisk, as it has a vast community support.

## Framework Solutions
Frameworks provide a foundation for extending root functionality through modules by allowing modification of various system configs and functions.

### LSPosed
**[LSPosed](https://github.com/LSPosed/LSPosed)** is an open-source framework that allows users to install and use Xposed/LSPosed modules on their Android devices. `FOSS`

### LSPosed Fork
**[LSPosed Fork by JingMatrix](https://github.com/JingMatrix/LSPosed)** is a fork of LSPosed after LSPosed's development was halted for some reasons.It has support for Android 15 as well as some other improvements. `FOSS`

---
## Frequently Asked Questions

### General Questions

#### Will rooting void my warranty?
Generally yes, rooting voids your device warranty. However, it specifically depends upon your device manufacturer.
You can usually unroot your device before sending it for warranty service. Some manufacturers may still detect that the device was previously rooted.

#### Can I unroot my device?
Yes. You can unroot by:
- Using the "Unroot" option in [Magisk Manager](https://github.com/topjohnwu/Magisk)
- Flashing stock firmware 

### Safety & Security

#### Is rooting safe?
Rooting itself is generally safe when done correctly, but carries some risks:
- Potential for bricking if done incorrectly 
- Security vulnerabilities if not properly managed
- System instability if incompatible modifications are made

#### How can I protect my banking apps on a rooted device?
You can:
1. Use [Magisk Hide](https://github.com/topjohnwu/Magisk) to hide root from specific apps
2. Install [Play Integrity Fix](https://github.com/chiteroman/PlayIntegrityFix)
3. Use [Shamiko](https://github.com/LSPosed/LSPosed.github.io/releases) for additional root hiding
4. Consider using app isolation tools like [Shelter](https://gitea.angry.im/PeterCxy/Shelter)

### Troubleshooting

#### What should I do if my device won't boot after rooting?
1. Try booting into recovery mode
2. Flash the original firmware if possible
3. Use manufacturer's emergency download mode if available
4. Seek help on Telegram group of your device,your device manufacturer forum or XDA Forums for your specific device

#### How do I fix SafetyNet/Play Integrity issues?
Use a combination of:
- [Play Integrity Fix](https://github.com/chiteroman/PlayIntegrityFix)
- [Magisk](https://github.com/topjohnwu/Magisk)'s DenyList
- [Shamiko](https://github.com/LSPosed/LSPosed.github.io/releases) for additional root hiding

#### Why aren't root apps detecting root access?
Check if:
1. Root management app (like [Magisk](https://github.com/topjohnwu/Magisk)) is properly installed
2. Apps have been granted root permissions
3. Root hiding features aren't accidentally blocking legitimate root apps
4. Use [Root Checker](https://play.google.com/store/apps/details?id=com.joeykrim.rootcheck) to verify root access


