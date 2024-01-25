+++
title = 'External Monitor Troubles'
date = 2024-01-24T16:14:07+01:00
tags = ["linux"]
+++

Today I wanted to connect an external monitor to my Linux laptop. (I use Arch, btw.)  
I added the necessary configuration to my hyprland.config and plugged in the HDMI cable (it's an old monitor),
the screen woke up and the backlight went on, but it stayed black.  
Nothing happened on screen, even though Hyprland obviously recognized the monitor and sent one of my workspaces there.

Something very strange was happening. 

I did a lot of searching and found a lot of different tips and proposed solutions, but most of them seemed to have
something to do with using Nvidia drivers, and I only have an Intel GPU on this laptop, the Thinkpad X1 Carbon (gen 7).

After updating some graphics drivers and trying a lot of different config, I found the solution.

Someone else had experienced the same thing, and the way to fix it was too incredible to believe at first:  
remove the power cable from the monitor and put it back in ...

Being out of ideas, I tried it even though I had zero hopes of it actually working, but it did.

So, if you're having trouble with an external display on Wayland/Hyprland and use an onboard Intel graphics card:

_Have you tried turning it off and on again?_
