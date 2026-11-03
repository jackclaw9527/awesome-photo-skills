# Decluttered Property Photo · 房源照片整理

[中文](../../README.md) · [English](../../README.en.md) · [Português](../../README.pt.md) · [Español](../../README.es.md) · [Français](../../README.fr.md) · [Deutsch](../../README.de.md) · [عربي](../../README.ar.md) · [русский](../../README.ru.md) · [日本語](../../README.ja.md) · [हिंदी](../../README.hi.md)


Clean up visible clutter while preserving the truthful condition and structure of a room.

把随手拍房间照片整理成房源展示图。用于房地产经纪人销售房源。

[复制公开提示词 / Copy prompt](#public-prompt) · [在 dearsketch 制作 / Try online](https://dearsketch.com/intent/i176-turn-a-casual-room-photo-into-a-polished-property-listing-image.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i176_cta) · [返回专题 / Collection](../guides/spaces.md)

## 参考素材与结果方向

<table>
<thead><tr><th width="50%">参考素材</th><th width="50%">结果示例</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>随手拍的有杂物房间照片</strong><br><img src="../../assets/cases/i176-before-1.webp" alt="房源照片整理 — 参考素材 1" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/intent/i176-turn-a-casual-room-photo-into-a-polished-property-listing-image.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i176_image"><img src="../../assets/cases/i176-after.webp" alt="房源照片整理 — 结果示例" width="320"></a></td></tr></tbody>
</table>

参考素材与结果用于说明视觉方向，公开模板不是配图的原始生成指令，不保证复现相同结果。

## 需要准备什么 / Inputs

| 素材 / Material | 类型 / Type | 数量 / Quantity | 条件 / Requirement |
| --- | --- | --- | --- |
| 随手拍的有杂物房间照片 | 图片 / Image | 1张；多角色或多视角可合并为一张已标注参考板 | 必需 / Required |

每次只生成一张图片。

## 保留与改变 / Editing brief

- **Preserve / 保留：** Keep layout, fixed elements, surfaces, lighting, and material defects.
- **Change / 改变：** Remove only listed movable clutter and make restrained presentation corrections.

## Public prompt

**新编公开模板 · Newly authored · Not generation-tested.** 替换方括号参数，在支持图片编辑的工具中附上所需素材；可选和条件输入按上表准备。此模板没有用于生成本页示例。

```text
Create one cleaned-up property image from [ROOM PHOTO].
Remove only these movable items: [APPROVED CLUTTER REMOVAL LIST].
Preserve the real room layout, walls, doors, windows, floor, ceiling, built-ins, fixtures, and camera view.
Do not erase cracks, stains, damage, structural issues, utility elements, or permanent features.
Do not enlarge the room, move openings, replace finishes, or add furniture unless explicitly requested.
Correct minor exposure, white balance, and verticals while keeping the scene natural.
Reconstruct exposed background areas consistently after approved objects are removed.
Keep reflections, shadows, edges, and material texture believable.
The result must remain a truthful presentation of the property, not a renovation concept.
Deliver one cleaned property image only.
```

[用自己的素材在线制作 / Make it online](https://dearsketch.com/intent/i176-turn-a-casual-room-photo-into-a-polished-property-listing-image.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i176_after-prompt) · [让 Agent 帮你整理 / Use the Skill](../quickstart.md#agent-skill)

## 检查重点 / Review

不掩盖房屋真实缺陷，不改变房型与固定结构。

Ensure no damage or permanent feature is hidden or altered.

结果方向：整洁的房源销售展示图。需要准确文字、透明文件、矢量或印刷交付时，检查实际文件；可用功能和费用以网站说明为准。

## 相关案例 / Related tasks

- [Turn a house photo into a watercolor or line-art keepsake · 住宅水彩纪念画](./i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.md#public-prompt)
- [Preview different interior styles in a room photo · 房间装修风格预览](./i169-preview-different-interior-styles-in-a-room-photo.md#public-prompt)
- [Create a landscape makeover concept from a yard photo · 庭院景观改造](./i178-create-a-landscape-makeover-concept-from-a-yard-photo.md#public-prompt)

## 需求背景参考

- [LightX全部工具](https://www.lightxeditor.com/all-tools/all-tools/)

这些链接仅帮助理解用途，不是本页图片的来源或授权证明。

图片与素材使用范围见[内容说明](../content-policy.md)。[查看全部 50 个模板](../prompts.md)。
