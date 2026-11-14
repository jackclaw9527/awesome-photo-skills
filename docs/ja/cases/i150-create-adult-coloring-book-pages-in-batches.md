# 大人のぬりえ · 大人のぬりえ

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


テキストだけから、指定した概要に関する大人のぬりえページを 1 つ作成します。

大人の塗り絵ページをバッチ生成します。 Etsy の場合は、KDP。

[プロンプトをコピー](#public-prompt) · [ は dearsketch によって作成されています / オンラインで試してください](https://dearsketch.com/ja/intent/i150-create-adult-coloring-book-pages-in-batches.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i150_cta) · [トピックに戻る / コレクション](../guides/text-only.md)

## 参考資料と結果の方向性

<p><strong>結果の例</strong></p>
<p><a href="https://dearsketch.com/ja/intent/i150-create-adult-coloring-book-pages-in-batches.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i150_image"><img src="../../../assets/cases/i150-after.webp" alt="大人のためのぬり絵 - 結果サンプル" width="320"></a></p>
<p>この例はテキスト入力であり、画像参照は添付されていません。</p>

参考資料と結果は、視覚的な方向性を説明するために使用されます。公開テンプレートは、添付画像のオリジナルの生成指示ではなく、同じ結果が再現されることは保証されません。

## 準備するもの・入力内容

| 素材 / Material | 種類・タイプ | 数量・個数 | 条件 / Requirement |
| --- | --- | --- | --- |
| テキスト作成概要: プロンプトワードにテーマ、目的、事実パラメータを入力します。 | 文字 / Text | 1食分 | 必須 / 必須 |

**純粋なテキストの生成 / テキストのみ: 画像、ロゴ、スケッチ、その他の添付ファイルは必要ありません。** 新しいコンセプトを作成するには、以下のテキスト概要のみを使用してください。

一度に生成される画像は 1 つだけなので、画像をアップロードする必要はありません。

## 保持および変更 / 編集概要

- **保持 / 保持：** 提供された書面による事実、正確な表現および制約を尊重します。
- **変更/修正：** 白地にくっきりとした黒のアウトライン、[DETAIL DENSITY] とバランスの取れた [COMPOSITION] を使用します。図形をきれいに閉じて、色を付けるのに十分な大きさの領域を残します。シェーディングやグレーの塗りつぶしはありません。

## Public prompt

**新しくコンパイルされたパブリック テンプレート · 新しく作成されました · 生成テストされていません。** 角括弧パラメータを置き換えるだけで、参照画像をアップロードする必要はありません。このテンプレートは、このページの例の生成には使用されませんでした。

```text
Create one adult coloring page about [THEME] from the following written brief only. No reference image or other attachment is needed.
Use crisp black outlines on white, [DETAIL DENSITY] and a balanced [COMPOSITION]. Close shapes cleanly and leave regions large enough to color; no shading or gray fill.
Check broken lines, unfillable slivers and print margins; this run delivers one page, not a whole book.
Use an original design. Do not imply fidelity to any existing person, product, property or artwork that has not been supplied.
Return one finished image only. Replace every bracketed field with your own details before generating.
```

[独自の資料を使用してオンラインで作成する / オンラインで作成する](https://dearsketch.com/ja/intent/i150-create-adult-coloring-book-pages-in-batches.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i150_after-prompt) · [エージェントに整理を手伝ってもらう / スキルを使用する](../quickstart.md#agent-skill)

## 要点確認・復習

破線、塗りつぶせない部分、印刷余白をチェックします。この実行では、本全体ではなく 1 ページが配信されます。

破線、塗りつぶせない部分、印刷余白をチェックします。この実行では、本全体ではなく 1 ページが配信されます。

結果の方向性: 大人向けの塗り絵。正確なテキスト、透明ファイル、ベクター、または印刷配信が必要な場合は、実際のファイルを確認してください。利用可能な機能と料金はウェブサイトの説明に準じます。

## 関連事例・関連タスク

- [YouTube またはストリーミング用のプロフィール写真を作成する · テキスト生成されたチャンネル アバター ](./i054-create-a-profile-picture-for-youtube-or-streaming.md#public-prompt)
- [テキストからカスタム絵文字を作成 · カスタム絵文字](./i057-create-a-custom-emoji-from-text.md#public-prompt)
- [衣料品用のシームレスなプリントと生地のパターンを作成する · ](./i100-create-seamless-prints-and-fabric-patterns-for-clothing.md#public-prompt)

## 要件の背景リファレンス

- [Etsy AI 塗り絵 ](https://www.etsy.com/market/ai_coloring_book)

これらのリンクは、目的の理解を助けることのみを目的としており、このページ上の画像の出典や許可を証明するものではありません。

写真や素材の使用範囲については、[コンテンツ説明](../content-policy.md)をご覧ください。 [100 個のテンプレートをすべて表示 ](../prompts.md)。
