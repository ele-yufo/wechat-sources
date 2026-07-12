---
layout: default
title: 深度拆解 Loop Engineering · 主要来源
---

# 深度拆解 Loop Engineering · 主要来源

本页汇集《大厂忙着造更聪明的神，我忙着给这个健忘又固执的神装一套关不掉的循环》一文中引用的所有原始资料。

## ⭐ 本文开源的两套工具（unstuck）

### 🛠️ unstuck · 仓库主页（MIT）
文中那两套工具的完整代码：north-star（交付点自我纠偏）+ moa（N+1 多模型会诊）。一个仓库，MIT 协议。
🔗 <https://github.com/ele-yufo/unstuck>

### 🌟 north-star · 交付点自我纠偏
PostToolUse hook 在每次交付时把 vision + 状态 + 失败清单重新注入上下文，防钻牛角尖 / 沉没成本 / 压缩失忆。
🔗 <https://github.com/ele-yufo/unstuck/tree/main/north-star>

### 🩺 moa · N+1 多模型会诊
卡住时并行问 N 个不同家族模型 + 1 个空上下文的自己，先出分歧地图再综合。
🔗 <https://github.com/ele-yufo/unstuck/tree/main/moa>

### 📓 地震竞赛案例（机制救回来了）
外部会诊一次点破 Agent 对自己撒的 5 个谎，带数字的实战复盘。
🔗 <https://github.com/ele-yufo/unstuck/blob/main/north-star/CASE_STUDY_earthquake.md>

### 📓 Nemotron 案例（机制没救回来）
机制在错误框架里越焊越死的失败复盘，以及是哪 5 个缺口造成的。
🔗 <https://github.com/ele-yufo/unstuck/blob/main/north-star/CASE_STUDY_nemotron.md>

## 范式：Context / Harness / Loop Engineering

### 📄 Anthropic《Effective Context Engineering for AI Agents》
context engineering 的定义、context rot、结构化笔记写到上下文窗口之外。
🔗 <https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents>

### 📄 LangChain《The Art of Loop Engineering》
"Agent 的潜力藏在你给它搭的那些循环里"，四层嵌套循环（Agent / 验证 / 事件驱动 / 爬坡）。
🔗 <https://www.langchain.com/blog/the-art-of-loop-engineering>

## 推理时扩展（并行 / 顺序两条腿）

### 📄《Scaling Test-Time Compute for Agentic Coding》
并行=锦标赛投票 RTV，顺序=Parallel-Distill-Refine（PDR）。Claude Opus 在 SWE-Bench Verified 70.9→77.6、Terminal-Bench 46.9→59.1。
🔗 <https://arxiv.org/abs/2604.16529>

### 📄 Mixture-of-Agents 原论文（Together AI, 2024-06）
模型的"协作性"，全开源合议 65.1 翻 GPT-4o 的 57.5（AlpacaEval 2.0）。
🔗 <https://arxiv.org/abs/2406.04692>

## Fable 5 / Mythos 5：下线与恢复

### 🚀 Anthropic 官方 · 重新部署 Fable 5
Fable 5 于 7 月 1 日面向全球用户恢复；Mythos 5 先恢复给一批获批机构。
🔗 <https://www.anthropic.com/news/redeploying-fable-5>

### 🚀 Anthropic 官方发布页 · Fable 5 & Mythos 5
SWE-Bench Pro 80.3 的来源。
🔗 <https://www.anthropic.com/news/claude-fable-5-mythos-5>

### 📰 Tom's Hardware：美方解除出口管制
19 天下线到恢复的时间线。
🔗 <https://www.tomshardware.com/tech-industry/artificial-intelligence/anthropic-restores-claude-fable-5-as-us-lifts-export-controls>

## 系列深度解析（公众号自家）

- 🔁 [下一篇 · 深度拆解 GPT-5.6：这套循环，正在被 OpenAI 焊进模型的骨头](./gpt56-loop-engineering.html)
- 🃏 [深度拆解 Mixture of Agents：最强模型被一封信关停的那几天，一桌便宜货合议差点掀了王座](./mixture-of-agents.html)
- 🔧 [Claude Code 动态工作流：编排这件事，终于不靠"脑子"了](./dynamic-workflows.html)

---

📅 截至 **2026 年 7 月 3 日**。

[← 返回首页](./)
