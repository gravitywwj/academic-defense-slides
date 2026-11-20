# 中文科研答辩演示稿

`academic-defense-slides` 是一个 Codex 技能，用于制作中文论文答辩和科研项目申请 PPT。它将两份同济大学答辩稿中的章节组织、配色、字号和证据页布局整理为可复用规则。

| 模式 | 典型页面 | 参考 |
| --- | --- | --- |
| 论文答辩 | 章节导航、实验方法、对照结果、结论与展望 | [版式说明](references/thesis-defense.md) · [预览](references/thesis-layouts.png) |
| 项目申请 | 编号页眉、技术路线、任务分工、进度与验收 | [版式说明](references/project-proposal.md) · [预览](references/proposal-layouts.png) |

## 安装和调用

将本仓库放入 `$CODEX_HOME/skills/academic-defense-slides`。未设置 `CODEX_HOME` 时，个人技能目录默认为 `~/.codex/skills/`。技能入口为 [SKILL.md](SKILL.md)。

调用示例

> 用 $academic-defense-slides 的论文答辩模式，把我的研究提纲和实验图表编排成 15 页 PPT。

预览页使用演示数据。版式依据 PDF 导出版提炼，字体和排版的复用范围以[技能规则](SKILL.md)为准。
