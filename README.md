# EFI
My configuration

Asrock B365M Pro4
Radeon Sapphire RX580 graphics card


In order to make the hardware acceleration work on the graphics card, I used the MacPro7,1 profile.
I have tried with iMac19,1 before but it doesn't work with hardware acceleration, so I have since changed to MacPro7,1 and it works 100%.

What works
- hardware acceleration. I have tested it with VideoProC.
- most USB ports works. At the least the ones I need to use, including the USB Type-C port.
- sound and mic both work. Before there was a problem with some weird noise on the mic but now it works normally
because I found that the problem was because I had not added the AppleALC to the boot args.
After I did it, the weird noise completely vanished. 

What doesn't work
- WiFi doesn't work but I installed a Fenvi card and it works well now. 
