# paper_reading — 论文阅读笔记

按周积累论文阅读记录，每份笔记对应一个文件夹。每个文件夹保存对应论文原文、已有粗读笔记和精读与学习笔记，阅读进度按实际记录补充。

## 阅读记录

- [Transformer](Transformer/README.md) — 已有学习笔记，复用课堂笔记。
- [Vision Transformer（ViT）](ViT/README.md) — 已有学习笔记，复用课堂笔记。
- [CLIP](CLIP/README.md) — 已有论文阅读与学习笔记。
- [ALBEF、BLIP、BLIP-2](ALBEF_BLIP_BLIP2/README.md) — 三篇论文共用一份合并笔记。
- [CoViP](CoViP/README.md) — 已粗读，精读笔记待补充。
- [LSA](LSA/README.md) — 已粗读，精读笔记待补充。

当前共六份笔记、八篇论文原文。每个文件夹的 README 标明文件角色和阅读状态。

## 组织约定

一份笔记对应一个文件夹，合并笔记对应的多篇论文原文放在同一文件夹。保留笔记原文件名，粗读和精读状态在目录说明中标注。暂缺的精读笔记后续补充。

论文阅读记录归入本仓库，课堂笔记与课程实践保存在 [class_for_AI](https://github.com/commoncreate/class_for_AI)。Transformer 与 ViT 现有笔记同时服务于课程学习与论文阅读，经本人确认复用到本仓库。

## 文件来源与保存

五篇原文从本地 Reading 文件夹复制，Transformer、ViT、ALBEF 原文从 arXiv 补齐。Reading 中名为 ViT.pdf 的文件经首页核对实际为 CLIP 原文，已按内容归档为 CLIP/CLIP.pdf，真正的 ViT 原文另行补齐。

笔记与本地论文副本逐份校验 SHA-256。原文件保留，具体来源、字节数、页数和哈希记录在 [manifest.json](manifest.json)。论文版权归原作者或出版方，阅读笔记来自本人学习记录。

PDF 使用 Git LFS 保存，完整克隆后可运行 `git lfs pull` 获取文件。
