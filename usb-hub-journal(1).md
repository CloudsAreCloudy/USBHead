# USB Hub — Journal Export

- Exported at: 2026-06-30T06:09:54Z
- Project ID: 3706
- Entries: 24

## Entry 1
- ID: 8475
- Author: CloudsAreCloudy
- Created At: 2026-05-22T14:36:59Z

### Content

Followed the guided tutorial for the most part, still trying to figure out how this works, from my understanding the schematic is just for understanding while the PCB is where the actual things happen. I also tried to figure out if the parts in the guided project are available in India but then later on decided that I'm not smart enough for this right now so I'll just do that part later if needed (which I really doubt), but I'm done with a bunch of the schematic section now, I'd say like 80% of it!
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTg1MjUsInB1ciI6ImJsb2JfaWQifX0=--e2194699954901b4096014ae4ca778a709e68850/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/8f4fc8e3-f036-4213-a043-ca953b3632e5/video.mp4

## Entry 2
- ID: 8636
- Author: CloudsAreCloudy
- Created At: 2026-05-23T11:14:57Z

### Content

I got the rest of the schematics done, mainly just added the capacitors and things like that. also if things look different thats because I assumed the WEB app would auto save and didn't save so I had to redo the entire thing off camera again :sob:. at least now I think i know what capacitors do
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTg5MDMsInB1ciI6ImJsb2JfaWQifX0=--2341be4685e4c0dbd3f7ff9df6f8b75a23e671b1/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/19150574-2729-4842-b081-18050e585a72/video.mp4

## Entry 3
- ID: 8676
- Author: CloudsAreCloudy
- Created At: 2026-05-23T16:36:03Z

### Content

I finally finished up the schematic and started on the PCB version, started off by creating a rough outline and keeping the upstream USB C at the back and the downstream ports in the front, I want to glue this onto the back of my desk for easy access of USB ports and ESPECIALLY USB C ports because I only have 1 USB C port which is driving me insane. anyway I laid out all the resistors and capacitors close to the ports and the IC, I think I did everything properly but I'm not too confident.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTkwMjgsInB1ciI6ImJsb2JfaWQifX0=--faddd2ccd0622a48c32e9ad8db1c2085d136dffc/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/a7fab585-7f49-47b4-a5ab-28b67a472bd4/video.mp4

## Entry 4
- ID: 8839
- Author: CloudsAreCloudy
- Created At: 2026-05-24T10:46:19Z

### Content

Placed the capacitors and resistors near the USB ports, and started routing everything except the ground and the 5V, I've only added the copper area for both the 5V and the ground but haven't connected it together.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTk1MTYsInB1ciI6ImJsb2JfaWQifX0=--f0319efd6cbbd47a22158c2f8930c8f417a70ae9/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/22db1f9a-4c9a-496d-9eb6-f3e31268306d/video.mp4

## Entry 5
- ID: 8864
- Author: CloudsAreCloudy
- Created At: 2026-05-24T13:23:30Z

### Content

I connected all the 5V and the ground components, added some fun silkscreens, and checked DRC which revealed a bunch more connections I forgot to connect lol, I need to figure out how to order the PCB now though because JLCPCB for some reason shows up realllyyyy expensive like 40$ and the one I saw in india (LionCircuits) seems to have a MOQ of 5, so I'm gonna ask around in slack and see if theres anyway to only order 1
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTk1ODgsInB1ciI6ImJsb2JfaWQifX0=--f3695d6d57ffd53b4a56ac058d4417cfd23c4f85/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/c6700c7d-b9cc-47f4-814c-bf0e0eba00b2/video.mp4

## Entry 6
- ID: 9042
- Author: CloudsAreCloudy
- Created At: 2026-05-25T04:57:16Z

### Content

Finally got a good supplier for the PCB, I decided after asking a bunch of people that it would be best if I hand soldered the SMD parts and didn't have the PCB Assembled, since that way I'll learn how to solder better AND its SO MUCH CHEAPER. Right now I found AllPCB to be the cheapest, 1$ for upto 30PCB's, but I still have to find a place to order the resistors, capacitors, and IC from, I thought robu maybe but SL2.1S is hard to find.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjAwMDUsInB1ciI6ImJsb2JfaWQifX0=--adb61a3fda1ed7db6e2334f408c66eebb9102a2f/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjAwMDYsInB1ciI6ImJsb2JfaWQifX0=--65c0ea686c92ab3d49a7c1c9aa7eda82dcc6478a/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/a40d0bf3-d7e8-48c0-9b8b-73bb607d96f8/video.mp4

