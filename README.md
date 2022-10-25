# Hackintosh - Gigabyte aorous elite z390 - i5-9600k

<img src="https://i.imgur.com/lo2B5TJ.png"/>



## Hackintosh Opencore 0.8.5 for Gigabyte Z390 Aorus elite - macOS Ventura 




### Hardware

Type|Item
:----|:----
**CPU** | [Intel - Core i5-9600K]
**CPU Cooler** | [NZXT kraken m22] 
**Motherboard** | [Gigabyte - Z390 AORUS elite]
**Memory** | [Corsair 16 GB Vengeance LPX DDR4 3000MHz C16]
**Storage (macOS)** | [KINGSTON A400 480GB] | 120GB]
**Storage (Windows)** | [WD sn-750 500GB NVME]
**Video Card** | [Gigabyte rtx 2070 super (disabled)]
**Video Card 2** | [Gigabyte rx 570 (working)]
**Case** | [NZXT H500]
**Power Supply** | [Antec 80+ Gold Semi-Modular]
**Monitor 1** | [ACER KG271C (Working at 144hz)]
**Monitor 2** | [ACER KG271(Workng at 75hz)


## Neccesary BIOS changes to be made before installing (IMP)
* Vtd - Disabled (not supported in mac)
* Internal Graphics - enabled (even tho you dont intent to plug in monitor via mobo)
* XCHI handoff - enabled
* above 4G encoding  enabled
* Sata config - switch it to ACHI from intel optane (if your ssd/hdd doesnt get recognised)
* CSM - Disabled
* secure boot - Disabled
* Windows 8/10 featured - windows 8/10 WHQL
* CGF lock - Disbaled (Please make sure if you have this disable this bc opencore 0.82 wont be able to boot)


## Whats working - Everything!
* Hardware Acc
* USB PORTS 2.0, 3.0.
* Audio via HDMI
* Icloud services (includes Imessage, Facetime, Apple TV)
* wifi/airdrop


Sbios ver - Imac19,1
 



<img src="https://i.imgur.com/De1jhL0.png"/>


#### If you are adding Extra kexts make sure to Inject them. Always Experiment on a seprate USB Drive just in case if anything goes south.
