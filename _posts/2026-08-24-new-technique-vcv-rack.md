---
layout: "article"
title: "New technique of playing cut-up harsh noise on VCV Rack"
heading: "New technique of playing cut-up harsh noise on VCV Rack"
date: "2026-08-24"
lang: "en"
permalink: "/articles/2026-08-24-new-technique-vcv-rack/"
---
Recently I found an interesting technique for making harsh noise (cut-up noise) in VCV Rack.

Step 1: create a patch.
Step 2: separate modules into 2 groups based on if they're safe to bypass (e.g. distortion, effect) or not (e.g. audio device).
Step 3: when the patch is making beautiful noise, randomly pressing ctrl+e while hovering the mouse over any modules (avoid important modules like audio device), to bypass/restore them. The absence of any module(s) could make the noise sounds completely different.
Advanced techniques:
Remember bypassing which modules would create what kind of noise, and reproduce it when needed.
Holding ctrl+e, move the cursor across the modules and toggling their bypass states. you won't be able to predict the bypass states of the modules you just hovered on.
Use ctrl+r sometimes to make the noise even more unpredictable, it might create gorgeous noise that you didn't expect, but also a bit risky because randomnizing some modules might make it sounds bad or completely silent (but you can use ctrl+z to undo or randomnize again anyway so who cares)

there are usually many modules in a patch, and each modules have at least 2 states of working/bypassed, so there would be a huge amount of different status of the system. this technique actually make VCV Rack itself works like a switcher. although it seems much more complex, but the performer can still precisely control each modules/groups, so it does not lack the controllability & predictability of traditional switchers.
