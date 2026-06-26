# Schema

这个仓库和 Notion 论文库使用同一套字段。论文标题保留原文，除标题外的说明字段默认使用中文。

## Fields

| Field | Meaning |
| --- | --- |
| `paper` | 论文标题，保留原文 |
| `published_date` | 论文发布或 arXiv 提交日期 |
| `added_date` | 加入收藏库日期 |
| `source` | 来源，例如 `arXiv`、`Conference`、`Journal`、`Project Page` |
| `read_status` | 阅读状态：`To Read`、`Skimmed`、`Read`、`Archived` |
| `priority` | 阅读优先级：`High`、`Medium`、`Low` |
| `primary_area` | 主方向，例如 `Quadruped`、`Navigation`、`Locomotion`、`VLA` |
| `tags` | 多标签，便于检索 |
| `arxiv_id` | arXiv ID |
| `arxiv_url` | arXiv 页面链接 |
| `alphaxiv_url` | alphaXiv 页面链接 |
| `pdf_url` | PDF 链接 |
| `project_url` | 项目主页，可为空 |
| `code_url` | 代码仓库，可为空 |
| `authors` | 作者，可后续补全 |
| `one_line_summary` | 中文一句话总结 |
| `why_save` | 中文收藏理由 |
| `engineering_notes` | 中文工程阅读备注 |

## Language Rule

- `paper` 保留论文原始标题。
- `one_line_summary`、`why_save`、`engineering_notes` 默认中文。
- `VLA`、`MPC`、`Sim2Real`、`ROS2`、`Nav2` 等术语保留英文。