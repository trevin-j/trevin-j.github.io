---
layout: post
title: There have never been more reasons to adopt Linux
subtitle: It's time to make the switch
gh-repo: trevin-j/trevin-j.github.io
gh-badge: [star, follow]
tags: [tech, linux, open-source, software, privacy, security, freedom, foss]
comments: true
author: Trevin Jones
readtime: true
cover-img: /assets/img/switch-to-linux/cover-img.png
---

Free and Open Source Software (FOSS) is an amazing thing. In all my conversations about technology, I always mention FOSS. It's been a philosophy that I have loved ever since I began learning how to program. To start, who doesn't love free stuff? With most FOSS software, not only is it free, but it's completely free without a catch, and you can even see the source code for yourself. Without open source software, there would be little to no innovation in the tech industry, and information would be gatekept by corporations. 

Given my love for free and open source software, it's no surprise that I am a huge advocate for Linux. Linux is a free and open source operating system that is widely used in the tech industry by individuals and companies alike. Because of its open source nature, countless distributions (distros) have been/are developed for nearly any use case you can imagine. From servers to desktops, mobile devices to robotics, there are Linux distributions and applications for whatever you need. Android, for example, is based on the Linux kernel, and is the most widely used operating system in the world. 

![My desktop running Fedora Linux](/assets/img/switch-to-linux/my-desktop.png)

# Linux as a desktop operating system

Ok so what? Just because Linux is important to the tech industry doesn't necessarily mean it matters to the average user, right? Well, let's analyze the most common desktop operating systems in use today: Windows and macOS. Both of these operating systems are proprietary, and you as a user and a consumer have little control over the OS's features, updates, and privacy. Windows 10, for example, is known for its telemetry and data collection, and macOS is known for its walled garden approach to software distribution. 

While installing and using Windows is quite easy, consider some recent and somewhat controversial changes being made to the OS. Windows 11, for example, requires a Microsoft account to use. Recent updates also force Microsoft Copilot into your operating system, whether you like it or not. There is also the increasing amount of ads and bloatware being pushed to users, even in the standard file explorer.

MacOS is often praised for its design and user experience, but you are completely limited to how Apple feels you should do things. You also can only legally run MacOS on Apple hardware, which is far more expensive than most alternatives. After all, why in the world would I pay thousands of dollars for hardware that performs worse than a PC that costs half as much? As a personal preference, I do not like being locked into a single company's ecosystem. For others like me, Apple products are not the way to go.

You may disagree with these points, or maybe they aren't a big deal to you. Whether you agree or not, it's still worth looking into Linux. For a desktop experience, Linux has whatever you need. If you are an enthusiast and tinkerer, there is Arch Linux. If you aren't super tech savvy, there is Linux Mint. If you are a gamer, steam has a Linux client and with the amazing improvements to Proton, you can play a large amount of windows games on Linux. If you love cutting-edge technology but still need a stable desktop experience, check out Fedora Linux, which is what I have been using for the last few months and I absolutely love it.

![Linux Mint](/assets/img/switch-to-linux/lm-logo.png)

# My recommendation for new users

If you've spent any time looking into what Linux distribution to use as a new user, you've likely been recommended Linux Mint or Ubuntu. Some may disagree with me on this, but I wouldn't recommend Ubuntu to most users right now. Ubuntu is a great, tried and true distribution for sure. However, Canonical, the company behind Ubuntu, has been making changes that some may not like. Primarily, canonical has been pushing snaps, which are containerized applications that are sandboxed from the rest of the system. While snaps are great for security, the snap store is controlled by Canonical, and makes use of proprietary software. Many experienced Linux users dislike snap for this reason, and Canonical's push towards snaps has caused some to move to other distributions. Besides, snaps are not the only sandboxed application format available on Linux. Flatpak is another option that is designed to be more open.

Linux Mint, on the other hand, is a great distribution for new users. It is based on Ubuntu, so you get the same great package manager and familiarty, but by design, it ships without snaps at all. Linux Mint follows the philosophy of open source by choice, and includes only open source software in its installation, but doesn't restrict users from installing proprietary software if they choose to. Linux Mint is also known for its stability and ease of transition from other popular operating systems. I would recommend Linux Mint to anyone looking to make the switch to Linux.

![LM Desktop with LibreOffice](/assets/img/switch-to-linux/office-apps-screenshot.png)

# Making the switch
One huge reason why some are very hesitant to switch to Linux is its lack of support for popular software such as Microsoft office, Adobe products, etc. The good news is that there are alternatives to most of these proprietary applications. For example, LibreOffice is a great open source alternative to Microsoft Office. It even supports editing and saving Office formats such as .docx, xlsx, and pptx. If you are looking for alternatives to Adobe products, check out GIMP for photo editing, Inkscape for vector graphics, and Krita for digital painting. You can use Kdenlive for video editing, and Audacity for audio editing. Blender, now one of the top 3D modeling and animation software, is also available on Linux and is open source as well.

