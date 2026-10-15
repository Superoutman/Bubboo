<p align="center"><img src="assets/AppIcon.png" width="128" alt="Bubboo 应用图标"></p>

# Bubboo

[English](README.md) | 简体中文

选中文字，让常用操作就在手边。Bubboo 是原生 macOS 文本选择工具，在选区附近显示轻巧的浮动工具条。

## 功能

- 快速复制、粘贴和网页搜索。
- 导入 `.popclipext` / `.popclipextz` 扩展，支持部分 URL、Shell、AppleScript 与 JavaScript 动作。
- 原生设置界面，可调整工具条和管理扩展。
- 中英双语跟随系统首选语言，其他语言默认使用英语。

扩展兼容性持续完善，并非所有 PopClip 扩展都受支持。

打开设置自动检查精选扩展更新，缓存 6 小时；手动逐项升级并保留配置；内容改变后需重新启用授权，不会自动升级。也可删除已安装扩展至废纸篓，或打开官方扩展下载页。

内置动作显示锁图标；打开设置时显示 Dock 图标，关闭后恢复原入口模式。

## 下载与更新

**最低系统要求：macOS 14.0（Sonoma）或更高版本。**

**当前版本：0.1.4 · Apple Silicon（M 系列芯片）。**

安装包已完成 Developer ID 签名及 Apple 公证，暂不提供 Intel 版本。

本仓库是 Bubboo 产品说明、官方下载和版本更新的唯一公开来源。应用已接入自动更新：点击设置底部的版本号可检查更新，有新版时显示绿色升级提示；关于页可控制自动检查与自动下载安装。自动更新使用本仓库的 appcast，安装包仍统一来自 Releases。

## 首次使用

下载解压后，将 `Bubboo.app` 移至「应用程序」并打开。在「系统设置 → 隐私与安全性 → 辅助功能」中允许 Bubboo，然后选中文字使用工具条。

新导入或内容变化的扩展默认停用，需在设置中明确启用。脚本扩展可能执行本地操作；仅启用可信来源的扩展。JavaScript 扩展访问网络时需要逐域名授权。

<a id="extensions"></a>

## 扩展下载

<!-- extension-table:start -->
扩展让 Bubboo 不止于内置动作：你可以为选中的文字选择不同的搜索服务、进行翻译和文本处理，或连接自己常用的工具。按工作习惯选择所需动作，就能组合出更适合自己的划词工具栏。

整理这份列表，是为了让扩展更容易被发现、比较和安装。下载入口、最低 App 版本、原作者及适配说明集中在同一处，减少四处寻找下载包、判断兼容性和反复试装的成本。项目希望在尊重原作者工作的基础上，为用户提供更多实用选择，也让每个扩展的来源与改动清晰可查。

**下表提供 31 个已验收扩展。** 收录前会检查兼容性并在 Bubboo 中实际测试；它是一份便于上手的精选目录，并非 PopClip 扩展的完整集合。部分扩展需要适配，点击名称即可了解来源、改动及已验证的使用范围，再决定是否安装。

**安装与更新：** 下载下表中的 `.popclipextz` 文件，在设置中导入并启用；有选项的扩展也在设置中配置。Bubboo 0.1.4 打开设置时检查扩展更新，结果缓存 6 小时。手动升级会保留配置，内容变化后需重新启用授权。扩展版本与 App 版本独立，升级前请检查表格中的最低 App 版本。

