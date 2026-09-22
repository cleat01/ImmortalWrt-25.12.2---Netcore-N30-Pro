# ImmortalWrt 25.12.2 | Netcore N30 Pro
> 已修复 USB VBUS 供电问题，原生支持USB外接存储。

## ✨ 固件特性
- 基于官方 ImmortalWrt v25.12.2 源码编译，内核6.12
- 设备：磊科 Netcore N30 Pro（MT7988A，aarch64_cortex-a53）
- ✅ 修复USB VBUS供电DTS补丁，USB硬盘/U盘可正常识别供电
- 包管理器：新版`apk`（不再支持旧`.ipk`软件包，请使用`.apk`格式）
- 预置基础LuCI中文界面，可按需在编译脚本增减插件

## 📥 下载固件
前往右侧 `Releases` 下载编译好的固件。
- `sysupgrade`：固件内升级（保留配置）
- `factory`：U-Boot 全新刷机（清空分区，首次刷机用）

## 📝 刷机步骤
1. U-Boot web页面刷入 `factory` 固件（首次刷机）
2. 系统内升级使用 `sysupgrade`
3. 刷机完成后，默认网关：`192.168.1.1`，默认密码无，首次登录请设置密码

