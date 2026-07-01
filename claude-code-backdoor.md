---
layout: default
title: Claude Code 被爆「后门」 · 主要来源
---

# Claude Code 被爆「后门」 · 主要来源

本页汇集《Claude Code 被爆「后门」：那不是暗道，是一道专查中国用户的隐形海关》一文中引用的原始资料，方便读者自行核实。

## 官方一手信源

### 📄 Anthropic 官方公告《Disrupting the first reported AI-orchestrated cyber espionage campaign》
2025-11-13 披露的 GTG-1002（Anthropic 高可信度认定为中国国家背景的组织）用 Claude Code 攻击约 30 个全球组织的间谍案原文。
🔗 <https://www.anthropic.com/news/disrupting-AI-espionage>

### 📄 Anthropic 8 月威胁情报报告
单一组织用 Claude Code 一个月内至少攻陷 17 个组织的更早案例。
🔗 <https://www.anthropic.com/news/detecting-countering-misuse-aug-2025>

### 📜 Anthropic「限制不支持地区销售」政策
说明受专制地区法律约束的公司可能被强制共享数据，是不向中国大陆提供服务的政策依据。
🔗 <https://www.anthropic.com/news/updating-restrictions-of-sales-to-unsupported-regions>

### 📄 Anthropic 支持国家列表
中国大陆不在列、IP 直接封禁的政策出处。
🔗 <https://www.anthropic.com/supported-countries>

## 爆料与社区讨论

### 🗣️ Reddit r/ClaudeAI 爆料原帖
标题 "Anthropic embedded spyware in Claude Code"，指控 Claude Code 检测 Asia/Shanghai 等中国时区 + 代理 URL，并把判断塞进 system prompt。
🔗 <https://www.reddit.com/r/ClaudeAI/comments/1ujila1/anthropic_embedded_spyware_in_claude_code_and/>

### 🗣️ Reddit r/ClaudeCode 跨帖
社区判断这道检查主要针对中国境内倒卖 Claude 账号的灰产，和拿 Claude 蒸馏自研模型的动作。
🔗 <https://www.reddit.com/r/ClaudeCode/comments/1ujilqt/anthropic_embedded_spyware_in_claude_code_and/>

## 源码泄露技术分析（内文配图来源）

### 📰 Layer5：The Claude Code Source Leak
51.2 万行 / 约 1900 文件 TypeScript 源码因 npm 打包失误裸奔的完整复盘（正文图 1 来源）。
🔗 <https://layer5.io/blog/engineering/the-claude-code-source-leak-512000-lines-a-missing-npmignore-and-the-fastest-growing-repo-in-github-history>

### 📰 The Verge：Claude Code 源码泄露报道
2.1.88 版本 source map 泄露的媒体报道。
🔗 <https://www.theverge.com/ai-artificial-intelligence/904776/anthropic-claude-source-code-leak>

### 📰 InfoQ：Claude Code source leak
确认泄露来自 2.1.88 版本。
🔗 <https://www.infoq.com/news/2026/04/claude-code-source-leak/>

## 媒体深度报道

### 📰 WIRED：中国用户如何绕过 Anthropic 地理限制
Anthropic 封禁中国 IP、用户挂代理访问的生态背景。
🔗 <https://www.wired.com/story/how-people-in-china-keep-outsmarting-anthropics-geolocation-restrictions>

---

📅 截至 **2026-07-01**。

[← 返回首页](./)
