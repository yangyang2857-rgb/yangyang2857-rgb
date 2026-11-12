<!--
AIGC:
    Label: "1"
    ContentProducer: 001191440300708461136T1XGW3
    ProduceID: ba89e2f233ef3708dee31ea6faa51e09_dd0d43a7debc11f1bc42525400638852
    ReservedCode1: vaEukp0fIcjATTqupS4f2gepdr6hL+HOx+JaNiOgoWKzwmUgRjszUKN8XGdGu7kdt9wtRqxGLbMng2SGCdocGpjCXUo/oqbCwriaMfKrfAo/Oz5anY9/4syuL/D6BBLVlgtXwb5EwT6xn6+O6tsmaGzaA4PJFCd4pgl+m2Xaet8/1QPEmECb3z9YxnY=
    ContentPropagator: 001191440300708461136T1XGW3
    PropagateID: ba89e2f233ef3708dee31ea6faa51e09_dd0d43a7debc11f1bc42525400638852
    ReservedCode2: vaEukp0fIcjATTqupS4f2gepdr6hL+HOx+JaNiOgoWKzwmUgRjszUKN8XGdGu7kdt9wtRqxGLbMng2SGCdocGpjCXUo/oqbCwriaMfKrfAo/Oz5anY9/4syuL/D6BBLVlgtXwb5EwT6xn6+O6tsmaGzaA4PJFCd4pgl+m2Xaet8/1QPEmECb3z9YxnY=
-->

<div align="center">

<img src="https://avatars.githubusercontent.com/u/223229607?v=4&s=200" width="110" alt="Wang Sunyang" />

<sub>[中文](README.md) &nbsp;·&nbsp; **English**</sub>

</div>

---

# Wang Sunyang · 王孙阳

**Indie developer · Native Android · No WebView shells, no dependency bloat**

One person doing product, code, QA and release. I believe *one less abstraction layer means one less class of bugs*.

