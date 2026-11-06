# 分类与标签规范

目录负责稳定的大类；标签负责跨目录检索。每条 Markdown 资料开头记录以下字段；不适用字段填空，不编造日期或来源。

```yaml
---
id: "唯一编号"
title: "资料标题"
category: "分类"
tags: []
tools: []
source_url: ""
author: ""
published_at: ""
updated_at: ""
status: "待整理"
visibility: "private或public，与仓库一致"
related: []
---
```

标签用清楚的中文，如：数据分析、横纵分析、经营分析、自动化、知识库。
工具名称统一：影刀、观远、FineBI、FineReport；具体产品不明时标记待确认。
资料状态：待整理、整理中、待验证、已验证、已归档。
标签可以后续增加；同义词沿用已有标准名称。

SQL、代码和图片的元数据放到同名 `.meta.json` 文件，避免破坏原文件格式。
例如 `门店销量.sql` 配 `门店销量.sql.meta.json`，字段与上面一致。
图片另补 alt（图像说明），代码补 language（语言），SQL 补 dialect（方言）。

事实、推断、待确认信息分别说明。AI 答复需给出仓库内文件路径和依据；未收录的资料不得声称已读。
