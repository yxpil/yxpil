<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1200&color=58A6FF&center=true&vCenter=true&random=false&width=560&lines=%E6%9E%95%E5%BF%B6+YxPil;Local-first+AI+Agent+%C2%B7+%E5%BC%80%E5%8F%91%E8%80%85%E5%B7%A5%E5%85%B7;Build+things+that+grow+by+themselves." alt="typing" />

**独立开发者** —— 专注本地优先（local-first）的 AI Agent 与开发者工具

*Independent developer focused on local-first AI agents and developer tools.*

[![Releases](https://img.shields.io/github/v/release/yxpil/BrainTentacle?style=flat-square&label=%E6%9C%80%E6%96%B0%E7%89%88)](https://github.com/yxpil/BrainTentacle/releases)
[![GitHub followers](https://img.shields.io/github/followers/yxpil?style=flat-square&label=Followers)](https://github.com/yxpil?tab=followers)
[![Repo count](https://img.shields.io/badge/dynamic/json?style=flat-square&color=blue&label=%E5%85%AC%E5%BC%80%E4%BB%93%E5%BA%93&query=%24.public_repos&url=https%3A%2F%2Fapi.github.com%2Fusers%2Fyxpil)](https://github.com/yxpil?tab=repositories)
[![Visitors](https://komarev.com/ghpvc/?username=yxpil&style=flat-square&color=blueviolet&label=%E8%AE%BF%E5%AE%A2)](https://github.com/yxpil)

</div>

---

## 关于 About

相信 AI Agent 不该住在别人的云上。正在打造 **BIT 触手怪**——一个跑在用户自己电脑上、可以自我成长的桌面智能体：工具、记忆、技能、MCP 扩展、远程访问，数据全部留在本地。

> Believing agents shouldn't live in someone else's cloud. Building **BIT**, a self-growing desktop agent that runs on your own machine — tools, memory, skills, MCP extensions, remote access — with all data staying local.

## 代表作 Featured Work

### [BIT 触手怪](https://github.com/yxpil/BrainTentacle) — 本地优先 AI Agent 中枢

<div align="center">

[![Release](https://img.shields.io/github/v/release/yxpil/BrainTentacle?style=flat-square&color=blue)](https://github.com/yxpil/BrainTentacle/releases)
[![License](https://img.shields.io/github/license/yxpil/BrainTentacle?style=flat-square)](https://github.com/yxpil/BrainTentacle)
[![Stars](https://img.shields.io/github/stars/yxpil/BrainTentacle?style=flat-square&color=yellow)](https://github.com/yxpil/BrainTentacle/stargazers)
[![Platform](https://img.shields.io/badge/Win%20%7C%20macOS%20%7C%20Linux-native-9cf?style=flat-square)](https://github.com/yxpil/BrainTentacle/releases)
[![Exotic](https://img.shields.io/badge/LoongArch%20%7C%20RISC--V-builds-8a2be2?style=flat-square)](https://github.com/yxpil/BrainTentacle/actions)

</div>

一个可以**自我成长**的桌面端 AI Agent，开箱即用、持续高频迭代：

- **对话 / 工具 / 记忆 / 技能**：完整 Agent 能力闭环，目标自动推进
- **本机操控**：截屏网格定位 + 鼠标键盘合成，AI 精准操作你的电脑
- **MCP 双向**：既是 MCP 客户端（stdio / Streamable HTTP 任接），也是 MCP 服务器
- **安全脱敏**：HiddenCode 敏感信息加密隔离，AI 触碰不到密钥 / 手机号 / 邮箱
- **系统托盘常驻**：任务状态灯、悬浮预览、面板与主题联动
- **远程访问**：LAN / IPv6 / 云中继多路连接，手机扫码即用（[bit-mobile](https://github.com/yxpil/bit-mobile)）
- **自动更新**：后台静默下载，一键暂停 / 恢复

- 官网与下载：[osbt.space](https://osbt.space) ｜ [全部 Releases](https://github.com/yxpil/BrainTentacle/releases)
- 自托管软件源：Scoop / Homebrew / APT / pacman / dnf

## BIT 生态 Ecosystem

| 仓库 | 说明 |
| --- | --- |
| [BrainTentacle](https://github.com/yxpil/BrainTentacle) | BIT 主仓库（Electron + React + Rust bit-core） |
| [TentacleTool](https://github.com/yxpil/TentacleTool) | 触手怪的 MCP 工具集 |
| [bit-mobile](https://github.com/yxpil/bit-mobile) | 安卓伴侣端 — 扫码配对 / 随身对话 / 工具审批（Apache-2.0） |
| [BITSDK](https://github.com/yxpil/BITSDK) | 开发者调用 BIT 能力的 SDK |
| [scoop-bit](https://github.com/yxpil/scoop-bit) / [homebrew-bit](https://github.com/yxpil/homebrew-bit) / [apt-repo](https://github.com/yxpil/apt-repo) / [pacman-repo](https://github.com/yxpil/pacman-repo) / [dnf-repo](https://github.com/yxpil/dnf-repo) | 全平台自托管软件源 |

## 更多项目 Selected Projects

| 仓库 | 说明 |
| --- | --- |
| [model-relay](https://github.com/yxpil/model-relay) | Rust LLM API 统一网关：多用户拼车、双层配额、用量统计 |
| [SECFORGE](https://github.com/yxpil/SECFORGE) | Security MCP Server — BITECO 卫星工具聚合，29 个 MCP 工具 |
| [PANOPTES](https://github.com/yxpil/PANOPTES) | Screen Operation MCP Server — AI 屏幕操控（截图 + 鼠标键盘） |
| [MQ](https://github.com/yxpil/MQ) | 事件驱动的模块化消息框架（Spring Boot + JPA） |
| [CloudSH](https://github.com/yxpil/CloudSH) | 云端 SSH — 解决闪断与机房低头连接的方案 |
| [MemoryPool](https://github.com/yxpil/MemoryPool) | 智能体记忆池程序 |
| [HOWCUEME](https://github.com/yxpil/HOWCUEME) | 智能体条件自唤醒程序 |
| [ADONWORD](https://github.com/yxpil/ADONWORD) | 智能体主动防御工具 |
| [Firelin](https://github.com/yxpil/Firelin) | 智能体网络渗透工具集 |
| [DocPI](https://github.com/yxpil/DOCPI) | 架构文档公示协作平台 |
| [PILSoftFlow](https://github.com/yxpil/PILSoftFlow) | 动态服务器启停组件 |
| [PILCOMMIX](https://github.com/yxpil/PILCOMMIX) | 音频合成器 |

## 技术栈 Tech Stack

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

## GitHub 统计 Stats

<div align="center">

<img height="165" src="https://github-stats.marchewczyk.eu/api?username=yxpil&show_icons=true&count_private=true&include_all_commits=true&theme=default" alt="stats" />
<img height="165" src="https://github-stats.marchewczyk.eu/api/top-langs/?username=yxpil&layout=compact&langs_count=8&theme=default" alt="top-langs" />
<img height="165" src="https://streak-stats.demolab.com?user=yxpil&short_numbers=true&theme=default" alt="streak" />

</div>

<div align="center">

![snake](https://raw.githubusercontent.com/yxpil/yxpil/output/github-contribution-grid-snake-dark.svg)

</div>

## 链接 Links

- BIT 官网：<https://osbt.space>
- 个人网站：<https://yxpil.com>
- 爱发电（支持开发）：<https://ifdian.net/a/yxpillow>

<div align="center">

*如果 BIT 对你有用，欢迎给 [BrainTentacle](https://github.com/yxpil/BrainTentacle) 一个 Star*

</div>
