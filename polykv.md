---
layout: default
title: 论文实战 · PolyKV 多 Agent 共享压缩 KV · 主要来源
---

# 论文实战 · PolyKV：多 Agent 共享压缩 KV · 主要来源

本页汇集《论文实战 · PolyKV：多个 AI Agent 怎么共用一份压缩 KV，把显存从爆炸压成一条平线》一文涉及的论文、代码与资料。

## 论文与官方实现

### 📄 PolyKV 论文（arXiv）
多 Agent 共享非对称压缩 KV 缓存的原始论文。
🔗 <https://arxiv.org/abs/2604.24971>

### 🚀 PolyKV 官方代码仓库
作者开源的实现，含一键复现入口（也可直接 `pip install polykv-llm`）。
🔗 <https://github.com/ishan1410/PolyKV>

## 本文的独立复现

### 🧪 paper-lab / 2026-05-30-polykv
本文从零独立实现的复现代码，单卡可跑，含 A/B/C 三组对照、全部原始运行日志、结果数据和图表。文中每个数字都能在 `logs/` 下回查。
🔗 <https://github.com/ele-yufo/paper-lab/tree/main/2026-05-30-polykv>

## 模型与数据

### 📦 SmolLM2-1.7B-Instruct
实验用的基座小模型。
🔗 <https://huggingface.co/HuggingFaceTB/SmolLM2-1.7B-Instruct>

### 📦 WikiText-2
实验用的文本数据集。
🔗 <https://huggingface.co/datasets/Salesforce/wikitext>

## 系列深度解析（公众号自家）

- 📄 [深度拆解 Claude Opus 4.8](./claude-opus-4-8.html)
- 📄 [「Vibe Coding 已死」？](./vibe-coding-dead.html)

---

📅 截至 **2026-06-01**。

[← 返回首页](./)
