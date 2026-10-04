# Started working on schematics

I started schematics for my badge, did some research on what module to use, inspirations etc.
Decided on a XIAO esp 32 c3 (idk how to make devboard:( ), a 2.9inch e ink display, WS812b LED's and NFC.
I had to figure out how to properly tune the nfc as ive never worked with it before, and also had to make the charging and management circuit for the battery from scratch for portability.

<img width="1470" height="956" alt="image" src="https://github.com/user-attachments/assets/5958f132-d0d6-40ea-b46a-e95b2844742e" />

**Total time spent: 2 - 3hrs **

# Finished Schematics and PCB (kinda)

Finished the schematics, after all the random errors, i suck at matching the right capacitors, resistors and all the tiny misc components for some reason, had to find footprints for all these components as Kicad refuses to do make our life easy. I had to figure out where to place all these tiny components on the pcb to ensure the routing isnt messed up, im still fairly new to pcb design as im more used to wiring everything, so not having the stuff in front of you still feels weird. And yea I messed up the routing once, so had to redo from the start. Routing took quite some time as i had to keep moving stuff around, but finally managed to make something thats functional. I still dont know what to put for the silkscreen, i went through lots of images and graphics but no matter what everything still looks really bad. Need to make a proper 3d model next and make the pcb look presentable.

<img width="1470" height="956" alt="image" src="https://github.com/user-attachments/assets/3c5cc2a9-4b0f-460a-808f-63ce19fbf683" />
<img width="1326" height="828" alt="image" src="https://github.com/user-attachments/assets/b58a8d3a-0650-46a9-82fa-2939b699d280" />


**Total time spent: 10+hrs (i literally did not get up from my desk after returning from school 😭) **

# Redid a whole bunch of stuff

After i finished the initial pcb with all the complicated ciruitry, like built in charging and a built in boost module, uploading it to jlc pcb made me realise how over budget i was due to the economic PCBA costs, so i had to simplify a great majority of the stuff and had to make a lot of the components hand solderable.
This time i went with bigger ws2812 LED's and decided to use external breakout boards for the boost and charging as jlc's parts were too expensive. I also made the edge cut a rectangle instead of the previous one which i liked from Kai's design as he said i can't use it 😭.

<img width="1470" height="956" alt="image" src="https://github.com/user-attachments/assets/43a7adb1-dbdd-481c-8ac8-b9916c72263d" />


**Total time spent: 3 - 4hrs **


# Redid more stuff

After i uploaded the design to JLC pcb, it was still a bit over budget, so now i had to replace all tiny resistors, capacitors etc with ones that were available locally and made them hand solderable too, except the nfc circuitry ofc. I also removed a lot of extra stuff, and in the end made only one side of the pcb PCBA, this helped as the cost finally came to about 40 to 50$. So the entire front of the PCB will be hand soldered by be and will use pretty generic and easily available components for it.

**Total time spent: 2 - 3hrs **


# Final touches and silkscreen

I came to the hardest part according to me so far. That is to decide what goes on the silkscreen. In the end after lots of random svg site searches etc, i decided on a kind of spider man theme for the back, and a pretty simple design for the front to keep things professional. I overcomplicated this way too much, and shouldve gone simpler from the first time only as ive not really made a lot of boards, but guess i learnt something that i wont repeat again.

<img width="1470" height="956" alt="image" src="https://github.com/user-attachments/assets/c6461358-3c4b-4f2f-a1a4-57b990154d48" />
<img width="1470" height="956" alt="image" src="https://github.com/user-attachments/assets/40a9ebed-1f8a-47f6-9c29-50f48791732c" />
<img width="1470" height="956" alt="image" src="https://github.com/user-attachments/assets/41f808aa-632b-44a2-8c7a-ccf18e740deb" />


**Total time spent: 2 - 3hrs **

