# 设备检维修决策系统 · 绿色演示版

这是设备检维修决策系统的公开演示安装包下载页。安装包已经包含运行环境、网页、知识图谱、用户组态决策树、推理网络、检维修规程和匿名演示案例，不需要另行安装 Python、Node.js 或数据库。

## 下载

请从 [Releases](https://github.com/dddabtc/equip-maint-ai-downloads/releases/latest) 下载与你的系统和处理器匹配的文件：

| 系统 | Intel / AMD 64 位 | ARM 64 位 |
| --- | --- | --- |
| Windows | `windows-x64.zip` | `windows-arm64.zip` |
| macOS | `macos-x64.tar.gz` | `macos-arm64.tar.gz` |
| Linux | `linux-x64.tar.gz` | `linux-arm64.tar.gz` |

同时下载 `SHA256SUMS.txt`，核对文件摘要后再解压。

## 启动

- Windows：解压后双击 `启动.cmd`。
- macOS / Linux：解压后，在终端进入目录并运行 `./start.sh`。
- 浏览器默认打开 `http://127.0.0.1:8088`。
- 初次登录：`admin / admin`。首次登录后请立即修改密码。

程序、运行环境和知识都在解压目录内。账户、诊断、上传资料和日志保存在 `runtime/`，升级时保留该目录即可。

## 演示内容

- 六层知识、本体和知识图谱
- 用户组态决策树与推理网络
- 屏蔽泵 / 磁力泵独立知识空间
- 匿名检维修规程与演示设备 `CP-DEMO-01`
- 基于历史趋势的演示剩余寿命计算
- 网页与 Word 诊断报告
- 七种界面语言

演示数据均为人工构造，只用于介绍和功能验证，不用于现场设备决策。公开包不包含真实客户名称、账号状态、密钥、日志、上传文件或现场运行记录。

## 提示

Windows 与 macOS 安装包目前未使用商业代码签名。系统可能显示来源或安全提示，请先核对 SHA-256 摘要，并按本单位软件使用规定操作。

