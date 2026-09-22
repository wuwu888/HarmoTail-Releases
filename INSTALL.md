# HarmoTail 安装说明

## 1. 下载

前往 GitHub Releases 下载最新版本：

`HarmoTail-v0.16.1-signed.hap`

## 2. 校验文件

v0.16.1 官方安装包 SHA256：

`4c10333a63fe3e1cdcf5367a6d26964ea8d870106c427a3eab7bde4b178ade2c`

建议安装前核对 SHA256。

macOS 校验命令：

    shasum -a 256 HarmoTail-v0.16.1-signed.hap

正确结果应为：

    4c10333a63fe3e1cdcf5367a6d26964ea8d870106c427a3eab7bde4b178ade2c

## 3. 安装

按照 HarmonyOS 支持的 HAP 安装方式安装 HarmoTail。

如果已经安装旧版本，建议直接覆盖安装，不要主动清除应用数据，以保留已有账号及 Tailnet 状态。

## 4. 首次使用

打开 HarmoTail 后：

1. 启动连接
2. 根据提示完成 Tailscale 身份认证
3. 如果 Tailnet 开启了设备审批，请等待管理员批准
4. 连接成功后即可查看 Tailnet 设备并使用相关功能

## 5. 问题反馈

如果出现连接、登录、DNS 或文件传输异常：

进入：

**设置 → 技术支持**

选择：

- 复制支持报告
- 导出支持报告

然后发送至：

`harmotail@163.com`