## Entry 7
- ID: 9324
- Author: CloudsAreCloudy
- Created At: 2026-05-26T10:12:22Z

### Content

Mostly spent this time checking if its possible for me to upgrade to USB 3.2 or USB 3, but found out that they don't have the pins things so it would be realllllly hard to solder and also I don't have any solder paste or a heat bed so I'm just gonna stick with USB 2. Also wanted to compare if buying locally was cheaper or LCSC is cheaper, so I also made an excel sheet with the BOM requirements and found out how much it costs me to make 1 USB Hub compared to 30, since I'm getting 30 PCB's. 
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjA3MDAsInB1ciI6ImJsb2JfaWQifX0=--4187a131452b7d61a82d010242dca431c28b46cc/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjA3MDEsInB1ciI6ImJsb2JfaWQifX0=--7be08a98212ca7420a0b3548f190e3eafd392f1f/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/f212b325-01f6-40cf-a9ff-857f5a697a63/video.mp4

## Entry 8
- ID: 9617
- Author: CloudsAreCloudy
- Created At: 2026-05-27T09:51:12Z

### Content

I'm going to include 2 lookouts in this, but basically I just did some more research on where to buy stuff from in the first lookout, and decided that ultimately LCSC is cheaper IF AND ONLY IF I go for the belgium post option which will take reallllllllly long, so I'm gonna see if I can get these parts at least before the deadline for the loan repayment period, otherwise I've no option but to go for the local options. Besides that I had a cool idea to make the USB hub like a hammerhead shark with an articulating cable cover, so I basically repositioned every part in the PCB, made it 2 USB C 2 USB A, and I have to reroute everything now :D
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjEyODksInB1ciI6ImJsb2JfaWQifX0=--341c2a9e0813cee894250558455a3b0866e47152/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/badc2efd-a030-44d2-9242-129d94d1e0c1/video.mp4
- https://lookout.hackclub.com/api/media/d73fa29d-4b23-4d17-8fae-7b9426888dd8/video.mp4

## Entry 9
- ID: 9979
- Author: CloudsAreCloudy
- Created At: 2026-05-28T18:28:08Z

### Content

I'm done routing everything now, it is a bit chaotic but I think it'll work, I had to change a few flags though to make it more optimal for routing, and then once all the routing and everything related to that was done I changed the silkscreens to be more reflective of what I want this project to be, personally I think it looks great, however I imported the fallout sticker design and it made the entire thing lag so much because the sticker is really high res. I think next up will be CAD along with some modifications to the PCB to suit the CAD design! I tried adding the entire lyrics of never gonna give you up too lol but it wouldn't fit
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjI1MDcsInB1ciI6ImJsb2JfaWQifX0=--82f2dc5e28659837ef7e1f287152095508cd5acd/image.png)
![Screenshot 2026-05-28 235647.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjI1MTAsInB1ciI6ImJsb2JfaWQifX0=--7b38f71990821acb2497227d4a5237d3dba16e6f/Screenshot 2026-05-28 235647.png)


### Recording Links

- https://lookout.hackclub.com/api/media/2b27b85f-4f32-44fc-97ba-0e61537e8076/video.mp4

## Entry 10
- ID: 10143
- Author: CloudsAreCloudy
- Created At: 2026-05-29T14:38:43Z

### Content

I started work on the CAD model, exporting the 3D model from easyeda was simple enough, but I still to this day don't know what the proper way to import and simplify meshes in fusion is so thats still a bit messed up. So far I've gotten the basic USB Hub box with some tolerances, and then I projected the USB A ports and USB C ports with .4mm tolerances. once I'm sure that the box is good I'm gonna move onto the rest of the body of the hammerhead
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjI5MTUsInB1ciI6ImJsb2JfaWQifX0=--900a647c92be41f3a5867c514a620cf55e9bd8f5/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/9fbcd1f5-89b7-4691-97ba-81e3ec7ccca4/video.mp4

