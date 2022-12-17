[![Build OpenWrt](https://github.com/minax007/ASRock_G10_OpenWrt/actions/workflows/build-snapshot.yml/badge.svg)](https://github.com/minax007/ASRock_G10_OpenWrt/actions/workflows/build-snapshot.yml)
[![Build OpenWrt](https://github.com/minax007/ASRock_G10_OpenWrt/actions/workflows/build-release.yml/badge.svg)](https://github.com/minax007/ASRock_G10_OpenWrt/actions/workflows/build-release.yml)
[![release](https://img.shields.io/github/v/release/minax007/ASRock_G10_OpenWrt.svg)](https://github.com/minax007/ASRock_G10_OpenWrt/releases)
# OpenWrt for ASRock G10

These GitHub actions are for building OpenWrt based on snapshot or official releases using imagebuilder.

![Unbenannt](https://user-images.githubusercontent.com/67478561/208256549-b7e62f22-a12d-448e-8c85-1b1aca04fd76.jpg)

Following packages are already included in the builds: 

Added features | Package names
------------ | -------------
**LuCI GUI** | luci
**LuCI Material Theme** | luci-theme-material 
**LuCI Bandwidth Monitor** | luci-app-nlbwmon
**LuCI Adblock** | luci-app-adblock
__________________________________________________________________
**Official OpenWrt snapshot build without LuCI:**

https://firmware-selector.openwrt.org/?version=SNAPSHOT&target=ipq806x%2Fgeneric&id=asrock_g10
__________________________________________________________________
**Official OpenWrt snapshot download directory for ipq806x routers, which includes the imagebuilder used in this action script:**

https://downloads.openwrt.org/snapshots/targets/ipq806x/generic/
