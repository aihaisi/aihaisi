<h1 align="center">aihaisi</h1>

<p align="center">
  <b>Digital Media Technology · Game Development &nbsp;|&nbsp; Real-time Rendering</b>
  <br><br>
  <sub>Turning what looks like art into computable parameters, reproducible pipelines, and results you can assert on.</sub>
  <br><br>
  <img src="https://img.shields.io/badge/FOCUS-Real--time_Rendering-1f6feb?style=flat-square" alt="Real-time Rendering">
  <img src="https://img.shields.io/badge/FOCUS-Agent_Skills-8957e5?style=flat-square" alt="Agent Skills">
</p>

---

<p align="center">
  <a href="README.md">简体中文</a> &nbsp;|&nbsp; <b>English</b>
</p>

## About

- **How I work** — Ask whether it can be computed, then whether it can be verified, and only then whether it looks good. Visual defects don't surface in assertions, so every pipeline has to end in pixel-level evidence.

- **Range** — Rendering (WebGL2 / GLSL, shaders and VFX in Unity Built-in RP), frontend (Vue 3 / TypeScript / single-file HTML), scripting (Python / Node / ffmpeg / XeLaTeX).

- **On the side** — Distilling every pitfall into an Agent Skill: triggers, methodology, troubleshooting paths, runnable scripts. 70+ so far, all in [aihaisi-workbuddy-skills](https://github.com/aihaisi/aihaisi-workbuddy-skills).

## Currently

- **Video pipeline** — Data-driven explainer videos: storyboard → smoke frames → render → assembly. Timing, motion parameters and pacing all come from data; each stage is gated on frame-level motion and pixel diffs rather than a gut feeling.

- **Real-time post-processing** — Probing where "the model only outputs parameters, the GPU redraws every frame" holds: the generative model never touches a pixel, and the image is rebuilt entirely in GLSL.

- **Agent skills** — Turning new pitfalls into skills: reproducible steps become scripts, judgment calls become decision points, failures leave a trail to debug from.

## Selected projects

- **[prompt-to-postfx](https://github.com/aihaisi/prompt-to-postfx)** — Natural language → parameter recipe → WebGL2 post-processing. The model decides parameters only; the GPU redraws every frame. Zero dependencies, one file, double-click to run. `WebGL2` `GLSL`

- **[aihaisi-workbuddy-skills](https://github.com/aihaisi/aihaisi-workbuddy-skills)** — Personal Agent skill library: 70+ self-contained skills covering media download, Chinese typesetting, video production and investment due diligence. `Agent Skills`

- **[token-dashboard-workbuddy](https://github.com/aihaisi/token-dashboard-workbuddy)** — Local-first token usage dashboard: per-model token counts, real credit cost and value ranking. Nothing leaves your machine. `TypeScript`

- **[elaina-mushroom-nim](https://github.com/aihaisi/elaina-mushroom-nim)** — Playable prototype for Luogu U145698; the AI strategy is proven optimal by exhaustive game-tree search, not by trial and error. `Game AI`

- **[hotel-web-book](https://github.com/aihaisi/hotel-web-book)** — Seaside resort website built with Vue 3, Vite, TypeScript and Tailwind. `Vue 3`

<details>
<summary><b>Earlier work</b></summary>

- [tagged-image-gallery](https://github.com/aihaisi/tagged-image-gallery) — A modern, tag-driven image gallery
- [vue-gallery](https://github.com/aihaisi/vue-gallery) — Image viewer built with Vue 3
- [GLstudy](https://github.com/aihaisi/GLstudy) — OpenGL practice while learning
- [plane-battle](https://github.com/aihaisi/plane-battle) · [fruit-cutting-game](https://github.com/aihaisi/fruit-cutting-game) · [MoleGame](https://github.com/aihaisi/MoleGame) · [JumpJumpGame](https://github.com/aihaisi/JumpJumpGame) — Early small games

</details>

## Stack

### Languages

[![My Language](https://skillicons.dev/icons?i=py,ts,vue,js,html,css,c,cpp,cs)](https://skillicons.dev)

### Skills

[![My Skills](https://skillicons.dev/icons?i=vscode,unity,ps,pr,ae)](https://skillicons.dev)

## What I keep coming back to

> Tools change. Models change. The only thing that carries over is knowing how to tell whether something was done right.
> So rather than adding one more feature, I'd rather leave one more assertion behind — so whoever picks this up next doesn't have to walk the same detour.

---

<h2 align="center">Stats</h2>

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

## Get in touch

A project worth building, a skill worth reusing, or just a pipeline that could hurt less — open an [Issue](https://github.com/aihaisi/aihaisi/issues). I usually reply.
