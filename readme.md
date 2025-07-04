This is the CircuitCyboard; A 153% keyboard made for video editors or anyone who is completely insane. I decided to design this board when I started editing videos for my robotics team. It took me approximately 47 hours to complete due to having to essentially complete two keyboards to complete a single set. 

HOW LONG DID THIS KEYBOARD TAKE TO DESIGN?
This keyboard took about 47 hours to design due to being on an FTC team that made it to the World Championship along with the rest of my school and what other "life" I have.

Here's one of my mid-project updates:

March 4, 2025
It's been a while since I have really had enough time to make some progress on my HackBoard. I was able to find some time this afternoon to nearly finish the project. Here's a little overview of where I'm at, but first for those who didn't see my original plans a few months ago: I do a decent amount of video editing for my FTC team and some personal projects. Back in October during HackpadV1, I created a little 3x3 macropad with 2 rotary encoders. It has sped up my editing by probably 35%. I really like efficiency, so I started looking into the BlackMagicDesign editor keyboard.

![image](https://github.com/user-attachments/assets/f7811efe-43c5-4441-90d0-d2a684436196)

Unfortunately, that keyboard costs $595. That's about $535 out of my price range on a normal month, and this year about $575 out of my range. When Alex announced HackpadV2 I knew I wanted to attempt to design my own version. But why stop designing when I have the exact same hardware design as BlackMagicDesign? Why not create my own unique one of a kind piece?
Introducing The CircuitCyboard: @CircuitCyborg's very own editing keyboard. It is a one of a kind piece that just so happens to resemble the Blackmagicdesign Editor Keyboard if it was a split keyboard. Why is it split you may ask? Because there are too many rows and columns for a single Raspberry Pi (Or in this case, a single Orpheus Pico). So in order to get two MCU's, Alex's requirement was that I make it a split keyboard. Now on to the update: The PCB is nearly finished. I need to add a few decorations to the silkscreen and make sure all of the stabilizer mounts will actually work (Who am I kidding, I'm not going to do that), then I think both PCB's will be ready to export. Both Cases are complete I think. I need to go through and make sure everything is 100% correctly done and finished. Today I decided I wanted to try and do the firmware in POG so that I can more easily change keys throughout the boards use. So I think firmware is complete (Enough until I get the hardware) and ready to be dropped onto the MCU's. Unfortunately, I don't believe the grants will be enough to cover everything so I may have to add some of my own funds into it. I guess that means I have to wait another month before I can buy that mic. Oh Well. It's worth it.

Here is what the original design looked like:

![image](https://github.com/user-attachments/assets/b46773fc-0c9d-4071-86e6-14f0601286d3)
![image](https://github.com/user-attachments/assets/360297f8-e9a7-49f5-bab6-59e192d0c877)
![image](https://github.com/user-attachments/assets/4988ab8b-f849-49e7-b123-b960509d991b)
![image](https://github.com/user-attachments/assets/8a1756d9-0ac4-4bd1-84a9-3e8521226acb)
![image](https://github.com/user-attachments/assets/edae4503-7edd-43f4-9c8e-30813760bb24)


Here is another update now that I am getting ready to submit:

June 2, 2025
It's been another 3 months since my last update. I have almost completely redone the whole keyboard. The only things that are still the same are the base keys and their positions, and the basic idea of having a mega split using two Orpheus Picos. Since the last update I decided that instead of using a completely 3D Printed case, I wanted an acrylic top. I then redesigned the case after redesigning the PCB so that the MCU on the left half was vertical instead of horizontal so that the chord would plug in to the top instead of the side. I then added three more rotary encoders to the left half. Next I designed the case to have an acrylic top. After some thought, I am considering cutting the base of the case out of wood after I confirm it fits with a 3D Printed version. Assuming it does, I will find a nice piece of wood to cut it out of and use my robotics team's CNC router to cut it out. Next I started sourcing parts for my board. At this point I still haven't ordered parts yet, but I am trying my best to not order any parts directly from AliExpress because I do not trust that site or any of its sibling sites. Do to this, parts may cost a little more for me, but occasionally, I can find better quality parts as well from Amazon over what can be found at AliExpress. I think that's all for this update. Signing off for now, Circuitcyborg.

Here is what the final design looks like:

![Screenshot 2025-06-08 222219](https://github.com/user-attachments/assets/0ae69ea6-9b46-4161-81f8-ff17e50ab264)
![Screenshot 2025-06-08 222453](https://github.com/user-attachments/assets/4f923500-1848-4de1-bc8f-d5b27e6c8a19)
![Screenshot 2025-06-08 222414](https://github.com/user-attachments/assets/280843d4-057b-4a95-91af-f6d8b7619b76)


I have now spent the last few days putting together all of the files and getting pricing down and finalizing part selections for the BOM and to create my Repo. Next up is the info for the firmware.

Firmware was kept simple for this because although editing the firmware on my macropad has been relatively simple, I want an even simpler way to edit the firmware. Introducing POG, a firmware editor/writer for keyboards based off of KMK. I have not tested it yet, but the idea is that anyone can install this firmware on it, then install POG and easily be able to edit the firmware on it. I'll update once I have the time to test this theory.
