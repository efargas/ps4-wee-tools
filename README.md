![PS4 Wee Tools](assets/splash.png)

# PS4 Wee Tools

PS4 wee tools help to work with PS4 nor and syscon dumps.

It is free open source alternative for BwE's PS4-NOR-Validator & Syscon-Patcher written in Python to keep it simple.

Currently it provides base functional and can not fully replace those tools.

![Main tool](assets/main.png)

Was tested with Python 3.8

## Features

NOR tool
* PS4 Nor dump info
  * MD5, SKU, Region, SN / Mobo SN, Southbridge
  * Torus (WiFi), MAC, HDD, FW (current, minimal), FW2 ver probability
* Flags toggle:
  * boot mode, safe boot, update mode, arcade mode, kiosk mode (idu)
  * registry recovery, manu, button swap, memory budget, slow hdd mode
* System flags cleaning
* Memory clock editing (GDDR5)
* SAMU boot flag edit
* Downgrade by slot switch
* Additional tools
  * Extract NOR's partitions
  * Build dump from extracted files
  * Get HDD EAP keys [keys.bin]
  * Base validation and entropy stats

Syscon tool
* Syscon check
* Patchable check
* Show active SNVS slot
* Manual SNVS patch
* Auto SNVS patch (4 modes)

Common
* Multy files compare
* Pack / Unpack SLB2 files

Don't use if you don't understant what is it for!

## Credits

* fail0verflow
* zecoxao
* Al-Azif
* Darknesmonk
* BwE
* pearlxcore

And of course [PSDevWiki](https://www.psdevwiki.com/ps4/)

## Donate

* **[Patreon](https://patreon.com/andy_man)**
* **[Boosty](https://boosty.to/andy_man/donate)**
* **[YandexMoney](https://yoomoney.ru/to/410011555252085)**
* **Bitcoin**: 39VaMnFqCQo751mvDc3M7ADVty71q2tWDm 

## Links

* [Twitter](https://twitter.com/AndyManDev)

## Changelog

### v0.7.7
* SLB2 pack / unpack
* File selection screen upgrade
* Preparations for EMC cfw (Aeolia)

### v0.7.6
* FW2 version assumption
* Validation screen update

### v0.7.5
* Base validation (header, mbrs, emc, eap, wifi)
* Southbridge and torus Info
* Code refactoring
* Minor bugs fix

### v0.7
* Extract NOR's partitions
* Build dump from extracted files
* Get HDD EAP keys [keys.bin]
* File selection screen fix

### v0.6
* Now with color highlighting
* Dialog improvements

### v0.5
* New screen "Flags toggle"
* boot mode, safe boot, update mode, arcade mode, kiosk mode (idu)
* registry recovery, manu, button swap, memory budget, slow hdd mode
* Syscon auto SNVS patch (4 modes)
* New FW detection (experemental)
* Region info
* Minor improvements

### v0.4
* Syscon patchable check
* Manual patch bug fix
* Minor errors fix

### v0.3
* NOR Entropy stats
* Syscon manual patch
* Minor errors fix

### v0.2
* Syscon DEBUG toggle
* Syscon NVStorage class
* Syscon show active slot

### v0.1
* Files compare
* UART, Memtest toggle
* Sys flags clean
* Edit mem clock and SAMU
* Downgrade switch patterns
* Syscon base check
