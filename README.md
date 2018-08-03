# nanopi wifi dual-band usb dongle drivers

Binaries drivers for nanopi Allwinner H5 kernel 4.14.52.

## Tested Hardward
TP-LINK TL-WDN5200 2.0 (Driver free version)

EDUP EP-AC1620

COMFAST CF-WU925A

## 8812AU
This repository contains drivers for the rtl8812AU and rtl8821AU/rtl8811AU chipsets.

source: https://github.com/diederikdehaas/rtl8812AU

## 8821CU
Drivers for rtl8811CU and rtl8821CU Wi-Fi chipsets.

source: https://github.com/whitebatman2/rtl8821CU

## How to install
```
git clone https://github.com/magicbear/nanopi-usb-wifi-dongle-driver-4.14.52.git
cp nanopi-usb-wifi-dongle-driver-4.14.52/8812au.ko /lib/modules/4.14.52/kernel/net/wireless/
cp nanopi-usb-wifi-dongle-driver-4.14.52/8821cu.ko /lib/modules/4.14.52/kernel/net/wireless/
depmod -a 4.14.52
```