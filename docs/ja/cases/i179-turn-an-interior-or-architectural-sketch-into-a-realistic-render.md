# スケッチからリアルな空間レンダリング · 建築スケッチをリアルな効果に変換

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


意図された構造を変更せずに、提供された建築またはインテリアの線画をレンダリングします。

インテリアまたは建築のスケッチをリアルなレンダリングに変換します。顧客とのコミュニケーションやプログラムのレビューに使用されます。

[プロンプトをコピー](#public-prompt) · [ は dearsketch によって作成されています / オンラインで試してください](https://dearsketch.com/ja/intent/i179-turn-an-interior-or-architectural-sketch-into-a-realistic-render.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i179_cta) · [トピックに戻る / コレクション](../guides/spaces.md)

## 参考資料と結果の方向性

<table>
<thead><tr><th width="50%">参考資料</th><th width="50%">結果の例</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>インテリアまたは建築のスケッチ/CAD ワイヤーフレーム</strong><br><img src="../../../assets/cases/i179-before-1.webp" alt="建築スケッチをリアルに変換 - 参考資料 1" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/ja/intent/i179-turn-an-interior-or-architectural-sketch-into-a-realistic-render.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i179_image"><img src="../../../assets/cases/i179-after.webp" alt="現実的な効果をもたらす建築スケッチ - 結果の例" width="320"></a></td></tr></tbody>
</table>

参考資料と結果は、視覚的な方向性を説明するために使用されます。公開テンプレートは、添付画像のオリジナルの生成指示ではなく、同じ結果が再現されることは保証されません。

## 準備するもの・入力内容

| 素材 / Material | 種類・タイプ | 数量・個数 | 条件 / Requirement |
| --- | --- | --- | --- |
| インテリアまたは建築のスケッチ/CAD ワイヤーフレーム | 写真/画像 | 1個 | 必須 / 必須 |
| 空間利用とスケッチの意味 | 文字 / Text | 1食分 | 必須 / 必須 |

一度に生成される画像は 1 つだけです。

## 保持および変更 / 編集概要

- **保存 / 保持：** 開口部、ジオメトリ、レイアウト関係、カメラのフレーミングを保持します。
- **変更 / 改变：** 素材、照明、家具、風景、雰囲気を変更します。

## Public prompt

**新しく編集されたパブリック テンプレート · 新しく作成された · 生成テストされていません。** 画像編集をサポートするツールで角括弧パラメータを置き換え、必要な素材を添付します。オプションおよび条件付き入力は、上の表に従って準備されます。このテンプレートは、このページの例の生成には使用されませんでした。

```text
Create one realistic rendering from [ARCHITECTURAL OR INTERIOR SKETCH / CAD VIEW].
Interpret the space as [SPACE USE] according to [SKETCH LEGEND OR EXPLANATION].
Preserve all indicated walls, openings, levels, roof lines, built forms, and camera framing.
Apply [MATERIALS], [COLOR PALETTE], [LIGHTING], and [ENVIRONMENT].
Add only the furniture, fixtures, landscape, or people listed in [ADD LIST].
Keep perspective, scale, structural relationships, shadows, and material transitions coherent.
Do not erase ambiguous source lines; resolve uncertainty conservatively or flag it.
Do not claim engineering accuracy, measured dimensions, buildability, or code compliance.
The source drawing remains authoritative when the rendering conflicts with it.
Deliver one realistic concept rendering only.
```

[独自の資料を使用してオンラインで作成する / オンラインで作成する](https://dearsketch.com/ja/intent/i179-turn-an-interior-or-architectural-sketch-into-a-realistic-render.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i179_after-prompt) · [エージェントに整理を手伝ってもらう / スキルを使用する](../quickstart.md#agent-skill)

## 要点確認・復習

スケッチ内の開口部と構造の関係を確認し、視覚的なレンダリングをエンジニアリング検証として扱わないでください。

レンダリングをソース行と比較し、エンジニアリング検証として扱わないでください。

結果の方向性: 現実的な空間レンダリング。正確なテキスト、透明ファイル、ベクター、または印刷配信が必要な場合は、実際のファイルを確認してください。利用可能な機能と料金はウェブサイトの説明に準じます。

## 関連事例・関連タスク

- [家の写真を水彩画または線画の記念品に変換します · 住宅の水彩画記念絵画 ](./i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.md#public-prompt)
- [部屋の写真でさまざまなインテリア スタイルをプレビュー · 部屋の装飾スタイルのプレビュー](./i169-preview-different-interior-styles-in-a-room-photo.md#public-prompt)
- [庭の写真から景観改造コンセプトを作成 · 庭景観改修 ](./i178-create-a-landscape-makeover-concept-from-a-yard-photo.md#public-prompt)

## 要件の背景リファレンス

- [OpenArt スケッチを画像に変換 ](https://openart.ai/generator/sketch/)
- [Adobe ビルディング生成 ](https://www.adobe.com/products/firefly/features/ai-architecture-generator.html)

これらのリンクは、目的の理解を助けることのみを目的としており、このページ上の画像の出典や許可を証明するものではありません。

写真や素材の使用範囲については、[コンテンツ説明](../content-policy.md)をご覧ください。 [50 個のテンプレートをすべて表示します (](../prompts.md))。
