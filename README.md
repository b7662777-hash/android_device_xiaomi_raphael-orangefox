# KaliFox Recovery Device Tree for Redmi K20 Pro (raphael)

> Device tree for building **KaliFox Recovery** for the Xiaomi Redmi K20 Pro / Mi 9T Pro (codename: `raphael`).

---

## Device Specifications

| Device | Redmi K20 Pro |
|--------|---------------|
| SoC | Qualcomm Snapdragon 855 |
| GPU | Adreno 640 |
| RAM | 6GB / 8GB LPDDR4X |
| Storage | 64GB / 128GB / 256GB UFS 2.1 |
| Display | 6.39" AMOLED, 1080×2340 |
| Battery | 4000mAh |

---

## Features

- ✅ Booting
- ✅ Android 12/13 Data Decryption
- ✅ ADB
- ✅ MTP
- ✅ OTG
- ✅ Vibration

---

## Build

```bash
lunch twrp_raphael-eng
mka recoveryimage
```

---

Maintainer: **Gojo**

Project: **KaliFox Recovery**
