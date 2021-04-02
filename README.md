Opencore EFI for Gigabyte Z370 AORUS ULTRA GAMING WIFI

Tested on Mac OS Big Sur 

What's working? 

Everything seems to be working so far.


Hardware Spec

* Monitor: LG 5K
* Motherboard: Gigabyte Z370 AORUS ULTRA GAMING WIFI
* CPU: Intel Core i&-8700 3.2 GHz 
* HDD: Samsung 500GB 960 EVO NVMe 
* GPU: MSI Gaming Radeon RX 570 8GB (RX 570 ARMOR MK2 8G OC)
* Thunderbolt: Titan Ridge
* Wifi: BCM94360CS2 with WiFi + Bluetooth 4.0 Card to PCI-E x1 Adapter


Notes

1. I removed the wifi & bluetooth card that came with this motherobard.
2. The default Opencore config.plist did not work. I had to enable ReleaseUsbOwnership.
3. If you don't have Titan Ridge, open config.plist and remove `SSDT-Z370-TB3HP.aml` entry.
