<p align="center"><img src="assets/AppIcon.png" width="128" alt="Bubboo 应用图标"></p>

# Bubboo

[English](README.md) | 简体中文

Bubboo 是一款更轻巧、美观的原生 macOS 划词工具，可作为 PopClip 的替代选择。选中文字即可唤出可自定义的浮动工具条，也能导入兼容的 PopClip 扩展。

## 功能

- 快速复制、粘贴和网页搜索。
- 导入 `.popclipext` / `.popclipextz` 扩展，支持部分 URL、Shell、AppleScript 与 JavaScript 动作。
- 原生设置界面，可调整工具条和管理扩展。
- 中英双语跟随系统首选语言，其他语言默认使用英语。

扩展兼容性持续完善，并非所有 PopClip 扩展都受支持。

可将已安装扩展移至废纸篓；新扩展可从下方链接进入 PopClip 官方目录下载。

内置动作显示锁图标；打开设置时显示 Dock 图标，关闭后恢复原入口模式。

## 下载与更新

**最低系统要求：macOS 14.0（Sonoma）或更高版本。**

**当前版本：0.1.8 · Apple Silicon（M 系列芯片）。**

安装包已完成 Developer ID 签名及 Apple 公证，暂不提供 Intel 版本。

本仓库是 Bubboo 产品说明、官方下载和版本更新的唯一公开来源。应用已接入自动更新：点击设置底部的版本号可检查更新，有新版时显示绿色升级提示；关于页可控制自动检查与自动下载安装。自动更新使用本仓库的 appcast，安装包仍统一来自 Releases。

## 首次使用

下载解压后，将 `Bubboo.app` 移至「应用程序」并打开。在「系统设置 → 隐私与安全性 → 辅助功能」中允许 Bubboo，然后选中文字使用工具条。

新导入或内容变化的扩展默认停用，需在设置中明确启用。脚本扩展可能执行本地操作；仅启用可信来源的扩展。JavaScript 扩展访问网络时需要逐域名授权。

<a id="extensions"></a>

## 扩展下载

前往 [PopClip 官方扩展集合](https://www.popclip.app/extensions/) 浏览和下载扩展。

下载扩展包后，在 Bubboo 设置中选择「导入扩展」，再手动启用；有选项的扩展也可在设置中配置。新导入或内容变化的扩展需重新授权。

Bubboo 支持不少 PopClip 扩展，但具体能否运行取决于扩展和目标 App。部分扩展依赖 Bubboo 尚未支持的 PopClip 功能、其他应用或在线服务。请只安装可信来源的扩展。

Bubboo 暂不继续维护独立精选扩展目录；Bubboo 与 PopClip 是独立产品。

## 反馈

请通过 [Issues](https://github.com/Superoutman/Bubboo/issues) 提交问题或建议，附上 macOS 版本、Bubboo 版本及复现步骤。请勿上传选中文本、密码或其他隐私信息。

## 关于本仓库

此仓库仅承载产品文档及发行文件，应用源码独立维护、不在此公开。公开可见不代表授予源码或品牌素材的开源使用许可。

Bubboo 为独立产品，与 PopClip 无隶属关系。发行包随附适用的第三方许可和声明。

发布渠道与文件约定见 [发布渠道](RELEASES.zh-CN.md)。
