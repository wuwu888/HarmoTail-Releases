# HarmoTail 安装说明

HarmoTail 以 HarmonyOS `.hap` 安装包形式发布。

对于普通用户，推荐使用 **小白调试助手** 安装 HarmoTail，无需安装 DevEco Studio。

## 1. 下载 HarmoTail

前往 HarmoTail Releases：

https://github.com/wuwu888/HarmoTail-Releases/releases/latest

当前正式版本：

`HarmoTail-v0.16.1-signed.hap`

SHA256：

`4c10333a63fe3e1cdcf5367a6d26964ea8d870106c427a3eab7bde4b178ade2c`

## 2. 下载小白调试助手

官方 GitHub 项目：

https://github.com/likuai2010/auto-installer

最新版下载：

https://github.com/likuai2010/auto-installer/releases/latest

Windows 用户下载 Windows 版本。

Mac 用户下载 Mac 版本。

## 3. 开启 HarmonyOS 开发者模式

在手机上：

1. 打开“设置 → 关于本机”
2. 连续点击“软件版本”约 5 次
3. 开启开发者模式
4. 返回设置，进入“系统 → 开发者选项”
5. 开启“无线调试”

不同 HarmonyOS 版本的菜单名称可能略有差异。

## 4. 使用小白调试助手连接手机

在电脑打开小白调试助手。

按照软件提示，通过：

- 无线调试
- 或 USB 数据线

连接 HarmonyOS 设备。

## 5. 安装 HarmoTail

手机连接成功后：

1. 在小白调试助手中选择 HAP 安装功能
2. 选择 `HarmoTail-v0.16.1-signed.hap`
3. 按照界面提示完成安装

如果工具提示需要登录、签名或配置 Profile，请按照小白调试助手的界面提示完成。

安装完成后，可以直接在手机桌面打开 HarmoTail。

## 6. Mac 用户提示

如果 macOS 首次运行小白调试助手时被系统拦截，可以打开终端执行：

    xattr -d com.apple.quarantine /Applications/小白调试助手.app

然后重新启动小白调试助手。

## 7. 升级 HarmoTail

发布新版本后：

1. 下载新版 HarmoTail HAP
2. 使用小白调试助手再次安装
3. 选择覆盖安装

建议不要先卸载旧版本，也不要主动清除应用数据，以保留已有账号和 Tailnet 状态。

## 8. 首次使用 HarmoTail

打开 HarmoTail 后：

1. 启动连接
2. 根据提示完成 Tailscale 身份认证
3. 如果 Tailnet 开启设备审批，请等待管理员批准
4. 连接成功后即可查看 Tailnet 设备并使用相关功能

## 9. 问题反馈

进入 HarmoTail：

**设置 → 技术支持**

可以：

- 复制支持报告
- 导出支持报告

反馈邮箱：

`harmotail@163.com`
