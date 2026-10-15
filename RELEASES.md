# 发布渠道

## 唯一公开真源

- 产品说明：https://github.com/Superoutman/Bubboo
- 所有版本与下载：https://github.com/Superoutman/Bubboo/releases
- 最新稳定版：https://github.com/Superoutman/Bubboo/releases/latest
- 稳定版元数据：https://api.github.com/repos/Superoutman/Bubboo/releases/latest

尚未发布正式版本时，最新稳定版页面或 API 可能返回 404；这不代表已存在可下载版本。

## 发行约定

- 正式版标签使用 `v<major>.<minor>.<patch>`，例如 `v0.1.0`。
- 每个版本的 Release 正文提供用户可读的更新说明、系统要求及支持的处理器架构。
- 安装包使用 `Bubboo-<version>-<arch>.zip` 或 `.dmg`；`arch` 为实际构建的 `arm64`、`x86_64` 或 `universal`。
- 同一 Release 附带 `SHA256SUMS` 和 `THIRD_PARTY_NOTICES.txt`，随包保留所需第三方完整许可证。
- 预发布版本标记为 prerelease，不作为最新稳定版。
- 已发布的版本不覆盖安装包；修正通过新版本发布。

当前尚未接入应用内自动更新，也未提供 Sparkle appcast。未来更新客户端及 feed 必须基于本仓库已发布、可验证的 Release 资产建立，不使用私有源码仓库作为用户下载来源。
