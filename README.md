<!-- ======================= BANNER ======================= -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2268F7,100:5EEAD4&height=200&section=header&text=Nagrax&fontColor=ffffff&fontSize=56&fontAlignY=34&desc=AI%20Agents%20%C2%B7%20Multi-Agent%20Systems%20%C2%B7%20LLM%20Engineering&descSize=18&descAlignY=58&animation=fadeIn" alt="banner"/>

<!-- ======================= TYPING ======================= -->
<p align="center">
  <a href="https://github.com/Nagrax">
    <img src="https://readme-typing-svg.demolab.com?font=Nunito&weight=600&size=24&pause=1800&color=2268F7&center=true&vCenter=true&width=640&lines=AI%20%E8%B5%8B%E8%83%BD%E7%94%9F%E4%BA%A7;Building%20self-evolving%20agents%20%F0%9F%A4%96;Multi-agent%20systems%20for%20industrial%20safety%20%F0%9F%9B%A1%EF%B8%8F;Context%20folding%20%C2%B7%20Skills%20evolution%20%C2%B7%20Offline%20evals" alt="typing"/>
  </a>
</p>

<!-- ======================= QUICK BADGES ======================= -->
<p align="center">
  <img src="https://img.shields.io/badge/Focus-AI%20Agent%20Engineering-2268F7?style=for-the-badge&logo=python&logoColor=white" alt="focus"/>
  <a href="mailto:m2469630225@163.com">
    <img src="https://img.shields.io/badge/Email-m2469630225%40163.com-D14836?style=for-the-badge" alt="email"/>
  </a>
</p>

---

## 👋 About me

嗨，我是 **Nagrax** 👋，方向是 **AI Agent 与 LLM 工程化**，一句话信条：**AI 赋能生产**——把大模型做成能在真实业务里稳定跑活的系统，而不是停在演示。

目前开源维护两个项目：

