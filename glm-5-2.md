---
layout: default
title: 深度拆解 GLM-5.2 · 主要来源
---

# 深度拆解 GLM-5.2 · 主要来源

本页汇集《深度拆解 GLM-5.2：最强模型被摁下线的那个周末，智谱把 SOTA 开源了》一文中引用的所有原始资料。

## 智谱官方（一手）

### 📄 智谱 GLM Coding Plan 官方页
GLM-5.2 官方一句话定位「可靠交付生产级代码」、三档定价 ￥49 / 149 / 469 的实时核实来源。
🔗 https://open.bigmodel.cn/glm-coding

### 📄 智谱 AI 开放平台首页
截至发稿仍主推上一代 GLM-5.1，GLM-5.2 仅在 Coding Plan 订阅里灰度开放。
🔗 https://bigmodel.cn/

### 📄 GLM-5 技术文档（智谱开放文档）
744B 总参数 / 40B 激活 / 256 专家 / 每次激活 8 / 28.5 万亿 tokens 预训练。
🔗 https://docs.bigmodel.cn/cn/guide/models/text/glm-5

### 📄 GLM-5.1 技术文档（智谱开放文档）
代码能力增强、长程任务（8 小时持续工作）。
🔗 https://docs.bigmodel.cn/cn/guide/models/text/glm-5.1

## GLM-5.2 开放公告（2026-06-13，转载智谱官方公众号）

### 📰 IT 之家
GLM-5.2 面向 GLM Coding Plan 全量用户开放，模型下周正式开源。
🔗 https://www.ithome.com/0/963/855.htm

### 📰 证券时报（人民财讯）
6 月 13 日 17:21 面向 Lite / Pro / Max / 团队版开放，API 下周上线，下周开源。
🔗 https://www.stcn.com/article/detail/3960105.html

### 📰 每日经济新闻
🔗 https://www.nbd.com.cn/articles/2026-06-13/4425590.html

### 📰 DoNews
GLM-5.2 今晚全量开放，下周开源并上线 API。
🔗 https://www.donews.com/news/detail/8/6594624.html

## GLM-5 系列架构（公开技术资料）

### 📊 智源社区 BAAI
智谱公开 GLM-5 的所有技术细节。
🔗 https://hub.baai.ac.cn/view/52685

### 📊 GLM-5.1 架构全解析（知乎专栏）
744B 总参 / 40B 激活，MoE + 稀疏注意力的工程路线。
🔗 https://zhuanlan.zhihu.com/p/2026384496501473622

### 🚀 GitHub zai-org/GLM-5
官方仓库，架构参数（从 355B/32B 扩到 744B/40B）。
🔗 https://github.com/zai-org/GLM-5

### 📊 HuggingFace zai-org/GLM-5.1
权重与 config（256 routed experts、每 token 8 experts、max_position 约 202,752）。
🔗 https://huggingface.co/zai-org/GLM-5.1

## 背景：Fable 5 / Mythos 5 被关停（2026-06-12）

### 📜 Anthropic 官方 news
收到美国出口管制指令，对所有客户禁用 Fable 5 与 Mythos 5。
🔗 https://www.anthropic.com/news

### 📰 钛媒体
Anthropic 撤回针对 Claude 的争议政策，Fable 5 安全措施改为可见。
🔗 https://www.tmtpost.com/agent/ai-article?id=18083

## 系列深度解析（公众号自家）

- 🍱 [深度拆解 Mixture of Agents：最强模型被一封信关停的那几天，一桌便宜货合议差点掀了王座](./mixture-of-agents.html)
- 📄 [速报 · Fable 5 被美国政府勒令下架](./fable-5-pulled.html)
- 📄 [深度拆解 Claude Fable 5：给神话戴上笼口，改名寓言，卖你两倍价](./claude-fable-5.html)

---

📅 截至 **2026-06-14**。

[← 返回首页](./)
