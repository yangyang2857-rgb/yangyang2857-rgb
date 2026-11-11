<div align="center">

<img src="https://avatars.githubusercontent.com/u/223229607?v=4&s=200" width="128" alt="王孙阳" />

# 王孙阳 · Wang Sunyang

**独立开发者 · 原生 Android · 不套壳、不堆依赖**

一个人做完产品、开发、测试、发布。
笃信「少一层抽象，就少一类 bug」。

[![个人网站](https://img.shields.io/badge/%E4%B8%AA%E4%BA%BA%E7%BD%91%E7%AB%99-yangyang2857--rgb.github.io-2ea44f?logo=githubpages&logoColor=white)](https://yangyang2857-rgb.github.io/)
[![Location](https://img.shields.io/badge/%E6%B9%96%E5%8C%97%C2%B7%E8%8D%86%E5%B7%9E-China-1f6feb?logo=googlemaps&logoColor=white)](#)
[![Followers](https://img.shields.io/github/followers/yangyang2857-rgb?label=%E5%85%B3%E6%B3%A8%E8%80%85&color=8957e5)](https://github.com/yangyang2857-rgb?tab=followers)
[![Profile views](https://komarev.com/ghpvc/?username=yangyang2857-rgb&label=%E4%B8%BB%E9%A1%B5%E8%AE%BF%E9%97%AE&color=3DDC84&style=flat)](https://github.com/yangyang2857-rgb)

</div>

---

## 关于我

| | |
| --- | --- |
| **身份** | 中职在读，同时是一人成军的独立开发者：产品、编码、测试、发版全流程自己跑 |
| **技术取向** | 原生实现优先。能用平台 API 就不引框架，能用系统工具链就不上构建系统 |
| **在做的事** | 一个绕开 Gradle/AGP 的 Android 构建链、一套给 AI Agent 调用加闸门的 SDK、一个零依赖的个人站点 |
| **相信的事** | 依赖越少，出问题的面越小；可复现的构建比聪明的构建更值钱 |

---

## 在做的三件事

### 🌱 拾光 OneStar

> 不用 Gradle、不用 AGP 的原生 Android 构建实验：`aapt2` + `javac` + `d8` + `apksigner` + `zig cc`，一条 `build.sh` 走完全程。

[![Repo](https://img.shields.io/badge/repo-onestar-1f6feb?logo=github&logoColor=white)](https://github.com/yangyang2857-rgb/onestar)
[![Release](https://img.shields.io/github/v/release/yangyang2857-rgb/onestar?label=release&color=3DDC84)](https://github.com/yangyang2857-rgb/onestar/releases)
[![Language](https://img.shields.io/github/languages/top/yangyang2857-rgb/onestar?label=lang&color=orange)](https://github.com/yangyang2857-rgb/onestar)
[![License](https://img.shields.io/github/license/yangyang2857-rgb/onestar?label=license&color=2ea44f)](https://github.com/yangyang2857-rgb/onestar/blob/main/LICENSE)
[![Last commit](https://img.shields.io/github/last-commit/yangyang2857-rgb/onestar?label=last%20commit&color=8957e5)](https://github.com/yangyang2857-rgb/onestar/commits/main)

- 支持 **Android 5.0+（API 21）**，i18n 覆盖 **15 种语言**
- JNI 部分用 `zig cc` 交叉编译，不依赖 NDK 的 Gradle 封装
- 无 Gradle 缓存、无 daemon、无守护进程，构建时间可预期

### 🛡 AppFunction Guard

> Android 16 让 AI Agent 能直接调用你 App 里的函数。这个项目补上平台没给的门卫、门铃和访客记录。

[![Repo](https://img.shields.io/badge/repo-appfunction--guard-1f6feb?logo=github&logoColor=white)](https://github.com/yangyang2857-rgb/appfunction-guard)
[![Language](https://img.shields.io/github/languages/top/yangyang2857-rgb/appfunction-guard?label=lang&color=7F52FF)](https://github.com/yangyang2857-rgb/appfunction-guard)
[![License](https://img.shields.io/github/license/yangyang2857-rgb/appfunction-guard?label=license&color=2ea44f)](https://github.com/yangyang2857-rgb/appfunction-guard/blob/main/LICENSE)
[![Status](https://img.shields.io/badge/status-alpha-orange)](https://github.com/yangyang2857-rgb/appfunction-guard)

- 面向 `AppFunctions` 的**逐函数级**调用管控：授权、限流、审计一条链
- Kotlin 实现，`minSdk 36`，MIT 协议
- 关注点：Agent 时代 App 的边界该由谁定义

### 🏠 yangyang2857-rgb.github.io

> 纯手写 HTML / CSS / JavaScript 的个人站点：没有框架、没有构建、没有第三方依赖，改完文件 `git push` 就发布。

[![Site](https://img.shields.io/badge/website-online-2ea44f?logo=githubpages&logoColor=white)](https://yangyang2857-rgb.github.io/)
[![Repo](https://img.shields.io/badge/repo-yangyang2857--rgb.github.io-1f6feb?logo=github&logoColor=white)](https://github.com/yangyang2857-rgb/yangyang2857-rgb.github.io)
[![Language](https://img.shields.io/github/languages/top/yangyang2857-rgb/yangyang2857-rgb.github.io?label=lang&color=E34F26)](https://github.com/yangyang2857-rgb/yangyang2857-rgb.github.io)
[![Last commit](https://img.shields.io/github/last-commit/yangyang2857-rgb/yangyang2857-rgb.github.io?label=last%20commit&color=8957e5)](https://github.com/yangyang2857-rgb/yangyang2857-rgb.github.io/commits/main)

- `dependencies: 0`，托管在 GitHub Pages
- 单页长滚动 + 深浅色主题，浏览器兼容与降级都手写处理

---

## 技术栈

<div align="center">

**语言**

![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/-Java-ED8B00?logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/-Shell-4EAA25?logo=gnubash&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black)

**平台与工具链**

![Android](https://img.shields.io/badge/-Android-3DDC84?logo=android&logoColor=white)
![aapt2](https://img.shields.io/badge/-aapt2-8957e5)
![d8](https://img.shields.io/badge/-d8-8957e5)
![apksigner](https://img.shields.io/badge/-apksigner-8957e5)
![JNI](https://img.shields.io/badge/-JNI-1f6feb)
![zig cc](https://img.shields.io/badge/-zig%20cc-F7A41D?logo=zig&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/-GitHub%20Pages-2ea44f?logo=githubpages&logoColor=white)

</div>

---

## 一些数字

<div align="center">

![Streak](https://streak-stats.demolab.com?user=yangyang2857-rgb&theme=github-dark&hide_border=true&locale=zh_Hans)

</div>

| 仓库 | 语言 | 最新版本 | 最近提交 |
| --- | --- | --- | --- |
| [onestar](https://github.com/yangyang2857-rgb/onestar) | ![top lang](https://img.shields.io/github/languages/top/yangyang2857-rgb/onestar) | ![release](https://img.shields.io/github/v/release/yangyang2857-rgb/onestar) | ![last](https://img.shields.io/github/last-commit/yangyang2857-rgb/onestar) |
| [appfunction-guard](https://github.com/yangyang2857-rgb/appfunction-guard) | ![top lang](https://img.shields.io/github/languages/top/yangyang2857-rgb/appfunction-guard) | ![release](https://img.shields.io/github/v/release/yangyang2857-rgb/appfunction-guard) | ![last](https://img.shields.io/github/last-commit/yangyang2857-rgb/appfunction-guard) |
| [yangyang2857-rgb.github.io](https://github.com/yangyang2857-rgb/yangyang2857-rgb.github.io) | ![top lang](https://img.shields.io/github/languages/top/yangyang2857-rgb/yangyang2857-rgb.github.io) | — | ![last](https://img.shields.io/github/last-commit/yangyang2857-rgb/yangyang2857-rgb.github.io) |

---

## 联系

- 个人网站：<https://yangyang2857-rgb.github.io/>
- 有问题或想法：直接在对应仓库开 [Issue](https://github.com/yangyang2857-rgb/onestar/issues)，比邮件更快

<div align="center">

<sub>少一层抽象，就少一类 bug。</sub>

</div>
