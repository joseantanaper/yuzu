# yuzu / Nintendo Switch - Emulator and Console Tips

## Setup Yuzu
1. Execute **yuzu_install.exe**
2. Copy **ProdKeys.zip** and extract **prod.keys** and **title.keys** into
[*C:/Users/%USERNAME%/AppData/Roaming/yuzu/keys*](file:///C:/Users/%USERNAME%/AppData/Roaming/yuzu/keys)

## Quick Config
1. Launch **yuzu**
2. Emulation > Configure
    - General
        - General
            - Limit Speed Percent: *100%*
            - Multicure CPU Emulation: *ON*
            - Extended memory layout (6GB DRAM): *ON* ???
            - Confirm exit while emulation is running: *ON*
            - Hide mouse on inactivity: *ON*
        - System
            - System: set *Language*, *Region* and *Device name*.
            - Profiles: create a new *Profile* with your own name and *Set Image*.
        - CPU
            - Accuracy: *Auto*
        - Graphics
            - Graphics
                - API: *Vulkan*
                - Device: *Your most powerful GPU*
                - Use disk pipeline cache: *ON*
                - Use asynchronous GPU emulation: *ON*
                - Accelerate ASTC texture decoding: *ON*
                - Resolution: *1X (720p/1080p)*
                - Window Adapting Filter: *Bilinear*
                - Anti-Aliasing Method: *FXAA*
            - Advanced
                - Accuracy Level: *High*
                - Use VSync: *ON*
                - Use Fast GPU Time (Hack): *ON*
                - Use Vulkan pipeline cache: *ON*
                - Anisotropic Filtering: *16X* | (Automatic, Default, 2X, 4X, 8X, **16X**)
        - Controls
            - Pro Controller - XBox One Controller 0
3. Double-click to add a new folder to the game list.

## Setup Yuzu Mod Downloader
1. Copy and extract **YuzuModDownloader.zip** into
[C:\Users\%USERNAME%\AppData\Local\yuzu](C:\Users\%USERNAME%\AppData\Local\yuzu)
2. Execute **YuzuModDownloader.exe** and download latest mods.

***

## Paths
C:\Users\%USERNAME%\AppData\Local\yuzu
C:\Users\%USERNAME%\AppData\Roaming\yuzu
C:\Users\%USERNAME%\AppData\Roaming\yuzu\keys
prod.keys
title.keys

***

## Downloads

### Yuzu Emulator
[https://yuzu-emu.org/downloads/](https://yuzu-emu.org/downloads/)

### Prod Keys:
[https://prodkeys.net/yuzu-prod-keys/](https://prodkeys.net/yuzu-prod-keys/)

### Firmware:
[https://prodkeys.net/switch-firmwares/](https://prodkeys.net/switch-firmwares/)

### Yuzu Mod Downloader
[https://github.com/amakvana/YuzuModDownloader/releases/tag/v1.3.1.0](https://github.com/amakvana/YuzuModDownloader/releases/tag/v1.3.1.0)
