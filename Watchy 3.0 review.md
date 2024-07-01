## Early review of the Watchy 3.0 - It's worse than bad. It's unacceptable.

First, a bit of introduction. Watchy is an open source eink watch, with open hardware and software. I'm a hobby [developer](https://github.com/Szybet/InkWatchy) for that device and a member of the community of it (I'm not associated with SQFMI in any way). I have been maintaining a [list of resellers](https://github.com/Szybet/WatchySourcingHub) because SQFMI delayed the 3.0 version for almost 2 years saying it "Will be shipping next month"... Well that situation was pretty much cleared out, SQFMI officially allowed those resellers to "resell". Well I'm not here about that, more information about it is in the repo above.

So the 3.0 version of the Watchy finally starts shipping to customers. I have been helping the first guy that received it to use it. Here is the story. His watch was not responding because he wanted to connect it to wifi. He tried to follow the official docs to troubleshoot it. And here is the second problem (apart from the endless delaying of shipping it). The docs are outdated at least 3 years, they don't work. They don't even work for the 2.0 watchy. That's not a problem I said, let's get the latest code for it... There is nothing, nothing is open sourced about it yet. We wanted to reflash the firmware, there is nothing. We wanted to look at the schematic to add support to my firmware, there is nothing... Customers have been waiting for 2 years and when the product arrives there is nothing what was promised. Let me say that again. Nothing.

Okay, well let's try to restore the firmware that's on there, I suggested he restarts it with esptool but he went with disconnecting the battery. Here is the reason why I'm writing the post, this was the final straw. There are small SMD components next to the battery port, Obviously when trying to disconnect it they broke off, the watchy is broken.  

https://github.com/Szybet/WatchySourcingHub/blob/main/images/3.0/20240629_223535.png

https://github.com/Szybet/WatchySourcingHub/blob/main/images/3.0/20240629_223446.png

This is a fatal design.

Do you know the best thing? In the 2.0 version there was empty space instead, so they thought of it then, not now.

https://github.com/Szybet/WatchySourcingHub/blob/main/images/3.0/2.0connector.png

For people who will say they needed to put it there because of lack of space, um no, the PCB is pretty empty in my standards of PCB designing 

https://github.com/Szybet/WatchySourcingHub/blob/main/images/3.0/pcb.png

I have only noticed it now, but they shipped that guy one button with the wrong size...

Further more, the 3.0 improvements are laughable compared to 2.0, with the increase in price. It's 100$ while the 2.0 is 50$ (Well I know the 2.0 currently is a reseller from china), I hope. I really do hope that the case costed so much, as for the improvements:
- CPU is more modern, it uses less components on the PCB. So in theory the thing should be cheaper. No USB-UART IC, no RTC IC. Well it will be a bit more power efficient for sure
- Buttons look more solid but it's still the same flawed design. The previous ones broke off too often.
- Screen is said to be a modern version. It's said it's faster, well no - Only full screen refreshes are, but my eye can't see a difference.
- They added a TVS protection diode on the USB traces. Yay, at least that

There may be more, but there is no spec or anything, so just my eye is guessing.

And to other issues with SQFMI:
- There has been almost no communication with the community, only a few times on discord (In 2 years!). I'm not even sure all people know who ordered that they will receive the 3.0 version instead of the 2.0. It's supposed to be better, but not really
- Recently people started getting banned from the discord server (without explanations), the watchy subreddit is now restricted, I can't post this post there. I could a month ago (Update: Reddit closed the subreddit, I contacted the mod and he reopened it... classic reddit)
- The software SQFMI provides is horribly basic, that's not an issue because I and others similar to me exist who write third party software, but for the 3.0 we can't. Also the software he wrote made the device not responding in the first place...

And that's the basics, I didn't even go deeper in the problems I described.

With all of that in mind, even if some issues that will be resolved in the future, others can't. Do you support such behavior? I don't, I will vote with my wallet and just order the 2.0 watchy from aliexpress, It's fine enough.

Why am I writing this? I just can't handle it anymore, I wanted the watchy to succeed, to be an awesome device. That's why I spend hundreds of hours to write a fully custom firmware for it, to help people in the community with their tech problems (mostly solved by not using the SQFMI provided software) but SQFMI does everything wrong. I'm sick of it.

But the biggest problem, the summary of it all? No communication, zero, none. None... Almost all of those issues would be solved with a bit of communication, a tiny tiny bit...

## Response:

Response from a moderator from the Watchy discord, so not an official response.

GuruSR is a cool guy, knowledgable developer but his defending of SQFMI is sometimes too much. He is not associated with SQFMI really, but that's also is not a clear topic.
![image](https://github.com/Szybet/WatchySourcingHub/assets/53944559/d27f517e-cc73-4d78-85f0-9516f774a3c6)