If you are a gamer, you may be hesitant to switch to Linux because of the lack of support for Windows games. However, as I mentioned earlier, Steam has a client on Linux, and Proton has made huge strides in compatibility with Windows games. Check out [ProtonDB](https://www.protondb.com/) to see how well your favorite games run on Linux. If you are a serious gamer, there still are some games that don't run well on Linux, but the list is getting smaller every day. There exist issues with anti-cheat software and some DRM, but the Linux gaming community is working hard to fix these issues. I love VR, but unfortunately if you are huge into virtual reality, you may want to stick with Windows for now, as VR support on Linux is still in its infancy at best.

## The process of installing Linux

Since Linux Mint is the best for new Linux users, I'll give a high level overview of how its installed. While I recommend trying Linux in a virtual machine first, you also have the option to boot Linux alongside your existing operating system. This is called dual booting. The installer for Linux Mint is designed to make this process as easy as possible. Don't try to use this as a guide, rather just a simplified overview of the process so you know what to expect. When you are ready to install Linux Mint, follow the official guide on the [Linux Mint website](https://linuxmint.com/).

![Flash drive](/assets/img/switch-to-linux/flash-drive.jpg)

### Prerequisites

1. You'll need a USB drive with at least 8GB, maybe 16GB of storage. You will install a "live" version of Linux Mint onto this USB drive. If there is anything on the USB drive that you want to keep, back it up first because it will be erased in this process.

2. Back up your data! This is important. When we mess with your hard drive to make room for Linux, something could go wrong. It's always good to have a backup of your important files.

3. Choose a desktop environment for your installation. There are three main desktop environments for Linux Mint: Cinnamon, MATE, and Xfce. Cinnamon is the most popular and is the default desktop environment for Linux Mint. It is developed specifically by and for Linux Mint, and it has the most support. I recommend Cinnamon for most users, as it gives you the experience that Linux Mint is built to give while still supporting fantastic plugins and customization. No matter which of the 3 desktops, you will be welcomed with a very natural Windows-like user interface. Later on down the road you will be able to install a different environment if you would like.

### Installing Linux Mint to a USB drive

1. Download the Linux Mint ISO from the [official website](https://linuxmint.com/download.php). 

2. Use a tool like [rufus](https://rufus.ie/) or [balenaEtcher](https://etcher.balena.io/) to write the ISO to the USB drive, making it bootable.

### Booting into the live environment

1. Plug the USB drive into your computer and restart it. You may need to press a key to enter the boot menu. This key is different for every computer, but it is usually one of the F keys or the ESC key. If you don't know which key to press, look it up for your specific computer.

2. Select the USB drive from the boot menu. You should see a screen that says "Linux Mint" and gives you the option to boot into the live environment.

3. Once you are in the live environment, you can try out Linux Mint without installing it. This is a great way to see if you like it before you commit to installing it.

### Installing Linux Mint

1. Once you are ready to install Linux Mint, double click the "Install Linux Mint" icon on the desktop.

2. Follow the on-screen instructions. You will be asked to choose your language, keyboard layout, and timezone. You will also be asked to connect to the internet, and to choose whether you want to install third-party software for graphics and Wi-Fi hardware.

3. When you get to the "Installation type" screen, choose "Install Linux Mint alongside Windows" if you want to dual boot. If you want to replace Windows with Linux, choose "Erase disk and install Linux Mint". If you want to manually partition your hard drive, choose "Something else". I would not recommend manually partitioning your hard drive unless you know what you are doing.

4. Follow the rest of the on-screen instructions. You will be asked to create a username and password.

### Post-installation

1. When booting into your new Linux Mint installation for the first time, you will be greeted with a welcome screen. This screen will give you some information about Linux Mint, and will provide some suggestions on what to do next.

2. Linux Mint comes with software called Timeshift, which is a system restore utility. I would recommend setting this up as soon as possible. Timeshift will take snapshots of your system, so if something goes wrong, you can restore your system to a previous state.

![Timeshift app](/assets/img/switch-to-linux/timeshift-screenshot.png)

3. LM also comes with a firewall application that you can set up. I would recommend setting this up as well.

![Firewall app](/assets/img/switch-to-linux/firewall-screenshot.png)

4. Most other software you would want can be found in the software manager. If you are going to become a more advanced user, you may want to learn how to use the command line, but Linux Mint is designed to be user-friendly and you can do most things through the GUI.

# Conclusion

I hope this post has given you some insight into why you should consider switching to Linux. Linux is a great operating system that is free, open source, and respects your privacy. It is also highly customizable and has a large community of users and developers. If you are tired of Windows or macOS, or if you are just looking for something new, I would highly recommend giving Linux a try. If you have any questions or comments, leave a comment below. I would be happy to help you get started with Linux. Thanks for reading!

---

# Some interesting Linux and general operating system statistics sources

* [General Linux and OS stats](https://www.enterpriseappstoday.com/stats/linux-statistics.html#:~:text=(Source%3A%20W3Techs)-,General%20Linux%20Statistics,using%20Linux%2Dbased%20operating%20systems.)

* [OS market share](https://gs.statcounter.com/os-market-share)

* [Desktop OS market share](https://gs.statcounter.com/os-market-share/desktop/worldwide)

* [Distrowatch - Linux distribution popularity](https://distrowatch.com/popularity)* Note that this is only a measure of interest in distributions based on page hits, and not a measure of actual usage.
