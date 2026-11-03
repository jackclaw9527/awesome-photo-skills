# Virtual Eyewear Preview · 眼镜试戴预览

[中文](../../README.md) · [English](../../README.en.md) · [Português](../../README.pt.md) · [Español](../../README.es.md) · [Français](../../README.fr.md) · [Deutsch](../../README.de.md) · [عربي](../../README.ar.md) · [русский](../../README.ru.md) · [日本語](../../README.ja.md) · [हिंदी](../../README.hi.md)


Place an exact product or a described eyewear concept on a front-facing portrait.

虚拟试戴眼镜。用于购买决策。

[复制公开提示词 / Copy prompt](#public-prompt) · [在 dearsketch 制作 / Try online](https://dearsketch.com/intent/i036-virtually-try-on-glasses.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i036_cta) · [返回专题 / Collection](../guides/people.md)

## 参考素材与结果方向

<table>
<thead><tr><th width="50%">参考素材</th><th width="50%">结果示例</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>人物正面照片</strong><br><img src="../../assets/cases/i036-before-1.webp" alt="眼镜试戴预览 — 参考素材 1" width="320"></p>
<p><strong>目标眼镜商品图</strong><br><img src="../../assets/cases/i036-before-2.webp" alt="眼镜试戴预览 — 参考素材 2" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/intent/i036-virtually-try-on-glasses.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i036_image"><img src="../../assets/cases/i036-after.webp" alt="眼镜试戴预览 — 结果示例" width="320"></a></td></tr></tbody>
</table>

参考素材与结果用于说明视觉方向，公开模板不是配图的原始生成指令，不保证复现相同结果。

## 需要准备什么 / Inputs

| 素材 / Material | 类型 / Type | 数量 / Quantity | 条件 / Requirement |
| --- | --- | --- | --- |
| 人物正面照片 | 图片 / Image | 1张 | 必需 / Required |
| 目标眼镜素材或款式描述 | 图片 / Image | 1张 | 按条件 / Conditional：精确商品试戴时必需；仅概念款式可用文字描述 |

每次只生成一张图片。

## 保留与改变 / Editing brief

- **Preserve / 保留：** Keep identity, face shape, skin, eyes, and the supplied frame details for the chosen branch.
- **Change / 改变：** Change only frame placement, lens appearance, and minimal lighting integration.

## Public prompt

**新编公开模板 · Newly authored · Not generation-tested.** 替换方括号参数，在支持图片编辑的工具中附上所需素材；可选和条件输入按上表准备。此模板没有用于生成本页示例。

```text
Create one eyewear preview using [FRONT-FACING PERSON PHOTO].
Choose one eyewear branch: use [EYEWEAR PRODUCT IMAGE] for an exact product, or [FRAME STYLE DESCRIPTION] for a concept; do not require both.
Preserve the person’s identity, face shape, eyes, eyebrows, skin tone, hair, and expression.
For the product-image branch, preserve the frame silhouette, color, material, bridge, and temple design exactly.
For the description branch, create only the described frame characteristics without implying a real product match.
Align the frame to the eyes, nose bridge, ears, head angle, and camera perspective.
Render [CLEAR / TINTED / PRESCRIPTION-LIKE] lenses with plausible reflections.
Do not reshape the face or claim exact sizing, optical correction, comfort, or real-world fit.
Keep the original portrait background unless [BACKGROUND CHANGE] is requested.
Deliver one preview image only.
```

[用自己的素材在线制作 / Make it online](https://dearsketch.com/intent/i036-virtually-try-on-glasses.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i036_after-prompt) · [让 Agent 帮你整理 / Use the Skill](../quickstart.md#agent-skill)

## 检查重点 / Review

要试戴具体商品就提供对应款式图；生成画面不能证明实际尺码与佩戴舒适度。

Check bridge, temples, perspective, and note that fit and comfort remain unverified.

结果方向：眼镜试戴图。需要准确文字、透明文件、矢量或印刷交付时，检查实际文件；可用功能和费用以网站说明为准。

## 相关案例 / Related tasks

- [Create a professional LinkedIn headshot from a selfie · 自拍转职业头像](./i001-create-a-professional-linkedin-headshot-from-a-selfie.md#public-prompt)
- [Replace casual clothing with professional attire · 休闲装换正装](./i015-replace-casual-clothing-with-professional-attire.md#public-prompt)
- [Turn yourself into a royal, vintage, or historical portrait · 皇家与复古人物肖像](./i052-turn-yourself-into-a-royal-vintage-or-historical-portrait.md#public-prompt)

## 需求背景参考

- [Picsart AI工具](https://picsart.com/ai/)

这些链接仅帮助理解用途，不是本页图片的来源或授权证明。

图片与素材使用范围见[内容说明](../content-policy.md)。[查看全部 50 个模板](../prompts.md)。
