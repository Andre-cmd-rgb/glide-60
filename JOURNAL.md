---
title: "glide 60"
author: "andre-cmd-rgb"
description: "A custom made, semi low profile 60% wireless keyboard"
created_at: "2025-06-23"
---

# June 23th: Day One!!!

Today i created the repo, made the pull request and started thinking about all the components i will need to build the keyboard.

For my keyboard i chose the Choc Louder Keycaps (https://www.printables.com/model/1066117-choc-louder-keycaps-choc-and-mx-spacing) because they looked super good and would also be super cheap to make; they are 18x18x5.4mm. For testing they will be printed in white PLA.
(Btw my printer is a creality CR10-S i had it for a while now and i have to recalibrate it every time i print😭.)

This is what i'm working with:
- case idea (a white case in PLA thinking about the marble pla from bambu(https://eu.store.bambulab.com/products/pla-marble?id=43964050964699))
- keycaps (withe and special keys coloured)
- pcb idea (thinking about a 19x19mm grid because my keycaps are 18x18mm so i have 1mm between each key.)(pcb will be black because it looks soo good)

I need some swiches and obviously i can buy the Kailh Low Profile Choc Switches (https://splitkb.com/products/kailh-low-profile-choc-switches) but tbh i really don't want to deal with their mesurments and stuff so i was thinking about making my own switches but we'll see about that.

While I'm writing this essay, my poor printer is printing an example of how the keycap will look like.
Ok here it is, <strong>BUT IT'S NOT LOOKING GREAT</strong>:</p>

<div style="display: flex; gap: 20px; align-items: flex-start;">
  <div>
    <img src="/Pictures/Keycap Print Fail.png" style="width: 300px; height: 200px; object-fit: cover;">
    <p style="text-align: center;"><em>Poor Printer</em></p>
  </div>
  <div>
    <img src="/Pictures/keycaps.png" style="width: 300px; height: 200px; object-fit: cover;">
    <p style="text-align: center;"><em>Anyways they should look like this</em></p>
  </div>
</div>



Now i will try to get more info about the pcb and parts a i need.
I am looking at the XIAO ESP32 C3 because it has ble and should be pretty cheap and small.
(5 minute later update) Bruh so i just realised it has not enough pins so i'm going to look for an alternative😭.

I think will be writing a custom firmware in micropython using this lib(https://github.com/Heerkog/MicroPythonBLEHID), hoping that it works.

Now i got bored so i swiched to looking at keycaps material and found this nice White Matte pla from bambu:
https://eu.store.bambulab.com/it/products/pla-matte?id=42996742586587

Also for special keys i would use two different colours(first is blue second orange, always matte):
https://eu.store.bambulab.com/it/products/pla-matte?id=42996751073499
https://eu.store.bambulab.com/it/products/pla-matte?id=42996742652123


Not gonna lie a few hours have passed in wich i designed a fully custom flat keycap, and a swich.
Here are the pictures of the designs:
<div style="display: flex; gap: 10px; align-items: flex-start;">
  <div>
    <p><strong>Flat keycap</strong></p>
    <img src="/Pictures/Flat Keycap Design.png" style="width: 300px; height: 200px; object-fit: cover;">
    </div>
    <div>
    <p><strong>Swich</strong></p>
    <img src="/Pictures/Swich Design.png" style="width: 300px; height: 200px; object-fit: cover;">
  </div>
  <div>
    <p><strong>Swich Clicker</strong></p>
    <img src="/Pictures/Swich Clicker.png" style="width: 300px; height: 200px; object-fit: cover;">
  </div>
</div>

Last thing of the day i will try to print them and see how they turn out.

So after a lot of trial and error (and a few Marlin firmware compiles) i was able to get my custom swich and keycap design to print, but it was not great and i would probably need a resin printer to get my own swiches and keycaps.

<div style="display: flex; gap: 10px; align-items: flex-start;">
  <div>
    <p><strong>Front:</strong></p>
    <img src="/Pictures/front.jpeg" style="width: 300px; height: 200px; object-fit: cover;">
  </div>
  <div>
    <p><strong>Back:</strong></p>
    <img src="/Pictures/back.jpeg" style="width: 300px; height: 200px; object-fit: cover;">
  </div>
</div>


Soo it's the end of the day and i feel that i'm overcomplicating everything and tbh i think that to make my own custom switches i would need a a resin printer.


**Total time spent: 5h**


# June 24th: Starting from scratch(again😭)

So yesterday was a mess but i still need to start somewhere right??

Now here's a recap of what are the features i want for my keyboard:

- Custom 3d printed low profile case
- Kailh Choc Low Profile Switches
- Custom Pcb with bluetooth support (with rgb??)
- Low profile keycaps (with letters on them)

For the case design i will have to wait a bit because i still need to design the pcb so i have some mesurements. In any case i will be using the matte pla from Bambulab because i think it looks great and adds a bit of texture to just plain white pla.
