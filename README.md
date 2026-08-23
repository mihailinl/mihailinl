<p align="center">
  <img src="assets/header.svg" alt="mihailin — Minice, software studio" width="100%">
</p>

<p align="center">
  <a href="https://minice.ai"><img src="https://img.shields.io/badge/minice.ai-17152A?style=flat-square&logo=safari&logoColor=9C8CFF" alt="minice.ai"></a>
  <a href="https://astra.minice.ai"><img src="https://img.shields.io/badge/astra.minice.ai-17152A?style=flat-square&logo=probot&logoColor=9C8CFF" alt="astra.minice.ai"></a>
  <a href="https://store.steampowered.com/app/3853440/Astra_Your_Virtual_Assistant/"><img src="https://img.shields.io/badge/Astra%20on%20Steam-17152A?style=flat-square&logo=steam&logoColor=9C8CFF" alt="Astra on Steam"></a>
  <a href="https://t.me/zxc_miha"><img src="https://img.shields.io/badge/Telegram-17152A?style=flat-square&logo=telegram&logoColor=9C8CFF" alt="Telegram"></a>
</p>

---

### About

I run **Minice**, a one-person software studio. Right now that mostly means **Astra** — a desktop voice assistant with a VRM character that lives in a transparent window on top of your desktop. It listens, answers, opens your apps, and changes expression depending on how the conversation is going.

It's written in Rust. Speech recognition and synthesis run locally. The avatar renderer is hand-rolled wgpu — MToon shading, GPU skeletal skinning, spring bones — because every off-the-shelf option wanted a game engine attached.

I started writing code in 2022 with a console Pac-Man in C#. The path went C# → .NET → WinUI → Rust and shader math, and that's where I stopped moving.

**Most of my work is closed source**, so this profile is the visible edge of it. The public repos below are pieces I pulled out of Astra and released on their own.

---

### Shipping

<table>
<tr>
<td width="50%" valign="top">

**[Astra](https://store.steampowered.com/app/3853440/Astra_Your_Virtual_Assistant/)** · closed source

A desktop voice assistant with a character. Rust + Tauri, local STT/TTS, custom wgpu VRM renderer, agentic tool-calling pipeline.

[Steam](https://store.steampowered.com/app/3853440/Astra_Your_Virtual_Assistant/) · [astra.minice.ai](https://astra.minice.ai)

</td>
<td width="50%" valign="top">

**[Minice](https://minice.ai)** · the studio

Small, independent, self-funded. Everything I ship goes out under this name.

[minice.ai](https://minice.ai)

</td>
</tr>
</table>

### Open pieces

| Repo | What it is |
| --- | --- |
| **[AstraPlugins](https://github.com/mihailinl/AstraPlugins)** | Plugin SDKs for Astra in Rust, Python and TypeScript, plus a CLI and example plugins. gRPC process isolation, so a plugin crash can't take the assistant down. |
| **[astra-search](https://github.com/mihailinl/astra-search)** | Search layer extracted from Astra, usable standalone. |
| **[astra-hotkey](https://github.com/mihailinl/astra-hotkey)** | Cross-platform global hotkey capture for desktop apps. |
| **[mihailin.dev](https://github.com/mihailinl/mihailin.dev)** | My site. GSAP scroll sequencing and a live Three.js VRM of Astra. |

---

### Stack

**Core**  
![Rust](https://img.shields.io/badge/Rust-17152A?style=flat-square&logo=rust&logoColor=9C8CFF)
![TypeScript](https://img.shields.io/badge/TypeScript-17152A?style=flat-square&logo=typescript&logoColor=9C8CFF)
![Python](https://img.shields.io/badge/Python-17152A?style=flat-square&logo=python&logoColor=9C8CFF)
![C#](https://img.shields.io/badge/C%23-17152A?style=flat-square&logo=csharp&logoColor=9C8CFF)
![Tokio](https://img.shields.io/badge/Tokio-17152A?style=flat-square&logoColor=9C8CFF)

**Desktop & graphics**  
![Tauri](https://img.shields.io/badge/Tauri-17152A?style=flat-square&logo=tauri&logoColor=9C8CFF)
![wgpu](https://img.shields.io/badge/wgpu-17152A?style=flat-square&logo=webgpu&logoColor=9C8CFF)
![WGSL](https://img.shields.io/badge/WGSL-17152A?style=flat-square&logoColor=9C8CFF)
![VRM](https://img.shields.io/badge/VRM%20%2F%20MToon-17152A?style=flat-square&logoColor=9C8CFF)
![Three.js](https://img.shields.io/badge/Three.js-17152A?style=flat-square&logo=threedotjs&logoColor=9C8CFF)
![Unity](https://img.shields.io/badge/Unity-17152A?style=flat-square&logo=unity&logoColor=9C8CFF)

**Voice & ML**  
![ONNX Runtime](https://img.shields.io/badge/ONNX%20Runtime-17152A?style=flat-square&logo=onnx&logoColor=9C8CFF)
![Parakeet](https://img.shields.io/badge/Parakeet%20STT-17152A?style=flat-square&logoColor=9C8CFF)
![Piper](https://img.shields.io/badge/Piper%20TTS-17152A?style=flat-square&logoColor=9C8CFF)
![model2vec](https://img.shields.io/badge/model2vec-17152A?style=flat-square&logoColor=9C8CFF)

**Ships on**  
![Linux](https://img.shields.io/badge/Linux-17152A?style=flat-square&logo=linux&logoColor=9C8CFF)
![Windows](https://img.shields.io/badge/Windows-17152A?style=flat-square&logo=windows&logoColor=9C8CFF)
![Steam](https://img.shields.io/badge/Steam-17152A?style=flat-square&logo=steam&logoColor=9C8CFF)
![Cloudflare](https://img.shields.io/badge/Cloudflare-17152A?style=flat-square&logo=cloudflare&logoColor=9C8CFF)

---

### Numbers

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=mihailinl&show_icons=true&hide_border=true&bg_color=00000000&title_color=7C6BF5&text_color=8A85A3&icon_color=FF9E6B&include_all_commits=true&rank_icon=github&hide=issues" alt="GitHub stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mihailinl&layout=compact&hide_border=true&bg_color=00000000&title_color=7C6BF5&text_color=8A85A3&langs_count=6&exclude_repo=unity-desktop-lite,paperclip&hide=shell" alt="Top languages">
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=mihailinl&hide_border=true&background=00000000&stroke=1F1C2F&ring=7C6BF5&fire=FF9E6B&currStreakLabel=7C6BF5&currStreakNum=8A85A3&sideLabels=8A85A3&sideNums=8A85A3&dates=6E6A85&excludeDaysLabel=6E6A85" alt="Streak">
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=mihailinl&theme=nord&no-frame=true&no-bg=true&column=6&margin-w=6&margin-h=6" alt="Trophies">
</p>

---

<p align="center">
  <sub>Reverse engineering, low-level internals, and two budgerigars who supervise.</sub>
</p>
