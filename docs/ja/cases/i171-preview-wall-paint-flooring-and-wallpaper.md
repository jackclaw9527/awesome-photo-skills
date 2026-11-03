# 塗装、床材、壁紙のプレビュー・壁塗装と床材の選択プレビュー

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


付属のサンプルまたは正確な色と材質の説明を使用して、指定された部屋の表面を交換します。

壁のペイント、床、壁紙の効果をプレビューします。装飾材料の選択に使用されます。

[プロンプトをコピー](#public-prompt) · [ は dearsketch によって作成されています / オンラインで試してください](https://dearsketch.com/ja/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i171_cta) · [トピックに戻る / コレクション](../guides/spaces.md)

## 参考資料と結果の方向性

<table>
<thead><tr><th width="50%">参考資料</th><th width="50%">結果の例</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>屋内の写真</strong><br><img src="../../../assets/cases/i171-before-1.webp" alt="壁塗装・床材選定プレビュー 参考資料1" width="320"></p>
<p><strong>ターゲット素材テンプレート</strong><br><img src="../../../assets/cases/i171-before-2.webp" alt="壁塗装・床材選定プレビュー 参考資料2" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/ja/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i171_image"><img src="../../../assets/cases/i171-after.webp" alt="壁塗装と床材の選択プレビュー - 結果の例" width="320"></a></td></tr></tbody>
</table>

参考資料と結果は、視覚的な方向性を説明するために使用されます。公開テンプレートは、添付画像のオリジナルの生成指示ではなく、同じ結果が再現されることは保証されません。

## 準備するもの・入力内容

| 素材 / Material | 種類・タイプ | 数量・個数 | 条件 / Requirement |
| --- | --- | --- | --- |
| 屋内の写真 | 写真/画像 | 1個 | 必須 / 必須 |
| ターゲット素材テンプレート | 写真/画像 | 0 ～ 1 個の画像。正確なテキストまたは色のデータも使用できます | 条件付き: 特定のテクスチャや製品サンプルを再現する必要がある場合 |
| 表面をターゲットの色/材質に置き換えます | 文字 / Text | 1食分 | 必須 / 必須 |

一度に生成される画像は 1 つだけです。

## 保持および変更 / 編集概要

- **保存 / 保持：** 部屋の構造、照明ロジック、オブジェクトの配置、対象外の表面を保持します。
- **変更/変更：** 名前付きの壁、床、または壁紙の領域のみを変更します。

## Public prompt

**新しく編集されたパブリック テンプレート · 新しく作成された · 生成テストされていません。** 画像編集をサポートするツールで角括弧パラメータを置き換え、必要な素材を添付します。オプションおよび条件付き入力は、上の表に従って準備されます。このテンプレートは、このページの例の生成には使用されませんでした。

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

[独自の資料を使用してオンラインで作成する / オンラインで作成する](https://dearsketch.com/ja/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i171_after-prompt) · [エージェントに整理を手伝ってもらう / スキルを使用する](../quickstart.md#agent-skill)

## 要点確認・復習

指定された製品にはサンプルまたは正確な色情報が提供されている必要があります。画面上の画像は実際の商品と同じ色の違いを保証するものではありません。

サンプルが存在する場合はそれと比較し、画面では実際の素材の色を保証できないことを警告します。

結果の方向: マテリアル効果のプレビュー。正確なテキスト、透明ファイル、ベクター、または印刷配信が必要な場合は、実際のファイルを確認してください。利用可能な機能と料金はウェブサイトの説明に準じます。

## 関連事例・関連タスク

- [家の写真を水彩画または線画の記念品に変換します · 住宅の水彩画記念絵画 ](./i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.md#public-prompt)
- [部屋の写真でさまざまなインテリア スタイルをプレビュー · 部屋の装飾スタイルのプレビュー](./i169-preview-different-interior-styles-in-a-room-photo.md#public-prompt)
- [庭の写真から景観改造コンセプトを作成 · 庭景観改修 ](./i178-create-a-landscape-makeover-concept-from-a-yard-photo.md#public-prompt)

## 要件の背景リファレンス

- [ライトXすべてのツール](https://www.lightxeditor.com/all-tools/all-tools/)
- [アドビ ホーム コンセプト](https://www.adobe.com/products/firefly/features/ai-room-design/home-design.html)

これらのリンクは、目的の理解を助けることのみを目的としており、このページ上の画像の出典や許可を証明するものではありません。

写真や素材の使用範囲については、[コンテンツ説明](../content-policy.md)をご覧ください。 [50 個のテンプレートをすべて表示します (](../prompts.md))。
