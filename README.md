<h1 align="center">aihaisi</h1>

<p align="center">
  <b>数字媒体技术 · 在读</b> &nbsp;|&nbsp; 游戏技术策划 · 实时渲染 · 代码渲染视频
  <br><br>
  <sub>把「看起来像美术的活」拆成可计算的参数、可复现的管线、可断言的产物。</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/FOCUS-Real--time_Rendering-1f6feb?style=flat-square" alt="Real-time Rendering">
  <img src="https://img.shields.io/badge/FOCUS-Agent_Skills-8957e5?style=flat-square" alt="Agent Skills">
  <img src="https://img.shields.io/badge/FOCUS-Code--rendered_Video-3fb950?style=flat-square" alt="Code-rendered Video">
</p>

---

## 关于

- **做法**：先问「这件事能不能被计算」，再问「能不能被验证」，最后才问「好不好看」。视觉类的问题断言测不出来，所以每条管线都要落到像素级证据。
- **跨度**：渲染层（WebGL2 / GLSL、Unity Built-in RP 的 Shader 与特效）、前端层（Vue 3 / TypeScript / 单文件 H5）、脚本层（Python / Node / ffmpeg / XeLaTeX）。
- **顺手做的**：把踩过的坑沉淀成 Agent 技能 —— 触发条件、方法论、排障路径、可直接执行的脚本，目前 70+ 个，都在 [aihaisi-workbuddy-skills](https://github.com/aihaisi/aihaisi-workbuddy-skills)。

## 此刻在做

| 方向 | 具体的事 |
| :--- | :--- |
| 代码渲染视频 | 数据驱动的解释类视频管线：分镜 → 冒烟帧 → 渲染 → 装配。时间轴、动效参数、呼吸感都由数据决定，出口按逐帧运动量与像素差验收，不看「感觉差不多」 |
| 实时后处理 | 探索「AI 只输出参数、GPU 逐帧重绘」的边界 —— 生成模型不碰一颗像素，画面全部由 GLSL 重建 |
| Agent 技能 | 持续把新踩的坑写成技能：能复现的步骤进脚本，判断类的进「关节判别」，失败现场留排障路径 |

## 代表项目

| 项目 | 它解决什么 | 关键词 |
| :--- | :--- | :--- |
| **[prompt-to-postfx](https://github.com/aihaisi/prompt-to-postfx)** | 自然语言 → 参数配方 → WebGL2 后处理。AI 只决策参数，GPU 逐帧重绘，零依赖单文件 | `WebGL2` `GLSL` |
| **[aihaisi-workbuddy-skills](https://github.com/aihaisi/aihaisi-workbuddy-skills)** | 个人 Agent 技能库，70+ 个自包含技能：媒体下载、中文排版、代码渲染视频、投研尽调 | `Agent Skills` |
| **[token-dashboard-workbuddy](https://github.com/aihaisi/token-dashboard-workbuddy)** | 本地优先的 Token 用量看板：按模型统计 token、真实 credit 与性价比排名 | `TypeScript` |
| **[elaina-mushroom-nim](https://github.com/aihaisi/elaina-mushroom-nim)** | 洛谷 U145698 玩法原型；AI 策略经博弈树穷举验证为最优，不是玄学调参 | `Game AI` |
| **[hotel-web-book](https://github.com/aihaisi/hotel-web-book)** | Vue 3 + Vite + TypeScript + Tailwind 的海滨度假酒店官网 | `Vue 3` |

<details>
<summary><b>更早的一些东西</b></summary>

- [tagged-image-gallery](https://github.com/aihaisi/tagged-image-gallery) — 标签化的现代图片画廊
- [vue-gallery](https://github.com/aihaisi/vue-gallery) — vue3 图片展示
- [GLstudy](https://github.com/aihaisi/GLstudy) — OpenGL 学习过程中的练习
- [plane-battle](https://github.com/aihaisi/plane-battle) · [fruit-cutting-game](https://github.com/aihaisi/fruit-cutting-game) · [MoleGame](https://github.com/aihaisi/MoleGame) · [JumpJumpGame](https://github.com/aihaisi/JumpJumpGame) — 早期小游戏
- [cuzthesis](https://github.com/aihaisi/cuzthesis) — 浙传 LaTeX 论文模板（fork）

</details>

## 技术栈

### Languages

[![My Language](https://skillicons.dev/icons?i=py,ts,vue,js,html,css,c,cpp,cs)](https://skillicons.dev)

### Skills

[![My Skills](https://skillicons.dev/icons?i=vscode,unity,ps,pr,ae)](https://skillicons.dev)

## 在想什么

> 工具会换、模型会换，能被复用的只有「怎么判断一件事做对了」。
> 所以比起多写一个功能，我更愿意多留一条断言 —— 让下一个接手的人不用重走一遍我的弯路。

---

<h2 align="center">数据</h2>

<p align="center">
  <a href="https://github.com/aihaisi">
    <img src="https://github-stats-extended.vercel.app/api?username=aihaisi&show=reviews%2Cdiscussions_started%2Cdiscussions_answered%2Cprs_merged%2Cprs_merged_percentage%2Cprs_commented%2Cprs_reviewed%2Cissues_commented&show_icons=true&include_all_commits=true&theme=dark" alt="GitHub stats">
  </a>
</p>

<p align="center">
  <a href="https://github.com/aihaisi">
    <img src="https://github-stats-extended.vercel.app/api/top-langs?username=aihaisi&langs_count=5&theme=dark" alt="Top Langs">
  </a>
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=AIhaisi&theme=nord_dark" alt="Most commit language">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=AIhaisi&theme=nord_dark" alt="Repos per language">
</p>

---

## 找我

有想一起做的项目、想复用的技能，或者只是觉得某条管线还能更省事 —— 开个 [Issue](https://github.com/aihaisi/aihaisi/issues) 就行，我基本都会回。

<!-- ============================================================ -->
<!-- 以下是原 README 的内容，全部保留未删除，仅移到此处存档        -->
<!-- ============================================================ -->

<!-- 原「stats 卡片」备用（alt 指向 stats-organization/github-stats-extended）： -->
<!--
[![https://github.com/stats-organization/github-stats-extended](https://github-stats-extended.vercel.app/api?username=aihaisi&show=reviews%2Cdiscussions_started%2Cdiscussions_answered%2Cprs_merged%2Cprs_merged_percentage%2Cprs_commented%2Cprs_reviewed%2Cissues_commented&show_icons=true&include_all_commits=true&theme=dark)](https://github.com/aihaisi)
-->

<!--
![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=AIhaisi&theme=transparent)
-->

<!-- 原「Languages」备用 badge： -->
<!--
![Python](https://img.shields.io/badge/Python-14354C.svg?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330.svg?logo=javascript&logoColor=F7DF1E&style=for-the-badge)
![C](https://img.shields.io/badge/C-00599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
-->

<!-- 原「Skills」备用 badge： -->
<!--
![VueJS](https://img.shields.io/badge/Vue.js-35495e.svg?style=for-the-badge&logo=vue.js&logoColor=4FC08D)
![Node](https://img.shields.io/badge/Node.js-43853D.svg?logo=node.js&logoColor=white&style=for-the-badge)
![Unity](https://img.shields.io/badge/Unity-100000.svg?logo=unity&logoColor=white&style=for-the-badge)
-->

<!-- 原 GitHub 默认引导文案： -->
<!--
**AIhaisi/AIhaisi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
