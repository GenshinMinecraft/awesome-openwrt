# Awesome OpenWrt

> OpenWrt 项目是一个针对嵌入式设备的 Linux 操作系统。OpenWrt 不是一个单一且不可更改的固件，而是提供了具有软件包管理功能的完全可写的文件系统。这使您可以从供应商提供的应用范围和配置中解脱出来，并且让您通过使用适配任何应用的软件包来定制设备。对于开发人员来说，OpenWrt 是一个无需围绕它构建完整固件就能开发应用程序的框架；对于普通用户来说，这意味着拥有了完全定制的能力，能以意想不到的方式使用该设备。

![](https://raw.githubusercontent.com/GenshinMinecraft/awesome-openwrt/main/images/OpenWrt.png)

Awesome OpenWrt 旨在提供 *好玩、有趣、方便* 的 OpenWrt 软件包列表，所有软件包均可在对应的 GitHub 链接内或 [OpenWrt 源](https://downloads.openwrt.org/)寻找

**WE LOVE OPEN-SOURCE**


## 目录

- [Network 网络类](https://github.com/GenshinMinecraft/awesome-openwrt#Network)
- [Manage 管理类](https://github.com/GenshinMinecraft/awesome-openwrt#Manage)
- [Proxy 代理类](https://github.com/GenshinMinecraft/awesome-openwrt#Proxy)
- [Service 服务类](https://github.com/GenshinMinecraft/awesome-openwrt#Service)
- [Monitor 监控类](https://github.com/GenshinMinecraft/awesome-openwrt#Monitor)

## Network

一些与 网络、DNS、DHCP、分流、防火墙等 有关的软件包

- [luci-app-adguardhome](https://github.com/rufengsuixing/luci-app-adguardhome): 复杂的 AdGuardHome 的 OpenWrt 的 luci 界面
- [luci-app-homebox](https://github.com/selfcan/luci-app-homebox): 基于 Homebox 的内网测速服务
- [luci-app-socat](https://github.com/chenmozhijin/luci-app-socat): 基于 Socat 的端口转发服务
- [luci-app-syncdial](https://github.com/rufengsuixing/luci-app-syncdial): 多线多播 / 单线多拨服务
- [luci-app-ddns-go](https://github.com/sirpdboy/luci-app-ddns-go): 自动获得你的公网 IPv4 或 IPv6 地址，并解析到对应的域名服务。支持的域名服务商 Alidns / Dnspod / Cloudflare / 华为云 / Callback / 百度云 / Porkbun / GoDaddy
- [luci-app-netspeedtest](https://github.com/sirpdboy/netspeedtest): 网络速度诊断测试 (包括：内网网页版测速、内网 Iperf3 吞吐测速、外网 Speedtest.net 网速测试、特定服务器的端口延迟测)
- [luci-app-nlbwmon](https://openwrt.org/packages/pkgdata/luci-app-nlbwmon): 网络流量监控
- [luci-app-wrtbwmon](https://github.com/brvphoenix/luci-app-wrtbwmon): 网络流量监控
- [luci-app-sqm](https://openwrt.org/packages/pkgdata/luci-app-sqm): Qos 限速
- [luci-app-wifidog](https://github.com/walkingsky/luci-wifidog): 无线认证 Wifidog 的 Luci 管理界面