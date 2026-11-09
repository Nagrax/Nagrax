<!-- ======================= BANNER ======================= -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2268F7,100:5EEAD4&height=200&section=header&text=Jiale%20Mou&fontColor=ffffff&fontSize=56&fontAlignY=34&desc=AI%20Agents%20%C2%B7%20Multi-Agent%20Systems%20%C2%B7%20LLM%20Engineering&descSize=18&descAlignY=58&animation=fadeIn" alt="banner"/>

<!-- ======================= TYPING ======================= -->
<p align="center">
  <a href="https://github.com/Nagrax">
    <img src="https://readme-typing-svg.demolab.com?font=Nunito&weight=600&size=24&pause=1800&color=2268F7&center=true&vCenter=true&width=640&lines=AI%20%E8%B5%8B%E8%83%BD%E7%94%9F%E4%BA%A7;Building%20self-evolving%20agents%20%F0%9F%A4%96;Turning%20daily%20work%20into%20reusable%20skills%20%E2%9A%A1;Multi-agent%20systems%20for%20industrial%20safety%20%F0%9F%9B%A1%EF%B8%8F" alt="typing"/>
  </a>
</p>

<!-- ======================= QUICK BADGES ======================= -->
<p align="center">
  <img src="https://img.shields.io/badge/Tsinghua%20University-M.S.%20Candidate-660874?style=for-the-badge&logo=googlescholar&logoColor=white" alt="tsinghua"/>
  <a href="mailto:m2469630225@163.com">
    <img src="https://img.shields.io/badge/Email-m2469630225%40163.com-D14836?style=for-the-badge" alt="email"/>
  </a>
</p>

---

## 👋 About me

嗨，我是 **牟佳乐 (Jiale Mou)**，清华大学硕士在读 👋

我相信 **AI 赋能生产**，也喜欢亲手把这句话变成每天真的在跑的系统。眼下我正全力打磨两个开源项目：**[EvoHarness](https://github.com/Nagrax/EvoHarness)**——一款自进化 Agent 运行时：上下文折叠、Skills 自进化、反注水评测，主场景是飞书日报助手，把日常会话沉淀成可复用的技能；**[SafetyMind](https://github.com/Nagrax/SafetyMind)**——面向工业安全生产的多 Agent 问答与隐患处置平台：确定性规则守底线、LLM 做理解，每一步可审计。

这两个都是开源项目，也是我想长期做下去的事。如果你也受够了「演示惊艳、上手拉胯」的 agent——记不住上下文、攒不下经验、benchmark 注水——欢迎来**提 issue 和 PR**，一起把 Agent 做成真正的生产力工具 ⭐

<!-- ======================= TECH STACK ======================= -->
## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,vue,redis,docker,linux,git,vscode&perline=8" alt="stack"/>
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
      <p><b>Skills accumulate from real work — then do the work.</b><br/>
      8,000+ 行零重依赖 · CLI / Web / 桌面 · OpenAI / Anthropic 双协议</p>
      <p>
        <img src="https://img.shields.io/badge/GAIA-49.1%20Pass%401-2268F7?style=flat-square" alt="gaia"/>
        <img src="https://img.shields.io/badge/HLE-10.7%20(n%3D75)-8A2BE2?style=flat-square" alt="hle"/>
        <img src="https://img.shields.io/github/languages/top/Nagrax/EvoHarness?style=flat-square&color=3776AB" alt="lang"/>
        <a href="https://github.com/Nagrax/EvoHarness/stargazers"><img src="https://img.shields.io/github/stars/Nagrax/EvoHarness?style=flat-square&color=5EEAD4" alt="stars"/></a>
      </p>
    </td>
  </tr>
</table>

**为什么值得关注？**

- 🧭 **一个论点** — 可靠 agent 缺的不是推理，是运行时：上下文怎么管、工具怎么放权、经验怎么沉淀、质量怎么证明。
- 📮 **在真实日常里干活** — 主场景飞书日报助手：请求与承诺整理成可追溯日报，待发回复走审批卡片，验证过的经验自动复用。
- 🪜 **这个量级不要向量库** — 纯文件 + BM25：LoCoMo 1,540 问以 1/5 检索量持平答对率，输入 token **−62%**。
- 🧬 **自进化不卡冷启动** — 沉淀即上线，但只考「出生后」的成绩单；换版本必须过人，可审计可回滚。
- 📊 **反注水评测** — 冻结口径下超时也计失败，结论标注 A–D 证据等级，跑不出的数字不写。

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
      <h3>SafetyMind · 工业安全生产的多 Agent 问答与隐患处置平台</h3>
      <p><b>Deterministic rules guard the bottom line; LLMs do the understanding.</b><br/>
      一句话输入 → 意图 → 检索 → 路由 → 工单 → 全程留痕</p>
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

- ⚖️ **底线不交给概率** — 紧急度与置信度解耦，CRITICAL 模板先于一切澄清，建单走纯规则闸门；LLM 只做理解与表达。
- 🧾 **可审计的处置链** — 依据哪条条款、谁授权建单、工单走到哪步、导出物什么版本，全程留痕可追责。
- 🎯 **输得起的基准** — 自建 19 类 2,453 条意图基准开源；BGE 零训练 96.4%，输掉的 LLM 融合对照也原样公布。
- 🚦 **自动化是挣来的** — 准入三档影子评审先行，分歧率摆出来，业务签批之前不自动建单。

<p align="center">
  <a href="https://github.com/Nagrax/SafetyMind"><b>📖 查看仓库</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/Nagrax/SafetyMind/stargazers"><b>⭐ Star on GitHub</b></a>
</p>

---

<p align="center"><sub>📫 <a href="mailto:m2469630225@163.com"><b>m2469630225@163.com</b></a> · welcome to reach out!</sub></p>
