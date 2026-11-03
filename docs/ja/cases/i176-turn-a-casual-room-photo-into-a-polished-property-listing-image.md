# 整理整頓された物件写真・物件写真の整理

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


部屋の実際の状態と構造を維持しながら、目に見える散らかったものを片付けます。

ランダムな部屋の写真をリスト表示に整理します。不動産業者が物件を販売するために使用します。

[プロンプトをコピー](#public-prompt) · [ は dearsketch によって作成されています / オンラインで試してください](https://dearsketch.com/ja/intent/i176-turn-a-casual-room-photo-into-a-polished-property-listing-image.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i176_cta) · [トピックに戻る / コレクション](../guides/spaces.md)

## 参考資料と結果の方向性

<table>
<thead><tr><th width="50%">参考資料</th><th width="50%">結果の例</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>散らかった部屋のランダムな写真</strong><br><img src="../../../assets/cases/i176-before-1.webp" alt="掲載写真構成－参考資料１" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/ja/intent/i176-turn-a-casual-room-photo-into-a-polished-property-listing-image.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i176_image"><img src="../../../assets/cases/i176-after.webp" alt="写真キュレーションのリスト — 結果のサンプル" width="320"></a></td></tr></tbody>
</table>

参考資料と結果は、視覚的な方向性を説明するために使用されます。公開テンプレートは、添付画像のオリジナルの生成指示ではなく、同じ結果が再現されることは保証されません。

## 準備するもの・入力内容

| 素材 / Material | 種類・タイプ | 数量・個数 | 条件 / Requirement |
| --- | --- | --- | --- |
| 散らかった部屋のランダムな写真 | 写真/画像 | 1枚。複数のキャラクターまたはパースペクティブを 1 つのマーク付きリファレンス ボードに組み合わせることができます | 必須 / 必須 |

一度に生成される画像は 1 つだけです。

## 保持および変更 / 編集概要

- **保存/保持：** レイアウト、固定要素、表面、照明、および材料の欠陥を保持します。
- **変更 / 改变：** リストされた移動可能なクラッタのみを削除し、制限されたプレゼンテーションの修正を行います。

## Public prompt

**新しく編集されたパブリック テンプレート · 新しく作成された · 生成テストされていません。** 画像編集をサポートするツールで角括弧パラメータを置き換え、必要な素材を添付します。オプションおよび条件付き入力は、上の表に従って準備されます。このテンプレートは、このページの例の生成には使用されませんでした。

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

[独自の資料を使用してオンラインで作成する / オンラインで作成する](https://dearsketch.com/ja/intent/i176-turn-a-casual-room-photo-into-a-polished-property-listing-image.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i176_after-prompt) · [エージェントに整理を手伝ってもらう / スキルを使用する](../quickstart.md#agent-skill)

## 要点確認・復習

住宅の本当の欠陥を隠蔽したり、住宅の種類や固定構造を変更したりしないでください。

損傷や永続的な機能が隠されたり変更されたりしていないことを確認してください。

結果の方向性: きちんとしたリストの販売プレゼンテーション。正確なテキスト、透明ファイル、ベクター、または印刷配信が必要な場合は、実際のファイルを確認してください。利用可能な機能と料金はウェブサイトの説明に準じます。

## 関連事例・関連タスク

- [家の写真を水彩画または線画の記念品に変換します · 住宅の水彩画記念絵画 ](./i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.md#public-prompt)
- [部屋の写真でさまざまなインテリア スタイルをプレビュー · 部屋の装飾スタイルのプレビュー](./i169-preview-different-interior-styles-in-a-room-photo.md#public-prompt)
- [庭の写真から景観改造コンセプトを作成 · 庭景観改修 ](./i178-create-a-landscape-makeover-concept-from-a-yard-photo.md#public-prompt)

## 要件の背景リファレンス

- [ライトXすべてのツール](https://www.lightxeditor.com/all-tools/all-tools/)

これらのリンクは、目的の理解を助けることのみを目的としており、このページ上の画像の出典や許可を証明するものではありません。

写真や素材の使用範囲については、[コンテンツ説明](../content-policy.md)をご覧ください。 [50 個のテンプレートをすべて表示します (](../prompts.md))。
