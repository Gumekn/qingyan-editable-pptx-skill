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

以下选取 **SafeTraffic Copilot 8 页学术答辩汇报**中的第 3、4、6 页，展示模板参考、最终版面与真实编辑界面。参考页来自内置模板1；成品图均从实际交付的可编辑 PPTX 经 **Microsoft PowerPoint 重新渲染**，分辨率为 1920 × 1080。点击图片可查看大图。

### 示例一：技术路线｜第 3 页

沿用模板的蓝白配色与标题层级，用论文框架图和分组说明呈现技术路线。右侧说明、标题和底部验证说明均为原生文本，可单独修改。

| 模板参考 · 模板1第 5 页 | 最终效果 · PPTX 实际渲染 |
| --- | --- |
| ![技术路线模板参考](assets/showcase/safetraffic/reference-05.png) | ![技术路线成品的 PowerPoint 实际渲染](assets/showcase/safetraffic/slide-03.png) |

**在 PowerPoint 中编辑正文：**下图保留完整幻灯片、左侧缩略图与功能区，可看到右侧正文文本框的选中边界及字体设置。

![技术路线页的真实 PowerPoint 编辑窗口，原生正文文本框已选中](assets/showcase/safetraffic/editor-03.jpg)

### 示例二：研究方法｜第 4 页

参考模板中“方法图解＋分区说明”的组织方式，将多模态文本化、模型适配与预测目标安排在同一页。预测目标使用 **PowerPoint 原生表格**，文字、单元格及行列尺寸均可调整。

| 模板参考 · 模板1第 6 页 | 最终效果 · PPTX 实际渲染 |
| --- | --- |
| ![研究方法模板参考](assets/showcase/safetraffic/reference-06.png) | ![研究方法成品的 PowerPoint 实际渲染](assets/showcase/safetraffic/slide-04.png) |

**在 PowerPoint 中编辑表格：**预测目标表格已选中，顶部“表布局”功能区显示插入行列、合并单元格与尺寸设置等原生工具。

![研究方法页的真实 PowerPoint 编辑窗口，预测目标表格及表布局工具](assets/showcase/safetraffic/editor-04.jpg)

### 示例三：研究结果｜第 6 页

参考模板的“数据对比＋图表证据＋结果解释”，将模型性能和跨州泛化结果重建为两张原生表格，并保留论文置信度曲线。可以直接修改数值、调整列宽、设置重点数据的字体与颜色。

| 模板参考 · 模板1第 12 页 | 最终效果 · PPTX 实际渲染 |
| --- | --- |
| ![研究结果模板参考](assets/showcase/safetraffic/reference-12.png) | ![研究结果成品的 PowerPoint 实际渲染](assets/showcase/safetraffic/slide-06.png) |

**在 PowerPoint 中编辑数据：**上方性能对比表格已选中，完整结果页与“表布局”工具栏同时可见。

![研究结果页的真实 PowerPoint 编辑窗口，原生性能对比表格已选中](assets/showcase/safetraffic/editor-06.jpg)

这三页合计包含 **39 个有文字的原生形状、3 张原生表格**（按页内对象统计，不含母版）。论文框架图、方法图与曲线各作为一张独立图片保留，可移动、缩放和替换；图片内部文字、曲线和连线仍属于原图。以上编辑界面为 PowerPoint 实拍，截图时仅选中对象，未修改汇报内容。

研究材料：Zhao et al., *Nature Communications* (2025), 16:8846，[DOI: 10.1038/s41467-025-64574-w](https://doi.org/10.1038/s41467-025-64574-w)。示例用于展示学术汇报的排版与可编辑交付，研究结论及原图归原论文作者。

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
