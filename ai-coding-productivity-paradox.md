---
layout: default
title: AI 编程的体感骗局：你以为快了 20%，数据说你慢了 19% · 主要来源
---

# AI 编程的体感骗局：你以为快了 20%，数据说你慢了 19% · 主要来源

本页汇集《AI 编程的体感骗局：你以为快了 20%，数据说你慢了 19%》一文中引用的所有原始资料，方便读者逐条核实。

## 核心研究：METR 随机对照实验

### 📊 Measuring the Impact of Early-2025 AI on Experienced Open-Source Developer Productivity（METR 官方博客）
本文的核心锚点。16 名资深开源开发者、246 个真实 issue 的随机对照实验，按 150 美元/小时付费：开发者动手前预测 AI 提速 24%，实测却慢了 19%（置信区间 +2% 到 +39%），干完后体感仍以为快了 20%。工具为 Cursor Pro + Claude 3.5/3.7 Sonnet，时间窗口 2025 年 2–6 月。用 AI 时，时间从「自己写代码 / 查资料」流向「写提示词 / 等待 / 审查与修正 AI 产出 / 闲置」。
🔗 <https://metr.org/blog/2025-07-10-early-2025-ai-experienced-os-dev-study/>

### 📄 论文原文（arXiv 2507.09089）
上述研究的完整论文，含工时分解（时间从「自己写代码 / 查资料」流向「写提示词 / 等待 / 审查 / 改错 / 闲置」）与方法学细节。
🔗 <https://arxiv.org/abs/2507.09089>

### 🔁 We are Changing our Developer Productivity Experiment Design（METR，2026-02）
半年后的后续：METR 想重做实验却凑不齐人——「越来越多开发者表示，即便按 50 美元/小时付费、让他们做自己挑的任务，也不愿意有一半的工作不用 AI。」并附 2025 下半年的复测区间。
🔗 <https://metr.org/blog/2026-02-24-uplift-update/>

## 共情数据：Stack Overflow 2025 开发者调研

### 📋 Stack Overflow 2025 Developer Survey
近 5 万名开发者、177 个国家。66% 把「AI 答案几乎对、但差一点」列为头号不满，45% 在 debug AI 生成代码上耗费大量时间；84% 在用或计划用 AI（2024 年为 76%），但信任 AI 输出的比例从 43% 跌到 33%。
🔗 <https://survey.stackoverflow.co/2025/>

## 客观验证：AI 代码 vs 人类代码

### 🐰 State of AI vs Human Code Generation Report（CodeRabbit，2025-12）
分析 470 个开源 PR（320 个 AI 协作 + 150 个纯人工）：AI 参与的提交平均 10.83 个问题，纯人工 6.45 个，约 1.7 倍。逻辑错误 1.75x、安全发现 1.57x，其中跨站脚本（XSS）漏洞高出 2.74x。
🔗 <https://www.coderabbit.ai/blog/state-of-ai-vs-human-code-generation-report>

## 2026 年的现场佐证

### 📰 Coders are refusing to work without AI — and that could come back to bite them（TechCrunch，2026-05-29）
依赖与维护成本的讨论。James Shore 的「拿暂时的提速换永久的卖身契」、Uber 首席运营官「AI 投入未带来可衡量产出增长」、CodeRabbit 1.7x、以及开发者自晒「把大量 token 花在修 AI 自己生成的 bug 上」均出自此文梳理。
🔗 <https://techcrunch.com/2026/05/29/coders-are-refusing-to-work-without-ai-and-that-could-come-back-to-bite-them/>

### 🗞️ AI coding tools make developers slower, study finds（The Register，2025-07）
对 METR 实验的第三方报道与工时分解解读。
🔗 <https://www.theregister.com/2025/07/11/ai_code_tools_slow_down/>

### 🧑‍💻 The best engineers in 2026 aren't the best coders（HiTechies）
「最值钱的技能从写得快变成知道何时别信 AI 代码」一节的来源，含 AI 一致翻车的几类场景（错误处理 / 安全上下文 / 并发状态 / 架构一致性 / 测试质量）。
🔗 <https://www.hitechies.com/ai-coding-agents-developer-skills-code-review-2026/>

## 相关阅读（公众号自家）

- 🪦 [「Vibe Coding 已死」？死的不是 AI，是你以为能闭眼许愿的那个幻觉](./vibe-coding-dead.html)
- 🧭 [Claude Code 动态工作流：编排这件事，终于不靠"脑子"了](./dynamic-workflows.html)

---

📅 截至 **2026-06-04**。

[← 返回首页](./)
