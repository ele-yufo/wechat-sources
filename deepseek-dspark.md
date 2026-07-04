---
layout: default
title: 速览 DeepSeek DSpark · 主要来源
---

# 速览 DeepSeek DSpark · 主要来源

本页汇集《DeepSeek 又更新了，但这次它一个脑细胞都没动》一文中引用的所有原始资料。

## 官方一手：模型卡与代码

### 🤗 DeepSeek-V4-Pro-DSpark 模型卡（HuggingFace）
文章那句"这不是一个新模型"的原始出处。模型卡开宗明义："is not a new model. It is the same checkpoint with an additional speculative decoding module attached."，并给出通过 `--speculative-config '{"method":"dspark"...}'` 启用的用法。MIT 协议。
🔗 <https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro-DSpark>

### 🤗 DeepSeek-V4-Flash-DSpark 模型卡（HuggingFace）
小号 V4-Flash（284B 总参 / 13B 激活）的 DSpark 版本，per-user 提速 60%~85% 的那一档。
🔗 <https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-DSpark>

### 🛠️ DeepSpec · 训练与评估草稿模型的代码库（GitHub, MIT）
DSpark 背后的全栈工具包：数据准备、模型实现、训练与评测脚本，一并覆盖 DSpark / DFlash / Eagle3 三种草稿算法。想给自己的模型训一个"实习生"，从这里开始。
🔗 <https://github.com/deepseek-ai/DeepSpec>

### 📄 DSpark 论文（PDF，随 DeepSpec 仓库发布）
DSpark 的方法论原文——半自回归草稿 + 硬件感知验证调度的细节，都在这份 PDF 里（注意：它没有单独上 arXiv，是随代码库一起放出的）。
🔗 <https://github.com/deepseek-ai/DeepSpec/blob/main/DSpark_paper.pdf>

### 📄 DeepSeek-V4 模型论文（arXiv）
底座 V4 本身的论文——1.6T/49B 激活的 Pro、284B/13B 激活的 Flash，以及 1M-token 上下文的效率设计。文中那些高分跑分对应的是这里的 V4-Pro-Max，与 DSpark 无关。
🔗 <https://arxiv.org/abs/2606.19348>

## 机制拆解与媒体报道

### 📰 MarkTechPost：DSpark 加速 V4 生成 60–85% 的机制拆解
草稿-验收两段式、MTP-1 基线、半自回归策略、看 GPU 占用的验证调度——这篇讲得最细。
🔗 <https://www.marktechpost.com/2026/06/27/deepseek-releases-dspark-a-speculative-decoding-framework-that-accelerates-deepseek-v4-per-user-generation-60-85-over-mtp-1/>

### 📰 Acing AI：半自回归推测解码到底改了什么
把 DSpark 和纯序列（EAGLE-3）、纯并行（DFlash）两派的取舍讲清楚，以及"保吞吐、降延迟"的调度权衡。
🔗 <https://acingai.com/articles/deepseek-dspark-speculative-decoding>

### 📰 AI Weekly：V4-Pro-DSpark 速报（1.6T MoE / MIT）
一页看完的发布要点。
🔗 <https://aiweekly.co/alerts/deepseek-releases-v4-pro-dspark-16t-param-moe-mit-license>

## 相关背景（草稿模型的两条前路）

### 📄 EAGLE-3（纯序列草稿，准但慢那一派）
🔗 <https://arxiv.org/abs/2503.01840>

### 📄 DFlash（纯并行草稿，快但后段衰减那一派）
🔗 <https://arxiv.org/abs/2602.06036>

## 系列往期（公众号自家）

- 🔁 [大厂忙着造更聪明的神，我忙着给这个健忘又固执的神装一套关不掉的循环（Loop Engineering）](./loop-engineering.html)
- 🧩 [深度拆解 Mixture of Agents：最强模型被一封信关停的那几天，一桌便宜货合议差点掀了王座](./mixture-of-agents.html)

---

📅 截至 **2026 年 7 月 5 日**。

[← 返回首页](./)
