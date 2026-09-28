---
title: 本机 60+ Skills 速查与选型
layer: 02-资产地图
tags: [资产地图]
date: 2026-09-27
reviewed: 2026-09-27
source: ~/.workbuddy/skills/ 实测扫描
confidence: 高
summary: 按四大簇归纳本机用户级技能，做事前先看有没有现成轮子。
status: budding
why: 做事前先看有没有现成轮子，别重复造
---

路径：`/Users/recover/.workbuddy/skills/`

## 一、农险业务簇（主力）

| Skill | 干什么 |
|---|---|
| `agri-selection-bid` | 遴选应标四步法：深度分析→板块响应→生成→审核 |
| `agri-bid-audit` | 标书审核五能力，纯本地单文件 HTML v2.1 |
| `agri-bid-score-audit` | 评分细则逐条对账核分，出差异报告 |
| `agri-index-ulr-backtest` | 天气指数 ULR 历史气象回测与逐县校准 |
| `weather-index-insurance-designer` | 纯天气指数保险设计流水线 |
| `agri-z16-agreement-image-verify` | 图片型 PDF 协议"当期有效性"核验 |
| `bid-image-pdf-ocr-audit` | 图像型标书全量 OCR 核验 |
| `nongxian-doc-ingest` / `nongxian-headcount` / `nongxian-xibao-poster` | 农险文档入库 / 人头测算 / 喜报海报 |
| `gov-dept-power-fetch` | 政府部门权责联网抓取 |

## 二、PPT 簇

`agri-ppt-maker`（农险专属·13-PPT库）、`ppt-master`、`ppt-integrate-audit`、
`ppt-template-distill`（蒸馏模板→回填）、`ppt-template-crawler`（批量下载模板）、
`ppt-photo-group-layout`（照片组排版三件套）、`pptx-render-verify`（**改完 PPTX 必跑目检**）。

## 三、文档工程簇

`docx-cjk-font-fix`（中英文字体割裂修复）、`docx-comment-inject`（注入 Word 批注不破结构）、
`gongwenformat-pro`（公文格式）、`html-render-verify`（无头浏览器渲染校验）、
`xmind-to-pdf`、`tuanke-weekly-report-update`（团客例会材料更新）。

## 四、外部数据簇

`qcc` 系列十余个（企业工商/股权/涉诉/尽调）、`wecom-unified`（企业微信）、
`tencentmap-map-assistant`（地图）、`gh-pages-static-site`（静态站发布）。

## 选型纪律

**做事前先查有没有现成 Skill**，尤其是 PPT —— `ppt-template-crawler` 已下 705 套真实模板，
不要重复造轮子。

## 相关条目

- [[农险专家包 14 库速查地图（含绝对路径）]]

<!-- MAP-CHECK:START -->
> **机器校验**：2026-09-27 23:51 · 实测 61 个 Skill · 本条收录 27 项
> 失效引用 **0** · 名称变更 **0** · 未收录 **34**
> （未收录多为内置/外部项，属正常；**失效引用必须为 0**，出现即为地图已失真）
<!-- MAP-CHECK:END -->
