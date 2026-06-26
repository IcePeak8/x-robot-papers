# X-Robot Papers

机器人与具身智能最新论文收藏库。

这个仓库用于公开归档每日发现的论文，重点覆盖四足机器人导航、locomotion、Sim2Real、ROS/Nav2、SLAM、控制、VLA、移动操作、机器人学习与工程部署。

内容定位：

- 论文标题保留原文。
- 摘要、收藏理由和工程备注默认使用中文。
- 每篇论文尽量同时保存 arXiv、alphaXiv 和 PDF 链接。
- 这里只做论文收藏与阅读管理，不写成推文草稿。

## Structure

- `papers/`: 按月份整理的人类可读 Markdown 论文列表。
- `data/`: 机器可读 JSONL 数据，便于后续同步 Notion、脚本检索或生成报告。
- `docs/schema.md`: 字段说明和写入约定。

## Related Notion Database

Notion 库：X-Robot 最新论文收藏

- Database: https://app.notion.com/p/7c89bf9b7178407a8ebe4ecc5144d899
- Data source: `collection://337098bf-0d98-4207-ad94-7fe57f9c91e3`

## Link Rule

arXiv 论文自动补 alphaXiv 链接：

```text
https://arxiv.org/abs/<paper_id> -> https://alphaxiv.org/abs/<paper_id>
```