- 🧬 **[EvoHarness](https://github.com/Nagrax/EvoHarness)** — 自进化 Agent 运行时：透明 Agent Loop、上下文折叠、Skills 自进化、离线评测。
- 🛡️ **[SafetyMind](https://github.com/Nagrax/SafetyMind)** — 面向工业安全生产的多 Agent 协同平台：意图识别、多 Agent 路由、RAG 与三级记忆。

平时折腾 Agent 评测、上下文工程、多 Agent 编排与检索增强。欢迎提 issue / PR，一起把 Agent 做成真正的生产力 ⭐

<!-- ======================= TECH STACK ======================= -->
## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,vue,redis,docker,linux,git,vscode&perline=8" alt="stack"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MCP-Client%20%2F%20Server-000000?style=flat-square" alt="mcp"/>
  <img src="https://img.shields.io/badge/RAG-父子召回-2268F7?style=flat-square" alt="rag"/>
  <img src="https://img.shields.io/badge/LLM--as--Judge-Eval-2EA043?style=flat-square" alt="eval"/>
  <img src="https://img.shields.io/badge/Claude%20API-Anthropic%20%E6%A0%BC%E5%BC%8F-D97757?style=flat-square" alt="anthropic"/>
  <img src="https://img.shields.io/badge/Chroma-Vector%20Store-FF6F00?style=flat-square" alt="chroma"/>
</p>

---

<!-- ======================= SPOTLIGHT: EVOHARNESS ======================= -->
## 🌟 Spotlight — EvoHarness

<table>
  <tr>
    <td width="150" align="center" valign="middle">
      <a href="https://github.com/Nagrax/EvoHarness">
        <img src="https://raw.githubusercontent.com/Nagrax/EvoHarness/main/logo.png" width="128" height="128" alt="EvoHarness"/>
      </a>
    </td>
    <td valign="middle">
      <h3>EvoHarness · 自进化 Agent 运行时</h3>
      <p><b>A transparent, self-evolving agent runtime — fold the context, evolve the skills, benchmark offline.</b><br/>
      透明 Agent Loop · 三层上下文折叠 · Skills 自进化晋升 · 离线评测可复算。</p>
      <p>
        <img src="https://img.shields.io/github/languages/top/Nagrax/EvoHarness?style=flat-square&color=3776AB" alt="lang"/>
        <a href="https://github.com/Nagrax/EvoHarness/stargazers"><img src="https://img.shields.io/github/stars/Nagrax/EvoHarness?style=flat-square&color=5EEAD4" alt="stars"/></a>
      </p>
    </td>
  </tr>
</table>

**为什么值得关注？**

- 🔍 **透明 Agent Loop** — plan → execute → verify → deliver 四阶段可观测，逐段记录 token / 折叠 / 产物，长任务 `--resume` 断点续跑。
- 🪜 **三层上下文折叠** — episode / working / tool 分级折叠：LoCoMo 1,540 题上检索输入 token **−61.7%**、token-F1 持平。
- 🧬 **Skills 自进化** — add / merge / revise / discard 全链路，champion 门控晋升 + experimental → staging → core 三区灰度，追加式审计可重放。
- 📊 **评测可复算** — GAIA validation 165 题 Pass@1 **51.5%**（85/165），predictions 全量落盘可复核；折叠消融配对显著（McNemar p=0.011）。

<p align="center">
  <a href="https://github.com/Nagrax/EvoHarness"><b>📖 查看仓库</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/Nagrax/EvoHarness/stargazers"><b>⭐ Star on GitHub</b></a>
</p>

---

<!-- ======================= SPOTLIGHT: SAFETYMIND ======================= -->
## 🌟 Spotlight — SafetyMind

<table>
  <tr>
    <td width="150" align="center" valign="middle">
      <a href="https://github.com/Nagrax/SafetyMind">
        <img src="https://raw.githubusercontent.com/Nagrax/SafetyMind/main/logo.png" width="128" height="128" alt="SafetyMind"/>
      </a>
    </td>
    <td valign="middle">
      <h3>SafetyMind · 面向工业安全生产的多 Agent 协同平台</h3>
      <p><b>Multi-agent collaboration for industrial safety — from intent recognition to closed-loop hazard handling.</b><br/>
      19 类安全意图识别 · 多 Agent 路由与人工升级分流 · 父子召回 RAG · 三级记忆 · 桌面 / Web / Docker 三形态。</p>
      <p>
        <img src="https://img.shields.io/github/languages/top/Nagrax/SafetyMind?style=flat-square&color=3776AB" alt="lang"/>
        <img src="https://img.shields.io/badge/Vue-frontend-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" alt="vue"/>
        <img src="https://img.shields.io/badge/Docker-compose-2496ED?style=flat-square&logo=docker&logoColor=white" alt="docker"/>
        <a href="https://github.com/Nagrax/SafetyMind/stargazers"><img src="https://img.shields.io/github/stars/Nagrax/SafetyMind?style=flat-square&color=5EEAD4" alt="stars"/></a>
      </p>
    </td>
  </tr>
</table>

**为什么值得关注？**

- 🎯 **意图识别快而准** — 19 类安全意图基准 **2,453 条**；BGE 双模型语义原型分类器零训练：test **96.42%**（n=1,033），单条 94ms CPU / 13ms GPU。
- ⚡ **两级级联提速** — 意图阶段 2,907ms → 47ms（GPU 20ms）≈ **62×**，低置信带自动澄清反问兜底。
- 📋 **隐患定级有依据** — 1,515 条隐患定级依据覆盖 14 大类；分层触发闸门：HIGH+ 自动建单 / MEDIUM 确认卡 / LOW 不触发。
- 🔄 **五阶段人机闭环** — brief → discuss → execute → feedback → accept/reject，EmployeeAgent 记忆装配 + ExpertAgent 无状态池化。
- 🧠 **三级记忆与画像** — Redis 工作记忆 / Chroma 情景记忆 / Chroma 人员安全画像，动态 Skills 人工审批落盘。

<p align="center">
  <a href="https://github.com/Nagrax/SafetyMind"><b>📖 查看仓库</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/Nagrax/SafetyMind/stargazers"><b>⭐ Star on GitHub</b></a>
</p>

---

<p align="center"><sub>📫 <a href="mailto:m2469630225@163.com"><b>m2469630225@163.com</b></a> · welcome to reach out!</sub></p>