## Entry 11
- ID: 10213
- Author: CloudsAreCloudy
- Created At: 2026-05-29T18:25:57Z

### Content

Added fillet to the CAD design and split it for easy assembly, but realized the USB C cables are not symmetrical so I went back to the PCB and found new problems, first a bunch of the 5V connections had disconnected from the copper region because of wires passing through, and then the same happened for ground, so I used a lot of vias, and then used the sketch dimension tool or whatever its called to try and position it correctly, but its going to be a lot harder than I thought
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjMxNDQsInB1ciI6ImJsb2JfaWQifX0=--66759e6c5191b700a4668cb1c5b0a444e93a4957/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjMxNDUsInB1ciI6ImJsb2JfaWQifX0=--c9d6020a0297f76dd4801d6a4a2eb52096ad1e9b/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/b7d57712-0f4f-4e83-b2c1-0f32a96b1e57/video.mp4

## Entry 12
- ID: 10720
- Author: CloudsAreCloudy
- Created At: 2026-05-31T18:21:45Z

### Content

I messed around with the positioning of the USB C and the USB A ports to make the USB C ports look like the eyes of the hammerhead shark, I think I finally settled on one but then I had a power cut so I had to redo some stuff again, I'm going to keep the USB A's to the sides and the USB C's to the front at the sides which is not at all efficient but this project is not about efficiency. I have to reroute everything AGAIN but I don't think I will need to do it again.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjQ0NjIsInB1ciI6ImJsb2JfaWQifX0=--2bc2ef9bb51bd0e0ad1e828f8898201497214be0/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjQ0NjQsInB1ciI6ImJsb2JfaWQifX0=--930211b18627f6b1a008d18b6a9dda452c194072/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/a416f3ca-5cf9-4db3-97e9-04bde4a0fee2/video.mp4
- https://lookout.hackclub.com/api/media/860149db-1f38-4e21-b438-fabea442ac4c/video.mp4

## Entry 13
- ID: 10776
- Author: CloudsAreCloudy
- Created At: 2026-05-31T22:51:20Z

### Content

Tried a different layout, with USB A's in the center and USB C's by the sides but didn't like that because of the height difference, I was going for the USB A's as the mouth. I sticked to the last journals design and modified the board outline and made all the connections. All DRC errors are solved except 2
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjQ1OTUsInB1ciI6ImJsb2JfaWQifX0=--96f6635a6a8ae019abc3bd2f8234245da3962aa0/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/b451f4c3-9efd-4097-a2e0-1d5fd7bbca58/video.mp4

## Entry 14
- ID: 10789
- Author: CloudsAreCloudy
- Created At: 2026-06-01T01:21:28Z

### Content

Fixed all the DRC Violations, made the PCB levelled/kinda symmetric, imported it into fusion and then deleted all the old things that I no longer need. I've already made the cutouts and added fillets, just need to re-import the PCB because I forgot to add fillets to that. also checked how much the PCB cost to manufacture locally.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjQ2MzUsInB1ciI6ImJsb2JfaWQifX0=--96cb09b72cc92c4ae677488cfc691832f6a40177/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjQ2MzYsInB1ciI6ImJsb2JfaWQifX0=--274d41543b0f5a3d580d130e0e69c24568437af0/image.png)
 I'm going to try and remember to check if the cost is around the same if the middle part is filled up, and if so fill that up just for the silkscreens lol

### Recording Links

- https://lookout.hackclub.com/api/media/60b4fbb3-9d67-43cd-bcf7-c91fa3fff4ad/video.mp4

## Entry 15
- ID: 12271
- Author: CloudsAreCloudy
- Created At: 2026-06-07T13:07:46Z

### Content

Spent a bunch of time figuring out how to make articulated bodies in fusion, figured I finally have to tackle surface modelling eventhough I absolutely despite it. I made the body of the hammerhead but it doesn't seem to work right so I'm going to redo it I think.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjg3ODIsInB1ciI6ImJsb2JfaWQifX0=--8c4f53879a5c4eb9eb67f115dcc1804f110d7610/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/daba94a0-3879-47ff-b64f-9c009045f412/video.mp4
- https://lookout.hackclub.com/api/media/9a02706d-cb8e-4be8-bd72-43dbc30fa444/video.mp4

