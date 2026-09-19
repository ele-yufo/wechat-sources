---
layout: default
title: 智谱 ZCode 偷传 Git 整仓：我第一时间卸载了 · 主要来源
---

# 智谱 ZCode 偷传 Git 整仓 · 主要来源

本页汇集《智谱 ZCode 偷传 Git 整仓：我第一时间卸载了》一文中引用的全部原始资料（2026-09-18/19 抓取口径）。

## 事件源头

### 🔍 最初发现：ZCode 疑似静默上传全量 Git 历史（linux.do 转载帖）
外部博客《扒一扒 ZCode 静默上传全量 Git 历史的骚操作》的社区转载与求证帖，附完整网页存档。
🔗 <https://linux.do/t/topic/2917923>

### 🔧 拆包实锤：Haleclipse 对 3.12.3 版本的逆向分析（linux.do）
repo-snapshots 改名 v2/checkpoint、.git 排除规则失效位次、无门控、加密与登录依赖等技术细节出处。
🔗 <https://linux.do/t/topic/2919210>

### 📢 智谱官方声明（飞书用户群，linux.do 转录）
「代码库索引」归因、「云端生成后立即销毁」口径、默认开启承认、开源承诺与周额度补偿。
🔗 <https://linux.do/t/topic/2919455>

## 前科与背景

### 📰 Grok Build 静默上传完整代码仓库被曝（开源中国，2026-07）
独立研究员 cereblab 抓包：违背「本地优先」宣传、全量上传 Git 仓库至 GCS 桶、禁用读取仍上传。
🔗 <https://www.oschina.net/news/285917>

### 📰 马斯克承认并删除数据、Grok Build 开源（腾讯新闻，2026-07）
48 小时删数据、72 小时后开源的时间线出处。
🔗 <https://news.qq.com/rain/a/20260716>

## 技术背景

### 📖 Pro Git 书 · reflog 与底层对象（中文版）
「删掉文件不等于删掉历史」的技术依据：已删分支的提交对象保留、reflog 默认 90 天。
🔗 <https://git-scm.com/book/zh/v2/Git-内部原理-维护与数据恢复>
