# Paint, Flooring, and Wallpaper Preview · 墙漆与地板选材预览

[中文](../../README.md) · [English](../../README.en.md) · [Português](../../README.pt.md) · [Español](../../README.es.md) · [Français](../../README.fr.md) · [Deutsch](../../README.de.md) · [عربي](../../README.ar.md) · [русский](../../README.ru.md) · [日本語](../../README.ja.md) · [हिंदी](../../README.hi.md)


Replace specified room surfaces using either a supplied sample or an accurate color and material description.

预览墙漆、地板和墙纸效果。用于装修选材。

[复制公开提示词 / Copy prompt](#public-prompt) · [在 dearsketch 制作 / Try online](https://dearsketch.com/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i171_cta) · [返回专题 / Collection](../guides/spaces.md)

## 参考素材与结果方向

<table>
<thead><tr><th width="50%">参考素材</th><th width="50%">结果示例</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>室内照片</strong><br><img src="../../assets/cases/i171-before-1.webp" alt="墙漆与地板选材预览 — 参考素材 1" width="320"></p>
<p><strong>目标材料样板</strong><br><img src="../../assets/cases/i171-before-2.webp" alt="墙漆与地板选材预览 — 参考素材 2" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i171_image"><img src="../../assets/cases/i171-after.webp" alt="墙漆与地板选材预览 — 结果示例" width="320"></a></td></tr></tbody>
</table>

参考素材与结果用于说明视觉方向，公开模板不是配图的原始生成指令，不保证复现相同结果。

## 需要准备什么 / Inputs

| 素材 / Material | 类型 / Type | 数量 / Quantity | 条件 / Requirement |
| --- | --- | --- | --- |
| 室内照片 | 图片 / Image | 1张 | 必需 / Required |
| 目标材料样板 | 图片 / Image | 0–1张；也可用准确文字或色彩数据 | 按条件 / Conditional：需要复现具体纹理或产品样时 |
| 替换表面与目标颜色/材质 | 文字 / Text | 1份 | 必需 / Required |

每次只生成一张图片。

## 保留与改变 / Editing brief

- **Preserve / 保留：** Keep room structure, lighting logic, object placement, and untargeted surfaces.
- **Change / 改变：** Change only named walls, floor, or wallpaper areas.

## Public prompt

**新编公开模板 · Newly authored · Not generation-tested.** 替换方括号参数，在支持图片编辑的工具中附上所需素材；可选和条件输入按上表准备。此模板没有用于生成本页示例。

```text
Create one material preview from [INTERIOR PHOTO].
Choose one target branch: use [TARGET MATERIAL OR COLOR SAMPLE] when matching a specific texture or product, or use [ACCURATE COLOR AND MATERIAL DESCRIPTION] when no sample exists.
Apply the chosen [PAINT / FLOORING / WALLPAPER] only to [EXACT SURFACES TO REPLACE].
Preserve doors, windows, trim, furniture, room geometry, camera angle, and all untargeted surfaces.
When a sample is supplied, retain its dominant color, pattern scale, grain direction, and finish as closely as possible.
Respect corners, occlusion, seams, perspective, reflections, and existing light falloff.
Do not recolor furnishings, skin, artwork, or adjacent surfaces.
Do not invent named-product availability, dimensions, finish, or performance claims.
Treat the preview as an approximation; verify physical samples and measured quantities before purchase or installation.
Deliver one edited material-preview image only.
```

[用自己的素材在线制作 / Make it online](https://dearsketch.com/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i171_after-prompt) · [让 Agent 帮你整理 / Use the Skill](../quickstart.md#agent-skill)

## 检查重点 / Review

指定产品应提供样板或准确色彩资料；屏幕画面不能保证实物色差一致。

Compare with a sample when one exists and warn that screens cannot guarantee real material color.

结果方向：材料效果预览。需要准确文字、透明文件、矢量或印刷交付时，检查实际文件；可用功能和费用以网站说明为准。

## 相关案例 / Related tasks

- [Turn a house photo into a watercolor or line-art keepsake · 住宅水彩纪念画](./i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.md#public-prompt)
- [Preview different interior styles in a room photo · 房间装修风格预览](./i169-preview-different-interior-styles-in-a-room-photo.md#public-prompt)
- [Create a landscape makeover concept from a yard photo · 庭院景观改造](./i178-create-a-landscape-makeover-concept-from-a-yard-photo.md#public-prompt)

## 需求背景参考

- [LightX全部工具](https://www.lightxeditor.com/all-tools/all-tools/)
- [Adobe家居概念](https://www.adobe.com/products/firefly/features/ai-room-design/home-design.html)

这些链接仅帮助理解用途，不是本页图片的来源或授权证明。

图片与素材使用范围见[内容说明](../content-policy.md)。[查看全部 50 个模板](../prompts.md)。
