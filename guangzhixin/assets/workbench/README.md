# Workbench visual assets

Small standalone icons and portraits extracted at their native display size from the user's supplied 1920×1080 workbench reference (2026-11-04). Source: design-reference/workbench-target-v8.png. Application content, layout, labels, controls and interactions remain live HTML/React; these images contain only the supplied icon/portrait artwork. Existing Figma banner artwork is reused separately.

## v10
顶部提醒、常用功能和系统导航的 PNG 图标已移除，改用 src/assets/workbench-vectors 中从 Figma 工作台1 原图层导出的 SVG。这里仅保留简报/栏目装饰及人物头像。

## 2026-11-10 用户替换资源

heading-brief.png 与 heading-tasks.png 分别替换为桌面提供的“位图.png”（红色喇叭）、“位图 2.png”（蓝色喇叭），保留原图内容与透明背景。heading-bar.png 使用“Gradient备份.png”橙红标记，仅裁去近乎透明的外部导出留白，保持原有标题显示尺寸及发光比例；公共标题与模式二简报复用同一资源。

2026-11-11：composer-sleep.png来自用户234bd3c8-6bb0-4a3e-85ab-20bae321715e.png，composer-awake.png来自992e546a-6075-4d12-a662-a3c5bd92ef27.png。原始PNG直接复制，仅在输入框小新姿态中按72px contain显示。应用渐变来源：row备份 2.svg（#FFB23C→#FF9B0C）、编组 35备份 13.svg（#FF7338→#FF4E1D）、编组 4备份 2.svg（#64C3FD→#288BFF），颜色由语义token及SVG渐变实现，原图形不替换。
