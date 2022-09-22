# tasmota-motor-pcb
PCB board for controll a nema17 with tasmota


Those are the gerber files for make a PCB to assemble all the components needed for control a nema 17 operating roller blinds, stores and more.

The info about how to config the tasmota is in here https://github.com/arendst/Tasmota/discussions/11731.

I have uploaded two PCB's. One is a little bit bigger than the other. The big one is fully tested, the little one is the big one but with some components stacked, but I have not produced this one yet.

There are two jumpers in order to use one of those drivers: A4988, DRV8825 and TMC2208. How to use those jumpers deppending of the driver selected Is written in the back of the PCB. "O" means open and "C" means closed.

I hame made also a little box to attach the pcb on the back of the nema. It is still a work in progress and It should be updated soon. It's uploaded in https://www.thingiverse.com/thing:5526654

The part list is:


-Wemos D1 mini. The esp 8266 should be faced to the pcb in the same face than the driver.

-JST 2.54mm XHP-2

-JST 2.54mm XHP-4

-35V 100μF capacitor (In the pcb and in the tasmota instructions is listed as 100mf, but is 100μF)

-4 1x8 pin female connector (you can solder directly to the board in the big one and not to use those, but is more difficult to replace a faulty part if needed)

-HW-613 step-down (this one should be set to 5V output)

-4 male pin

-2 2pin jumper

![foto1](https://user-images.githubusercontent.com/5169740/191841561-7c89e66a-ec90-4526-a355-b9c57f50acb5.jpg)


![imagen](https://user-images.githubusercontent.com/5169740/191841045-fd6e1e0a-721f-4c07-bcf0-691c5f9dedc5.png)
