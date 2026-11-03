# Room Style Preview · 房间装修风格预览

[中文](../../README.md) · [English](../../README.en.md) · [Português](../../README.pt.md) · [Español](../../README.es.md) · [Français](../../README.fr.md) · [Deutsch](../../README.de.md) · [عربي](../../README.ar.md) · [русский](../../README.ru.md) · [日本語](../../README.ja.md) · [हिंदी](../../README.hi.md)


Preview a new interior style while retaining the photographed room structure.

上传房间照片预览不同装修风格。用于装修决策、客户提案。

[复制公开提示词 / Copy prompt](#public-prompt) · [在 dearsketch 制作 / Try online](https://dearsketch.com/intent/i169-preview-different-interior-styles-in-a-room-photo.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i169_cta) · [返回专题 / Collection](../guides/spaces.md)

## 参考素材与结果方向

<table>
<thead><tr><th width="50%">参考素材</th><th width="50%">结果示例</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>现有房间照片</strong><br><img src="../../assets/cases/i169-before-1.webp" alt="房间装修风格预览 — 参考素材 1" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/intent/i169-preview-different-interior-styles-in-a-room-photo.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i169_image"><img src="../../assets/cases/i169-after.webp" alt="房间装修风格预览 — 结果示例" width="320"></a></td></tr></tbody>
</table>

参考素材与结果用于说明视觉方向，公开模板不是配图的原始生成指令，不保证复现相同结果。

## 需要准备什么 / Inputs

| 素材 / Material | 类型 / Type | 数量 / Quantity | 条件 / Requirement |
| --- | --- | --- | --- |
| 现有房间照片 | 图片 / Image | 1张；多角色或多视角可合并为一张已标注参考板 | 必需 / Required |

每次只生成一张图片。

## 保留与改变 / Editing brief

- **Preserve / 保留：** Keep walls, doors, windows, ceiling, fixed openings, and camera viewpoint.
- **Change / 改变：** Change furniture, finishes, decor, palette, and lighting mood.

## Public prompt

**新编公开模板 · Newly authored · Not generation-tested.** 替换方括号参数，在支持图片编辑的工具中附上所需素材；可选和条件输入按上表准备。此模板没有用于生成本页示例。

```text
Create one interior style preview from [ROOM PHOTO].
Preserve the room geometry, walls, doors, windows, ceiling height, fixed openings, and camera viewpoint.
Apply [TARGET INTERIOR STYLE] with [PALETTE], [MATERIAL DIRECTION], and [LIGHTING MOOD].
Replace or add only the furniture and decor described in [CHANGE LIST].
Keep circulation paths, perspective, furniture scale, shadows, and floor contact believable.
Do not move structural elements or enlarge the room unless [EXPLICIT STRUCTURAL CHANGE] is supplied.
Retain items listed in [KEEP LIST] and remove only items in [REMOVE LIST].
Treat materials and colors as a visual concept, not a guaranteed product match.
Do not claim measured dimensions, budget accuracy, code compliance, or construction feasibility.
Deliver one single-view room concept image only.
```

[用自己的素材在线制作 / Make it online](https://dearsketch.com/intent/i169-preview-different-interior-styles-in-a-room-photo.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i169_after-prompt) · [让 Agent 帮你整理 / Use the Skill](../quickstart.md#agent-skill)

## 检查重点 / Review

检查门窗与空间结构，效果图不能代替尺寸、预算和施工可行性核查。

Check structure and disclose that dimensions, cost, and buildability are unverified.

结果方向：装修效果图。需要准确文字、透明文件、矢量或印刷交付时，检查实际文件；可用功能和费用以网站说明为准。

## 相关案例 / Related tasks

- [Turn a house photo into a watercolor or line-art keepsake · 住宅水彩纪念画](./i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.md#public-prompt)
- [Create a landscape makeover concept from a yard photo · 庭院景观改造](./i178-create-a-landscape-makeover-concept-from-a-yard-photo.md#public-prompt)
- [Preview wall paint, flooring, and wallpaper · 墙漆与地板选材预览](./i171-preview-wall-paint-flooring-and-wallpaper.md#public-prompt)

## 需求背景参考

- [Adobe房间设计](https://www.adobe.com/products/firefly/features/ai-room-design.html)
- [Adobe家居概念](https://www.adobe.com/products/firefly/features/ai-room-design/home-design.html)

这些链接仅帮助理解用途，不是本页图片的来源或授权证明。

图片与素材使用范围见[内容说明](../content-policy.md)。[查看全部 50 个模板](../prompts.md)。
