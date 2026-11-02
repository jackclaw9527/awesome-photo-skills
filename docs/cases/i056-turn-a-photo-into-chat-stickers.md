# Single Chat Sticker · 照片转聊天贴纸

Turn a person, pet, or object photo into one expressive sticker.

把照片制作成聊天贴纸。用于WhatsApp、Telegram、社媒。

[复制公开提示词 / Copy prompt](#public-prompt) · [在 dearsketch 制作 / Try online](https://dearsketch.com/intent/i056-turn-a-photo-into-chat-stickers.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i056_cta) · [返回专题 / Collection](../guides/people.md)

## 参考素材与结果方向

<table>
<thead><tr><th width="50%">参考素材</th><th width="50%">结果示例</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>人物、宠物或物体照片</strong><br><img src="../../assets/cases/i056-before-1.webp" alt="照片转聊天贴纸 — 参考素材 1" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/intent/i056-turn-a-photo-into-chat-stickers.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i056_image"><img src="../../assets/cases/i056-after.webp" alt="照片转聊天贴纸 — 结果示例" width="320"></a></td></tr></tbody>
</table>

参考素材与结果用于说明视觉方向，公开模板不是配图的原始生成指令，不保证复现相同结果。

## 需要准备什么 / Inputs

| 素材 / Material | 类型 / Type | 数量 / Quantity | 条件 / Requirement |
| --- | --- | --- | --- |
| 人物、宠物或物体照片 | 图片 / Image | 1张 | 必需 / Required |
| 本张贴纸的动作或情绪 | 文字 / Text | 0或1项 | 可选 / Optional |

每次只生成当前选定的一张；系列中的其他图片分别执行。

## 保留与改变 / Editing brief

- **Preserve / 保留：** Keep the subject recognizable and retain defining markings or features.
- **Change / 改变：** Change expression, pose emphasis, outline, background removal, and sticker styling.

## Public prompt

**新编公开模板 · Newly authored · Not generation-tested.** 替换方括号参数，在支持图片编辑的工具中附上所需素材；可选和条件输入按上表准备。此模板没有用于生成本页示例。

```text
Create one chat sticker from [SUBJECT PHOTO].
Preserve the subject’s identity, silhouette, colors, markings, and defining features.
Express [ACTION OR EMOTION] through a clear pose and readable facial or object cues.
Use [STICKER STYLE], a bold clean outline, and simple shading suitable for small display.
Keep hands, paws, limbs, and object edges coherent and uncluttered.
Use a transparent-looking or plain preview background according to [BACKGROUND REQUEST].
If text is requested, reproduce “[EXACT SHORT TEXT]” exactly and keep it legible.
Do not create a sheet, pack, or multiple emotional variants in this run.
If a transparent file is required, verify the exported alpha channel rather than trusting a checkerboard preview.
Deliver one sticker image only; platform sizing and pack assembly are separate steps.
```

[用自己的素材在线制作 / Make it online](https://dearsketch.com/intent/i056-turn-a-photo-into-chat-stickers.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i056_after-prompt) · [让 Agent 帮你整理 / Use the Skill](../quickstart.md#agent-skill)

## 检查重点 / Review

一次只做当前选定的一张；系列一致性和平台贴纸打包需要另行检查。

Check small-size readability and remember that platform packaging is separate.

结果方向：聊天贴纸包。需要准确文字、透明文件、矢量或印刷交付时，检查实际文件；可用功能和费用以网站说明为准。

## 相关案例 / Related tasks

- [Create a professional LinkedIn headshot from a selfie · 自拍转职业头像](i001-create-a-professional-linkedin-headshot-from-a-selfie.md#public-prompt)
- [Replace casual clothing with professional attire · 休闲装换正装](i015-replace-casual-clothing-with-professional-attire.md#public-prompt)
- [Turn yourself into a royal, vintage, or historical portrait · 皇家与复古人物肖像](i052-turn-yourself-into-a-royal-vintage-or-historical-portrait.md#public-prompt)

## 需求背景参考

- [LightX全部工具](https://www.lightxeditor.com/all-tools/all-tools/)

这些链接仅帮助理解用途，不是本页图片的来源或授权证明。

图片与素材使用范围见[内容说明](../content-policy.md)。[查看全部 50 个模板](../prompts.md)。
