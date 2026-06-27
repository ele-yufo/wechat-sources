---
layout: default
title: 深度拆解 Mixture of Agents · 主要来源
---

# 深度拆解 Mixture of Agents · 主要来源

本页汇集《深度拆解 Mixture of Agents：最强模型被一封信关停的那几天，一桌便宜货合议差点掀了王座》一文中引用的所有原始资料。

## MoA 概念与原论文

### 📄 Together AI《Mixture-of-Agents Enhances Large Language Model Capabilities》
MoA 提出者，2024 年 6 月。AlpacaEval 2.0 上开源模型合议 65.1 翻 GPT-4o 的 57.5。
🔗 <https://arxiv.org/abs/2406.04692>

### 📄 Together MoA 官方博客
proposer / aggregator / 多层机制，「collaborativeness of LLMs」发现，六个开源 proposer 名单。
🔗 <https://www.together.ai/blog/together-moa>

### 📄 Together MoA 代码仓库
65.1% on AlpacaEval with OSS models 的参考实现。
🔗 <https://github.com/togethercomputer/moa>

## OpenRouter Fusion

### 🚀 官方公告《Surpassing Frontier Performance with Fusion》
DRACO 全表数据来源（正文那张柱状图即此页）：预算组合 64.7、Fable 5 单跑 65.3、Opus+Opus 自融合 65.5、Fusion 顶配 69.0，以及 100 题里 7 题被 Fable 5 内容过滤器挡掉的脚注。
🔗 <https://openrouter.ai/blog/announcements/fusion-beats-frontier/>

### 🚀 OpenRouter Fusion 产品页
扇出 + judge 合成的机制与成本说明。
🔗 <https://openrouter.ai/fusion>

## Hermes Agent · Mixture of Agents

### 📰 Teknium 原帖（MoA 2.0 + HermesBench 演示）
正文嵌的那张图即此帖，内嵌演示直接显示 moa 0.8202 / opus-4.8 0.7607 / gpt-5.5 0.7412。
🔗 <https://x.com/Teknium/status/2070615003674366277>

### 📄 Hermes Agent 官方文档 · Mixture of Agents
reference models + aggregator 机制、preset 配置、HermesBench 三个分数的来源。
🔗 <https://hermes-agent.nousresearch.com/docs/user-guide/features/mixture-of-agents>

## Claude Fable 5 / Mythos 5 与下线事件

### 🚀 Anthropic 官方发布页 · Claude Fable 5 & Mythos 5
6 月 9 日发布，「Mythos」层首个公开版。
🔗 <https://www.anthropic.com/news/claude-fable-5-mythos-5>

### 📰 Tom's Hardware：Fable 5 benchmark
SWE-Bench Pro 80.3、甩开次席 11 分，「state-of-the-art on nearly all tested benchmarks」。
🔗 <https://www.tomshardware.com/tech-industry/artificial-intelligence/claude-fable-5-brings-mythos-to-the-masses-anthropics-next-frontier-model-is-state-of-the-art-on-nearly-all-tested-benchmarks>

### 📰 9to5Mac：Mythos 5 部分恢复（6 月 26 日）
正文嵌图即此页。出口管制迫使 Anthropic 对所有客户关停 Fable 5 + Mythos 5；这次只放行 Mythos 5 给 100+ 家美国机构。
🔗 <https://9to5mac.com/2026/06/26/anthropic-cleared-to-release-claude-mythos-5-to-over-100-us-institutions/>

### 📜 Fable 5 当前状态追踪（截至 6 月 27 日仍下线）
🔗 <https://explainx.ai/blog/is-fable-5-back-2026>

## 预算组合涉及的模型

### 📄 Kimi K2.6（Moonshot, 1T MoE）
🔗 <https://huggingface.co/moonshotai/Kimi-K2.6>

## 系列深度解析（公众号自家）

- 🦝 [深度拆解 Claude Fable 5：给神话戴上笼口，改名寓言，卖你两倍价](./claude-fable-5.html)
- 🚓 [速报 · Fable 5 被美国政府勒令下架](./fable-5-pulled.html)
- 🔓 [深度拆解 GLM-5.2：最强模型被摁下线的那个周末，智谱把 SOTA 开源了](./glm-5-2.html)

---

📅 截至 **2026 年 6 月 28 日**。

[← 返回首页](./)
