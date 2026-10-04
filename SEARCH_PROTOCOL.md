# 文献检索与整理说明 / Search and Curation Protocol

## 记录边界

作者实际主要使用 **Google Scholar（谷歌学术）** 开展文献检索。已有正式发表版本时优先引用期刊或会议版本；尚未确认完整正式出版信息的研究，主要使用 arXiv 预印本。

**历史检索的逐次词组、检索命中数、去重数和排除数没有保留。** 因此，不能据此重现原始检索结果，也不能补写未经记录的流程数字。下列查询词组是此次根据综述主题补充整理的查询建议，并非对当时逐组执行记录的追述。

2026-10-05 的公开快照含 **289 条已纳入文献**，是当前综述引用清单的可复核索引。它不等于检索命中数量。清单引用版本的年份跨度为 **1971–2026**，重点讨论 **2023–2026** 的进展；早期文献补充基础概念与技术路线。这里的年份范围不代表一个有日志支持的历史检索日期区间，快照整理日期也不代表原始检索截止日。

## 本次补充的查询词组

以下各词组可分别在 Google Scholar 中检索；不将整列视为某种已执行的数据库布尔语法。结合任务词、方法词和基准词扩展检索，并通过已知工作的参考文献和后续引用补充相关研究。

| 主题 | 本次补充的基础查询词组 | 可结合的扩展查询词组 |
| --- | --- | --- |
| 综合与边界 | `spatial intelligence` | `spatial cognition embodied intelligence` |
| 空间感知 | `spatial perception`；`depth estimation`；`multi-view stereo`；`camera pose estimation` | `3D perception`；`active perception viewpoint selection` |
| 空间表征 | `3D representation`；`neural radiance field`；`3D Gaussian splatting`；`3D scene graph` | `3D multimodal alignment` |
| 空间理解 | `3D scene understanding`；`open-vocabulary 3D understanding`；`3D visual grounding` | `3D object detection`；`open vocabulary 3D segmentation`；`3D scene graph generation` |
| 空间推理 | `spatial reasoning`；`multimodal spatial reasoning`；`3D spatial reasoning` | `spatial reasoning vision language models`；`metric relational perspective reasoning`；`video spatial temporal reasoning`；`3D large language models` |
| 空间生成 | `3D generation`；`4D generation`；`world model` | `text to 3D generation`；`3D scene generation`；`geometry consistent video generation`；`interactive world models` |
| 评测 | `benchmark`；`evaluation` | 与 `spatial intelligence`、`spatial understanding`、`spatial reasoning`、`3D generation` 或 `world model` 等主题词组合 |

这些词组用于说明覆盖思路，并为后续维护提供可执行的起点。具体查询时还需记录最终词组、时间过滤条件、排序方式和实际查看的结果范围。Google Scholar 的索引与排序会变化，单靠同一词组不能保证不同时间检索结果完全一致。

## 后续维护时采用的流程

1. **记录检索。** 按上述主题分别查询，记录执行日期、平台、实际词组、过滤条件与查看范围；同时记录通过参考文献、被引关系或已知项目补充的来源。命中数只在当次界面可观察并已记录时填写，不能以当前清单数替代。
2. **建立候选清单。** 保存题名、作者、年份、摘要、公开链接及候选主题。先检查题名与摘要，必要时阅读全文，判断是否涉及物体或场景尺度的三维几何、空间关系、空间状态或相关评测。
3. **按工作去重。** 优先用 DOI、arXiv ID 和正式发表关联识别同一工作，再结合标准化题名与作者核对。预印本和正式发表版合并为同一工作，保留版本关系；不能仅凭相似题名合并不同作品。
4. **筛选与记录理由。** 综合主题相关性、技术路线代表性、对方法或评测发展的贡献选择文献，兼顾基础方法、关键进展与公开基准。纯地理空间分析、与三维空间问题无直接关联的研究或重复版本，可记录原因后排除。相近的具身和物理研究需根据空间能力的实际关联判断，不能仅凭关键词一律排除。
5. **核查版本与事实。** 优先检查出版社、会议、期刊、OpenReview 或 arXiv 原始记录；已有正式版本时引用正式版本。逐项核对题名、作者、年份、会议或期刊、卷期页码和标识符，不把预印本上传年份等同于最终发表年份。
6. **纳入并分类。** 更新文献表与主题索引；记录纳入日期、分类理由及来源链接。分类对应本综述的能力链与评测任务，同一作品可有多个标签。
7. **发布可核对的更新。** 在提交记录中说明新增、合并、排除或元数据修正，保存当次实际查询与筛选记录；缺失项标为未记录，不进行追溯性猜填。

这一流程是对未来整理和维护的明确规定，不能证明历史检索已经以相同方式逐项记录。当前可供复核的是公开的参考文献清单、版本链接和分类主题，而不是不存在的原始检索日志。

## arXiv 与正式发表版本的持续更新

定期检查已收录预印本的论文页面、journal-ref、DOI 以及会议或期刊页面。有正式发表版本时更新引用版本与出版信息；保留必要的 arXiv 关联，说明变更，不将两个版本重复计数。对新研究同样先核对原始来源，再决定是否纳入。

## 数据来源与限制

- 文献编号、题名和完整引文来自综述当前文末实际显示清单，删除修订不纳入，插入修订纳入。
- DOI、arXiv 与原文 URL 从当前引文及题名匹配的文献元数据中提取。与当前题名不一致的旧元数据不用于替换当前引用事实。
- 主题图谱按当前分类结构整理。原图中的引用数字可能随文稿版本变化，公开主题页省略这些数字，通过作品名称查找当前文献清单。
- 公开文件不包含文稿、审稿往来、私人文献库用户标识或附件内容。清单导入不意味着全部条目已经重新完成外部独立核验；后续更正以可追溯的原始来源为依据。
