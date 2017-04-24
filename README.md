Acer V5-573g macOS Sierra
===========================

This Repo keeps the needed hardware drivers.

List Of Folders
===============

- Audio(`Realtek ALC262`): DummyHDA.kext
- Battery(`Battery`): ACPIBatteryManager.kext
- ElanTouchPad(`ElanTouchPad`): ApplePS2SmartTouchPad.kext
- FakePciId(`Fake HD4400 GPU`): 
    * FakePCIID.kext 
    * FakePCIID.kext
- HwSensors(`HWMonitor`): 
    * ACPISensors.kext
    * ACPISensors.kext
    * FakeSMC.kext
    * GPUSensors.kext
    * LPCSensors.kext
- Network(`Realtek RTL8111`): RealtekRTL8111.kext

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

