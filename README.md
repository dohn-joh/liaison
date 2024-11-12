![cover_photo](photos/1.jpg)

# Liaison
`Liaison` is a wireless 36-key split keyboard that leverages custom keycaps, splay, and tenting for ergonomics.

**Video showcase**:  
[Fit and layout](https://vimeo.com/1022366207)  
[Typing test](https://vimeo.com/1022366241)

***

# Build Guide

## Case and Tenting
[Here](case) you can find the models for the case and magsafe tenting legs.

Print 1 of each of the following:
* [top left](case/case_top_left.step)
* [top right](case/case_top_right.step)
* [bottom left](case/case_bottom_left.step)
* [bottom right](case/case_bottom_right.step)

If you are interested in magnetic tenting legs, you can print 2 of [these](case/magsafe_tenting_leg).

If you are interested in an case for the dongle, check out this [repo](https://github.com/dohn-joh/dongle-zmk).

## Required parts
|Part|Quantity|Link|
|-|-|-|
|Microcontroller: Xiao nRF52840|1|https://www.seeedstudio.com/Seeed-XIAO-BLE-nRF52840-p-5201.html|
|Battery: 301230 with molex pico ezmate connector|1|Select L0040. https://www.aliexpress.us/item/3256802674181210.html|
|Battery connector: molex pico ezmate 1x02|1|Select 2P. https://www.aliexpress.us/item/3256805726980487.html|
|Power button: 1208YD|1|https://www.aliexpress.us/item/3256801267126259.html|
|Reset button: SKHLLCA010|1|https://www.aliexpress.us/item/3256805176534062.html|
|M2 heatset inserts (OD:3.2, Height: 2-3mm)|8|https://www.aliexpress.us/item/3256804856964661.html|
|Switches|36|Your choice of choc v1 or v2. Recommended: Lofree ghost, swap springs|
|Kailh Choc PG1350 Hot Swap Sockets|36|https://www.aliexpress.us/item/3256803687338432.html|
|Silicone sheet for feet|1|https://www.amazon.com/dp/B09NW63JLC|
|Keycaps|36|Your choice. Recommended: [low profile DES](https://github.com/dohn-joh/PseudoMakeMeKeyCapProfiles) + [lever keycaps](https://github.com/dohn-joh/keycaps)|

> [!NOTE]
> Keycap dimensions must be ≤17.85mm wide and ≤18mm deep. All standard choc keycaps will fit.

## Optional parts for tenting and USB
|Part|Quantity|Link|
|-|-|-|
|Magsafe puck: Vrig MG-01|2|https://www.aliexpress.us/item/3256804940825578.html|
|Magsafe rings|2|https://www.aliexpress.us/item/3256805759445725.html|
|1/4" thread screw ~9mm|2|There are cheaper sources out there, but here is a link: https://www.amazon.com/dp/B01MS60KSY|
|Magnetic USB connector: Netdot Gen10|2|https://www.amazon.com/dp/B07MBD3FZD|

## Firmware
[Here](https://github.com/dohn-joh/liaison-zmk-module) you can find the source for liaison's ZMK firmware. This firmware is configured for dongle usage, however you may edit the files if you prefer not to use a dongle.

> [!IMPORTANT]
> Flash your microcontrollers with firmware and test them before doing any soldering. Once the microcontrollers are soldered, they will be extremely difficult to remove.



***

# Photos

![2](photos/2.jpg)
![3](photos/3.jpg)
![4](photos/4.jpg)
![5](photos/5.jpg)
![6](photos/6.png)
![exp](photos/exp.png)

***

## Thanks
These people and many more helped make this keyboard possible. Yall are legends.
```
MrZealot
Pseudoku
petejohanson
caksoylar(bravekarma)
jcmkk3
ceoloide
infused-kim
Flatfootfox
sadekbaroudi
zzeneg
joelspadin
wolfwood
claussen
Geist
rmwphd(atinyzubat)
fish
Araxia
honorless
elkepenin
reeves
```

