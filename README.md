[![Build OpenWrt](https://github.com/minax007/ASRock_G10_OpenWrt/actions/workflows/build-openwrt.yml/badge.svg)](https://github.com/minax007/ASRock_G10_OpenWrt/actions/workflows/build-openwrt.yml)
[![release](https://img.shields.io/github/v/release/minax007/ASRock_G10_OpenWrt.svg)](https://github.com/minax007/ASRock_G10_OpenWrt/releases)


# OpenWrt snapshot for ASRock G10 incl. LuCI

This GitHub action is to build fresh images of latest OpenWrt snapshot using imagebuilder.

Following packages are already installed, so that you do not need to install them via the command line afterwards: 

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
