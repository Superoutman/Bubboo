# 发布渠道

[English](RELEASES.md) | 简体中文

## 唯一公开真源

- 产品说明：https://github.com/Superoutman/Bubboo
- 所有版本与下载：https://github.com/Superoutman/Bubboo/releases
- 最新稳定版：https://github.com/Superoutman/Bubboo/releases/latest
- 稳定版元数据：https://api.github.com/repos/Superoutman/Bubboo/releases/latest

当前稳定版本为 **0.1.8（build 12）**，适用于 macOS 14.0 及更高版本的 Apple Silicon Mac。

## 发行约定

- 正式版标签使用 `v<major>.<minor>.<patch>`，例如 `v0.1.3`。
- Release 标题只使用产品名和版本号；更新说明默认使用英文，包含系统要求及支持的处理器架构。
- 安装包使用 `Bubboo-<version>-<arch>.zip` 或 `.dmg`；`arch` 为实际构建的 `arm64`、`x86_64` 或 `universal`。
- Release 附带 `SHA256SUMS`；第三方许可证及声明保留在 App 包内，不再单独上传声明附件。
- 预发布版本标记为 prerelease，不作为最新稳定版。
- 已发布的版本不覆盖安装包；修正通过新版本发布。

## 应用内自动更新

固定 feed：https://raw.githubusercontent.com/Superoutman/Bubboo/main/appcast.xml

Bubboo 使用 Sparkle 检查、下载、验证签名并安装更新。后台下载完成后可在退出时安装，也可点击设置中的绿色版本提示立即升级；关于页提供自动检查和自动下载安装开关。

当前 appcast 提供 0.1.8 的签名更新并保留旧版本。条目必须指向本仓库已发布的 Release 安装包，并包含 Sparkle EdDSA 签名、构建号、显示版本、最低系统要求及适用的硬件要求。先验证 Release 附件可下载，再更新 appcast；保留兼容旧系统和处理器的历史条目。

此 feed 地址是已安装客户端依赖的长期入口，不得随意删除或迁移。
