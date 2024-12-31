![img](/img/screenshot.png)

# OpenCore-ASUS-ROG-Strix-Z490G-Gaming-Wifi

OpenCore configuration for the ASUS ROG Strix Z490-G Gaming (Wifi) motherboard.
Designed for 14.5, but may be used with older and newer versions (within reason)
if you replace AirportItlwm.kext and Bluetooth related kexts.

Before using, you must get OpenCore.efi, OpenCanopy.efi and OpenRuntime.efi from
the latest OpenCore version. Place OpenCore.efi in EFI/OC and the others in EFI/OC/Drivers.
You must also generate an appropriate SMBIOS and corresponding serial.

## Specifications

The specifications of my system. This config will very likely work with similar configurations.

- Motherboard: ASUS ROG Strix Z490-G Gaming (Wifi)
- CPU: Intel Core i9 10900 (10c/20t) @ 5.20Ghz
- GPU: AMD Radeon RX 570 (8GB)
- RAM: 2x16GB Corsair Vengeance @ 3666Mhz
- Storage: Any NVMe SSD, really. Avoid PM981 though ;)

## Functionality

- GPU acceleration (natively)
- Ethernet (using AppleIGC)
- Audio (using AppleALC)*
- WIFI (built in, using AirportItlwm)
- Bluetooth (built in, using IntelBluetoothFirmware)
- USB 2/3/3.1/3.2 (mapped ports from macOS with USBMap)
  - If you wish to reuse my config, it's very likely that you will have to map the ports yourself, since they won't necessarily be the same for you.
- Full XMP RAM speeds (3600mhz)
- Most likely anything else I did not specify.
