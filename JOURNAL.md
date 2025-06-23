---
title: "glide 60"
author: "andre-cmd-rgb"
description: "A custom made, semi low profile 60% wireless keyboard"
created_at: "2025-06-23"
---

# June 23th: Day One!!!

Today i created the repo, made the pull request and started thinking about all the components i will need to build the keyboard, effectively making a first and temporary BOM.

I chose the Choc Louder Keycaps (https://www.printables.com/model/1066117-choc-louder-keycaps-choc-and-mx-spacing) because they looked super good and would also be super cheap to make; they are 18x18x5.4mm. For testing they will be printed in white PLA. Btw my printer is a creality CR10-S i had it for a while now and i have to recalibrate it every time i print😭.

so now i have this:
- case idea( a white case in PLA thinking about the marble pla from bambu(https://eu.store.bambulab.com/products/pla-marble?id=43964050964699))
- keycaps (withe and special keys coloured)
- pcb idea (thinking about a 19x19mm grid because my keycaps are 18x18mm so i have 1mm between each key.)(pcb will be black because it looks soo good)

i need some swiches and obviously i can buy the Kailh Low Profile Choc Switches (https://splitkb.com/products/kailh-low-profile-choc-switches) but tbh i really don't want to deal with their mesurments and stuff so i was thinking about making my own switches but we'll see about that.

While i'm writing this essay my poor printer is printing an example of how the keycap will look like.
Ok here it is, NOT GREAT:

![bruh](https://github.com/Andre-cmd-rgb/glide-60/blob/master/Pictures/fail.png)

anyways they should look like this:

![lol](https://github.com/Andre-cmd-rgb/glide-60/blob/master/Pictures/keycaps.png)

In the meantime i will try to get more info about the pcb and parts a i need.
I am looking at the XIAO ESP32 C3 because it has ble and should be pretty cheap and small.
Bruh so i just realised it has not enough pins so i'm going to look for an alternative😭.

I will be writing a custom firmware in micropython using this lib(https://github.com/Heerkog/MicroPythonBLEHID), hoping that it works.

Now i got bored so i swiched to looking at keycaps material and found this nice White Matte pla from bambu:
https://eu.store.bambulab.com/it/products/pla-matte?id=42996742586587
Also for special keys i would use two different colours(first is blue second orange, always matte):
https://eu.store.bambulab.com/it/products/pla-matte?id=42996751073499
https://eu.store.bambulab.com/it/products/pla-matte?id=42996742652123

I Know this is getting expensive but tbh i want this keyboard to be super easy to recreate and easly fixable, and with 3d printed parts you don't have to worry if parts go out of stock or pay for shipping.

**Total time spent: 2h**
