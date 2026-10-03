# xiaomi-mt6991

Development for the **POCO X8 Pro Max** (codename `dash`, MediaTek Dimensity 9500s (MT6991)).

Open-source side of the port. Vendor blobs are on GitLab: <https://gitlab.com/xiaomi-mt6991>.

## Repositories

| Repository | Description |
|---|---|
| [device_xiaomi_dash](https://github.com/xiaomi-mt6991/device_xiaomi_dash) | Main device tree |
| [device_xiaomi_dash-miuicamera](https://github.com/xiaomi-mt6991/device_xiaomi_dash-miuicamera) | MIUICamera tree |
| [device_xiaomi_dash-kernel](https://github.com/xiaomi-mt6991/device_xiaomi_dash-kernel) | Prebuilt kernel and device tree blobs |
| [hardware_mediatek](https://github.com/xiaomi-mt6991/hardware_mediatek) | MediaTek hardware modules |
| [hardware_xiaomi](https://github.com/xiaomi-mt6991/hardware_xiaomi) | Xiaomi hardware modules |
| [hardware_nxp_nfc](https://github.com/xiaomi-mt6991/hardware_nxp_nfc) | NXP NFC |
| [device_mediatek_sepolicy_vndr](https://github.com/xiaomi-mt6991/device_mediatek_sepolicy_vndr) | MediaTek vendor SEPolicy |
| [packages_apps_LunarisDolby](https://github.com/xiaomi-mt6991/packages_apps_LunarisDolby) | Dolby app |
| [packages_modules_DeviceLock](https://github.com/xiaomi-mt6991/packages_modules_DeviceLock) | DeviceLock fork |
| [packages_modules_Bluetooth](https://github.com/xiaomi-mt6991/packages_modules_Bluetooth) | Bluetooth fork |
| [external_wpa_supplicant_8](https://github.com/xiaomi-mt6991/external_wpa_supplicant_8) | wpa_supplicant fork |
| [vendor_qcom_opensource_vibrator](https://github.com/xiaomi-mt6991/vendor_qcom_opensource_vibrator) | Vibrator HAL |
| [local_manifests](https://github.com/xiaomi-mt6991/local_manifests) | Manifest for this organisation |
| [poco_dash_dump](https://github.com/xiaomi-mt6991/poco_dash_dump) | Stock ROM dump tool |

## Build

```bash
git clone -b bka https://github.com/xiaomi-mt6991/local_manifests .repo/local_manifests
```

Default branch is `bka`. LineageOS, Evolution-X and AxionOS are all supported via
`lineage_dash.mk`, `evolution.mk` and `axion.mk`.
