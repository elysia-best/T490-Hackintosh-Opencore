# T490-Hackintosh-Opencore
This is Opencore for Thinkpad T490.
OC Version 0.8.3

# File included.
- ACPI
  - BlockOptane.aml
  - SSDT-AWAC.aml
  - SSDT-EC-USBX-LAPTOP.aml
  - SSDT-PLUG-DRTNIA.aml
  - SSDT-PNLF.aml
  - SSDT-RHUB.aml
- Kexts
  - AirportItlwm.kext
  - AppleALC.kext
  - BrightnessKeys.kext
  - ECEnabler.kext
  - IntelBluetoothFirmware.kext
  - IntelBluetoothInjector.kext
  - IntelMausi.kext
  - Lilu.kext
  - NVMeFix.kext
  - SMCBatteryManager.kext
  - SMCLightSensor.kext
  - SMCProcessor.kext
  - SMCSuperIO.kext
  - USBToolBox.kext
  - UTBMap.kext
  - VirtualSMC.kext
  - VoodooPS2Controller.kext
  - WhateverGreen.kext
- Drivers
  - HfsPlus.efi
  - OpenCanopy.efi
  - OpenRuntime.efi  
- Tools
  - OpenShell.efi 
  
# Compability
 - Optane SSD support. For modle 20RY.
 - macOS 11.6 tested. However macOS 13 may work.
 - Intel bluetooth and wlan. The airplay will display but it does not work.
 - Hand Off is suppoorted.
 - Light sensor OK.
 - Camera OK.
 - tracepad OK.
 - Sleep function ok.
 
# How to use?
1. Clone this repo.
2. Modify SMBIOS info.
3. Compile `BlockOptane.dsl` if you are using optane.

# Information for Optane
Please refer to this [PR #388](https://github.com/dortania/OpenCore-Install-Guide/pull/388)
