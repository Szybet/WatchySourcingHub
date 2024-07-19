### Before looking at the rest of this repo

SQFMI, the original creator of the watchy started shipping again, further more it's in stock so no more waiting. Well now, the reputation of SQFMI is not that great because of the sooo long shipping delays in the past (see the "Whyyyy" section below) and the rough release of the watchy 3.0 and it's design (Situation explained [here](https://github.com/Szybet/WatchySourcingHub/blob/main/Watchy%203.0%20review.md)) but I still think it's better to buy from him, for those reasons:

- It's always better to support the original creator who open sourced his work (or will eventually) than a copy who "borrowed" the design and didn't contributed much back
- You buying from mouser / any shop that is not aliexpress really will be a better experience for you - warranty, faster shipping, safer shipping, better packaging, better more quality components (battery, case & strap). Do I really need to explain that aliexpress is the last resort for buying stuff?
- The V3 has some cool features (mainly for me bigger flash) <sub>and some flaws</sub> If you can get either one of them, then get the newer version (as software support will slowly shift to the newer one)
- Communication recently improved, I hope I will not need to remove this statement from here

Also SQFMI about the clones:

"it has become a problem for us to support and address issues. Many users have reached out to us on receiving faulty hardware, broken parts, case not fitting, or other firmware issues, and only upon further discussion did we realize they have purchased a clone"

With that in mind, here is the link: https://watchy.sqfmi.com/ as always decide for yourself

And for the people who bought a watchy from aliexpress and then went to SQFMI to complain... what the **** ** ***** **** ***. No further comment.

The rest of the repo is about those alternative clones, There is also infortmation about communities, firmwares, 3D printed case and more which also concern the watchy v3

<sub>The USB-C 1.0 watchy is now depracated. To find info about it, look into watchy-usbc folder. The rest of this repo contains info about the replacement of it. the USB-C 2.0 version that is currently sold</sub>

# WatchySourcingHub
A clone of the Watchy, sold on various platforms from probably various sellers, but the manufacturer is probably the same.
- Aliexpress seller, the first one that appeared, the most trusted in my opinion (The most people buught from him)
  - Here is their Github repo for the "E-watch". There is nothing really there ;) - https://github.com/01Space/E-Watch
  - Their aliexpress store: https://pl.aliexpress.com/store/912632218
  - And the watchy on their store: https://pl.aliexpress.com/item/1005005209927318.html (It's the original manufacturer, others on Ali probably resell his watchy)
- Banggood
  - No one yet bought from him
  - [A horrible long link](https://usa.banggood.com/Watchy-ESP32-Open-Source-E-Watch-WiFi-bluetooth-Programmable-Watch-E-Paper-Watch-with-Open-Source-Hardware-and-Software-p-2004157.html?af_force_deeplink=true&tags=direct&source_caller=api&pid=direct&is_retargeting=true&shortlink=ecydp3md&af_ad=-&deep_link_value=https%3A%2F%2Fm.banggood.com%2FWatchy-ESP32-Open-Source-E-Watch-WiFi-bluetooth-Programmable-Watch-E-Paper-Watch-with-Open-Source-Hardware-and-Software-p-2004157.html%3Futm_source%3Ddirect%26utm_medium%3Dnone%26utm_content%3D-%26utm_campaign%3Dnone_pps_copy&af_channel=none&c=-&cur_warehouse=CN)
- Shopee
  - No one bought it too
  - [A horrible link, I can't change the language from vietnamese](https://shopee.vn/product/936949083/25811373902?d_id=605f0&uls_trackid=4vh4705i000v)

<p float="left" align="middle">
  <img src="/images/imgc1.jpg" width="300" height="400"/>
  <img src="/images/imgc2.jpg" width="300" height="400"/>
  <img src="/images/imgc3.jpg" width="300" height="400"/>
  <img src="/images/imgc4.jpg" width="300" height="400"/>
  <img src="/images/imgc5.jpg" width="300" height="400"/>
</p>

# Why?...
A few thousand people ordered on crowdfund and now their shippind date is shifting and shifting again and again. On mouser 1.5k people are waiting. Pi hut doesn't ship anywhere really ( Like couldn't you just don't ship the battery, we could buy it locally... ). Obviously I don't blame anyone. I understand the problems with supply chains in the recent years. But the situation is and was bad, just bad.

This statement was true in october 2023 and is still true in january 2024🥴

I wasn't able to get a original watchy as I was hunting for it from 2021 so...

**That was a light version of this whole situation. [Here](https://szybet.github.io/WatchySourcingHub/SQFMI-controversy-conversation/Watchy%20-%20Text%20Channels%20-%20general%20[804832183516266498]%20(after%202024-05-11).html) is a whole conversation about it.** 

This conversation was heated up. Later we concluded that SQFMI is not a scammer because he didn't run away with the money and after 2 years he cleared up the situation a bit, but the pain remains.

SQFMI about the whole situation:

![image](https://github.com/Szybet/WatchySourcingHub/assets/53944559/1379433e-449f-464c-9b52-875d11787fc6)

**The rest of the repo describes the aliexpress micro USB 2.0 watchy. Currently the seller sells USBC 2.0 Watchy, but I quess they are the same, as only the USB port changed**

# Further notes that you should know before you buy:
**Some of those issues below, are related to the design of the 2.0 version of the Watchy. Don't contact the aliexpress seller for no reason, If you have any questions, ask me through contact below.**
- ~~The schematic is 1:1 with the oryginal watchy (Now it's the 2.0 version). The PCB too because **it is compatible** with official SQFMI metal cases. That's why this repo no longer contains schematics for this version. They are the same as the SQFMI ones~~ Well now there is a USBC 2.0 version. I quess, logically it's not compabitable with SQFMI cases
- In the previous USB-C version, the components were not original. Maybe they were recycled or idk. In the current version I didn't checked, but expect the same thing `¯\_(ツ)_/¯`
- The screen is already glued in and has a foil that can be taken off. cool.
- As you can see in the images - It comes in a mini pcb based case that it's screwed in. Even with the screw holes, the PCB is solid. You can use that case or 3D print one like I did.
- It also comes with a very good looking 200mAh battery and a strap. cool. But the capacity of the battery may very, you might need to replace it sooner than you expect.
- The buttons from their design are very fragile, some of them are more clicky then others. They may come off after some time. Replacements cost a few cents but the soldering is tricky
- **🇩🇪🇩🇪🇩🇪 GERMANS LOOK HERE 🇩🇪🇩🇪🇩🇪 DEUTSCHLAND 🇩🇪🇩🇪🇩🇪** This seller doesn't ship to germany. But there are others that ship (Very fast shipping it was) to germany but have at a higher price, just search for them **🇩🇪🇩🇪🇩🇪 GERMANS LOOK HERE 🇩🇪🇩🇪🇩🇪 DEUTSCHLAND 🇩🇪🇩🇪🇩🇪** <sub>If I see one more guy complaining they don't ship to germany I will not hesitate to steal your Bratwurst</sub>
- In my experience, the screen ghosts in extreme temperatures - arround 0 or 30 degrees C it's bad - maybe I'm not sure about the cold part. But, from what I had heard recently the seller started using a newer generation of screens. (SQFMI says it's "the faster" screen, not really ). The only difference is that it blinks less in full refreshes, still cool. Some users suggested that it withstands extreme temperatures better, but the documentation for those screens doesn't support this claim.

# Things to know when coding the watch
- **Use platformio. Don't use arduino IDE. 90% of issues on the Watchy server are solved by using platformio. Not only that, arduino ide compiling is slower.**
- The 2.0 version doesn't work without a battery - the RTC reading are corrupted. Just connect the battery.
  - The RTC is drifting, **that's normal for the RTC by design.** You just need to adjust for that, there are automated libraries to do that.
  - When USB is connected the RTC drifts in a non linear way - that's horrible, my solution to that is connect to wifi when charging and sync NTP every few minutes

# For people who are not tech savvy
Don't worry! You can either learn, ask for help in the communities I listed below or buy me a big coffe for premium guidanance or even to create your personal firmware / add some features to existing ones (I could also propably 3D print you a case...) Contact below :)

# Some firmwares for the watchy that I like
### Firmwares that are "the new generation?"

Using other firmwares than these 4 will get you problems (most probably), these are the newest written ones

- https://github.com/Michal-Szczepaniak/TinyWatchy
- https://github.com/Szybet/InkWatchy - Mine, many unique features, the most configurable one
- https://github.com/GuruSR/Watchy_GSR - Has many features that you would expect from a smart watch, but the codebase... motivated me to write mine
- maybe this one too, not sure: https://github.com/NiklasNeugebauer/minty-os
### Other firmwares
- https://github.com/Prokuon/watchy-starfield - Looks awesome
- https://github.com/OregonJunco/Watchytchi
### Other other things
- https://github.com/Szybet/watchy-scom - For lazy people

# Some 3D printed cases
- https://www.printables.com/model/745711-watchy-invader-remix - Reuben designed it from the Watchy discord server, thanks! Some users reported that it works with USB-C and micro usb. This case is really thick
- https://www.printables.com/model/664145-watchy-10-usb-c-case-with-a-bigger-battery - By me, Szybet - for the Watchy 1.0 USB-C. You would need to adjust it for your new 2.0 version
- https://www.printables.com/model/906093-watchy-flat-case - By me too, the flattest watchy, for the micro usb version
- https://www.printables.com/model/503282-watchy-case-minty - Minty case by minty
- https://www.printables.com/model/906117-watchy-kit-case - By me, slimmer minty version
- https://makerworld.com/en/models/498091 - Slimmer stock version from [this](https://www.reddit.com/r/watchy/comments/1e75bzy/best_3d_printable_cases/) reddit post

# FAQ
Q: Can I trust the seller? Won't they scam me?

A: ~~**I do not know.** Now I'm talking about the one seller I'm linking. I was talking to someone who knows what a schematic is ( That's rare too ). He was a human too so I'm happy with the service. Delivered without issues, device works without issues too. Many other people were very happy with their watch. They praised the seller for communication that it was better than SQFMI. When they changed to the 2.0 version from the USB-C one, the communication and tranfer was clear. No one was dissatisfied.~~ At this point so many people bought the device that there is no risk basically. But well, the crossed out text still is true

# Contact
for any questions, you can create a github issue here or catch me on:
- Quill OS [Matrix space](https://matrix.to/#/#inkbox-os-project:matrix.org) or [Discord server](https://discord.com/invite/uSWtWbY23m)
- Because of the lack of moderation on the official watchy server, while also banning random people without giving any reason I don't feel comfortable with advertising it here, We created an alternative, a community drived <a href="https://discord.gg/6PUmRXZRGD">discord server: *atchy community</a>
