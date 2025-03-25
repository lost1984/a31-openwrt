# OpenWRT-CI
云编译OpenWRT固件 for A31 

# 插件情况
去除USB
luci-app-passwall=y
luci-app-gecoosac=y #集客AC 1.0
luci-app-tailscale=y
luci-app-autoreboot=y
luci-theme-kucat=y
luci-app-zerotier=y
luci-app-lucky=y


官方版：
https://github.com/immortalwrt/immortalwrt.git



# 固件简要说明：

固件每天早上4点自动编译。

固件信息里的时间为编译开始的时间，方便核对上游源码提交时间。



# 目录简要说明：

workflows——自定义CI配置

Scripts——自定义脚本

Config——自定义配置
