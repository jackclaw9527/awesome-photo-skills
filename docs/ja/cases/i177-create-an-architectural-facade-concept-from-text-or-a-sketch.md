# 建築ファサードコンセプト・建物ファサードコンセプト

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


オプションのスケッチ、または建物の用途とデザイン方向の概要からファサードを作成します。

テキストまたはスケッチから建物のファサードのコンセプトを生成します。コンペや企画書、レポートなどに利用されます。

[プロンプトをコピー](#public-prompt) · [ は dearsketch によって作成されています / オンラインで試してください](https://dearsketch.com/ja/intent/i177-create-an-architectural-facade-concept-from-text-or-a-sketch.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i177_cta) · [トピックに戻る / コレクション](../guides/spaces.md)

## 参考資料と結果の方向性

<table>
<thead><tr><th width="50%">参考資料</th><th width="50%">結果の例</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>建築スケッチまたは集合図面</strong><br><img src="../../../assets/cases/i177-before-1.webp" alt="建物ファサードコンセプト 参考資料1" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/ja/intent/i177-create-an-architectural-facade-concept-from-text-or-a-sketch.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i177_image"><img src="../../../assets/cases/i177-after.webp" alt="建物のファサードのコンセプト - 結果の例" width="320"></a></td></tr></tbody>
</table>

参考資料と結果は、視覚的な方向性を説明するために使用されます。公開テンプレートは、添付画像のオリジナルの生成指示ではなく、同じ結果が再現されることは保証されません。

## 準備するもの・入力内容

| 素材 / Material | 種類・タイプ | 数量・個数 | 条件 / Requirement |
| --- | --- | --- | --- |
| 建築スケッチまたは集合図面 | 写真/画像 | 0–1;複数の材料を 1 つのラベル付きリファレンスボードに組み合わせることができます | オプション/オプション: ユーザーがすでに建物の型枠、開口部、または敷地のスケッチを持っている場合 |
| 建築用途・デザインキーワード | 文字 / Text | 1食分 | 必須 / 必須 |

一度に生成される画像は 1 つだけです。

## 保持および変更 / 編集概要

- **保持 / 保持：** スケッチまたはマス参照が存在する場合にのみ、提供されたマスと開口部を保持します。
- **変更 / 改变：** ファサードの素材、関節、環境、景観、光を変更します。

## Public prompt

**新しく編集されたパブリック テンプレート · 新しく作成された · 生成テストされていません。** 画像編集をサポートするツールで角括弧パラメータを置き換え、必要な素材を添付します。オプションおよび条件付き入力は、上の表に従って準備されます。このテンプレートは、このページの例の生成には使用されませんでした。

```text
Create one architectural facade concept for [BUILDING USE] with [DESIGN KEYWORDS].
Choose one branch: follow [OPTIONAL SKETCH OR MASSING IMAGE] when supplied, or create a text-led concept from the brief when no image exists.
For the reference branch, preserve the supplied massing, floor count, principal openings, roof form, proportions, and camera view.
For the text-only branch, do not claim that any generated geometry reproduces an existing design.
Develop [FACADE MATERIALS], [OPENING TREATMENT], [SHADING ELEMENTS], and [ENTRY EXPRESSION].
Add a restrained [SITE CONTEXT], [LANDSCAPE], and [LIGHTING CONDITION] for scale.
Keep perspective, material joints, shadows, and human scale coherent.
Do not invent planning approval, structural feasibility, energy performance, or code compliance.
Do not treat generated details as measured dimensions or construction assemblies.
Deliver one facade concept rendering only for design discussion.
```

[独自の資料を使用してオンラインで作成する / オンラインで作成する](https://dearsketch.com/ja/intent/i177-create-an-architectural-facade-concept-from-text-or-a-sketch.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i177_after-prompt) · [エージェントに整理を手伝ってもらう / スキルを使用する](../quickstart.md#agent-skill)

## 要点確認・復習

建築の目的と設計の方向性を明確にし、その結果を施工図ではなく概念的なコミュニケーションに活用します。

出力は、構築のための図面ではなく、コンセプトのコミュニケーションとして扱います。

結果の方向性: 建築コンセプトのレンダリング。正確なテキスト、透明ファイル、ベクター、または印刷配信が必要な場合は、実際のファイルを確認してください。利用可能な機能と料金はウェブサイトの説明に準じます。

## 関連事例・関連タスク

- [家の写真を水彩画または線画の記念品に変換します · 住宅の水彩画記念絵画 ](./i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.md#public-prompt)
- [部屋の写真でさまざまなインテリア スタイルをプレビュー · 部屋の装飾スタイルのプレビュー](./i169-preview-different-interior-styles-in-a-room-photo.md#public-prompt)
- [庭の写真から景観改造コンセプトを作成 · 庭景観改修 ](./i178-create-a-landscape-makeover-concept-from-a-yard-photo.md#public-prompt)

## 要件の背景リファレンス

- [Adobe ビルディング生成 ](https://www.adobe.com/products/firefly/features/ai-architecture-generator.html)

これらのリンクは、目的の理解を助けることのみを目的としており、このページ上の画像の出典や許可を証明するものではありません。

写真や素材の使用範囲については、[コンテンツ説明](../content-policy.md)をご覧ください。 [50 個のテンプレートをすべて表示します (](../prompts.md))。
