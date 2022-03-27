# xiaomi_R3G V1_Openwrt
这是一个利用P3TERX编写的Github action小米路由器3G V1 openwrt自动云编译固件

基于lean的openwrt与kanzok8的openwrt-packages

## Full Version
主分支仅集成passwall(xray core)、ShadowSocksR Plus+（xray core)、SmartDNS 和 集成usb支持，aria2，samba，minidlna
并包含例如Python、解压缩、加密等在内的package

具体配置可以修改：config/full.config

## Lite Version 
主分支仅集成passwall(xray core)、ShadowSocksR Plus+（xray core)、SmartDNS。目的只针对网络需求

具体配置可以修改：config/lite.config

## Reference
* https://github.com/P3TERX/Actions-OpenWrt
* https://github.com/coolsnowwolf/lede
* https://github.com/kenzok8/openwrt-packages

# openwrt official rom
建议先刷 [openwrt](https://downloads.openwrt.org/) 标准版本，例如：

https://downloads.openwrt.org/releases/21.02.2/targets/ramips/mt7621/

然后在openwrt中刷入release中的 sysupgrade 文件