# E-Watch-FOSS
A clone of the Watchy with USB-C, sold mostly on aliexpress. Now thanks to the kindness of the creator and my relentless requests - it's open source

I have received the schematics and the permission to share it ( I know it's a open source fork, but I'm kind anyway ) from the oryginal creator:
- Here is their Github repo for the "E-watch". There is nothing really there ;) - https://github.com/01Space/E-Watch
- Their aliexpress store: https://pl.aliexpress.com/store/912632218
- And the watchy on their store: https://pl.aliexpress.com/item/1005005209927318.html ( It has the least ammount of description among other stores, but it's the original creator ;o )

# Why?...
A few thousand people ordered on crowdfund and now their shippind date is shifting and shifting again and again. On mouser 1.5k people are waiting. Pi hut doesn't ship anywhere really ( Like couldn't you just don't ship the battery, we could buy it locally... ). Obviously I don't blame anyone. I understand the problems with supply chains in the recent years. But it's bad as you see to get it. That's why i ~~harrased ;)~~ asked all sellers of this clone for half a month to release the schematics, until I found the original creator. Is it moral to use this clone? To my quick google search, yes until the schematic is shared + taking in mind all the issues in actually getting the oryginal watchy...

# Further notes that you should know before you buy:
- The schematic is 1:1 with the oryginal watchy, the creator said that the only diffrence is usb-c. We have the board view so it's not a problem
- The components are not original but they work without issues. Looking for datasheets took a while but they are here: https://szybet.github.io/E-Watch-FOSS/hardware/watchy_usbc_chips_and_datasheets.html
- It has a blue charging LED, cool
- The screen is glued in. It seems that the screen could be detached with a heat gun - I haven't tried, won't risk it
- The buttons are horrible to press without the case and they all sound and behave diffrently. With a case where the click area is bigger it's fine
- No confirmation yet if it would fit inside original watchy cases. Grab the dxf file and compare dimensions I quess
- GSR firmware works fine so I think it's fully compatible. Here is a list of firmwares I like:
  -  https://github.com/GuruSR/Watchy_GSR
  -  https://github.com/Szybet/Watchy_Hard_Firmware - Mine ;p
  -  https://github.com/Prokuon/watchy-starfield - Looks awesome
  -  And here are some I didn't tested but people sended over when I asked on the discord server
    - https://github.com/OregonJunco/Watchytchi
    - https://github.com/NiklasNeugebauer/minty-os
