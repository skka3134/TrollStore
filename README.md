# iOS 巨魔 (TrollStore) & 越狱工具终极指南

这是一份集成了 TrollStore（巨魔）二代安装、界面汉化、版本更新、实用工具及多巴胺越狱的综合指南。无论您是新手还是玩家，都能在这里找到所需的信息。

***

## Ⅰ. 巨魔二代 (TrollStore 2) 新手指南

TrollStore 是一款革命性的工具，它利用了苹果的系统漏洞，让用户可以永久签名和安装任何 IPA 应用，无需担心证书过期或掉签的问题。

![](https://mmbiz.qpic.cn/mmbiz_png/CqwzFPUx3cud7OvxDicIWBuNNtBsBRYcmlhwlIicibo0P9ia82gcL3GjQqHicFfe8tANSAmKE7vHdvNa5ibfeib6bRuog/640?wx_fmt=png&from=appmsg&wxfrom=5&wx_lazy=1&wx_co=1)

### 核心优点

*   **完全免费**：无需支付任何费用。
*   **永久签名**：安装的应用永不过期，告别掉签烦恼。
*   **手机端直装**：直接在设备上安装 IPA 文件。
*   **无需越狱**：不破坏系统完整性，享受更高的自由度。

### 支持的 iOS 版本

*   🟢 **支持**: iOS 15.0 - 16.6.1, iOS 17.0
*   🔴 **不支持**: iOS 14.0 Beta 1及更早版本
*   🔴 **不支持**: iOS 16.7 - 16.7.5 （因缺少必要漏洞）
*   🔴 **不支持**: iOS 17.0.1 及更高版本
> **注意**: iOS 17.0 beta 1-5 理论上支持，但目前成功率不高，可以尝试。
好的，这是从您提供的HTML代码中提取并转换成Markdown格式的表格：

好的，我已经将您提供的链接补充到表格中，现在表格中的方法名称可以直接点击跳转到对应的教程页面。

| From | To | arm64 (A8) | arm64 (A9-A11) | arm64e (A12-A17/M1-M2) |
| :---: | :---: | :---: | :---: | :---: |
| **14.0 beta 1 and earlier** | | **Unsupported** | | |
| **14.0 beta 2** | **14.8.1** | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| **15.0** | **15.5 beta 4** | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | | |
| **15.5** | **15.5** | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| **15.6 beta 1** | **15.6 beta 3** | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | | |
| **15.6 beta 4** | **15.6.1** | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| **15.7** | **15.7.1** | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | |
| **15.7.2** | **15.8.4** | [TrollMisaka](https://ios.cfw.guide/installing-trollstore-trollmisaka) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | |
| **16.0 beta 1** | **16.0 beta 3** | Not Applicable | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| **16.0 beta 4** | **16.6.1** | Not Applicable | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | |
| **16.7 RC** | **16.7 RC** | Not Applicable | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | |
| **16.7** | **16.7.11** | Not Applicable | Unsupported | |
| **17.0 beta 1** | **17.0 beta 4** | Not Applicable | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | **[TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore)** |
| **17.0 beta 5** | **17.0** | Not Applicable | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | |
| **17.0.1 and later** | | Not Applicable | **Unsupported** | |

### 官方资源与教程

*   **官方 GitHub 发布页**: [TrollStore Releases](https://github.com/opa334/TrollStore/releases)
*   **新手安装指南**: [查看巨魔二代安装教程](https://mp.weixin.qq.com/s?__biz=Mzg5OTgzNTgxNQ==&mid=2247498844&idx=1&sn=b497c933929829ae3775bfd5f9db2294&chksm=c04f8e94f73807822aff9f55a5abad8fb493a7a1a87e7fa3d3cc9e602d1ea5f2695419e25b92)
*   **综合使用教程**: [查看 iOS 巨魔使用教程](https://mp.weixin.qq.com/s?__biz=Mzg5OTgzNTgxNQ==&mid=2247502087&idx=2&sn=1589cda6d67b180880ff0ead7b55243d&chksm=c04fbbcff73832d9879f15d608c574e7b90561069feaafc7bfc6022f210dc87cd309d5e0795f)

***

## Ⅱ. Misaka - 巨魔辅助安装与系统美化

Misaka 是一款强大的 iOS 系统定制工具，它利用 KFD 和 MDC 漏洞，让非越狱用户也能实现丰富的个性化设置，并且可以作为安装 TrollStore 的辅助工具。

<p align="left">
  <img align="left" height="150" src="https://cdn.discordapp.com/attachments/1157757093097521162/1181224754993184848/App_Store-removebg-preview.png" alt="misaka" style="float: left; border-radius: 10px; margin-right: 15px;"/>
</p>

### Misaka 支持版本

| iOS 版本范围 | MDC 漏洞 | KFD 漏洞 |
| :--- | :---: | :---: |
| 15.0 - 15.7.1 | ✓ | - |
| 15.7.2 - 15.7.6 | - | ✓ |
| 16.0 - 16.1.2 | ✓ | - |
| 16.2 - 16.6 beta 1| - | ✓ |
| 17.0 & 以上 | - | - |

> *Misaka 是一款免费应用，请勿从任何渠道购买。*

### 下载与安装

*   **IPA 下载地址**: [从 GitHub 下载最新版 Misaka](https://github.com/straight-tamago/misaka/releases/latest)
*   **官方安装教程**: [如何使用 Misaka 安装 TrollStore](https://ios.cfw.guide/installing-trollhelper-misaka/)

***

## Ⅲ. 多巴胺 (Dopamine 2.0) 越狱指南

对于希望获得更高系统权限的用户，Dopamine 2.0 是一款适用于 iOS 15.0 - 16.6.1 的优秀越狱工具。

![](https://mmbiz.qpic.cn/mmbiz_jpg/CqwzFPUx3csLicMGRZMuicQ6jy6qJ8uF1Q1EAvx9PKIH44ozTNBUqWLR7jkt1oicc8icWgdKkVt26Q2Z06kl5rPu1w/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

*   **教程地址**: [多巴胺二代 iOS 15.0 - 16.6.1 越狱指南](https://mp.weixin.qq.com/s?__biz=Mzg5OTgzNTgxNQ==&mid=2247501067&idx=1&sn=6f9f9593c45d306abefb8665ff2a4d56&chksm=c04fb7c3f7383ed5578eac45c7e117b981304dbcb03a110f6357ff8010903dda572e6aa1d082)
*   **推荐越狱源**:
    ![](https://mmbiz.qpic.cn/mmbiz_jpg/CqwzFPUx3csLicMGRZMuicQ6jy6qJ8uF1QrOJpPkicqoKTBucec9DtlYcF0mFsRxnHgv2qZsQcoHJXUhofSvent5w/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

***

## Ⅳ. 实用巨魔工具推荐

### TrollRecorder - 通话录音神器
一款由国人开发的纯巨魔版通话录音工具，无需越狱即可使用，核心功能免费。

*   **支持系统**: iOS 15.0 至 16.6.1 和 17.0
*   **核心功能**:
    *   UI 界面美观，操作简单。
    *   支持微信、QQ 等应用的通话录音。
    *   可设置自动启动录音。
    *   支持生物识别验证、录音地址记录等。
*   **免费版**: [GitHub 下载](https://github.com/Lessica/TrollRecorder)
*   **付费版 (高级功能)**: [Havoc 商店链接](https://havoc.app/package/trollrecorder)

### TrollSpeed - 状态栏网速显示
在状态栏实时显示当前网速，让你对网络状况了如指掌。

![](https://user-images.githubusercontent.com/5410705/213263734-1ef1b553-88d4-41cc-856e-891ea08d185c.jpeg)

*   **下载地址**: [GitHub 下载](https://github.com/Lessica/TrollSpeed)

***

## Ⅴ. 开发者与进阶指南

### Theos 开发环境安装 (macOS)
对于希望开发越狱插件的开发者，以下是 Theos 环境的简要安装步骤。

1.  **安装 Homebrew**: 访问官网 [https://brew.sh](https://brew.sh) 获取安装命令。
2.  **安装 ldid 和 dpkg**:
    ```bash
    brew install ldid fakeroot
    brew install dpkg
    ```
    > 如果遇到 `dpkg` 安装失败，可尝试手动下载依赖包或更换 Homebrew 镜像源。
3.  **克隆 Theos 仓库**:
    ```bash
    sudo git clone --recursive https://github.com/theos/theos.git /opt/theos
    ```
4.  **修改权限**:
    ```bash
    sudo chown -R $(id -u):$(id -g) /opt/theos
    ```
5.  **配置环境变量**: 在 `~/.zshrc` 或 `~/.bash_profile` 文件中添加：
    ```bash
    export THEOS=/opt/theos
    export PATH=/opt/theos/bin/:$PATH
    ```
    完成后执行 `source ~/.zshrc` 使其生效。
6.  **验证安装**: 运行命令 `nic.pl`，如果看到模板列表则表示安装成功。

### Xcode 调试插件推荐
一款能使 Xcode 支持调试任意第三方签名 App 或系统进程的插件，同时支持查看任意 App 界面布局。
*   **推荐插件**: [debugserver_azj](https://github.com/lich4/debugserver_azj)

***

## Ⅵ. 技术细节：TrollStore 利用的漏洞

TrollStore 的实现依赖于一个核心漏洞 **CVE-2023-41991**，该漏洞允许恶意应用绕过系统的签名验证。苹果公司已经意识到此漏洞，并在后续的系统版本中进行了修复。

*   **漏洞详情**: [GHSA-fj3m-2r8f-m4x9](https://github.com/advisories/GHSA-fj3m-2r8f-m4x9)
*   **NVD 记录**: [CVE-2023-41991](https://nvd.nist.gov/vuln/detail/CVE-2023-41991)
*   **修复版本**: iOS 16.7, iOS 17.0.1 及更高版本。

***

> **问题支持**: 如遇任何问题，可以联系公众号 **Cydiapps** 获取帮助和最新教程。
> ![](https://mmbiz.qpic.cn/mmbiz_jpg/CqwzFPUx3ctlvhiaKFaaIwemTHgsib2zcTsXNvRxq9NGzEMQOUibFfKKvhuaC0U5SYLOV15EhjCLcvtruYkiaa6ang/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)
