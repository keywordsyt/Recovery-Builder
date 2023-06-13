# Use Github Action to compile Recovery

- Support TWRP SHRP PBRP OFRP compilation and production

---

## Thanks to
- All contributors

---

## Release Notes
```
= 2023/06/13
- Added Support for PBRP SHRP
- Other improvements
- Merging OFPR With TWRP Action Build Repo
- Now Those Recoveries Should Work JUST FINE:
  1 TeamWin Recovery Project (TWRP)
  2 Pitch Black Recovery Project (PBRP)
  3 Sky Hawk Recovery Project (SHRP)
  4 Orangefox Recovery Project (OFRP)
  Thanks to @azwhikaru for those scripts really and those who helped him

= 2022/10/28
- OFRP manifest is changed, so not fully support OFRP now (if you can slove this, please submit a pull request!)

= 2022/07/08
- TWRP and TWRP-based 5.X ~ 12.X are ***ALL COMPILED SUCCESSFULLY***

= 2022/07/06
- Add support for 5.1 branch

= 2022/07/05
- Updated to work with trees back to 6.0
- Add conditionals to include common trees for syncing
- Update README for SSH keys

= 2022/07/04
- Updated to work with Android 12.1 AOSP minimal TWRP manifest

= 2022/05/29
- Should work correctly with Android 11 based source code

= 2022/02/03
- Due to the hardware resource limitation of GitHub action, this version cannot be compiled based on AOSP and other source codes of Android 11 and above. If necessary, please use local compilation

= 2021/10/29: 
- Refactored version 2.0
- Completely reconstruct the use logic to reduce the difficulty of use
- Optimize the parameter transfer part, now you can run multiple Workers at the same time
```

-----

## Parameter Description

| Name | Description | Example |
| ------------ | -------------------- | ------------ |
| `MANIFEST_URL` | Source address | https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp.git |
| `MANIFEST_BRANCH` | Source branch | twrp-12.1 |
| `DEVICE_TREE_URL` | Device address | https://github.com/SWDevelopments/device_realme_RMX2170-TWRP |
| `DEVICE_TREE_BRANCH` | Device branch | main |
| `DEVICE_PATH` | Device location | device/realme/RMX2170 |
| `DEVICE_NAME` | Model name | I003D |
| `MAKEFILE_NAME` | Makefile name | twrp_I003D |
| `BUILD_TARGET` | Build Target Partition (boot/recovery/vendorboot) | recovery |

-----

## Compilation results
Can be downloaded at [Release](../../releases)

-----
## Remark

#### TeamWin Recovery Project: https://github.com/minimal-manifest-twrp
#### OrangeFox Recovery Project: https://gitlab.com/OrangeFox/
#### SKYHAWK Recovery Project: https://github.com/SHRP/manifest
