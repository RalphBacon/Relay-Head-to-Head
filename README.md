# Relay-Head-to-Head

This video is sponsored by https://www.pcbway.com  
*We invite you to join the 2nd PCB design contest to win highest $1000.00 cash reward.   
Check the guide to find more information.  
https://www.pcbway.com/project/PCB_DESIGN_CONTEST.aspx*  

#See the accompanying video #127 at https://youtube.com/ralphbacon  
(Direct link to video: https://youtu.be/aZdq5WPJyog)

**Comparison of three different relay types: electromechanical, SSR and latching**  

All relays provide some form of switch. Relays come in various shapes, sizes and purposes.  They are operated electrically, electronically or even manually. In our Arduinite world they are used to enable higher voltages and/or currents to be switched by something that could not handle that requirement. So your Arduino, PIC or Raspberry Pi can now switch high current household voltages without a problem.  

So which one to choose? And why choose one type over another?

In this video we look first at the traditional, electromechanical relay. It's a switch that is operated by an electromagnetic coil. I've already done a complete video on the ins and outs of such a video but we summarise it here.

If you want the full details watch this other opto-isolated relay video #18 Opto-isolated Relay:  
https://youtu.be/d9evR-K6FAY

We next look at a Solid State Relay (SSR). This is not a mechanical switch at all, but an electronic one. As such there are some disadvantages in using it but also some advantages too. For example, SSRs take up little room and are opto-isolated by default. No moving parts, either. But they are connected to the switching voltage at all times, even when off.

There are some precautions to be taken when using Solid State Relays so I've include a PDF document for some bed time reading:  
https://omronfs.omron.com/en_US/ecb/products/pdf/precautions_ssr.pdf

Finally we take a look at a mechanical latching relay. It's a bit like the first one, but the switching process, from one contact to another, is a latching process. Once switched, using one coil, you need to un-switch it using another coil. This could be very useful in low power circuits, as an alternative to using MOSFETs, perhaps.

Now be aware that some Far Eastern manufacturers offer "latching" relays that are not the same as the one used here. Their "latching" mechanism still requires power to be applied at all times, and the flip-flop between contacts is controlled by a further on-board component. You just supply a high or low to a single input and the latching process happens - but it's not permanent (across power breaks) and it's not a true latching process at all. Caveat emptor!

Here's an example of a hardware-controlled flip-flop "latching" relay - NOT what we mean in this video at all!  
https://www.aliexpress.com/item/OOTDTY-6-24V-Flip-Flop-Latch-Relay-Bistable-Self-locking-Low-Pulse-Trigger-Module/32884746156.html
Do not buy this unless you understand what you are buying!  

## LINKS
(Some links may be affiliate links which pay me commission - doesn't affect my editorial content either way)  

Opto-isolated electromechanical (traditional) relay double pack (ensure you get OPTOCOUPLED or OPTOISOLATED):  
https://www.banggood.com/2Pcs-5V-1-Channel-Level-Trigger-Optocoupler-Relay-Module-For-Arduino-p-1366337.html?p=FQ040729393382015118&utm_campaign=25129675&utm_content=3312

Solid State Relay (SSR)  
https://www.banggood.com/One-way-Solid-State-Relay-Module-For-Arduino-p-979853.html?p=FQ040729393382015118&utm_campaign=25129675&utm_content=3312  
https://www.aliexpress.com/item/5V-1-Channel-OMRON-SSR-G3MB-202P-Solid-State-Relay-Module-240V-2A-Output-with-Resistive/32311293343.html

SSR Spec Sheet as used in the video:  
https://www.openhacks.com/uploadsproductos/g3mb-ssr-datasheet.pdf

Latching (bistable) relay (also other multi-packs available, cheaper)  
https://www.aliexpress.com/item/12V-Coil-Bistable-Latching-Relay-DPDT-2A-30VDC-1A-125VAC-HFD2-005-S-L2-D-Realy/32908954230.html  
Also in packs of two (and more, check the website):  
https://www.aliexpress.com/item/2PCS-lot-HFD2-005-M-L2-D-HFD2-005-M-L2-D-10pin-5V/32717910397.html

Useful background reading on relays on Wikipedia:  
https://en.wikipedia.org/wiki/Relay  

If you like this video please give it a thumbs up, share it and if you're not already subscribed please consider doing so :)

My channel and blog are here:  
------------------------------------------------------------------  
https://www.youtube.com/RalphBacon  
https://ralphbacon.blog  
------------------------------------------------------------------  