## Entry 16
- ID: 12436
- Author: CloudsAreCloudy
- Created At: 2026-06-08T05:43:05Z

### Content

I got done with the body of the shark, now I just have to figure out how to do the finishing touches and turn this into a normal solid/something I can see along with the USB Hub so I can do the rest of the things. This tutorial is pretty helpful (https://www.youtube.com/watch?v=k6ecfjhd5Bo), and I'm just watching what the guy does in the tutorial and doing my own thing using the tools he's explaining.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjkxOTQsInB1ciI6ImJsb2JfaWQifX0=--27b2533567f6e1a59808e08c54fd5016631ff39e/image.png)
![Screenshot 2026-06-08 110948.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjkxOTUsInB1ciI6ImJsb2JfaWQifX0=--3ffba28e5009dbe4f4e4b7731c6098a73d14c14f/Screenshot 2026-06-08 110948.png)


### Recording Links

- https://lookout.hackclub.com/api/media/e331b030-ca85-4c0e-8306-8a23f994cb23/video.mp4

## Entry 17
- ID: 12449
- Author: CloudsAreCloudy
- Created At: 2026-06-08T08:25:53Z

### Content

As expected I'm being ragebaited by surface modelling, I just got a bunch of errors thrown at me and when the model is exported and re-imported its very different, so now I need to figure out how to fix these issues and actually export the model properly. 
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjkyMjUsInB1ciI6ImJsb2JfaWQifX0=--9210250bd9d0d5e3f36e01b2ba4abcf769425e33/image.png)
This image shows how it exports
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjkyMjYsInB1ciI6ImJsb2JfaWQifX0=--af9313d099387e8ef8e105c34cec6644efd81142/image.png)
This shows how its supposed to be
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjkyMjcsInB1ciI6ImJsb2JfaWQifX0=--afd38480dff5151403c0060b7f6724909e3777d1/image.png)
and this screenshot with the pimple patches shows where the issues are arising from.

### Recording Links

- https://lookout.hackclub.com/api/media/20c1f929-e91f-404a-ab46-2888f13b0728/video.mp4

## Entry 18
- ID: 12460
- Author: CloudsAreCloudy
- Created At: 2026-06-08T10:16:24Z

### Content

I somehow got the model all fixed, I pressed the place in the object menu where it was showing that it had errors, and I think that showed me the more critical errors, and once I fixed that by just messing around till it worked, and (accidentally) ignoring the error saying its still not fixed,
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjkzNTMsInB1ciI6ImJsb2JfaWQifX0=--636ac9ccbe41af7804f7a13d4455fdf9aedb38b9/image.png)
This is how it looks after being done with the form, and now I've moved onto the head of the snake, or in this case shark.

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjkzNTQsInB1ciI6ImJsb2JfaWQifX0=--03ee5932acc6c54ab0e63c269fd71e15a3f732fd/image.png)
I've just got a basic head over the hub right now that makes sure everything fits while giving me the flexibility to move around

### Recording Links

- https://lookout.hackclub.com/api/media/6c6f5f82-ddb6-4789-890c-e878a84f9ce1/video.mp4

## Entry 19
- ID: 12478
- Author: CloudsAreCloudy
- Created At: 2026-06-08T11:47:11Z

### Content

done with the head of the shark, took forever for me to figure out how to hollow out the head because shell wouldn't work, eventually I figured out that I can just split the body of the case and then just sketch and cut out the part where the PCB is, sure it won't be as strong but it'll get the job done. I'm gonna see if I can scale it up a liiiitle bit maybe to make the walls thicker, although I'm concerned about the ports not sticking out enough. Also, there is a screenshot of slack in this because fusion was frozen, and I tabbed to firefox and fusions overlays got stuck on my screen so I was closing all windows.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjkzOTMsInB1ciI6ImJsb2JfaWQifX0=--be182b1d417c3bcdeb4e0a29ac69f332bf319a2b/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/45615244-8370-4b84-9ac6-2e9ea93eda15/video.mp4

## Entry 20
- ID: 12512
- Author: CloudsAreCloudy
- Created At: 2026-06-08T14:04:54Z

