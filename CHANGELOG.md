# Changelog

## v0.16.1

首个面向普通用户的公开发行版本。

### 核心升级

- Tailscale Core 升级至 v1.102.4
- OpenHarmony Go Runtime 升级至 Go 1.26.6
- Tailscale 设备名称支持根据设备型号自动生成

### 产品体验

- 正式用户界面重新整理
- 新增简化的“技术支持”页面
- 保留脱敏支持报告导出能力
- 内部开发、取证和诊断入口默认隐藏
- About 页面移除 Beta 标识

### 网络与设备

- 保留 Exit Node、DNS、Tailnet Lock、Taildrop、Taildrive 等功能
- 保留 VPN 自动恢复及后台诊断能力
- 隐藏内部诊断界面不会影响 VPN 自愈机制

### 验证

- Release Compliance：19 / 19 通过
- Third-party notice：38 dependencies / 40 components
- 已在 Huawei Mate X7 完成真机验证

### 安装包

文件：

`HarmoTail-v0.16.1-signed.hap`

SHA256：

`4c10333a63fe3e1cdcf5367a6d26964ea8d870106c427a3eab7bde4b178ade2c`