**兼容性与权限：** 验收不代表所有系统、地区站点和第三方服务均可用。依赖其他 App 的扩展需先安装对应应用，网站可能要求登录或受地区限制。网页搜索会将选中文字发送给对应网站，脚本可能执行本地操作，请仅启用可信扩展。详情见[扩展使用说明](https://github.com/Superoutman/Bubboo-Extensions#current-stable-collection)。

| 扩展 / Extension | 用途 | 版本 | 最低 Bubboo | 作者 / 许可证 | 下载 |
| --- | --- | --- | --- | --- | --- |
| [Amazon](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Amazon.popclipext/NOTICE.md) | Amazon 检索 | 0.1.0 | 0.1.4 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Amazon.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Amazon.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/Amazon-0.1.0.popclipextz) |
| [Baidu](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Baidu.popclipext/NOTICE.md) | 百度搜索 | 0.1.0 | 0.1.2 | [Junxue Zhang; Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Baidu.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Baidu.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/Baidu-0.1.0.popclipextz) |
| [Base64](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Base64.popclipext/NOTICE.md) | UTF-8 编解码，标准 / URL-safe（适配版） | 0.1.0 | 0.1.4 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Base64.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Base64.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/Base64-0.1.0.popclipextz) |
| [Bing](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Bing.popclipext/NOTICE.md) | Bing 搜索 | 0.1.0 | 0.1.2 | [Morton Fox; Nicholas Moore and contributors. Icon acknowledged upstream as Simple Icons.](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Bing.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Bing.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/Bing-0.1.0.popclipextz) |
| [Capitalize Words](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Capitalize.popclipext/NOTICE.md) | 单词首字母大写 | 0.1.0 | 0.1.4 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Capitalize.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Capitalize.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/Capitalize-0.1.0.popclipextz) |
| [Character Count](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/CharCount.popclipext/NOTICE.md) | 字符计数 | 0.1.0 | 0.1.2 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/CharCount.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/CharCount.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/CharCount-0.1.0.popclipextz) |
| [Comma List](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/CommaList.popclipext/NOTICE.md) | 逗号列表与多行互转 | 0.1.0 | 0.1.4 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/CommaList.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/CommaList.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/CommaList-0.1.0.popclipextz) |
| [DuckDuckGo](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/DuckDuckGo.popclipext/NOTICE.md) | 隐私搜索 | 0.1.0 | 0.1.2 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/DuckDuckGo.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/DuckDuckGo.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/DuckDuckGo-0.1.0.popclipextz) |
| [Ebay](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Ebay.popclipext/NOTICE.md) | Ebay 检索 | 0.1.0 | 0.1.4 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Ebay.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Ebay.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/Ebay-0.1.0.popclipextz) |
| [Full/Half Width](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/FullHalfWidth.popclipext/NOTICE.md) | 全角 / 半角转换 | 0.1.0 | 0.1.4 | [Lucifr; Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/FullHalfWidth.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/FullHalfWidth.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/FullHalfWidth-0.1.0.popclipextz) |
| [Goodreads](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Goodreads.popclipext/NOTICE.md) | Goodreads 检索 | 0.1.0 | 0.1.4 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Goodreads.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Goodreads.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/Goodreads-0.1.0.popclipextz) |
| [Google](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/GoogleSearch.popclipext/NOTICE.md) | Google 搜索，可选地区站点 | 0.1.0 | 0.1.2 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/GoogleSearch.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/GoogleSearch.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/GoogleSearch-0.1.0.popclipextz) |
| [Google Images](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/GoogleImages.popclipext/NOTICE.md) | Google Images 检索 | 0.1.0 | 0.1.4 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/GoogleImages.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/GoogleImages.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/GoogleImages-0.1.0.popclipextz) |
| [Google Maps](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/GoogleMaps.popclipext/NOTICE.md) | 地图搜索 | 0.1.0 | 0.1.2 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/GoogleMaps.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/GoogleMaps.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/GoogleMaps-0.1.0.popclipextz) |
| [Google Scholar](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/GoogleScholar.popclipext/NOTICE.md) | 学术搜索 | 0.1.0 | 0.1.2 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/GoogleScholar.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/GoogleScholar.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/GoogleScholar-0.1.0.popclipextz) |
| [Google Translate](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/GoogleTranslate.popclipext/NOTICE.md) | 网页翻译，可选地区站点 | 0.1.0 | 0.1.2 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/GoogleTranslate.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/GoogleTranslate.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/GoogleTranslate-0.1.0.popclipextz) |
| [IMDb](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/IMDb.popclipext/NOTICE.md) | IMDb 检索 | 0.1.0 | 0.1.4 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/IMDb.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/IMDb.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/IMDb-0.1.0.popclipextz) |
| [Join Lines](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/JoinLines.popclipext/NOTICE.md) | 合并多行 | 0.1.0 | 0.1.4 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/JoinLines.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/JoinLines.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/JoinLines-0.1.0.popclipextz) |
| [Lowercase](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Lowercase.popclipext/NOTICE.md) | 转小写 | 0.1.0 | 0.1.2 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Lowercase.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Lowercase.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/Lowercase-0.1.0.popclipextz) |
| [PubMed](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/PubMed.popclipext/NOTICE.md) | PubMed 检索 | 0.1.0 | 0.1.4 | [Pierre Wizla; Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/PubMed.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/PubMed.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/PubMed-0.1.0.popclipextz) |
| [Remove Spaces](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/RemoveSpaces.popclipext/NOTICE.md) | 删除空白 | 0.1.0 | 0.1.4 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/RemoveSpaces.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/RemoveSpaces.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/RemoveSpaces-0.1.0.popclipextz) |
| [Reverse](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Reverse.popclipext/NOTICE.md) | 反转行序 | 0.1.0 | 0.1.4 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Reverse.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Reverse.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/Reverse-0.1.0.popclipextz) |
| [Sentence Case](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/SentenceCase.popclipext/NOTICE.md) | 句首大写 | 0.1.0 | 0.1.4 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/SentenceCase.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/SentenceCase.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/SentenceCase-0.1.0.popclipextz) |
| [Sort](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Sort.popclipext/NOTICE.md) | 自然排序文本行 | 0.1.0 | 0.1.4 | [Agassi; Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Sort.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Sort.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/Sort-0.1.0.popclipextz) |
| [StartPage](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/StartPage.popclipext/NOTICE.md) | StartPage 检索 | 0.1.0 | 0.1.4 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/StartPage.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/StartPage.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/StartPage-0.1.0.popclipextz) |
| [Title Case](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/TitleCase.popclipext/NOTICE.md) | 英文单行标题大小写（适配版） | 0.1.0 | 0.1.4 | [John Gruber; Aristotle Pagaltzis; Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/TitleCase.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/TitleCase.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/TitleCase-0.1.0.popclipextz) |
| [Uppercase](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Uppercase.popclipext/NOTICE.md) | 转大写 | 0.1.0 | 0.1.2 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Uppercase.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Uppercase.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/Uppercase-0.1.0.popclipextz) |
| [Urban Dictionary](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/UrbanDictionary.popclipext/NOTICE.md) | Urban Dictionary 检索 | 0.1.0 | 0.1.4 | [zhiyelee; Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/UrbanDictionary.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/UrbanDictionary.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/UrbanDictionary-0.1.0.popclipextz) |
| [URL Encode](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/URLEncode.popclipext/NOTICE.md) | URL 编码 / 解码 | 0.1.0 | 0.1.2 | [Nicholas Moore and contributors; original Perl extension by Brett Terpstra.](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/URLEncode.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/URLEncode.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/URLEncode-0.1.0.popclipextz) |
| [Wikipedia](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Wikipedia.popclipext/NOTICE.md) | 维基百科，可选语言站点 | 0.1.0 | 0.1.2 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Wikipedia.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/Wikipedia.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/Wikipedia-0.1.0.popclipextz) |
| [YouTube](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/YouTube.popclipext/NOTICE.md) | 视频搜索 | 0.1.0 | 0.1.2 | [Nicholas Moore and contributors](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/YouTube.popclipext/NOTICE.md) · [MIT](https://github.com/Superoutman/Bubboo-Extensions/blob/main/extensions/YouTube.popclipext/LICENSE.txt) | [下载 / Download](https://github.com/Superoutman/Bubboo-Extensions/releases/download/v0.1.3/YouTube-0.1.0.popclipextz) |

## 版权与来源

扩展版权归原作者及相应权利人所有。Bubboo 对扩展的收录、兼容适配和分发，不代表拥有原作版权，也不表示原作者或 PopClip 官方认可或参与本项目。Bubboo 与 PopClip 是独立项目。

每个包保留原作者署名、适用许可证和来源记录；适配改动在 `NOTICE.md` 中说明。代码、图标等资源可能适用不同许可，使用或再分发时请查看包内文件。下载表格中的 MIT 指扩展代码；例如 Amazon 图标由 Dave Gandy 创作，适用 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)。

如发现署名、许可或收录有误，请通过[问题反馈](https://github.com/Superoutman/Bubboo-Extensions/issues)提供扩展名称、相关来源和问题说明，以便核查处理。

<!-- extension-table:end -->

## 反馈

请通过 [Issues](https://github.com/Superoutman/Bubboo/issues) 提交问题或建议，附上 macOS 版本、Bubboo 版本及复现步骤。请勿上传选中文本、密码或其他隐私信息。

## 关于本仓库

此仓库仅承载产品文档及发行文件，应用源码独立维护、不在此公开。公开可见不代表授予源码或品牌素材的开源使用许可。

Bubboo 为独立产品，与 PopClip 无隶属关系。发行包随附适用的第三方许可和声明。

发布渠道与文件约定见 [发布渠道](RELEASES.zh-CN.md)。
