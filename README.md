Acer V5-573g macOS Sierra
===========================

This Repo keeps the needed hardware drivers.

List Of Folders
===============

- Audio(`Realtek ALC262`): DummyHDA.kext or [AppleALC](https://github.com/vit9696/AppleALC) [AppleALC Download Link](https://github.com/vit9696/AppleALC/releases) update: 2017/03/31 `release 1.1.1`
- Battery(`Battery`): [ACPIBatteryManager.kext](https://bitbucket.org/RehabMan/os-x-acpi-battery-driver/downloads/) - update: 170428
- ElanTouchPad(`ElanTouchPad`): [ApplePS2SmartTouchPad.kext](http://forum.osxlatitude.com/index.php?/topic/1948-elan-focaltech-and-synaptics-smart-touchpad-driver-mac-os-x/) [link](https://applelife.ru/threads/elan-focaltech-and-synaptics-smart-touchpad-driver-mac-os-x.207992/) - update :Version v4.7 beta 5 (10 - 12 - 2016) (work in progress, available to try from attachments).
- FakePciId(`Fake HD4400 GPU`): [github](https://github.com/RehabMan/OS-X-Fake-PCI-ID) [download](https://bitbucket.org/RehabMan/os-x-fake-pci-id/downloads/) - update: 20170503
    * FakePCIID.kext      
    * FakePCIID_Intel_HD_Graphics.kext
- [HwSensors(`HWMonitor`)](http://www.hwsensors.com/releases): update: 6.25.1426
    * ACPISensors.kext
    * ACPISensors.kext
    * FakeSMC.kext
    * GPUSensors.kext
    * LPCSensors.kext
- Network(`Realtek RTL8111`): [RealtekRTL8111.kext](https://bitbucket.org/RehabMan/os-x-realtek-network/downloads/) - update: 2017/03/22
- Usb(`USBInjectAll.kext`): [USBInjectAll.kext](https://bitbucket.org/RehabMan/os-x-usb-inject-all/downloads/) - update: 2017/01/12
- Wifi(`BCM43228 802.11n Wireless `): no kext needed.

Download
========

https://github.com/V5OSX/kexts/archive/master.zip

Install
=======

Install with Kext Install Tool Whatever you like

Keep Update
===========

You can fork and update the new kext and pull, i will merge it into master.
But please be careful with the kext that maybe destory other's OS X.

