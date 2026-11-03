# Transparent-Background Product Asset · 透明底商品素材

[中文](../../README.md) · [English](../../README.en.md) · [Português](../../README.pt.md) · [Español](../../README.es.md) · [Français](../../README.fr.md) · [Deutsch](../../README.de.md) · [عربي](../../README.ar.md) · [русский](../../README.ru.md) · [日本語](../../README.ja.md) · [हिंदी](../../README.hi.md)


Extract a product as a reusable cutout with a real alpha channel.

生成可复用的透明底商品PNG。用于海报、目录、广告。

[复制公开提示词 / Copy prompt](#public-prompt) · [在 dearsketch 制作 / Try online](https://dearsketch.com/intent/i066-create-a-reusable-product-png-with-a-transparent-background.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i066_cta) · [返回专题 / Collection](../guides/products.md)

## 参考素材与结果方向

<table>
<thead><tr><th width="50%">参考素材</th><th width="50%">结果示例</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>商品照片</strong><br><img src="../../assets/cases/i066-before-1.webp" alt="透明底商品素材 — 参考素材 1" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/intent/i066-create-a-reusable-product-png-with-a-transparent-background.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i066_image"><img src="../../assets/cases/i066-after.webp" alt="透明底商品素材 — 结果示例" width="320"></a></td></tr></tbody>
</table>

参考素材与结果用于说明视觉方向，公开模板不是配图的原始生成指令，不保证复现相同结果。

## 需要准备什么 / Inputs

| 素材 / Material | 类型 / Type | 数量 / Quantity | 条件 / Requirement |
| --- | --- | --- | --- |
| 商品照片 | 图片 / Image | 1张 | 必需 / Required |

每次只生成一张图片。

## 保留与改变 / Editing brief

- **Preserve / 保留：** Keep every product edge, opening, label, color, and transparent or reflective detail.
- **Change / 改变：** Change only background removal, edge cleanup, and optional neutral shadow handling.

## Public prompt

**新编公开模板 · Newly authored · Not generation-tested.** 替换方括号参数，在支持图片编辑的工具中附上所需素材；可选和条件输入按上表准备。此模板没有用于生成本页示例。

```text
Create one reusable product cutout from [PRODUCT PHOTO].
Preserve the exact product shape, proportions, colors, labels, openings, fine edges, transparent parts, and reflective details.
Remove the entire background without removing real product pixels.
Refine hair-like, fabric, glass, glossy, perforated, and semi-transparent edges carefully.
Do not redesign the product, fill openings, straighten labels, or invent hidden geometry.
Keep or remove the contact shadow according to [SHADOW REQUIREMENT].
Avoid white halos, dark fringes, jagged edges, color spill, and artificial outlines.
Export as [PNG / OTHER ALPHA-CAPABLE FORMAT] at [REQUIRED SIZE].
Open the delivered file over dark and light backgrounds to verify a genuine alpha channel.
Deliver one cutout asset only; do not substitute a white-background image.
```

[用自己的素材在线制作 / Make it online](https://dearsketch.com/intent/i066-create-a-reusable-product-png-with-a-transparent-background.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i066_after-prompt) · [让 Agent 帮你整理 / Use the Skill](../quickstart.md#agent-skill)

## 检查重点 / Review

检查真实透明通道与细小边缘，不把白底预览当作透明文件证明。

Verify the exported file’s alpha channel; a checkerboard preview is not proof.

结果方向：透明底商品素材。需要准确文字、透明文件、矢量或印刷交付时，检查实际文件；可用功能和费用以网站说明为准。

## 相关案例 / Related tasks

- [Turn an ordinary product photo into a white-background listing image · 商品白底主图](./i065-turn-an-ordinary-product-photo-into-a-white-background-listing-image.md#public-prompt)
- [Place a product in a realistic lifestyle scene · 商品生活方式场景](./i067-place-a-product-in-a-realistic-lifestyle-scene.md#public-prompt)
- [Turn an ordinary photo into a professional studio product shot · 商品影棚照](./i068-turn-an-ordinary-photo-into-a-professional-studio-product-shot.md#public-prompt)

## 需求背景参考

- [Cutout.pro](https://www.cutout.pro/)
- [insMind商品摄影](https://www.insmind.com/image-tools/ai-product-photography)

这些链接仅帮助理解用途，不是本页图片的来源或授权证明。

图片与素材使用范围见[内容说明](../content-policy.md)。[查看全部 50 个模板](../prompts.md)。
