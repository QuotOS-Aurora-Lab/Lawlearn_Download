<div align="center">

# 法法典 Lawlearn

中文法律条文检索与智能解读工具

**本仓库仅存放安装包，不包含源代码。**

</div>

---

## 体验激活码

> [!NOTE]
> 以下激活码适用于 **macOS 版**，在当前最新版本上仍然可用，供体验 Pro 与 Ultimate 的完整功能。**不保证对将来的新版本永久有效**，如某天失效，以届时页面上的说明为准。

| 版本 | 激活码 |
| :--- | :--- |
| Pro | `PROUL-A5Q9S-XXKT8-R4JR9-WC2YE` |
| Ultimate | `ULT6Q-Y7UM7-5FTSK-5QJSZ-GRFWT` |

- Pro 码在「Lawlearn AI Pro」入口输入，Ultimate 码在「Lawlearn AI Ultimate」入口输入，两者互不通用。
- 激活成功后绑定当前设备；把配置拷贝到另一台机器会失效，需要重新激活。
- **Windows 版没有版本分层**，安装后即可使用全部功能，不需要激活码。
- **Android 版**的 AI 升级是演示流程，请使用应用内提示的演示码，上面两个码在安卓上无效。

---

## 下载

| 平台 | 稳定版本 | 系统要求 | 安装包 |
| --- | --- | --- | --- |
| macOS | 3.9.0 | macOS 14.0 及以上 | [Lawlearn-3.9.0.dmg](https://github.com/2822598790-ui/lawlearn-download/releases/download/macOS-v3.9.0/Lawlearn-3.9.0.dmg) · 25 MB |
| Windows | 1.2.5 | Windows 7 SP1 及以上（64 位） | [Lawlearn-Setup-1.2.5.exe](https://github.com/2822598790-ui/lawlearn-download/releases/download/Windows-v1.2.5/Lawlearn-Setup-1.2.5.exe) · 101 MB |
| Windows Lite | 1.2.5 | 同上 | [Lawlearn-Lite-Setup-1.2.5.exe](https://github.com/2822598790-ui/lawlearn-download/releases/download/Windows-v1.2.5-Lite/Lawlearn-Lite-Setup-1.2.5.exe) · 91 MB |
| Android | 1.3.2 | Android 8.0 及以上 | [Lawlearn_v1.3.2_android.apk](https://github.com/2822598790-ui/lawlearn-download/releases/download/Android-v1.3.2/Lawlearn_v1.3.2_android.apk) · 29 MB |

全部历史版本都在 [Releases](../../releases) 里，最早可以追溯到 1.2.3。

> [!IMPORTANT]
> 1.x 和 2.x 属于早期存档，界面结构、功能范围与当前版本差别很大，未必适配新系统。日常使用请以下载表格里的版本为准，旧版本只在需要找回某个特定版本时下载。

## Windows 4.0.0 Beta（测试版）

> [!WARNING]
> 这是预览版，功能与界面仍在调整，可能不稳定。**不建议把它当作唯一安装的版本**，稳妥起见请先装 1.2.5 作为日常使用，再把 Beta 装到另一个目录试用。

Windows 端 4.0.0 正在更换技术栈（PySide6 + Python 3.13），目前提供三个测试包：

| 类型 | 说明 | 安装包 |
| --- | --- | --- |
| Beta1 安装版 | 较早的测试构建 | [Lawlearn-Setup-4.0.0-Beta1.exe](https://github.com/2822598790-ui/lawlearn-download/releases/download/Windows-v4.0.0-Beta1/Lawlearn-Setup-4.0.0-Beta1.exe) · 42 MB |
| Beta2 安装版 | 稍晚的测试构建 | [Lawlearn-Setup-4.0.0-Beta2.exe](https://github.com/2822598790-ui/lawlearn-download/releases/download/Windows-v4.0.0-Beta2/Lawlearn-Setup-4.0.0-Beta2.exe) · 98 MB |
| 免安装版 | 解压后直接运行，不写系统、不产生卸载项 | [Lawlearn-Portable-4.0.0-Beta.zip](https://github.com/2822598790-ui/lawlearn-download/releases/download/Windows-v4.0.0-Beta-Portable/Lawlearn-Portable-4.0.0-Beta.zip) · 53 MB |

- 免安装版解压后运行 `Lawlearn/Lawlearn.exe`，可以把整个文件夹放在 U 盘里带走。
- Beta 版与 1.2.5 可以同时安装，但请装在不同的目录下，避免数据文件互相覆盖。
- **4.0.0 Beta 不提供源代码。** 本节之外的下载项均为正式版本，源码说明只针对正式版本。
- 反馈问题时请注明用的是 `Beta1` 还是 `Beta2`，两者并非同一份构建。

## 版本选择

**Windows 有两个版本**，按需要选一个装即可，不要同时装：

- **完整版**：包含全部法律条文与司法解释，覆盖范围最广。
- **Lite 版**：只包含民商法相关的法条，体积更小、启动更快，适合日常查民商事条文。

## 安装说明

### macOS

1. 下载 `.dmg` 后双击打开，把 `Lawlearn` 拖进「应用程序」文件夹。
2. 首次打开如果提示「无法验证开发者」，到「系统设置 → 隐私与安全性」里点「仍要打开」。
3. 如果提示文件已损坏，在终端执行一次下面这行再打开：

```bash
xattr -dr com.apple.quarantine /Applications/Lawlearn.app
```

### Windows

1. 运行 `.exe` 安装包，按向导完成安装。
2. 程序默认装在当前用户目录下，不需要管理员权限。
3. SmartScreen 拦截时点「更多信息 → 仍要运行」。

### Android

1. 下载 `.apk` 后点击安装，需要在系统设置里允许「安装未知来源应用」。
2. 覆盖升级时请使用同一个签名版本，否则需要先卸载旧版——卸载会清空本地的收藏、笔记与浏览记录。

## 校验值

下载后可以对比 SHA-256，确认文件没有损坏或被动过：

| 文件 | SHA-256 |
| --- | --- |
| `Lawlearn-3.9.0.dmg` | `1d7e6db3dcc52dc788910ccf130a71de8c319b93809f51c43d935b9136711066` |
| `Lawlearn-Setup-1.2.5.exe` | `9db55520a9c3168f436ccb985a4736dd6e8817418ab0725898ba61170dff8183` |
| `Lawlearn-Lite-Setup-1.2.5.exe` | `f984aae048be31bf88e6d5ddb862769997be8784e931d6469bea6f32d59068ca` |
| `Lawlearn_v1.3.2_android.apk` | `e2a7993c2ac6c0cf43f8f6f6fd4fc9de9b1b4685228339453243ef7397cc11d0` |

macOS 上执行 `shasum -a 256 文件名`，Windows 上执行 `certutil -hashfile 文件名 SHA256`。

Windows 4.0.0 Beta 的校验值：

| 文件 | SHA-256 |
| --- | --- |
| `Lawlearn-Setup-4.0.0-Beta1.exe` | `97b4690b4c86d50550d7a83d79e024a75bb3bfb912a590d1291a23586047d299` |
| `Lawlearn-Setup-4.0.0-Beta2.exe` | `d62188e7f3ac111917cf2c69b61076bf33b921d3013cc374b76ee401623573e0` |
| `Lawlearn-Portable-4.0.0-Beta.zip` | `9f574fd4701f7050bf53ba257314eb84f0ede5566bdeb0ddccf6ee39dec9cce5` |

## 版本说明

每个版本的改动记录写在对应 Release 的说明里，点进 [Releases](../../releases) 即可查看。

## 关于源代码

本项目的源代码未公开，本仓库也不含任何源文件。

安装包内仅包含编译后的程序与法条数据，可以自由使用本软件，但不允许反编译、二次打包或剥离版权声明后分发。法条文本本身来自公开的法律法规，司法解释文本来自公开渠道。

## 问题反馈

在 [Issues](../../issues) 里提交，请说明：

- 使用的平台与版本号（在「关于」里可以看到）
- 具体的操作步骤
- 期望的结果与实际的结果
- 如有截图或错误提示，一并附上

## 数据说明

法条数据来自公开渠道整理，检索与解读结果仅供学习参考，不构成法律意见。涉及真实案件的，请咨询执业律师。
