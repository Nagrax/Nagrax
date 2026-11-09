<!-- ======================= BANNER ======================= -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2268F7,100:5EEAD4&height=200&section=header&text=Jiale%20Mou&fontColor=ffffff&fontSize=56&fontAlignY=34&desc=AI%20Agents%20%C2%B7%20Multi-Agent%20Systems%20%C2%B7%20LLM%20Engineering&descSize=18&descAlignY=58&animation=fadeIn" alt="banner"/>

<!-- ======================= TYPING ======================= -->
<p align="center">
  <a href="https://github.com/Nagrax">
    <img src="https://readme-typing-svg.demolab.com?font=Nunito&weight=600&size=24&pause=1800&color=2268F7&center=true&vCenter=true&width=640&lines=AI%20%E8%B5%8B%E8%83%BD%E7%94%9F%E4%BA%A7;Building%20self-evolving%20agents%20%F0%9F%A4%96;Multi-agent%20systems%20for%20industrial%20safety%20%F0%9F%9B%A1%EF%B8%8F;Context%20folding%20%C2%B7%20Skills%20evolution%20%C2%B7%20Offline%20evals" alt="typing"/>
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

我相信 **AI 赋能生产**——把大模型做成能在真实业务里稳定跑活的系统，而不是停在演示。眼下我正全力打磨两个开源项目：**[EvoHarness](https://github.com/Nagrax/EvoHarness)**——一款 8,000+ 行零重依赖的自进化 Agent 运行时，上下文折叠、Skills 自进化、评测证据分级可复算，最近跑通了飞书日报自迭代闭环；**[SafetyMind](https://github.com/Nagrax/SafetyMind)**——面向工业安全生产的多 Agent 问答与隐患处置平台，从意图识别到工单五阶段治理、全程留痕，发布门禁 104/104 全绿。

它们都是我想长期做下去的事。如果你也对 Agent 与 LLM 工程化感兴趣，欢迎来**提 issue 和 PR**，一起把 Agent 做成真正的生产力 ⭐

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
      <p><b>A transparent, self-evolving agent runtime — fold the context, evolve the skills, prove it offline.</b><br/>
      8,000+ 行零重依赖 · CLI / Web / 桌面三形态 · OpenAI / Anthropic 双协议。</p>
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

- 🔍 **透明 Agent Loop，不用框架** — 消息历史每个字节可控：流式 tool 参数拼装、每轮落盘、`--resume` 断点续跑；五档权限做在 runtime 代码层，不靠 prompt 劝模型。
- 🪜 **上下文折叠** — 70% 硬阈值折叠为 episode / working / tool 三层结构化记忆，文件路径、已否定结果等硬状态绝不丢；LoCoMo 1,540 问以 **1/5 检索量**持平答对率、输入 token **−62%**。
- 🧬 **Skills 自进化** — 证据组 / 成绩组双池、五级状态机接回运行时检索加权、三区部署灰度 + 追加式审计；SKILL.md 写坏从「静默消失」到 diff 建议一键修复。
- 📊 **评测可复算，证据分级** — GAIA 165 题冻结口径 Pass@1 **49.1**（超时/执行错误一律计失败）、HLE n=75 有效 **10.7**；每条结论标注 A–D 证据强度，D 级禁止对外宣称。
- 📮 **飞书日报自迭代闭环** — 把会话中的请求、承诺与解决办法整理成可追溯日报，待批回复走审批卡片，验证过的经验在限定范围自动复用——运行时自己成了第一个生产用户。

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
      <h3>SafetyMind · 面向工业安全生产的多 Agent 问答与隐患处置平台</h3>
      <p><b>Industrial safety Q&A with an auditable disposal chain — deterministic rules guard the bottom line, LLMs do the understanding.</b><br/>
      意图识别 → 安全知识检索 → 多 Agent 路由 → SOP 注入 → 工单 / 升级 → 全程留痕。</p>
      <p>
        <img src="https://img.shields.io/badge/Gate-104%2F104-2EA443?style=flat-square" alt="gate"/>
        <img src="https://img.shields.io/github/languages/top/Nagrax/SafetyMind?style=flat-square&color=3776AB" alt="lang"/>
        <img src="https://img.shields.io/badge/Vue-frontend-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" alt="vue"/>
        <img src="https://img.shields.io/badge/Docker-compose-2496ED?style=flat-square&logo=docker&logoColor=white" alt="docker"/>
        <a href="https://github.com/Nagrax/SafetyMind/stargazers"><img src="https://img.shields.io/github/stars/Nagrax/SafetyMind?style=flat-square&color=5EEAD4" alt="stars"/></a>
      </p>
    </td>
  </tr>
</table>

**为什么值得关注？**

- 🎯 **自建意图基准，敢贴对照** — 19 类安全意图 **2,453 条**基准随仓库开源；BGE 双模型零训练分类器 test **96.4%** / 独立留出 **94.9%**，单条 94ms CPU——LLM 融合 64.6%、关键词 56.5% 等输掉的对照也原样公布。
- 🛡️ **安全底线由确定性规则守** — 紧急度与意图置信度解耦，CRITICAL 模板先于一切澄清；隐患建单走纯规则闸门：HIGH+ 自动建单、MEDIUM 确认卡防工单贬值；「爆炸极限」不会被误判成现场爆炸。
- 📋 **工单五阶段治理闭环** — 服务端唯一状态机 + 角色权限矩阵 + 乐观并发 409 + 不可变授权快照；验收摘要「预览哈希 → 授权导出」两步授权，同秒并发导出不覆写。
- 🚦 **准入三档与影子评审** — `off / observe / auto` 分级放开自动化：影子双轨评审报告可见分歧与确认率，未获业务签批 `auto` 不开启——能力到位但边界诚实。
- 🔁 **19 轮无人值守闭环** — 93 条发现修复 91、待办清零；发布门禁 **104/104** 全绿（RED 违规零容忍），403 拒绝同样落审计。

<p align="center">
  <a href="https://github.com/Nagrax/SafetyMind"><b>📖 查看仓库</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/Nagrax/SafetyMind/stargazers"><b>⭐ Star on GitHub</b></a>
</p>

---

<p align="center"><sub>📫 <a href="mailto:m2469630225@163.com"><b>m2469630225@163.com</b></a> · welcome to reach out!</sub></p>
