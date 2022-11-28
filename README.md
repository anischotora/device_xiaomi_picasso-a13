![pixel](https://imgur.com/phIk5MXl.png "pixel")

pixel experince A13 for Redmi K30 5G (picasso)
======================================

# How to build
=======
 Device configuration for Redmi K30/K30i 5G
 =========================================

 The Redmi K30/K30i 5G (codenamed _"picasso/picasso_48m"_) is a smartphone from Xiaomi.

Download pixel experince source and picasso repos. You can have a look at my manifest:

https://github.com/masemoel/local_manifests/blob/master/picasso_t.xml

 Basic   | Spec Sheet
 -------:|:-------------------------
 SoC     | Qualcomm SM7250 Snapdragon 765G 5G (7 nm)
 CPU     | Octa-core (1x2.4 GHz Kryo 475 Prime & 1x2.2 GHz Kryo 475 Gold & 6x1.8 GHz Kryo 475 Silver)
 GPU     | Adreno 620
 Memory  | 6/8 GB RAM
 Android Version | Android 10, upgradable to Android 11, MIUI 12
 Storage | 64/128/256 GB
 Battery | Li-Po 4500 mAh, non-removable
 Display | IPS LCD, 120Hz, HDR10
 Camera (K30 5G) | 64 MP, f/1.9, 26mm (wide), 1/1.72", 0.8µm, PDAF, 8 MP, f/2.2, 13mm (ultrawide), 1/4.0", 1.12µm, 5 MP, f/2.4, (macro), 2 MP, f/2.4, (depth)
 Camera (K30i 5G) | 	48 MP, f/1.9, (wide), 1/2.0", 0.8µm, PDAF, 8 MP, f/2.2, 120˚ (ultrawide), 1/4.0", 1.12µm, 2 MP, f/2.4, (macro), 2 MP, f/2.4, (depth)

Then go to the source folder and run:

```bash
. build/envsetup.sh
lunch aosp_picasso-userdebug
m bacon -j$(nproc -all)
```

# Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
Network	| GSM (B2/B3/B5/B8) / HSPA (B1/B2/B5/B8) / LTE (B1/B3/B5/B7/B8, B34/B38/B39/B40/B41) / NR (n41/n78)
SIM Slots | Dual Nano SIM card capability
Launch	| 2020, January
SoC     | Qualcomm Snapdragon 765G
CPU     | Octa-core (1x2.4 GHz Kryo 475 Prime & 1x2.2 GHz Kryo 475 Gold & 6x1.8 GHz Kryo 475 Silver)
GPU     | Adreno 620
Memory  | 6/8 GB RAM
Shipped Android Version | 10 with MIUI 11
Storage | 64/128/256 GB (without SD card slot)
Battery | Non-removable Li-Po 4500 mAh battery
Display | 1080 x 2400 pixels, 20:9 ratio, 6.67 inches, 120hz, HDR10, IPS LCD (~386 ppi density), Gorilla Glass 5
Weight  | 208 grams
Back cameras   | 64.0MP (main) + 8.0MP (wide) + 5.0MP (macro) + 2.0MP (portrait), LED flash, 2160p@30fps or 1080p@60fps
Front cameras  | 20.0MP (main) +2.0MP (portrait), 1080p@30fps
WLAN  | Wi-Fi 802.11 a/b/g/n/ac, Wi-Fi Direct, dual band, hotspot
Bluetooth  | v5.1 A2DP, LE, aptX HD
GPS	    | Yes, with A-GPS, GLONASS, BDS, GALILEO
NFC	    | Yes
Radio   | FM radio
USB	    | C-type 2.0 with fast charge up to 30 W, OTG
Colors 	| Blue, purple, red or white
Sensors | Fingerprint ID with the power button, infrared, 3.5mm jack

![Xiaomi Redmi K30 5G](https://cdn.cnbj0.fds.api.mi-img.com/b2c-shopapi-pms/pms_1575882160.38569692.jpg "Xiaomi Redmi K30 5G")
 ![Redmi K30 5G](https://cdn.cnbj0.fds.api.mi-img.com/b2c-shopapi-pms/pms_1575882053.33827103.jpg "Redmi K30 5G")
