# Hackintosh - Gigabyte aorous elite z390 - i5-9600k

<img src="https://i.imgur.com/gTMnXON.png"/>



## Hackintosh Opencore 0.7.7 for Gigabyte Z390 Aorus elite - macOS Monetery 12.2.2
### *Updated to 12.3.1

### Hardware

Type|Item
:----|:----
**CPU** | [Intel - Core i5-9600K]
**CPU Cooler** | [NZXT kraken m22] 
**Motherboard** | [Gigabyte - Z390 AORUS elite]
**Memory** | [Corsair 16 GB Vengeance LPX DDR4 3000MHz C16]
**Storage (macOS)** | [ALKETRON - Blue Shark SSD (Internal Solid State Drive) | 120GB]
**Storage (Windows)** | [KINGSTON A400 480GB]
**Video Card** | [Gigabyte rtx 2070 super (disabled)]
**Video Card 2** | [Gigabyte rx 570 (working)]
**Case** | [NZXT H500]
**Power Supply** | [Antec 80+ Gold Semi-Modular]
**Monitor 1** | [ACER KG271C]
**Monitor 2** | [ACER KG271]


## Neccesary BIOS changes to be made before installing (IMP)
* Vtd - Disabled (not supported in mac)
* Internal Graphics - enabled (even tho you dont intent to plug in monitor via mobo)
* XCHI handoff - enabled
* above 4G encoding  enabled
* Sata config - switch it to ACHI from intel optane (if your ssd/hdd doesnt get recognised)
* CSM - Disabled
* secure boot - Disabled
* Windows 8/10 featured - windows 8/10 WHQL


## Whats working - Everything!
* Hardware Acc
* USB PORTS 2.0, 3.0.
* Audio via HDMI
* Icloud services (includes Imessage, Facetime, Apple TV)
* Dual Display (High Refresh Rate)

Sbios ver - Imac19,1
 

### Not tested - Wifi / Bluetooth since i use lan (which works btw)

* follow the guide to fix external wifi - https://github.com/chris1111/Wireless-USB-Big-Sur-Adapter

* #### UPDATE: Wifi Works (Make sure SIP is disabled by Going in Recovery/Utility/Terminal)

* Type the following command and Restart

> csrutil disable


<img src="https://i.imgur.com/De1jhL0.png"/>



## Don't forget to make neccesary SSDT changes to the plist, in most cases it will work just as fine. If you are adding Extra kexts make sure to Inject them. Always Experiment on a seprate USB Drive just in case if anything goes south.
