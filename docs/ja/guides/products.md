# 製品写真の編集と e コマースのプロンプト · 製品写真の編集と e コマースの表示

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


同じ商品を維持しながら、きれいな出品画像、ライフスタイルのシーン、モデルの服装のプレビュー、商品情報のレイアウトなど、表示方法を変更します。製品の形状、色、ラベルの正確さは、装飾効果よりも重要です。

まず製品の構造、カラーマッチング、ラベルを確認し、次に照明とシーンを確認します。寸法、セールスポイント、仕様は本物の情報を使用しています。透明な背景と印刷配信はドキュメント自体で確認する必要があります。

## 適切なタスクを選択してください

鮮明な商品写真を提供してください。情報レイアウトの寸法、承認されたクレーム、および正確なコピーを追加します。モデル上の画像として実際の衣服を提供します。魅力的なレンダリングは適切ではありません。

| タスク | 保存する | 変化 | プロンプトと入力 |
| --- | --- | --- | --- |
| 白背景商品リスト画像 / 商品白背景メイン画像 | 製品の形状、比率、色、ラベル、表面の詳細、および付属の部品を維持します。 | 背景、トリミング、照明バランス、影の抑制を変更します。 | [I065](../cases/i065-turn-an-ordinary-product-photo-into-a-white-background-listing-image.md#public-prompt) |
| Transparent-Background Product Asset / 透明底商品素材 | 製品の端、開口部、ラベル、色、透明または反射の細部をすべて維持します。 | 背景の削除、エッジのクリーンアップ、およびオプションのニュートラル シャドウ処理のみを変更します。 | [I066](../cases/i066-create-a-reusable-product-png-with-a-transparent-background.md#public-prompt) |
| ライフスタイルプロダクトシーン/商品ライフスタイルシーン | 製品モデル、形状、色、ラベル、材質、比率を維持します。 | 環境、スタイル、ライト、カメラのコンテキスト、およびサポートする小道具を変更します。 | [I067](../cases/i067-place-a-product-in-a-realistic-lifestyle-scene.md#public-prompt) |
| スタジオ製品写真 / 製品スタジオ写真 | ジオメトリ、ラベル、色、マテリアル、テクスチャ、および含まれるコンポーネントを保持します。 | 背景、照明の配置、カメラの磨き、影の処理を変更します。 | [I068](../cases/i068-turn-an-ordinary-photo-into-a-professional-studio-product-shot.md#public-prompt) |
| 季節商品キャンペーンイメージ／お祭りグッズ風景 | 製品のアイデンティティ、デザイン、ラベル、色、提供されたプロモーション情報を保持します。 | 装飾、背景、ライト、パレット、キャンペーン構成を変更します。 | [I069](../cases/i069-create-christmas-black-friday-or-seasonal-product-imagery.md#public-prompt) |
| 飲食コマーシャル画像 / 飲食コマーシャル写真 | 実際の部分、成分、パッケージ、外観を写真ブランチに保存します。 | メッキ、セット、照明、背景、カメラの処理を変更します。 | [I080](../cases/i080-create-commercial-photography-for-food-cakes-pizza-or-drinks.md#public-prompt) |
| 平らな衣服からモデル上の画像へ / 衣服の平らな画像からモデルの上半身画像へ | シルエット、構造、色、プリント、生地の特徴、トリム、ブランディングを維持します。 | プレゼンテーションを平面レイアウトからモデル、ポーズ、設定、照明に変更します。 | [I089](../cases/i089-turn-flat-lay-clothing-into-an-on-model-image.md#public-prompt) |
| 製品インタラクションイメージ / 製品インタラクションイメージ | 製品のデザイン、サイズのヒント、ラベル、色、機能の真実を維持します。 | 手を変更し、ユーザーのコンテキスト、環境、カメラの角度、光を変更します。 | [I075](../cases/i075-show-a-product-being-held-or-used.md#public-prompt) |
| 製品特徴インフォグラフィック / 製品セールスポイントインフォグラフィック | 製品の外観、提供されたすべての数量、単位、および表示内容を正確に保ちます。 | レイアウト、吹き出し、アイコン、階層、およびサポートする背景を変更します。 | [I076](../cases/i076-create-a-product-infographic-with-dimensions-features-and-specifications.md#public-prompt) |
| Eコマース詳細ページのビジュアルドラフト / Eコマース詳細ページのビジュアルドラフト | すべての製品ビューに一貫性を保ち、提供されるすべての主張と文言を正確に保ちます。 | セクションの順序、グラフィック階層、背景、吹き出し、ライフスタイルのコンテキストを変更します。 | [I077](../cases/i077-create-a-long-form-e-commerce-detail-image-from-product-information.md#public-prompt) |

## 参考資料と結果の方向性

### 白背景の商品リスト画像

<table>
<thead><tr><th width="50%">参考資料</th><th width="50%">結果例</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>携帯電話で撮影した商品写真</strong><br><img src="../../../assets/cases/i065-before-1.webp" alt="普通の商品写真を白背景の出品画像に変える — 参考写真 1" width="280"></p></td><td valign="top"><a href="https://dearsketch.com/ja/intent/i065-turn-an-ordinary-product-photo-into-a-white-background-listing-image.html?utm_source=github&amp;utm_medium=guide&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i065_image"><img src="../../../assets/cases/i065-after.webp" alt="普通の商品写真を白背景の出品画像に変える — 結果例" width="280"></a></td></tr></tbody>
</table>

[プロンプトを読んで要件を入力してください](../cases/i065-turn-an-ordinary-product-photo-into-a-white-background-listing-image.md#public-prompt) · [独自のマテリアルで試してください](https://dearsketch.com/ja/intent/i065-turn-an-ordinary-product-photo-into-a-white-background-listing-image.html?utm_source=github&utm_medium=guide&utm_campaign=dearsketch-public-cases&utm_content=i065_cta)

### ライフスタイルプロダクトシーン

<table>
<thead><tr><th width="50%">参考資料</th><th width="50%">結果例</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>製品白背景画像</strong><br><img src="../../../assets/cases/i067-before-1.webp" alt="リアルな生活シーンに商品を配置 参考写真1" width="280"></p></td><td valign="top"><a href="https://dearsketch.com/ja/intent/i067-place-a-product-in-a-realistic-lifestyle-scene.html?utm_source=github&amp;utm_medium=guide&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i067_image"><img src="../../../assets/cases/i067-after.webp" alt="リアルな生活シーンに商品を配置 結果例" width="280"></a></td></tr></tbody>
</table>

[プロンプトを読んで要件を入力してください](../cases/i067-place-a-product-in-a-realistic-lifestyle-scene.md#public-prompt) · [独自のマテリアルで試してください](https://dearsketch.com/ja/intent/i067-place-a-product-in-a-realistic-lifestyle-scene.html?utm_source=github&utm_medium=guide&utm_campaign=dearsketch-public-cases&utm_content=i067_cta)

これらは視覚的な例です。公開テンプレートは新しく作成されたもので、画像の入力に対してテストされていません。出力を使用する前に、ID、コンテンツ、およびファイルの要件を確認してください。画像用語: [コンテンツ ポリシー](../content-policy.md)。
