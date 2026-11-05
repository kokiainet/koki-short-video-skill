[English](#english) · [简体中文](#简体中文)

## English

# Optional visuals & closing configuration

These are starting points, not a fixed template for every creator. The user's current project and request take priority.

## Titles & CTA

- Default to Smiley Sans for vertical covers and opening titles. Captions and closing CTA may use different fonts.
- Use a static white rounded opening title with black text. On a 1080×1920 canvas, start near `left=32`, `top≈200`, `width=1000`, then adjust for faces and wrapped height.
- Support real newlines and a user's literal `\n`. If the tool supports only single-line fields, offer editable line 1/2/3 fields; empty fields consume no line.
- Compute the background height from line count, line height, and vertical padding. Reduce font size only after reaching the safe on-screen height. Inspect the entire background and all text, not just the baseline.
- A CTA may use bold Inter, up to roughly 68 px, black text on white without heavy outlines or shadows. Read the current user's configuration; do not hardcode the author's name or comment keyword.

## Two staggered closing images

Use only when the current user supplies two closing images and wants this arrangement. Place the main photo centered low in the frame behind a second image at lower right. Substantial overlap is fine if key titles, people, and identifying details remain visible.

Preserve both aspect ratios. Start with the main photo around 58% of canvas width and foreground image around 50%, then adjust to content. Avoid source cropping by default. Edges may extend off-screen naturally; do not shrink everything into illegibility to fit.

Inspect frames at closing start, middle, and end for mouth, captions, CTA, image layering, and timing. Preserve an existing manual arrangement.

---

## 简体中文

# 可选视觉与结尾配置

这些是默认样式起点，用户当前项目和本轮要求优先，不是所有创作者都必须使用的固定模板。

## 标题与 CTA

- 竖屏封面和开头标题默认用 Smiley Sans；字幕和结尾 CTA 可用各自的字体。
- 开头标题为静态白色圆角框、黑字，1080×1920 画布可从 `left=32`、`top≈200`、`width=1000` 开始，结合脸部位置和换行高度调整。
- 支持真实换行和用户输入的字面 `\n`；工具只有单行字段时，可以提供第 1/2/3 行可编辑字段，空字段不占行。
- 白底高度由文字行数、行高和上下内边距计算；达到镜头安全高度上限后才缩字号。检查整块白底和全部文字，不只检查基线。
- CTA 可以使用 Inter 粗体，最大字号约 68 px、白底黑字，不加密集描边或阴影；内容读取当前用户配置，不内置原作者名字与评论口令。

## 两图错位叠放

只有当前用户提供了两张收尾图并需要这种布局时才使用：主照片在画面下部居中、位于后层，第二张图片叠在右下、位于前层。照片与第二张图可明显重叠，保留有效标题、人物和标识。

两图保持原始比例；先给主照片约画面宽度 58%、前层图约 50% 的可见面积，再按实际内容调整。默认不做源裁切。允许画面边缘自然超出，不为收进整图把内容缩得难读。

在收尾开始、中间和结束各看一帧；同时检查嘴部、字幕、CTA、两图层次以及进出点。用户已有手动布局时保留。
