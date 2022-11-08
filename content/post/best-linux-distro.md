---
author: Bram
title: Best Linux Distro
date: 2022-11-08
description: Discussing the best Linux distro, just because
---

**<h3>Here I will discuss the best linux distro that I ever use, why?</h3>**
Because I have use a lot of them and people that new to Linux in general nowadays have no idea what is actually the best Linux distro without actually using them (there's a lot of trials and error need to be done).

Now, what needs to be considered when choosing a distro, is something like this:

{{% notice info "The Consideration" %}}
1. It needs to works perfectly usable out of the box.
2. Stable, even if it's on the cost of not getting the bleeding edge version of the software.
3. Lighter than Windows, assuming people using Linux as an alternative of their current OS choice (Windows)
   because the current system is slow and not comfortable to use.
4. Popular programs or alternative works (Steam, Blender, Krita, ShotCut, GIMP).
5. Not a hassle to install.
6. Still getting continuous support from the developer.
7. Fairly popular distro or distro it's based on. Because the road to Linux isn't always smooth, getting
   answer from a big community is always a good thing to have.
8. The layout is Windows-like, assuming people using this recommendation comes from Windows, so similar
   layout can help new users be comfortable.
{{% /notice %}}

**<h3>Now with all that stuffs out of the way, we can finally talk about the choice:</h3>**

1. [Linux Mint](https://linuxmint.com/)

   Linux Mint is considered to be the best just works distro, and the reason is it checks all the "The Consideration" list above. Linux Mint is a distro that is based on Ubuntu, a hugely popular and known distro that is based on Debian. There's 3 main flavors of Linux Mint or as we called them in the Linux community, Desktop Environment, to anyone that didn't understand the concept of DE, it's basically just how things setup and configured, there's 3 main Desktop Environment that Mint offer:

   - Cinnamon,
   the DE that is developed by the Linux Mint Developer, the layout is pretty similar to Windows and pretty nice to look at. This is the one that I hugely recommend to starting out if you're using Linux Mint mainly because it's also developed by the Mint developer (new features comes faster and better integrated to Mint).
   - MATE,
   the DE that is based on GNOME 2, while the layout is also similar to Windows, I personally can't say much because I haven't used it.
   - Xfce,
   the lightest of the 3, while also got the least amount of feature of the 3, doesn't offer that much customization.

   Ubuntu based also means that a lot of popular program that didn't exist in the official repository can be downloaded from the internet and be installed on Mint system (the one with .deb file format), also Mint didn't use any snap packages and let users install a snap packages by default, read Ubuntu part on why snap is not a good thing to have on a Linux system.

**<h3>Now with the things I don't recommend using, and why:</h3>**

1. [Debian](https://www.debian.org/)

    While Debian is by far the most popular distro because Ubuntu is Debian-based, the package in the repository is pretty old, for anyone that didn't understand what repository is, it's basically like a package store that is maintained by a specific distro, so it's a good choice for a server because it's stable and a server didn't need to have the latest and greatest update on a popular program like GIMP and Krita, but it's not a good distro for a regular usage.

2. [Ubuntu](https://ubuntu.com/)

    Ubuntu is the most popular and hugely advertised towards beginner, while it's sounds good on paper for a beginner to use Ubuntu, there's few things we need to understand why Ubuntu is not the best choice:
    - The layout isn't Windows-like.
    So while some user can get comfortable with their new OS layout, some can't say the same, so it's always a good idea to introduce a familiarity to new users.
    - Snap packages.
    To understand why this is not a good thing, we need to understand what snap packages is and what it does to a system. Snap is a package that is maintained by Canonical, the Ubuntu developer. It's a package that introduce sandbox to your system, similar to a cage that only run in that cage, while some say this might be a good idea to do as it's to prevent something goes horribly wrong to a system, it's not a good thing to do. Firstly, every application that run in that cage need a very specific dependency, so each snap package comes with the application, library (dependency), and metadata, so every snap application that runs, their own dependency also runs, this makes multiple of the same libraries running in the background and use unnecessary system resources. Some system reportedly starts 5-10 times slower than system that didn't have snap packages installed (extreme cases). There's also things that snap automatically updates their applications, this is a bad thing because Linux is never forcing update to their users.

3. [Fedora](https://getfedora.org/)

    Fedora is a fairly popular distro choice but it's not a good starting distro, in term of stability, Fedora is between Debian and Arch based distro, offers more bleeding edge application than Debian based distro but still more stable than Arch. It's a good choice for an intermediate user because while it doesn't have Windows-like layout, some people enjoy using it as a productivity OS because the layout is really similar to MacOS. Fedora also have RPM Fusion repository, a repo that offers a lot of package that didn't exist in the official repo.

4. [Manjaro](https://manjaro.org/)

    Manjaro is a distro that is based on Arch, while Arch is the most unstable OS compared to Fedora and Debian based OS, Manjaro repo that is maintained by the Manjaro developer sometimes is even more unstable than the official Arch repo because there's a lot of changes that's being made to fit Manjaro changes from the official Arch packages. It's simply not a good choice as a distro in general.

5. [EndeavourOS](https://endeavouros.com/)

    EndeavourOS is also a distro that is based on Arch, it's marginally better than Manjaro because it doesn't make a lot of changes from basic Arch installation, and has the easiest installation process than other similar OS. EndeavourOS repo uses official Arch repo so while it's still not as stable as Debian and Fedora based distro, it's still considerably better than Manjaro. It's a good choice for an intermediate and expert user because there's a repo that is called AUR (Arch User Repository), it's basically an unofficial repo for Arch that is maintained by the community and has a lot of program that didn't exist in the official repo, more than RPM Fusion in Fedora. User still needs to be careful with this AUR packages, while considering the malicious aspect of a certain application, there's a lot of program that breaks a system stability if they didn't be very careful.

**<h3>So what distro a complete beginner need to use?</h3>**

Honestly, this comes down to their personal preferences, but from my personal experiences, I have a lot of good things that I can personally say about Linux Mint, it doesn't really use that much resources compared to Windows, stable enough for regular usage, Ubuntu-based OS, and as [Mental Outlaw](https://www.youtube.com/c/MentalOutlaw) said:
**<h5>"Linux Mint is like the Honda Civic of the OS world, it just works and never breaks down."</h5>**