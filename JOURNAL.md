---
title: "Open RGBW Lightwall"
author: "Edward Hesketh"
description: "An open-source RGBW lightwall!"
created_at: "2025-06-01"
---

# Open RGBW Lightwall Journal

## 2025-06-01

I have always wanted to make a massive LED wall to display cool graphics effects, train information, and simmilar.

## 2025-06-11

I have some time to work on the lightwall after pausing my [soldery](https://github.com/headblockhead/soldery) hotplate project!

I started by looking at the cost of LEDs to determine the size of my array.

Sorting from low to high price on LCSC results, I chose the [TZ-5050S2RGB-5V-I4-H1](https://lcsc.com/product-detail/RGB-LEDs-Built-in-IC_TUOZHAN-TZ-5050S2RGB-5V-I4-H1_C26167850.html) RGB neopixel chip.

I decided on a 60 by 60 array of LEDs, made from 36 100x100mm boards, each having a 10x10 LED array. Using 100x100mm boards significantly decreases my JLCPCB order cost, as JLCPCB charges special lower prices to designs ≤ 100mm. I can order 4 10 board batches, coming out to $20 USD total for all 40 boards! (excluding shipping and taxes)

However, LED cost is quite high. 3,600 LEDs is a *LOT* of LEDs. For the cheapest LED on LSCS at discount, this comes out to $52.20 USD. More than a third of the budget. Also, the LEDs would be a backorder with a possibly high lead time, as there are only ~2k in stock currently.

In the meantime while I think about cost etc, I created a 10x10 LED schematic in KiCAD.

More coming soon.
