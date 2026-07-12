---
layout: default
title: 深度拆解 GPT-5.6 · 主要来源
---

# 深度拆解 GPT-5.6 · 主要来源

本页汇集《深度拆解 GPT-5.6：十天前我教你给模型搭循环，今天 OpenAI 把循环焊进了它骨头里》一文中引用的所有原始资料，方便读者亲手核实。

## ⭐ 三张截图的一手出处

### 📄 GPT-5.6 官方提示词指南
正文截图 1。开篇「说清楚结果 + 完工标准，把选路的自由留给模型」；精简提示词后跑分 +10–15%、Token −41–66%、成本 −33–67% 的数据来源。
🔗 <https://developers.openai.com/api/docs/guides/prompt-guidance-gpt-5p6>

### 📄 一年前的 GPT-5 提示词指南（对照组）
正文截图 2。手把手教你把 `<context_gathering>` 的 `Loop:` 循环抄进提示词的那一版（2025 年 8 月）。
🔗 <https://cookbook.openai.com/examples/gpt-5/gpt-5_prompting_guide>

### 📄 Jason Wei《Asymmetry of verification and verifier's law》
正文截图 3。验证者法则原文，含五条属性（客观对错 / 秒级可验 / 可并行验 / 低噪声 / 连续奖励），发布于 2025 年 7 月 15 日。
🔗 <https://www.jasonwei.net/blog/asymmetry-of-verification-and-verifiers-law>

## GPT-5.6 发布事实

### 🚀 OpenAI 官方发布页 · GPT-5.6
Sol / Terra / Luna 三型号；Agents' Last Exam 53.6 超 Claude Fable 5 13.1 分；`max` / `ultra` 档位；ultra 默认 4 智能体并行、评测演示 16-agent 配置；BrowseComp 92.2%。
🔗 <https://openai.com/index/gpt-5-6/>

### 📄 OpenAI 模型指南
gpt-5.6 默认路由到 Sol；推理档位 none / low / medium / high / xhigh / max。
🔗 <https://developers.openai.com/api/docs/guides/latest-model>

### 📄 Programmatic Tool Calling 指南
「模型写小程序去调度工具、处理中间结果、自己决定下一步」的官方能力说明。
🔗 <https://developers.openai.com/api/docs/guides/tools-programmatic-tool-calling>

### 📰 TechCrunch：GPT-5.6 家族发布（2026-07-09）
🔗 <https://techcrunch.com/2026/07/09/openai-launches-its-new-family-of-models-with-gpt-5-6/>

## Loop Engineering 社区思潮

### 📰 ADTmag《Loop Engineering Emerges as Developers Put AI Coding Agents on Repeat》
Boris Cherny「我已经不自己写提示词了」原话；吴恩达三层循环 + 「情境优势」；Addy Osmani「无人值守的循环也在无人值守地犯错」。2026-07-01。
🔗 <https://adtmag.com/articles/2026/07/01/loop-engineering-emerges-as-developers-put-ai-coding-agents-on-repeat.aspx>

## 社区实测（正文引用的第一人称体验）

### 🧵 全天实测 GPT-5.6-Sol：兴奋 → 质疑 → 理解
Ultra 一言不合拉一大群子代理、「拿 Token 堆排场」的吐槽；Sol + High 才是日常甜点区。
🔗 <https://x.com/i/status/2075629729508667719>

### 🧵 GPT-5.6-Sol 消耗倍增，改 config 摁住胃口
去 `~/.codex/config.toml` 改上下文窗口配置，让额度耐用 1.5–2 倍。
🔗 <https://x.com/i/status/2075961253873516879>

### 🧵「用 GPT-5.6 请立刻删掉 Superpowers 系列 Skills」
删脚手架的实证——正文「精简提示词」范式在一线的直接印证。
🔗 <https://x.com/i/status/2075941106899112422>

## 本文提到的两套外挂循环工具（unstuck）

### 🛠️ unstuck · 仓库主页（MIT）
正文说的「那两套没有客观验证器也要守的外循环工具」：north-star（交付点自我纠偏）+ moa（N+1 多模型会诊）。
🔗 <https://github.com/ele-yufo/unstuck>

## 系列深度解析（公众号自家）

- 🔁 [上一篇 · 大厂忙着造更聪明的神，我忙着给这个健忘又固执的神装一套关不掉的循环（Loop Engineering）](./loop-engineering.html)
- 🃏 [深度拆解 Mixture of Agents：一桌便宜货合议差点掀了王座](./mixture-of-agents.html)
- 🔧 [Claude Code 动态工作流：编排这件事，终于不靠"脑子"了](./dynamic-workflows.html)

---

📅 截至 **2026 年 7 月 13 日**。

[← 返回首页](./)
