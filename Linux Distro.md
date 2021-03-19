# Choosing a Linux Distro
- As a great man once said "The distribution doesn't matter as long as you know how to customize the install". That being said, distros do matter when it comes to stability and reliability. 
- Mostly debian based distros like Ubuntu or Pop!\_OS have a very stable out of the box experience. Where as Arch based distros need a little bit of tweaking. Manjaro might be the best bet for a stable Arch based distro. Although there are probably hundreds of distros out there, I would like to focus on a few I have used in the past.
- These distros usually differ in kernel, package managers and update cycles. Arch based distros get the updates relatively quickly. This sometimes breaks the system, but this is linux and you have control over the update (unlike windows which doesn't provide this option intuitively). That means, you can choose not to install the updates until you have saved your work or you are about to take a vacation and it doesn't matter if the update is going to break your workflow.

# My choice of Distro
- I have been using linux on and off for a few years now. I started off with Ubuntu because of its popularity and sometimes Linux is used synonymous with Ubuntu. It was a good starting point and I really enjoyed the experience. However, the install was on a laptop and this did not have gestures enabled out of the box (but you can easily enable them with a single package and a couple of commands) when I first used it. So I started looking for a way to enable it and came across Elementary OS.
- The Elementary OS had a really minimal, yet a beautiful asthethic to it. And this actually enabled gestures out of the box and it was a good experience. But I had discovered that there are many more such distributions so I wanted to explore. 
- Since my childhood I have a wierd obsession with gaming, so if I see a product targeted at gamers, it makes me go Yay! So having used Ubuntu and going back to windows, switching to elementary and then again going back to windows I was on a look out for a distribution which could make my system feel a little powerful (Windows made my system feel so slow!) and this is when I came across Pop!\_OS, which was marketed as Linux distro for gaming. 
- I have been using Pop!\_OS on my laptop ever since. But recently, I bought a surface laptop which actually integrates well with Windows and I did not want to mess with my newly bought laptop so I decided that I will be installing linux on my PC which could potentially increase my productivity.
- I have been on debian based system forever and would like to try out Arch based distros. My experience with arch has been mostly negative. I tried to use Arch on WSL(Windows Subsystem for Linux) but I could never understand the way it handled user permissions. It is also important to note that Windows does not support Arch as a subsystem. Having said that, I have only heard great things about arch and would like to learn more about it.
- I would be going with Arch based distro =="Manjaro"== for this project. 

# Installing Manjaro
These are the few references I used to understand the installation of arch linux on my hardware. 
https://www.youtube.com/watch?v=DPLnBPM4DhI
[Arch Wiki](https://wiki.archlinux.org/index.php/Installation_guide)

## Creating bootable USB
Before installing the OS, it is necessary to create a bootable USB. The .iso file of your choice can be downloaded on [Manjaro's](https://manjaro.org/download/) official website. 

If you are on windows, I would recommend the tool [Balena Etcher](https://etcher.download/) to create a bootable USB. This is a crossplatform tool so it should also work on the other OS. Please do check their official website (Just click on the name above) for more information. This is a very reliable tool which has worked 100% of the times I have used. There are other tools like Rufus, but I have had problems with them in the past so I would stick with Etcher for this install.

## Installation 
If you choose the officially supported edition (XFCE, Plasma and Gnome) of manjaro, the installation is quite straight forward. The installation can also be done using CLI(Command line interface) with Manjaro Architect if you would like to customize what is being installed on the system (including the kernel version you would like). More information on the installation can be found on [Manjaro Wiki](https://wiki.manjaro.org/index.php/Installation_Guides).
For this install I will probably go with Plasma or Gnome as the desktop environment(DE) because I am quite familiar with these DE already.

## Post Installation
Once the standard installation is done, I will probably go with a tiling window manager(Awesome or Qtile). I am working on writing a config file for both of them, but running Linux on a vm on Windows(using the Hyper-V) is really a crappy experience. So I might do that after my switch to linux. I will make a seperate section when that happens.
Mounting the extra SSD and HDD I have on the pc would be another task I need to take care of, because I would want it to be automatically mounted rather than mounting it everytime I log on to the system.