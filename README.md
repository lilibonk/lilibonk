# 狸狸咚的 space

写一些工程工具、AI 协作面板和桌面实验小件。

<picture>
  <source media="(prefers-color-scheme: dark) and (prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/lilibonk/lilibonk/main/assets/workshop-night.png">
  <source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/lilibonk/lilibonk/main/assets/workshop-day.png">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lilibonk/lilibonk/main/assets/workshop-night.gif">
  <img src="https://raw.githubusercontent.com/lilibonk/lilibonk/main/assets/workshop-day.gif" alt="space 工作台像素插画，日夜配色随阅读环境切换。" width="100%">
</picture>

## 精选项目

| 项目 | 定位 |
| :--- | :--- |
| [**pi-pane**](#user-content-pi-pane) | pi Coding Agent 的浏览器实时协作面板 |
| [**Apocalypse**](#user-content-apocalypse) | Java 25 / Spring Boot 4.1 / React 19 模块化单体后台基座 |
| [**Codex Pet Collection**](#user-content-codex-pet-collection) | Codex 可安装动画宠物合集与 CLI 工具 |

### pi-pane

为 pi Coding Agent 提供浏览器端的会话镜像界面。终端运行 `/web` 即可接管同一会话，实时查看流式回复、工具调用与代码 diff，也支持直接发送消息、上传图片、明暗主题同步和 HTTPS 外部访问。

<a href="https://github.com/lilibonk/pi-pane#readme">
  <img src="https://raw.githubusercontent.com/lilibonk/pi-pane/main/docs/preview.png" alt="pi-pane 浏览器会话界面：AI 回复、工具执行卡片、代码 diff 与消息输入栏。" width="640">
</a>

**[文档与安装](https://github.com/lilibonk/pi-pane#readme)** · [设计说明](https://github.com/lilibonk/pi-pane/blob/main/docs/design.md) · [v0.3.0-rc.4](https://github.com/lilibonk/pi-pane/releases/tag/v0.3.0-rc.4)

<sub>TypeScript / Preact / WebSocket</sub>

---

### Apocalypse

基于 Java 25、Spring Boot 4.1 与 React 19 的模块化单体脚手架与管理后台。后端保持单 Maven 模块并由 Spring Modulith 和 ArchUnit 检查边界，内置独立业务权限目录、部门数据范围、审计日志与两级缓存；管理台内置清透流体、手绘手账与 Obsidian 夜色三套主题。

<a href="https://github.com/lilibonk/apocalypse#readme">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lilibonk/apocalypse/main/.github/assets/readme/admin-dark.jpg">
    <img src="https://raw.githubusercontent.com/lilibonk/apocalypse/main/.github/assets/readme/admin-light.jpg" alt="Apocalypse 用户管理界面：左侧部门树、多维筛选与统一分页器，数据均为示例。" width="100%">
  </picture>
</a>

**[快速开始](https://github.com/lilibonk/apocalypse/blob/main/docs/getting-started.md)** · [项目源码](https://github.com/lilibonk/apocalypse) · [v0.1.0-rc.2](https://github.com/lilibonk/apocalypse/releases/tag/v0.1.0-rc.2)

<sub>Java 25 / Spring Boot 4.1 / Spring Modulith / React 19 · 预发布阶段</sub>

<details>
<summary>角色授权工作台与登录页</summary>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lilibonk/apocalypse/main/.github/assets/readme/role-workbench-dark.jpg">
  <img src="https://raw.githubusercontent.com/lilibonk/apocalypse/main/.github/assets/readme/role-workbench-light.jpg" alt="Apocalypse 角色授权工作台：权限动作开关、数据范围覆盖与有效期设置。" width="100%">
</picture>

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lilibonk/apocalypse/main/.github/assets/readme/login-dark.jpg">
  <img src="https://raw.githubusercontent.com/lilibonk/apocalypse/main/.github/assets/readme/login-light.jpg" alt="Apocalypse 登录页预览。" width="100%">
</picture>

</details>

---

### Codex Pet Collection

为 Codex 准备的自定义动画宠物合集，附带状态预览与命令行安装工具，可按需选取角色并在等待回复期间展示待机动画。

<table>
  <tr>
    <td align="center"><a href="https://github.com/lilibonk/codex-pet-collection/tree/main/pets/aira-xinghui"><img src="https://raw.githubusercontent.com/lilibonk/codex-pet-collection/main/pets/aira-xinghui/preview/idle.gif" alt="Aira · 星辉待机动画。" width="128"></a><br><strong>Aira · 星辉</strong></td>
    <td align="center"><a href="https://github.com/lilibonk/codex-pet-collection/tree/main/pets/airi-chibi"><img src="https://raw.githubusercontent.com/lilibonk/codex-pet-collection/main/pets/airi-chibi/preview/idle.gif" alt="Airi · 艾莉待机动画。" width="128"></a><br><strong>Airi · 艾莉</strong></td>
  </tr>
</table>

**[角色目录与安装](https://github.com/lilibonk/codex-pet-collection#readme)**

## 最近更新

- **2026.11.18**　[Apocalypse v0.1.0-rc.2](https://github.com/lilibonk/apocalypse/releases/tag/v0.1.0-rc.2) — 重构角色授权工作台与 V2 三主题前端体系，统一分页交互并巩固后端基线。
- **2026.10.13**　[pi-pane v0.3.0-rc.4](https://github.com/lilibonk/pi-pane/releases/tag/v0.3.0-rc.4) — 支持浏览器实时镜像、工具/diff 查看、图片输入与 HTTPS 访问。
- **2026.10.01**　[Codex Pet Collection](https://github.com/lilibonk/codex-pet-collection) 与 [Apocalypse v0.1.0-rc.1](https://github.com/lilibonk/apocalypse/releases/tag/v0.1.0-rc.1) 公开。

## 代码足迹

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lilibonk/lilibonk/codex/profile-generated/contributions-dark.svg">
  <img src="https://raw.githubusercontent.com/lilibonk/lilibonk/codex/profile-generated/contributions-light.svg" alt="过去一年公开贡献图的暖陶铜色贪吃蛇动画。" width="100%">
</picture>
