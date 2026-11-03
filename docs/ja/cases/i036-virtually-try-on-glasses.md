# バーチャルメガネプレビュー・メガネ試着プレビュー

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


正確な製品または説明されたアイウェアのコンセプトを正面のポートレートに配置します。

実際にメガネを試着してみます。購入の決定に使用されます。

[プロンプトをコピー](#public-prompt) · [ は dearsketch によって作成されています / オンラインで試してください](https://dearsketch.com/ja/intent/i036-virtually-try-on-glasses.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i036_cta) · [トピックに戻る / コレクション](../guides/people.md)

## 参考資料と結果の方向性

<table>
<thead><tr><th width="50%">参考資料</th><th width="50%">結果の例</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>人物の正面写真</strong><br><img src="../../../assets/cases/i036-before-1.webp" alt="メガネ試着プレビュー 参考資料1" width="320"></p>
<p><strong>対象メガネ商品イメージ</strong><br><img src="../../../assets/cases/i036-before-2.webp" alt="メガネ試着プレビュー 参考資料2" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/ja/intent/i036-virtually-try-on-glasses.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i036_image"><img src="../../../assets/cases/i036-after.webp" alt="メガネの試着プレビュー - 結果の例" width="320"></a></td></tr></tbody>
</table>

参考資料と結果は、視覚的な方向性を説明するために使用されます。公開テンプレートは、添付画像のオリジナルの生成指示ではなく、同じ結果が再現されることは保証されません。

## 準備するもの・入力内容

| 素材 / Material | 種類・タイプ | 数量・個数 | 条件 / Requirement |
| --- | --- | --- | --- |
| 人物の正面写真 | 写真/画像 | 1個 | 必須 / 必須 |
| 対象となるメガネの素材またはスタイルの説明 | 写真/画像 | 1個 | 条件付き/条件付き: 製品を正確に試着するために必要です。テキストで説明できるのはコンセプト スタイルのみです |

一度に生成される画像は 1 つだけです。

## 保持および変更 / 編集概要

- **保持 / 保持：** 選択したブランチのアイデンティティ、顔の形、肌、目、および提供されたフレームの詳細を保持します。
- **変更/修正：** フレームの配置、レンズの外観、最小限の照明の統合のみを変更します。

## Public prompt

**新しく編集されたパブリック テンプレート · 新しく作成された · 生成テストされていません。** 画像編集をサポートするツールで角括弧パラメータを置き換え、必要な素材を添付します。オプションおよび条件付き入力は、上の表に従って準備されます。このテンプレートは、このページの例の生成には使用されませんでした。

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

[独自の資料を使用してオンラインで作成する / オンラインで作成する](https://dearsketch.com/ja/intent/i036-virtually-try-on-glasses.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i036_after-prompt) · [エージェントに整理を手伝ってもらう / スキルを使用する](../quickstart.md#agent-skill)

## 要点確認・復習

特定の製品を試着したい場合は、対応するスタイル画像を提供してください。生成された画像では実際のサイズや着用感を証明することはできません。

ブリッジ、テンプル、遠近感をチェックしてください。フィット感と快適さは未検証のままであることに注意してください。

結果の方向性: メガネの試着チャート。正確なテキスト、透明ファイル、ベクター、または印刷配信が必要な場合は、実際のファイルを確認してください。利用可能な機能と料金はウェブサイトの説明に準じます。

## 関連事例・関連タスク

- [自撮り写真からプロの LinkedIn ヘッドショットを作成する · 自撮り写真からプロの顔写真へ ](./i001-create-a-professional-linkedin-headshot-from-a-selfie.md#public-prompt)
- [カジュアルな服装をプロフェッショナルな服装に置き換える · ](./i015-replace-casual-clothing-with-professional-attire.md#public-prompt)
- [自分自身を王室、ビンテージ、または歴史的な肖像画に変身させましょう · 王室およびビンテージの肖像画 ](./i052-turn-yourself-into-a-royal-vintage-or-historical-portrait.md#public-prompt)

## 要件の背景リファレンス

- [Picsart AI ツール](https://picsart.com/ai/)

これらのリンクは、目的の理解を助けることのみを目的としており、このページ上の画像の出典や許可を証明するものではありません。

写真や素材の使用範囲については、[コンテンツ説明](../content-policy.md)をご覧ください。 [50 個のテンプレートをすべて表示します (](../prompts.md))。
