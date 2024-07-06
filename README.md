 Hackintosh - Gigabyte aorous elite z390 - i5-9600k

[Imgur](https://imgur.com/G7luVxi)



## Hackintosh Opencore 1.0.0 for Gigabyte Z390 Aorus elite - macOS Sonoma 14.5 




### Hardware

Type|Item
:----|:----
**CPU** | [Intel - Core i5-9600K - OC - 5.0 GHZ]
**CPU Cooler** | [Lian Li Galahad 240 ARGB AIO Liquid CPU Cooler - White] 
**Motherboard** | [Gigabyte - Z390 AORUS elite]
**Memory** | [Corsair 32 GB Vengeance LPX DDR4 3000MHz C16]
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
* CGF lock - Disbaled (Please make sure if you have this disable this bc opencore 0.85 wont be able to boot)



## Whats working - Everything!
* Hardware Acc
* USB PORTS 2.0, 3.0.
* Audio via HDMI
* Icloud services (includes Imessage, Facetime, Apple TV)
* wifi/airdrop


Sbios ver - Imac19,1
 


(updated wifi card to Broadcom BCM94360CS2 with a pcix4 adapter)

For WIFI follow this tut: Appt. Apple has dropped the supoort for broadcom cards.

https://www.youtube.com/watch?v=gHs2CFox6gc&t=376s


#### If you are adding Extra kexts make sure to Inject them. Always Experiment on a seprate USB Drive just in case if anything goes south.
