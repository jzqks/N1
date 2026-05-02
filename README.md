# 项目简介
本固件适配斐讯 N1 旁路网关（不具备 PPPoE、WiFi 相关功能）。<br>
固件包含下列 luci-app：<br>
[luci-app-amlogic](https://github.com/ophub/luci-app-amlogic)：晶晨宝盒<br>
[luci-app-passwall](https://github.com/Openwrt-Passwall/openwrt-passwall)：科学上网<br>
luci-app-dockerman：Docker管理<br>
luci-app-samba4：NAS网络共享<br>
***
# 致谢
本项目基于 [ImmortalWrt-24.10](https://github.com/immortalwrt/immortalwrt/tree/openwrt-24.10) 源码编译，使用 ophub 的[脚本](https://github.com/ophub/amlogic-s9xxx-openwrt)和[内核](https://github.com/ophub/kernel/releases/tag/kernel_flippy)打包成完整固件，感谢开发者们的无私分享。<br>
