The USB-C watchy is now depracated. To find info about it, look into watchy-usbc folder. The rest of this repo contains info about the replacement of it.

# E-Watch-FOSS
A clone of the Watchy, sold on aliexpress.
- Here is their Github repo for the "E-watch". There is nothing really there ;) - https://github.com/01Space/E-Watch
- Their aliexpress store: https://pl.aliexpress.com/store/912632218
- And the watchy on their store: https://pl.aliexpress.com/item/1005005209927318.html (It's the original manufacturer)

<p float="left" align="middle">
  <img src="/images/img1.jpg" width="300" height="300"/>
  <img src="/images/img2.jpg" width="300" height="300"/>
  <img src="/images/img3.jpg" width="300" height="300"/>
  <img src="/images/img4.jpg" width="300" height="300"/>
  <img src="/images/img5.jpg" width="300" height="300"/>
  <img src="/images/img6.jpg" width="300" height="300"/>
</p>

# Why?...
A few thousand people ordered on crowdfund and now their shippind date is shifting and shifting again and again. On mouser 1.5k people are waiting. Pi hut doesn't ship anywhere really ( Like couldn't you just don't ship the battery, we could buy it locally... ). Obviously I don't blame anyone. I understand the problems with supply chains in the recent years. But it's bad as you see to get it. That's why i ~~harrased ;)~~ asked all sellers of this clone for half a month to release the schematics, until I found the original creator. Is it moral to use this clone? To my quick google search, yes until the schematic is shared + taking in mind all the issues in actually getting the oryginal watchy...

This statement was true in october 2023 and is still true in january 2024🥴

I wasn't able to get a original watchy as I was hunting for it from 2021 so...

# Further notes that you should know before you buy:
**All of those issues below, are related to the design of the 2.0 version of the Watchy. Don't contact the aliexpress seller for no reason, If you have any questions, ask me through contact below.**
- The schematic is 1:1 with the oryginal watchy (Now it's the 2.0 version). The PCB too because **it is compatible** with official SQFMI metal cases. That's why this repo no longer contains schematics for this version. They are the same as the SQFMI ones
- In the previous USB-C version, the components were not original. Maybe they were recycled or idk. In the current version I didn't checked `¯\_(ツ)_/¯`
- The screen is already glued in and has a foil that can be taken off. cool.
- As you can see in the images - It comes in a mini pcb based case that it's screwed in. Even with the screw holes, the PCB is solid. You can use that case or 3D print one like I did.
- It also comes with a very good looking 200mAh battery and a strap. cool.
- It's micro usb now, not USB-C how it was before ;)
- The buttons are now way better than in the previous version. More clicky but more noisy. Still better
- This seller doesn't ship to germany. But they are other that ship (Very fast shipping it was) to germany but have at a higher price
- It comes with a micro usb cable too!
- In my experience, the screen ghosts in extreme temperatures - arround 0 or 50 degree C it's bad - maybe I'm not sure about the cold part

# Things to know when coding the watch
- The 2.0 version doesn't work without a battery - the RTC reading are corrupted. Just connect the battery.
- The RTC is drifting, **that's normal for the RTC by design.** You just need to adjust for that, there are automated libraries to do that.

# For people who are not tech savvy
Don't worry! You can either learn, ask for help in the communities I listed below or buy me a big coffe for premium guidanance or even to create your personal firmware / add some features to existing ones (I could also propably 3D print you a case...) Contact below :)

# Some firmwares for the watchy that I like
### Firmwares that are "the new generation?"
<sub>Using other firmwares than these 4 will get you problems, these are the newest written ones, they use **platformio, *Don't use arduino IDE. Use only platformio.***</sub>
- https://github.com/Michal-Szczepaniak/TinyWatchy
- https://github.com/Szybet/InkWatchy - Mine ;p
- https://github.com/GuruSR/Watchy_GSR - Most advanced but the codebase... motivated me to write mine
- maybe this one too, not sure: https://github.com/NiklasNeugebauer/minty-os
### Other
- https://github.com/Prokuon/watchy-starfield - Looks awesome
- https://github.com/OregonJunco/Watchytchi

# 3D printed case
https://www.printables.com/model/745711-watchy-invader-remix
Reuben designed it from the Watchy discord server, thanks!

# FAQ
Q: Can I trust the seller? Won't they scam me?

A: **I do not know.** Now I'm talking about the one seller I'm linking. I was talking to someone who knows what a schematic is ( That's rare too ). He was a human too so I'm happy with the service. Delivered without issues, device works without issues too. Many other people were very happy with their watch. They praised the seller for communication that it was better than SQFMI. When they changed to the 2.0 version from the USB-C one, the communication and tranfer was clear. No one was dissatisfied.

# Contact
for any questions, you can create a github issue here or catch me on:
- Inkbox OS [Matrix space](https://matrix.to/#/#inkbox-os-project:matrix.org) or [Discord server](https://discord.com/invite/uSWtWbY23m)
- [Watchy discord community](https://discord.gg/ZXDegGV8E7)
