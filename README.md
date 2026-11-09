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

我相信 **AI 赋能生产**——把大模型做成能在真实业务里稳定跑活的系统，而不是停在演示。眼下我正全力打磨两个开源项目：**[EvoHarness](https://github.com/Nagrax/EvoHarness)**——一款 8,000+ 行零重依赖的自进化 Agent 运行时，主场景是飞书日报助手：把日常会话里的请求与解决办法沉淀成可复用的 skill，替用户处理重复任务；**[SafetyMind](https://github.com/Nagrax/SafetyMind)**——面向工业安全生产的多 Agent 问答与隐患处置平台，确定性规则守底线、LLM 做理解，每一步可审计。

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
      <p><b>A self-evolving agent runtime — skills accumulate from real work, then do the work.</b><br/>
      8,000+ 行零重依赖 · CLI / Web / 桌面 · OpenAI / Anthropic 双协议 · 主场景：飞书日报助手。</p>
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

- 🧭 **一个论点** — 把大模型变成可靠的 agent，缺的从来不是推理能力，而是运行时：上下文怎么管、工具怎么放权、经验怎么沉淀、沉淀质量怎么证明。8,000+ 行零重依赖回答这四个问题。
- 📮 **已经在真实日常里干活** — 主场景是飞书日报助手：把会话中的请求、承诺与进展整理成可追溯日报，待发回复走审批卡片；验证过的经验在限定范围自动复用——沉淀下来的 skill 持续替用户处理重复的日常任务，而不只是回答问题。
- 🪜 **这个量级，记忆不需要向量库** — 纯文件 + BM25：LoCoMo 1,540 问以 **1/5 检索量**持平向量基线的答对率，输入 token **−62%**；人可以直接改，git 可以版本化。
- 🧬 **自进化不卡冷启动** — 沉淀即上线攒真实使用证据，但只考「出生后」的成绩单：skill 不为出生前的回复负责，纠正型 skill 不会被旧样本永久卡死；换版本必须过人，可审计可回滚。
- 📊 **反注水的评测** — 冻结口径：超时与执行错误一律计失败；结论标注 A–D 证据强度，跑不出来的数字不写。

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
        <img src="https://img.shields.io/github/languages/top/Nagrax/SafetyMind?style=flat-square&color=3776AB" alt="lang"/>
        <img src="https://img.shields.io/badge/Vue-frontend-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" alt="vue"/>
        <img src="https://img.shields.io/badge/Docker-compose-2496ED?style=flat-square&logo=docker&logoColor=white" alt="docker"/>
        <a href="https://github.com/Nagrax/SafetyMind/stargazers"><img src="https://img.shields.io/github/stars/Nagrax/SafetyMind?style=flat-square&color=5EEAD4" alt="stars"/></a>
      </p>
    </td>
  </tr>
</table>

**为什么值得关注？**

- ⚖️ **答错代价不对称的领域，底线不能交给概率** — 安全底线由确定性规则守：紧急度与意图置信度解耦、CRITICAL 模板先于一切澄清、隐患建单走纯规则闸门；LLM 只负责理解与表达，模型不可信时底线仍在。
- 🧾 **给得出聊天机器人给不了的东西：可审计的处置链** — 不止「答对了」，而是依据哪条法规条款、谁授权建单、工单走到哪个阶段、导出物的哈希与版本——每个动作留痕，可回放、可追责。
- 🎯 **输得起的基准** — 自建 19 类安全意图 **2,453 条**基准随仓库开源；BGE 零训练分类器 test **96.4%** / 独立留出 **94.9%**，而 LLM 融合 64.6%、关键词 56.5% 这些输掉的对照也原样公布，复现步骤齐全。
- 🚦 **自动化是挣来的，不是白拿的** — 准入三档 `off / observe / auto`：影子评审先双轨跑出与人工的分歧率，业务签批之前 `auto` 不开启。宁可慢一步，不做黑箱。

<p align="center">
  <a href="https://github.com/Nagrax/SafetyMind"><b>📖 查看仓库</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/Nagrax/SafetyMind/stargazers"><b>⭐ Star on GitHub</b></a>
</p>

---

<p align="center"><sub>📫 <a href="mailto:m2469630225@163.com"><b>m2469630225@163.com</b></a> · welcome to reach out!</sub></p>
