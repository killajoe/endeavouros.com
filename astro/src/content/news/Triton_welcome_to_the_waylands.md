---
title: "Triton is available"
description: "Triton has arrived: a complete transition to Wayland in the Live ISO, addition of Sway and COSMIC, removal of legacy desktops, refined NVIDIA support, and keymap/translation fixes."
date: 2026-10-20
author: "Bryanpwo"
hero: "../../assets/news/2026/Triton.png"
heroAlt: "Triton"
heroDecorative: true
---

After a prolonged development cycle and navigating through the technical challenges we mentioned during our Titan Nova update, we are thrilled to announce that our major release, Triton, is finally here!
The biggest milestone with Triton is the complete transition to Wayland in the Live environment. Driven by upcoming changes in the Plasma desktop ecosystem and modern display stack requirements, our development team has refactored the entire live session to run natively under Wayland. This marks a significant leap forward in ISO performance, multi-monitor handling, and overall security.

## The Triton release

As always, a quick reminder:

The changes described here affect new installs, our Calamares installer, the offline installer, and the Live environment on the ISO only. Existing installations do not need to be reinstalled; if you update your system regularly, you are already up to date.

Triton’s live environment and offline installer ship with up-to-date core packages, updated graphics stacks, and our latest installer refinements.

## Key Changes & New Features

* Wayland Native Live Session: The Live ISO now boots and operates fully under Wayland, ensuring smooth rendering and proper scaling out-of-the-box on modern hardware.

* Sway & COSMIC Desktop Options: We are expanding our desktop offerings! Users can now select and install both the Sway window manager setup and the COSMIC desktop environment directly through the installer options.

* Legacy Desktops Removed: To streamline maintenance and focus on reliable, modern desktop experiences, deprecated legacy desktop choices have been officially removed from the install options. Budgie is still off the rack too, but we hope to add it back soon.

* Refined NVIDIA Implementation: We have overhauled how NVIDIA driver handling and module loading operate during both the Live session boot and the target system installation, providing better compatibility across proprietary and open kernel modules.

## Installer & Module Bug Fixes

* Keymap Configuration: The persistent keyboard setup issues previously mitigated in Titan Nova have been fully resolved with a permanent, structural fix in Calamares.

* User Module Localization: Resolved an issue within the Calamares user module where localized strings and translations were not being applied correctly during the account setup phase.

* Overall Process Refinement: Cleaned up script execution order, post-install cleanup tasks, and package group handling across the entire installation flow.


Last but not least, a huge thank you to our entire community testing team for their relentless bug hunting during the Wayland transition, and to everyone seeding our ISO releases!

You can download and/or seed the Torrent or Magnet files over here.
