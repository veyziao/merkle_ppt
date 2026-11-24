# Merkle PPT Skill

**版本 0.2.0** | 面向可编辑 PowerPoint 的 Merkle 风格制作流程。

每次制作以指定 PowerPoint 模板和母版为基础，按页面用途检索 Slide Library，根据内容选择并调整版式，沿用参考对象的实际格式和视觉层级。制作前由用户选择英文字体（Proxima Nova、Aptos、Arial）和中文字体（微软雅黑、苹方）。

## 工作流程

1. 确定受众、故事线和页面重点，确认字体及其可用性。
2. 使用模板母版和版式建立页面，保留 Logo 与自动页码。
3. 按页面类型检索 Slide Library；正文使用多种适合内容的布局。
4. 章节 Divider 优先选取 DIVIDER IMAGES 中不同的带图页面。
5. 读取参考页的文字、位置、间距、图片裁剪、形状、阴影及三维属性，包括继承属性。
6. 适量使用 ICON Library，依据内容灵活匹配；图示参考 Diagram Library。
7. 按内容需要使用 Chrome 截图或生成图片，保持比例，不留图片占位；可编辑元素使用 PowerPoint 原生对象。
8. 渲染并检查所有页面，验证文件结构，尽可能用 PowerPoint 检查是否需要修复。

## 必需文件

- `merkle_ppt/assets/Merkle PowerPoint Template.potx`
- `merkle_ppt/assets/Slide Library.pptx`
- `merkle_ppt/assets/DIVIDER IMAGES.pptx`
- `merkle_ppt/assets/Merkle_icon.pptx`
- `merkle_ppt/assets/Diagram library - Diagram Elements.pptx`

保留整个 `merkle_ppt` 目录并复制到适用的 Skill 目录。素材或所选字体不可用时，应先解决缺失，不应假装已完成检查或用虚构内容代替真实截图。

使用示例：`请使用 merkle_ppt skill，基于我提供的材料制作可编辑的 PowerPoint。`
