This project is for e5470 but since every dell laptop is likely the same you could use it like mine.

Dell latidue e5470:
- Cpu: i5 6300u
- Ram: 8gb
- some weird brand ssd pre install with this laptop, i bought it in china.
- stock intel wifi/bluetooth card.

Things work:
- brightness/function key
- sleep/wake lid open/close
- charging not freeze anymore
- webcam/sound
- bluetooth 

- add acpi-wake-type, if you found your computer have different pci adress then change it according to this guide: 

https://dortania.github.io/OpenCore-Post-Install/usb/misc/keyboard.html#method-1-add-wake-type-property-recommended


Not working:
- i don't know, haven't tested everything since i forked this for fun.

I also install some very interesting kext called itlwm(use it with Heliport, it has GUI in it), it make your intel card can access internet through wifi, though maybe changing in the future so i don't know, just want to mention it.

Every apci hot patch is from original dell e5570 from @Mateo, i just delete and update some kext and keep testing until i got it works just right, so if yours doesn't work properly please trying another way or google it, apci is very complicated and i have no idea how to make it works either. 

* Remember to put your own smbios in config.plist

credit:

Mateo1234454545 [https://github.com/Mateo1234454545/DELL-5570-Hackintosh]

zxystd 

acidanthera


https://github.com/OpenIntelWireless/itlwm

https://github.com/OpenIntelWireless/HeliPort
