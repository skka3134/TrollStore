# iOS 巨魔 (TrollStore) & 越狱工具终极指南 😈

一份详尽的综合指南，涵盖 TrollStore（巨魔）的安装、汉化、更新，以及多巴胺 (Dopamine) 越狱和各类实用工具。无论您是初次接触的新手，还是资深玩家，都能在此找到所需的一切。

---

## Ⅰ. 巨魔二代 (TrollStore 2) 新手指南

TrollStore 是一款革命性的工具，它利用苹果的系统漏洞，让用户可以永久签名并安装任何 IPA 应用，彻底告别证书过期和应用掉签的烦恼。

![TrollStore Logo](https://mmbiz.qpic.cn/mmbiz_png/CqwzFPUx3cud7OvxDicIWBuNNtBsBRYcmlhwlIicibo0P9ia82gcL3GjQqHicFfe8tANSAmKE7vHdvNa5ibfeib6bRuog/640?wx_fmt=png&from=appmsg&wxfrom=5&wx_lazy=1&wx_co=1)

### 核心优势

*   ✅ **完全免费**：无需支付任何费用。
*   ✍️ **永久签名**：安装的应用永不过期，告别掉签烦恼。
*   📱 **手机端直装**：直接在设备上轻松安装 IPA 文件。
*   🔓 **无需越狱**：不破坏系统完整性，享受更高的自由度。

### 支持的系统版本

*   🟢 **完美支持**: iOS `15.0` - `16.6.1`, iOS `17.0`
*   🔴 **不支持**: iOS `14.0 Beta 1` 及更早版本
*   🔴 **不支持**: iOS `16.7` - `16.7.5` (因缺少必要漏洞)
*   🔴 **不支持**: iOS `17.0.1` 及更高版本

> **💡 注意**: iOS `17.0 beta 1-5` 理论上支持，但目前成功率不高，可以自行尝试。

### 安装方法兼容性总览

这张表格详细列出了不同系统版本和设备芯片对应的最佳安装方法。

| 系统版本 (From) | 系统版本 (To) | arm64 (A8) | arm64 (A9-A11) | arm64e (A12-A17/M1-M2) |
| :---: | :---: | :---: | :---: | :---: |
| **14.0 beta 1 and earlier** | | <font color="red">**Unsupported**</font> | | |
| **14.0 beta 2** | **14.8.1** | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| **15.0** | **15.5 beta 4** | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | | |
| **15.5** | **15.5** | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| **15.6 beta 1** | **15.6 beta 3** | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | | |
| **15.6 beta 4** | **15.6.1** | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| **15.7** | **15.7.1** | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | |
| **15.7.2** | **15.8.4** | [TrollMisaka](https://ios.cfw.guide/installing-trollstore-trollmisaka) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | |
| **16.0 beta 1** | **16.0 beta 3** | N/A | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| **16.0 beta 4** | **16.6.1** | N/A | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | |
| **16.7 RC** | **16.7 RC** | N/A | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | |
| **16.7** | **16.7.11** | N/A | <font color="red">Unsupported</font> | |
| **17.0 beta 1** | **17.0 beta 4** | N/A | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | **[TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore)** |
| **17.0 beta 5** | **17.0** | N/A | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | |
| **17.0.1 and later** | | N/A | <font color="red">**Unsupported**</font> | |

### 设备型号与芯片架构速查表

**iPhone**
| 手机型号 | 芯片 | 架构 |
| :--- | :--- | :---: |
| iPhone 15 Pro / Pro Max | A17 Pro | `arm64e` |
| iPhone 15 / 15 Plus | A16 Bionic | `arm64e` |
| iPhone 14 Pro / Pro Max | A16 Bionic | `arm64e` |
| iPhone 14 / 14 Plus | A15 Bionic | `arm64e` |
| iPhone SE (第三代) | A15 Bionic | `arm64e` |
| iPhone 13 全系列 | A15 Bionic | `arm64e` |
| iPhone 12 全系列 | A14 Bionic | `arm64e` |
| iPhone SE (第二代) | A13 Bionic | `arm64e` |
| iPhone 11 全系列 | A13 Bionic | `arm64e` |
| iPhone XS / XS Max / XR | A12 Bionic | `arm64e` |
| iPhone X / 8 / 8 Plus | A11 Bionic | `arm64` |
| iPhone 7 / 7 Plus | A10 Fusion | `arm64` |
| iPhone SE (第一代) / 6S | A9 | `arm64` |
| iPhone 6 / 6 Plus | A8 | `arm64` |

**iPad**
| 平板型号 | 芯片 | 架构 |
| :--- | :--- | :---: |
| iPad Pro (M2) | M2 | `arm64e` |
| iPad Pro (M1) / Air (第五代) | M1 | `arm64e` |
| iPad Air (第四代) / iPad (第十代) | A14 Bionic | `arm64e` |
| iPad (第九代) | A13 Bionic | `arm64e` |
| iPad (第八代) / mini (第五代) | A12 Bionic | `arm64e` |
| iPad mini (第六代) | A15 Bionic | `arm64e` |

### 官方资源与教程

*   **官方发布页**: [TrollStore Releases on GitHub](https://github.com/opa334/TrollStore/releases)
*   **新手安装教程**: [查看巨魔二代安装教程](https://mp.weixin.qq.com/s?__biz=Mzg5OTgzNTgxNQ==&mid=2247498844&idx=1&sn=b497c933929829ae3775bfd5f9db2294&chksm=c04f8e94f73807822aff9f55a5abad8fb493a7a1a87e7fa3d3cc9e602d1ea5f2695419e25b92)
*   **综合使用指南**: [查看 iOS 巨魔使用教程](https://mp.weixin.qq.com/s?__biz=Mzg5OTgzNTgxNQ==&mid=2247502087&idx=2&sn=1589cda6d67b180880ff0ead7b55243d&chksm=c04fbbcff73832d9879f15d608c574e7b90561069feaafc7bfc6022f210dc87cd309d5e0795f)

---

## Ⅱ. Misaka - 巨魔安装 & 系统美化利器 ✨

Misaka 是一款强大的 iOS 系统定制工具，它利用 KFD 和 MDC 漏洞，让非越狱用户也能实现丰富的个性化设置。同时，它也是安装 TrollStore 的重要辅助工具之一。

<p align="center">
  <img height="150" src="https://cdn.discordapp.com/attachments/1157757093097521162/1181224754993184848/App_Store-removebg-preview.png" alt="misaka" style="border-radius: 10px;"/>
</p>

### Misaka 支持版本一览

| iOS 版本范围 | MDC 漏洞 | KFD 漏洞 |
| :--- | :---: | :---: |
| 15.0 - 15.7.1 | ✅ | - |
| 15.7.2 - 15.7.6 | - | ✅ |
| 16.0 - 16.1.2 | ✅ | - |
| 16.2 - 16.6 beta 1| - | ✅ |
| 17.0 & 以上 | - | - |

> ⚠️ **警告**: Misaka 是一款免费应用，请勿从任何非官方渠道购买。

### 下载与安装

*   **IPA 下载**: [从 GitHub 下载最新版 Misaka](https://github.com/straight-tamago/misaka/releases/latest)
*   **官方教程**: [如何使用 Misaka 安装 TrollStore](https://ios.cfw.guide/installing-trollhelper-misaka/)

---

## Ⅲ. 多巴胺 (Dopamine 2.0) 越狱指南 💉

对于追求更高系统权限和自定义自由度的用户，Dopamine 2.0 是一款稳定且强大的越狱工具，适用于 iOS 15.0 - 16.6.1 系统。

<p align="center">
  <img src="https://mmbiz.qpic.cn/mmbiz_jpg/CqwzFPUx3csLicMGRZMuicQ6jy6qJ8uF1Q1EAvx9PKIH44ozTNBUqWLR7jkt1oicc8icWgdKkVt26Q2Z06kl5rPu1w/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" alt="Dopamine" width="400"/>
</p>

*   **详细教程**: [多巴胺二代 iOS 15.0 - 16.6.1 越狱指南](https://mp.weixin.qq.com/s?__biz=Mzg5OTgzNTgxNQ==&mid=2247501067&idx=1&sn=6f9f9593c45d306abefb8665ff2a4d56&chksm=c04fb7c3f7383ed5578eac45c7e117b981304dbcb03a110f6357ff8010903dda572e6aa1d082)
*   **推荐越狱源**:
<p align="center">
  <img src="https://mmbiz.qpic.cn/mmbiz_jpg/CqwzFPUx3csLicMGRZMuicQ6jy6qJ8uF1QrOJpPkicqoKTBucec9DtlYcF0mFsRxnHgv2qZsQcoHJXUhofSvent5w/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" alt="Sileo Sources" width="400"/>
</p>

---

## Ⅳ. 实用巨魔工具推荐 🛠️

### TrollRecorder - 通话录音神器

一款由国人开发的纯巨魔版通话录音工具，无需越狱即可使用，核心功能完全免费。

*   **支持系统**: iOS 15.0 - 16.6.1 及 17.0
*   **核心功能**:
    *   美观简洁的 UI 界面，操作直观。
    *   支持微信、QQ 等主流社交应用的通话录音。
    *   可设置通话自动录音。
    *   支持生物识别（面容/指纹）加密。
    *   支持记录录音时的地理位置。
*   **免费版**: [GitHub 下载](https://github.com/Lessica/TrollRecorder)
*   **高级版**: [Havoc 商店链接](https://havoc.app/package/trollrecorder) (解锁更多高级功能)

### TrollSpeed - 状态栏网速显示

在状态栏实时显示当前上传/下载网速，让你对网络状况了如指掌。

<p align="center">
  <img src="https://user-images.githubusercontent.com/5410705/213263734-1ef1b553-88d4-41cc-856e-891ea08d185c.jpeg" alt="TrollSpeed" width="400"/>
</p>

*   **下载地址**: [GitHub 下载](https://github.com/Lessica/TrollSpeed)

---

## Ⅴ. 开发者与进阶指南 👨‍💻

### Theos 开发环境安装 (macOS)

对于希望开发越狱插件的开发者，以下是在 macOS 上配置 Theos 环境的简要步骤。

1.  **安装 Homebrew**:
    访问官网 [https://brew.sh](https://brew.sh) 获取并执行安装命令。

2.  **安装 ldid 和 dpkg**:
    ```bash
    brew install ldid fakeroot dpkg
    ```
    > **提示**: 如果 `dpkg` 安装失败，可尝试更换 Homebrew 镜像源或手动解决依赖问题。

3.  **克隆 Theos 仓库**:
    ```bash
    sudo git clone --recursive https://github.com/theos/theos.git /opt/theos
    ```

4.  **修改目录权限**:
    ```bash
    sudo chown -R $(id -u):$(id -g) /opt/theos
    ```

5.  **配置环境变量**:
    编辑 `~/.zshrc` (或 `~/.bash_profile`) 文件，添加以下内容：
    ```bash
    export THEOS=/opt/theos
    export PATH=/opt/theos/bin/:$PATH
    ```
    然后执行 `source ~/.zshrc` 使配置立即生效。

6.  **验证安装**:
    在终端运行 `nic.pl` 命令，如果成功显示模板列表，则表示 Theos 环境已安装成功。

### Xcode 调试插件推荐

**debugserver_azj**: 一款强大的 Xcode 插件，支持调试任意第三方签名的 App 或系统进程，并能方便地查看任意 App 的界面布局。

*   **项目地址**: [debugserver_azj on GitHub](https://github.com/lich4/debugserver_azj)

---

## Ⅵ. 技术细节：TrollStore 背后的漏洞 🔬

TrollStore 的实现依赖于一个核心的 CoreTrust 漏洞 **CVE-2023-41991**，该漏洞允许恶意应用绕过系统的签名验证。苹果公司已经意识到此漏洞，并在后续的系统版本中进行了修复。

*   **漏洞详情**: [GHSA-fj3m-2r8f-m4x9](https://github.com/advisories/GHSA-fj3m-2r8f-m4x9)
*   **NVD 记录**: [CVE-2023-41991](https://nvd.nist.gov/vuln/detail/CVE-2023-41991)
*   **修复版本**: 已在 iOS `16.7`, iOS `17.0.1` 及更高版本中被修复。

---

> ### **寻求帮助与支持**
>
> 如果在操作过程中遇到任何问题，可以关注公众号 **Cydiapps** 获取最新的教程和帮助。
>
> <p align="center">
>  <img src="https://mmbiz.qpic.cn/mmbiz_jpg/CqwzFPUx3ctlvhiaKFaaIwemTHgsib2zcTsXNvRxq9NGzEMQOUibFfKKvhuaC0U5SYLOV15EhjCLcvtruYkiaa6ang/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" alt="Cydiapps QR Code" width="200"/>
> </p>
