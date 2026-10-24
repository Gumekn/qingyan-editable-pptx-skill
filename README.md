# Qingyan-ppt-design｜轻研可编辑学术 PPTX 生成 Skill

**Editable Academic PowerPoint Generation Skill · Template Learning**

**学会你的模板，交付可编辑的学术 PPT。**

从论文材料到答辩汇报，轻量驱动、快速生成，让学术表达有据可依，让每一页都能继续修改。

项目仓库：[Gumekn/qingyan-editable-pptx-skill](https://github.com/Gumekn/qingyan-editable-pptx-skill)。核心特征：原生可编辑、学习真实模板、对话快速启动、面向学术表达、轻量 Skill 工作流。

## 1. 安装与快速开始

在 Codex 对话中发送以下安装指令：

```text
$skill-installer

请从 https://github.com/Gumekn/qingyan-editable-pptx-skill 安装 Qingyan-ppt-design。
Skill 位于仓库根目录，请将安装目录命名为 Qingyan-ppt-design。
```

安装器会将仓库根目录中的 `SKILL.md` 和配套资源放入 Codex 用户级技能目录 `~/.codex/skills/Qingyan-ppt-design/`（自定义 `CODEX_HOME` 时使用对应目录），供各项目使用。Skill 名称与安装目录统一为 `Qingyan-ppt-design`，调用方式为 `$Qingyan-ppt-design`。

安装后，在任意项目对话中附上研究材料，直接调用；若尚未识别到技能，重启 Codex 后再试：

```text
$Qingyan-ppt-design

根据我提供的论文、研究材料和配图，制作一份约 8 页的中文学术汇报。
优先使用我提供的 PPTX 模板；没有提供时，请从内置模板中推荐。
最终交付整页 PNG 视觉稿和可编辑 PPTX。
```

## 2. 项目介绍与效果展示

Qingyan-ppt-design（轻研 Slide，简称「轻研」）是一款面向科研与学术汇报的 Codex Skill，通过对话将研究材料转化为学术 PPT。学习真实模板的图文组织、字体、配色与版式，让新内容延续参考风格。支持分阶段确认，交付整页视觉稿与可编辑 PPTX。

> 效果展示图待补充公开演示案例。

## 3. 核心设计：从真实模板中学习

以用户指定模板为主要依据，比较多份 PPT 中的同类页面，学习图文组织、文字层级、配色、版式与留白，形成适合本次材料的设计方案。将具体参考页、原始素材和完整文稿共同传入生成请求，让参考中的表达方式落实到每一页，并在整套汇报中延续已确认的风格。

## 4. 制作流程：输入、阶段与交付

提供论文或研究材料、已有配图，以及汇报用途、页数或时长；有指定模板时一并提供。四个阶段分别展示成果，经用户确认后继续：

| 阶段 | 工作与展示内容 |
| --- | --- |
| 需求与方案 | 理解材料，安排逐页内容，选择模板与参考方向 |
| 文稿与素材 | 展示完整上屏文稿、拟用配图和模板净底板 |
| 整页视觉稿 | 先确认代表页方向，再展示完整页面 PNG |
| 可编辑交付 | 重建 PPTX，展示实际渲染与可编辑性，确认交付版本 |

产物保存在指定任务目录：`配图素材/` 保存选定原图，`视觉稿/` 保存整页 PNG，`可编辑版本/` 保存 PPTX 及渲染预览，`content-plan.md` 记录方案、来源与确认结果。文本、表格、流程等按可编辑对象重建；直接使用的论文原图与复杂插图保留为独立图片。

## 5. 配套模板与运行环境

内置四套 PPTX 模板，配有整套预览、逐页 PNG 和文字索引。用户指定模板决定主要风格与固定格式，其他参考提供补充。

| 模板 | 原始 PPTX | 整套预览 |
| --- | --- | --- |
| 模板1 | [下载](assets/visual-references/模板1/模板1.pptx) | [查看](assets/visual-references/模板1/preview.png) |
| 模板2 | [下载](assets/visual-references/模板2/模板2.pptx) | [查看](assets/visual-references/模板2/preview.png) |
| 模板3 | [下载](assets/visual-references/模板3/模板3.pptx) | [查看](assets/visual-references/模板3/preview.png) |
| 模板4 | [下载](assets/visual-references/模板4/模板4.pptx) | [查看](assets/visual-references/模板4/preview.png) |

完整流程需要具备本地文件读写、ImageGen 生图和 PPTX 编辑能力的 Codex 环境；实际 PPTX 渲染优先使用 Microsoft PowerPoint。这些工具由运行环境提供，本项目提供 [Skill 工作流程](SKILL.md) 与配套模板资源。
