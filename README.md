# 方舟桌宠

“方舟桌宠”是一个非官方同人桌宠下载页。本仓库只提供软件介绍、安装说明、截图、版本记录、问题反馈和安装包下载，不公开开发源码，也不包含角色 GIF 素材目录。

> **安装包尚未公开发布**
>
> macOS 与 Windows 候选包仍在完成发布前启动验证。验证通过后，将在 [GitHub Releases](https://github.com/xihuii17/fangzhou-desktop-pets/releases) 开放下载；在此之前请勿从其他来源获取候选包。
>
> 正式下载前请认准角色名称、版本、平台与“通用版”字样，并在 [完整安装包清单](RELEASE_MANIFEST.md) 中核对文件大小和 SHA-256。

## 下载

| 桌宠 | 版本 | 简介 | 支持系统 | 计划下载页 |
| --- | --- | --- | --- | --- |
| <img src="docs/images/zhuang-fangyi.png" alt="庄方宜桌宠" width="110"><br>庄方宜桌宠 | 0.7.3 | 162 个内置动作，支持点击互动、随机动作、动作管理；macOS 可选 QQ 音乐同步歌词。 | macOS 11+ Apple Silicon；Windows 10/11 x64 | [zhuang-fangyi-v0.7.3](https://github.com/xihuii17/fangzhou-desktop-pets/releases/tag/zhuang-fangyi-v0.7.3) |
| <img src="docs/images/kaltsit-sihengtuo.png" alt="凯尔希-思衡托桌宠" width="110"><br>凯尔希-思衡托桌宠 | 0.1.1 | 197 个内置动作，支持点击互动、随机动作和动作管理。 | macOS 11+ Apple Silicon；Windows 10/11 x64 | [kaltsit-sihengtuo-v0.1.1](https://github.com/xihuii17/fangzhou-desktop-pets/releases/tag/kaltsit-sihengtuo-v0.1.1) |
| <img src="docs/images/kaltsit-childhood.png" alt="凯尔希童真桌宠" width="110"><br>凯尔希童真桌宠 | 0.1.1 | 122 个内置动作，支持点击互动、随机动作和动作管理。 | macOS 11+ Apple Silicon；Windows 10/11 x64 | [kaltsit-childhood-v0.1.1](https://github.com/xihuii17/fangzhou-desktop-pets/releases/tag/kaltsit-childhood-v0.1.1) |
| <img src="docs/images/endministrator-unmasked.png" alt="管理员桌宠（不带面罩）" width="110"><br>管理员桌宠（不带面罩） | 0.1.1 | 183 个不带面罩形态动作，支持点击互动、随机动作和动作管理。 | macOS 11+ Apple Silicon；Windows 10/11 x64 | [endministrator-unmasked-v0.1.1](https://github.com/xihuii17/fangzhou-desktop-pets/releases/tag/endministrator-unmasked-v0.1.1) |
| <img src="docs/images/endministrator-masked.png" alt="管理员桌宠（带面罩）" width="110"><br>管理员桌宠（带面罩） | 0.1.0 | 165 个带面罩形态动作，支持点击互动、随机动作和动作管理。 | macOS 11+ Apple Silicon；Windows 10/11 x64 | [endministrator-masked-v0.1.0](https://github.com/xihuii17/fangzhou-desktop-pets/releases/tag/endministrator-masked-v0.1.0) |
| <img src="docs/images/endministrator.png" alt="管理员桌宠（双形态）" width="110"><br>管理员桌宠（双形态） | 0.1.0 | 集成 348 个动作，可在带面罩与不带面罩形态之间切换。 | macOS 11+ Apple Silicon；Windows 10/11 x64 | [endministrator-v0.1.0](https://github.com/xihuii17/fangzhou-desktop-pets/releases/tag/endministrator-v0.1.0) |

每个 Release 尽量提供以下三个文件：

- macOS Apple Silicon：`*.dmg`
- Windows x64 安装版：`*-安装包.exe`
- Windows x64 免安装版：`*-免安装版.zip`

本页只发布通用版。**AI 版、养成测试版、录制体验版和其他实验构建不得混入上述下载。**

## Windows 安装

### 安装版

1. 从对应角色的 Release 下载带有 `Windows` 和 `安装包.exe` 的文件。
2. 在 [安装包清单](RELEASE_MANIFEST.md) 中核对文件大小和 SHA-256。
3. 双击安装包，选择安装位置并完成安装。

### 免安装版

1. 下载带有 `Windows` 和 `免安装版.zip` 的文件。
2. 完整解压 ZIP；不要直接在压缩包预览窗口内运行。
3. 双击文件夹内以角色命名的 `.exe` 主程序。

### Windows 安全提示

当前安装包未购买代码签名证书，Windows SmartScreen 或安全软件可能显示“未知发布者”。请只从本仓库 Releases 下载并核对 SHA-256；校验不一致时不要运行。若 SmartScreen 拦截，可在确认文件来源和校验值后选择“更多信息”查看文件详情。不要为了安装桌宠而长期关闭系统安全防护。

## macOS 安装与首次打开

1. 下载对应角色的 `macOS-版本号.dmg`。
2. 打开 DMG，将桌宠拖入“应用程序”文件夹。
3. 当前 DMG 未经过 Apple 开发者签名和公证。首次打开时，请在 Finder 的“应用程序”中按住 Control 点击桌宠，选择“打开”，再在提示中确认“打开”。
4. 如果仍被拦截，可前往“系统设置 → 隐私与安全性”，在安全提示旁选择“仍要打开”。

当前 macOS 包只提供 Apple Silicon（arm64）版本，不支持 Intel Mac。

## 已知问题

- macOS 与 Windows 安装包目前均未使用商业代码签名；首次打开可能出现系统安全提示。
- macOS 当前只有 Apple Silicon 版本，Intel Mac 暂不支持。
- Windows 当前只有 x64 版本，Windows on ARM 未单独提供原生安装包。
- 庄方宜桌宠的 QQ 音乐同步歌词只在 macOS 提供，默认关闭；开启后需要辅助功能权限，并依赖 QQ 音乐与第三方歌词服务可用性。
- 角色动作数量较多，安装包体积会明显大于普通桌面小工具。

## 版本记录

| 日期 | 角色 | 版本 | 说明 |
| --- | --- | --- | --- |
| 2026-08-29 | 庄方宜桌宠 | 0.7.3 | 首次纳入统一公开下载页。 |
| 2026-08-29 | 凯尔希-思衡托桌宠 | 0.1.1 | 首次纳入统一公开下载页。 |
| 2026-08-29 | 凯尔希童真桌宠 | 0.1.1 | 依据 0.1.1 角色配置重新构建，替换旧 0.1.0 候选包。 |
| 2026-08-29 | 管理员桌宠（不带面罩） | 0.1.1 | 首次纳入统一公开下载页。 |
| 2026-08-29 | 管理员桌宠（带面罩） | 0.1.0 | 首次纳入统一公开下载页。 |
| 2026-08-29 | 管理员桌宠（双形态） | 0.1.0 | 首次纳入统一公开下载页。 |

更完整的记录见 [CHANGELOG.md](CHANGELOG.md)。

## 隐私说明

- 通用版不包含 AI 对话功能，不需要也不应要求用户填写任何 API Key。
- 桌宠设置、自定义动作和诊断信息保存在本机用户数据目录；项目不内置遥测或用户分析服务。
- 庄方宜桌宠的 QQ 音乐同步歌词默认关闭。用户主动开启后，应用会在 macOS 本机读取 QQ 音乐当前曲目信息，并把歌名、歌手等搜索参数发送至 `lrclib.net` 查找歌词；结果会缓存在本机。
- 提交 Issue 前请检查截图和日志，不要公开 API Key、账号、个人路径或其他敏感信息。

## 反馈与问题

请前往 [GitHub Issues](https://github.com/xihuii17/fangzhou-desktop-pets/issues) 提交反馈。请注明桌宠名称、版本、操作系统、安装包文件名、问题复现步骤，以及是否能稳定复现。

## 非官方同人声明

本项目为非官方同人项目，与《明日方舟》及其权利方无官方隶属、授权或背书关系。角色名称、形象及相关素材的权利归原权利方所有。下载内容仅供个人桌面娱乐与交流使用，请勿用于商业用途或重新打包分发。详见 [NOTICE.md](NOTICE.md)。
