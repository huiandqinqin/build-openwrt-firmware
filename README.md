# Openwrt sbcbox firmware
Scripts for build openwrt router box firmware.

# Features

* Use [Immortalwrt](https://github.com/immortalwrt/immortalwrt) source, which makes things easier.
* Use Openwrt 21.02 branch.
* For TV boxes, use [unifreq's script](https://github.com/unifreq/openwrt_packit/blob/master/README.ACTION.md) and [flippy's kernel](https://github.com/breakings/OpenWrt/tree/main/opt/kernel) (pre-compiled), which makes things better.
* Enable IPv6 compatibility by default.
* Enable Flow Offloading and Full Cone NAT by default.
* Enable WiFi by default. You can turn it off to achieve lower temperature.
* You can fork this repo and make your own [package config](https://github.com/riverscn/openwrt-sbcbox-firmware/blob/main/configs/custom.seed). It's very easy.

# Pre-installed packages

* luci-app-passwall
* luci-app-udpxy
* luci-app-upnp
* luci-theme-argon

# Build Locally

Alternatively, you can build openwrt on your own computer.

Support Ubuntu or Debian. You can run in a Virtual Machine or Docker [container](https://github.com/riverscn/openwrt-dev-container) (recommend).

Run `./build.sh` and that's all.