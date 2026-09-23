# AES67 Virtual Soundcard Releases

AES67 Virtual Soundcard 的 Windows 二进制发布仓库。

> 本仓库仅用于发布经过打包的可执行版本，不包含项目源码、开发历史、用户配置或媒体文件。

## 下载与使用

1. 打开右侧 **Releases**。
2. 下载对应版本的 Windows x64 ZIP。
3. 对照同版本的 `.sha256.txt` 校验文件确认下载完整性。
4. 解压整个 ZIP 后，运行 `AES67 Virtual Soundcard.exe`。

## 当前预览版

`v0.1.52-preview`

- 修复启动过程界面闪烁，启动器改用 GDI 双缓冲绘制。
- 仪表盘加入中文、英文、西班牙语切换。
- 语言选择会保存在本机浏览器中。
- 保留 AES67/PTPv2、播放器、运行监控及诊断功能。

## 注意

- 当前为 Preview 预览版本，不建议未经长时间实机验证直接用于关键播出环境。
- Windows 可能对未签名可执行文件显示 SmartScreen 提示。
- GitHub Release 只提供二进制包，不代表源码以开源许可证发布。