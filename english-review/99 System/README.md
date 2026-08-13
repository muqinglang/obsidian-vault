---
title: English Review 使用说明
kind: navigation
tags:
  - english/navigation
  - graph/hide
aliases:
  - 英语知识库使用说明
---

# English Review 使用说明

入口是 [[00 Master Learning Log|English Learning Home]]。这个知识库采用“场景中心”结构：先完成真实沟通任务，再从表达、错误和听音卡获得反馈。

## 文件结构

- `01 Daily Practice`：按日期保存原始学习证据，不进入知识图谱。
- `02 Scenes`：真正的学习入口。
- `03 Expressions`：可整体提取和迁移的表达。
- `04 Vocabulary`：值得主动使用的词汇。
- `05 Patterns`：重复出现或明显影响表达的错误模式。
- `06 Sound`：可复用的听力、连读和发音规律。
- `07 Review`：今天练什么以及每周输出。
- `99 System`：索引、数据质量说明和已合并旧卡。

## 链接规则

- Daily 只链接 Scene。
- Scene 链接完成任务需要的表达、词汇、错误和听音点。
- 知识卡不再链接日期、Index 或 Review Queue。
- 同一关系只手动写一侧，另一侧用反向链接查看。
- 每张知识卡只保留少量直接、有意义的关系。

## 图谱

全局学习图谱使用：`path:"english-review" -tag:#graph/hide`

日常学习优先使用 Scene 的局部图谱，深度设为 `1`。全局图谱用于每周检查主题簇、孤岛和过度连接，不作为每日复习入口。

## 数据边界

语音识别乱码、专名误识别、发音试读和残句不会自动进入错误库。详见 [[语音识别噪声处理说明]]。