[![Website](https://img.shields.io/badge/website-yangyang2857--rgb.github.io-2ea44f?logo=githubpages&logoColor=white)](https://yangyang2857-rgb.github.io/)
[![Location](https://img.shields.io/badge/location-Hubei%C2%B7Jingzhou%2C%20China-1f6feb?logo=googlemaps&logoColor=white)](#)
[![Followers](https://img.shields.io/github/followers/yangyang2857-rgb?label=followers&color=8957e5)](https://github.com/yangyang2857-rgb?tab=followers)
[![Profile views](https://komarev.com/ghpvc/?username=yangyang2857-rgb&label=views&color=3DDC84&style=flat)](https://github.com/yangyang2857-rgb)

## About me

| | |
| --- | --- |
| **Who I am** | Vocational student and a one-person dev team: product, coding, testing and release all run by me |
| **Approach** | Native first. If the platform API can do it, no framework; if the system toolchain can do it, no build system |
| **Currently building** | A Gradle-free Android build chain, a guardrail SDK for AI agent function calls, and a dependency-free personal site |
| **What I believe** | Fewer dependencies, fewer failure surfaces. A reproducible build beats a clever one |

## Three things I'm building

### OneStar

> A native Android build experiment with no Gradle and no AGP: `aapt2` + `javac` + `d8` + `apksigner` + `zig cc`, all driven by one `build.sh`.

[![Repo](https://img.shields.io/badge/repo-onestar-1f6feb?logo=github&logoColor=white)](https://github.com/yangyang2857-rgb/onestar)
[![build](https://img.shields.io/github/actions/workflow/status/yangyang2857-rgb/onestar/android.yml?branch=main&label=build&logo=githubactions&logoColor=white)](https://github.com/yangyang2857-rgb/onestar/actions/workflows/android.yml)
[![regression](https://img.shields.io/github/actions/workflow/status/yangyang2857-rgb/onestar/regression.yml?branch=main&label=regression&logo=githubactions&logoColor=white)](https://github.com/yangyang2857-rgb/onestar/actions/workflows/regression.yml)
[![Release](https://img.shields.io/github/v/release/yangyang2857-rgb/onestar?label=release&color=3DDC84)](https://github.com/yangyang2857-rgb/onestar/releases)
[![License](https://img.shields.io/github/license/yangyang2857-rgb/onestar?label=license&color=2ea44f)](https://github.com/yangyang2857-rgb/onestar/blob/main/LICENSE)

- Supports **Android 5.0+ (API 21)**, localized into **15 languages**
- JNI pieces cross-compiled with `zig cc`, no NDK Gradle wrapper
- No Gradle cache, no daemon — predictable build times

### AppFunction Guard

> Android 16 lets AI agents call functions inside your app. This project adds the doorman, the doorbell and the visitor log the platform forgot.

[![Repo](https://img.shields.io/badge/repo-appfunction--guard-1f6feb?logo=github&logoColor=white)](https://github.com/yangyang2857-rgb/appfunction-guard)
[![build](https://img.shields.io/github/actions/workflow/status/yangyang2857-rgb/appfunction-guard/build.yml?branch=main&label=build&logo=githubactions&logoColor=white)](https://github.com/yangyang2857-rgb/appfunction-guard/actions/workflows/build.yml)
[![publish](https://img.shields.io/github/actions/workflow/status/yangyang2857-rgb/appfunction-guard/publish-central.yml?branch=main&label=publish&logo=githubactions&logoColor=white)](https://github.com/yangyang2857-rgb/appfunction-guard/actions/workflows/publish-central.yml)
[![License](https://img.shields.io/github/license/yangyang2857-rgb/appfunction-guard?label=license&color=2ea44f)](https://github.com/yangyang2857-rgb/appfunction-guard/blob/main/LICENSE)
[![Status](https://img.shields.io/badge/status-alpha-orange)](#)

- **Per-function** access control over `AppFunctions`: authorization, rate limiting and auditing in one chain
- Kotlin, `minSdk 36`, MIT licensed

### yangyang2857-rgb.github.io

> A hand-written HTML / CSS / JavaScript site: no framework, no build step, no third-party dependencies. Edit a file, `git push`, done.

[![Site](https://img.shields.io/badge/website-online-2ea44f?logo=githubpages&logoColor=white)](https://yangyang2857-rgb.github.io/)
[![pages](https://img.shields.io/github/actions/workflow/status/yangyang2857-rgb/yangyang2857-rgb.github.io/pages/pages-build-deployment?branch=main&label=pages&logo=githubactions&logoColor=white)](https://github.com/yangyang2857-rgb/yangyang2857-rgb.github.io/actions)
[![Repo](https://img.shields.io/badge/repo-yangyang2857--rgb.github.io-1f6feb?logo=github&logoColor=white)](https://github.com/yangyang2857-rgb/yangyang2857-rgb.github.io)

- `dependencies: 0`, hosted on GitHub Pages
- Single-page long scroll, dark/light themes, hand-written browser fallbacks

## Toolbox

<div align="center">

**Languages**

![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/-Java-ED8B00?logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/-Shell-4EAA25?logo=gnubash&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black)

**Platform & toolchain**

![Android](https://img.shields.io/badge/-Android-3DDC84?logo=android&logoColor=white)
![aapt2](https://img.shields.io/badge/-aapt2-8957e5)
![d8](https://img.shields.io/badge/-d8-8957e5)
![apksigner](https://img.shields.io/badge/-apksigner-8957e5)
![JNI](https://img.shields.io/badge/-JNI-1f6feb)
![zig cc](https://img.shields.io/badge/-zig%20cc-F7A41D?logo=zig&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/-GitHub%20Pages-2ea44f?logo=githubpages&logoColor=white)

</div>

## Numbers

<div align="center">

![Streak](https://streak-stats.demolab.com?user=yangyang2857-rgb&theme=github-dark&hide_border=true&locale=en)

</div>

| Repo | Language | Latest release | Last commit |
| --- | --- | --- | --- |
| [onestar](https://github.com/yangyang2857-rgb/onestar) | ![lang](https://img.shields.io/github/languages/top/yangyang2857-rgb/onestar) | ![release](https://img.shields.io/github/v/release/yangyang2857-rgb/onestar) | ![last](https://img.shields.io/github/last-commit/yangyang2857-rgb/onestar) |
| [appfunction-guard](https://github.com/yangyang2857-rgb/appfunction-guard) | ![lang](https://img.shields.io/github/languages/top/yangyang2857-rgb/appfunction-guard) | ![release](https://img.shields.io/github/v/release/yangyang2857-rgb/appfunction-guard) | ![last](https://img.shields.io/github/last-commit/yangyang2857-rgb/appfunction-guard) |
| [yangyang2857-rgb.github.io](https://github.com/yangyang2857-rgb/yangyang2857-rgb.github.io) | ![lang](https://img.shields.io/github/languages/top/yangyang2857-rgb/yangyang2857-rgb.github.io) | — | ![last](https://img.shields.io/github/last-commit/yangyang2857-rgb/yangyang2857-rgb.github.io) |

### CI status

| Repo | Workflow | Status |
| --- | --- | --- |
| onestar | `android.yml` | ![build](https://img.shields.io/github/actions/workflow/status/yangyang2857-rgb/onestar/android.yml?branch=main&label=status) |
| onestar | `regression.yml` | ![regression](https://img.shields.io/github/actions/workflow/status/yangyang2857-rgb/onestar/regression.yml?branch=main&label=status) |
| appfunction-guard | `build.yml` | ![build](https://img.shields.io/github/actions/workflow/status/yangyang2857-rgb/appfunction-guard/build.yml?branch=main&label=status) |
| appfunction-guard | `publish-central.yml` | ![publish](https://img.shields.io/github/actions/workflow/status/yangyang2857-rgb/appfunction-guard/publish-central.yml?branch=main&label=status) |
| yangyang2857-rgb.github.io | `pages-build-deployment` | ![pages](https://img.shields.io/github/actions/workflow/status/yangyang2857-rgb/yangyang2857-rgb.github.io/pages/pages-build-deployment?branch=main&label=status) |

## Contact

- Website: <https://yangyang2857-rgb.github.io/>
- Questions or ideas: open an issue in the relevant repo — faster than email

<div align="center">

<sub>One less abstraction layer, one less class of bugs.</sub>

</div>
