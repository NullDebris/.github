# Nothing Phone (3a) / (3a) Pro (Asteroids) Development


## Manifests
[Lineage 23.1 - Kernel 6.6](https://github.com/NullDebris/manifest/blob/main/asteroids-6.6-lineage-23.1.xml)

[Lineage 23.1 - Kernel 6.1](https://github.com/NullDebris/manifest/blob/main/asteroids-6.1-lineage-23.1.xml)

[Lineage 23.0 - Kernel 6.6](https://github.com/NullDebris/manifest/blob/main/asteroids-6.6-lineage-23.0.xml)

[Lineage 23.0 - Kernel 6.1](https://github.com/NullDebris/manifest/blob/main/asteroids-6.1-lineage-23.0.xml)

# Status
## Kernel 6.1 (android14-6.1) 
- has broken IMS and will cause mobile data connectivity issues

## Kernel 6.6 (android15-6.6) 
- Condsidered stable for now (Dec 25, 2025)
> To avoid the need to ship a fastboot build or a full set of initial install images (boot, recovery, dtbo, vendor_boot, init_boot, vendor_dlkm, system_dlkm), build a recovery image with 6.1 trees, then provide that to users coming from the stock firmware. (NOS/Nothing OS)

#### Credits
[Alex Koskovich](https://github.com/AKoskovich) - Initial Device/Kernel/Vendor Trees

[HELLBOY017](https://github.com/HELLBOY017) - Glyph Interface support for AOSP, Sony Dolby adaptation

[Fabian Leutenegger](https://github.com/33bca) - Initial Glyph Interface support for AOSP