### Content

Did all the cutouts for the ports, scaled a little to make the walls thicker for the top, and made the cutouts for the cable to go through the sharks body, now I have to figure out how to do the assembly, and also figure out whether or not I want to make it articulated or not (seems less possible considering the cable has to go through)
![Screenshot 2026-06-08 193119.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjk0NDQsInB1ciI6ImJsb2JfaWQifX0=--a4df3c04b2ce42f63f1ecbfaa51bc1a622d5e6f3/Screenshot 2026-06-08 193119.png)
![Screenshot 2026-06-08 193102.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjk0NDYsInB1ciI6ImJsb2JfaWQifX0=--4d8e4c9b9fd153e4b9c972815191de092926661e/Screenshot 2026-06-08 193102.png)
![Screenshot 2026-06-08 193111.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjk0NDcsInB1ciI6ImJsb2JfaWQifX0=--453ad1b4fa33cf0ece60a5fe29d846b0865968b9/Screenshot 2026-06-08 193111.png)


### Recording Links

- https://lookout.hackclub.com/api/media/44703368-e946-47d4-adde-4258ae1f42c8/video.mp4

## Entry 21
- ID: 12884
- Author: CloudsAreCloudy
- Created At: 2026-06-10T01:28:18Z

### Content

I'm pretty much done with the case, besides some very small things, so I've moved onto sourcing parts now, SL2.1s is hard to find anywhere except JLCPCB/LCSC, and I did want to go for LCSC before but apparently LCSC gets lots of customs, so now I'm looking for alternatives to the SL2.1s, I've found the GL850G but it has a few too many pins for me which scares me lol
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzAyODQsInB1ciI6ImJsb2JfaWQifX0=--a151918a56ebf99dfc0c4a286aeca5dd01babd6c/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzAyODUsInB1ciI6ImJsb2JfaWQifX0=--4aee8e139d6cba6ce3270479f0faf9e5ff905643/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/b7bbafaa-bcdd-4ef0-a83e-e9eecd2ff8dd/video.mp4
- https://lookout.hackclub.com/api/media/6f398307-660c-4cb4-a2f3-2e3c13341f4a/video.mp4

## Entry 22
- ID: 12942
- Author: CloudsAreCloudy
- Created At: 2026-06-10T05:23:44Z

### Content

I've decided my only option is the GL850G, but it has a lot more pins than the SL2.1s and I'm heavily relying on the clanker to guide me on what to do, while trying to understand what I'm doing. I'm not done with the schematics of it yet but I've done a major part of it. I'm going to consult some hardware people after I'm done with it.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzA0MTcsInB1ciI6ImJsb2JfaWQifX0=--ee105f197b61f124da94125ffdf1b23c29ab4387/image.png)
Like what even is ts bro 🥀

### Recording Links

- https://lookout.hackclub.com/api/media/1c4ada59-d981-4fb1-b6ef-c8ca059cb0bb/video.mp4

## Entry 23
- ID: 12974
- Author: CloudsAreCloudy
- Created At: 2026-06-10T09:01:59Z

### Content

Checked multiple PCB Assembly companies because I was told that 0607 footprint things are really hard to solder for a beginner (I might have been too ambitious in my previous journals), also I will be scrapping the GL850G because it is WAY more complicated than the SL2.1s, and will genuinely take way more time than money saved. I've landed on JLCPCB (again), and even if I get customs I'll have to live with it. I think my project is really close to finishing now yayyy
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzA1MjEsInB1ciI6ImJsb2JfaWQifX0=--cb8e943892db51c26a1d2700197b529bd5f265fc/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/1f4938d4-cc7a-4c49-8f1f-443698a494be/video.mp4

## Entry 24
- ID: 13445
- Author: CloudsAreCloudy
- Created At: 2026-06-12T11:49:14Z

### Content

Finished up the silkscreen on the PCB, found out JLCPCB was charging extra fees because of some components so changed those back to the cheaper ones, and made the github repo
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzE4NDYsInB1ciI6ImJsb2JfaWQifX0=--e4558dc9da5a2de644e898b366b4d22ab6804632/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/01467930-5ae7-452f-b106-5513130f7aff/video.mp4
