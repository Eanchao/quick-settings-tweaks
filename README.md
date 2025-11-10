# Quick Settings Tweaks / 快速设置优化[<img src=".github/images/quick-settings-tweaker.png" width="200px" align="right" alt="QuickSettings-Tweaker SkeletonUI">](https://extensions.gnome.org/extension/5446/quick-settings-tweaker/)

<div align="center">

### 让我们优化下 Gnome 快速设置吧!

[<img src="https://raw.githubusercontent.com/andyholmes/gnome-shell-extensions-badge/master/get-it-on-ego.svg?sanitize=true" alt="Get it on GNOME Extensions" height="100" align="middle">](https://extensions.gnome.org/extension/5446/quick-settings-tweaker/)

<a href="https://weblate.paring.moe/engage/gs-quick-settings-tweaks/">
<img src="https://weblate.paring.moe/widgets/gs-quick-settings-tweaks/-/gs-extension/svg-badge.svg" alt="翻译状态" />
</a>
<br>
<br>
Quick Settings Tweaker 是 Gnome 46+ 的扩展程序，可让您根据自己的喜好自定义新的快速设置面板！

</div>
<br>
<br>

> 本项目 Fork 自 `https://github.com/qwreey/quick-settings-tweaks`
<br>
> 本项目为简体中文版（因原项目汉化已锁定）



## 功能


| <p align="center">通过本扩展，你可以...</p>                                                                                                                                                                                                                          |                                        How it will appear                                        |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-----------------------------------------------------------------------------------------------: |
| <p align="center">**添加媒体控制组件**</p><p align="center">直接从快速设置（而不是日期菜单）控制您的音乐和视频。<br><br>为了获得更酷的外观，您还可以从封面图像中获取颜色并创建渐变背景。</p> | <img src=".github/images/media-control.png" width="600px" alt="媒体控制组件截图"> |
| <p align="center">**添加音量混合器组件**</p><p align="center">无需打开额外的应用程序即可调整应用程序音量。<br><br>将菜单按钮放在输出滑块旁边，以获得紧凑自然的布局。</p>                                   |  <img src=".github/images/volume-mixer.png" width="600px" alt="音量混合器组件截图">  |
| <p align="center">**添加通知组件**</p><p align="center">您可以检查已发送到您的邮箱或信息的内容，不会容易错过它们！</p>                                                                                                          | <img src=".github/images/notifications.png" width="600px" alt="通知组件截图"> |
| <p align="center">**布局自定义**</p><p align="center">隐藏、重新排序、重新着色您的面板和快速设置布局使其<br><br>变得简单并保持井井有条！</p>                                                                                              |     <img src=".github/images/layout.png" width="600px" alt="Notifications widget screenshot">     |
| <p align="center">**覆盖菜单布局**</p><p align="center">您的快速设置面板太大？<br><br>尝试叠加布局！您也可以自定义背景和动画样式。</p>                                                                            |    <img src=".github/images/overlay.png" width="600px" alt="Notifications widget screenshot">    |

## 赞助

您可以通过 [github sponsor](https://github.com/sponsors/eanchao) 支持开发者。您可以帮助维护这个项目

Here is my sponsors, thank for your support!

[![sponsors](https://readme-contribs.as93.net/sponsors/eanchao?shape=square&margin=16&perRow=15&title=eanchao's%20Sponsors&textColor=f5acff&backgroundColor=0e001a&fontFamily=cursive&fontSize=14&limit=90&footerText=none&outerBorderRadius=24)](https://github.com/sponsors/eanchao)

## Stars

[![Star History Chart](https://api.star-history.com/svg?repos=eanchao/quick-settings-tweaks&type=Date)](https://star-history.com/#eanchao/quick-settings-tweaks&Date)

## 项目开发

### 翻译

<img src="https://weblate.paring.moe/widgets/gs-quick-settings-tweaks/-/gs-extension/multi-auto.svg">

您可以通过打开拉取请求或使用 [weblate](http://weblate.paring.moe/engage/gs-quick-settings-tweaks/) 来帮助翻译此扩展

### 构建

> 前置条件：您必须安装 `nodejs`、`bash`、`gettext` 以及 `gnome-shell` 来打包本扩展

1. 请先安装依赖：
```sh
pnpm i
```

2. 打包
```sh
./install.sh install
```

您可以通过执行`TARGET=dev ./install.sh create-release`来创建开发构建。 确保先运行`npm i`以确保安装了所有构建依赖项

或者，您可以从 [Github 版本发布选项卡](https://github.com/eanchao/quick-settings-tweaks/releases) 获取已构建好的版本。不鼓励从 `dev` 分支构建扩展，因为 `dev` 分支具有未经检查的前沿功能，无法保证工作。Github预 由开发人员测试，比构建 `dev` 分支稳定得多。

### 参与贡献与问题追踪

请查看 [Github 项目页面](https://github.com/users/eanchao/projects/2)了解问题优先级和进度。

#### 提出问题

如果您想提出问题，首先**您必须先搜索您的问题**。重复的问题将被关闭，请不要让开发人员的时间浪费在这种地方。

其次，**您必须附加相关的日志文件、Gnome 版本和扩展版本信息**。如果您没有提供太多有关问题的信息，则很难解决您的问题。需要明确的是，请使用`[migration]`， `[feature]`， `[bug]` 作为问题标题前缀，对于搜索和整理问题非常有用

最后，**你必须使用格式良好的英语**，您可以使用翻译器或AI来编写它，因此请避免让开发人员翻译和做笔记来浪费时间。这占用了开发人员惊人的时间，使分析变得非常困难，尤其是在日志混合使用英语和其他语言的情况下。

#### PR 和代码贡献

如果你想做出贡献，**你必须拉取 `dev` 分支，而不是 `master` 分支。** `master` 分支是发布分支，因为 `AUR` 和一些用户发行版使用 `master` 分支作为构建源。**如果您创建了对 `master` 分支的拉取请求，它将被关闭。** 您应该重新打开 PR 到 `dev` 分支。

### 测试

![gnome-docker devlopment screenshot](.github/images/dev-preview.png)

您可以使用命令`./install.sh dev`测试扩展。您将需要 `TigerVNC` 客户端和 `docker`。
> 在 Arch Linux 中进行了测试，但它应该可以在任何基于 systemd 的平台上运行

您可以通过注销并关闭 vnc 窗口或发送 `SIGINT` 退出 `dev docker` 来重新构建扩展。
