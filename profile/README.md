# Nothing Phone (3a) / (3a) Pro (Asteroids) Development


## Manifests
[Lineage 23.2 - Kernel 6.6](https://github.com/NullDebris/manifest/blob/main/asteroids-6.6-lineage-23.2.xml)

[Lineage 23.1 - Kernel 6.6](https://github.com/NullDebris/manifest/blob/main/asteroids-6.6-lineage-23.1.xml)

[Lineage 23.1 - Kernel 6.1](https://github.com/NullDebris/manifest/blob/main/asteroids-6.1-lineage-23.1.xml)

[Lineage 23.0 - Kernel 6.6](https://github.com/NullDebris/manifest/blob/main/asteroids-6.6-lineage-23.0.xml)

[Lineage 23.0 - Kernel 6.1](https://github.com/NullDebris/manifest/blob/main/asteroids-6.1-lineage-23.0.xml)

# Status
## Kernel 6.1 (android14-6.1) 
- has broken IMS / half-dead modem and will cause mobile data connectivity issues

## Kernel 6.6 (android15-6.6) 

- Will quite often get stuck when booting for the first time or rebooting. This is due to the secure side of the device (securemsm) not properly responding/being handled for some reason

> To avoid the need to ship a fastboot build or a full set of initial install images (boot, recovery, dtbo, vendor_boot, init_boot, vendor_dlkm, system_dlkm), build a recovery image with 6.1 trees, then provide that to users coming from the stock firmware. (NOS/Nothing OS)

#### Credits
[Alex Koskovich](https://github.com/AKoskovich) - Initial Device/Kernel/Vendor Trees

[HELLBOY017](https://github.com/HELLBOY017)  - Glyph Interface support for AOSP, Sony Dolby adaptation

[GHOST](https://github.com/Ghosuto) - Additional Glyph Interface features, Lunaris Dolby UI

[Fabian Leutenegger](https://github.com/33bca) - Initial Glyph Interface support for AOSP

> I'm not responsible for bricked devices, dead SD cards, thermonuclear war, or you getting fired because the alarm app failed.
> YOU are choosing to make these modifications, and if you point the finger at me for messing up your device, I will laugh at you.
> Your warranty will be void if you tamper with any part of your device / software.
