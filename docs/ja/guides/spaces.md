# インテリア、住宅、建築のイメージ プロンプト · 住宅、インテリア、建築のビジョン

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


部屋の再設計、仮想ステージング、家のポートレート、またはスケッチからレンダリングのコンセプトを探索します。これらのタスクにはさまざまな境界があります。ステージングでは家具を追加し、リスティングのクリーンアップでは散らかったものを取り除き、デザインコンセプトでは将来のスペースの可能性を探ります。

まず、変更できないドア、窓、壁、境界線、備品を説明し、次に試したい素材とスタイルを指定します。レンダリングは方向性を伝えるために使用され、寸法、材質、施工可能性は別途確認する必要があります。

## 適切なタスクを選択してください

編集には鮮明な部屋または外観の写真、レンダリングには読みやすいスケッチ、指定されたペイントまたは表面製品の正確な見本を使用します。リストで使用する場合は、仮想的にステージングされたイメージをマークします。

| タスク | 保存する | 変化 | プロンプトと入力 |
| --- | --- | --- | --- |
| ハウス水彩記念品 / ハウス水彩記念絵画 | 屋根のライン、ドア、窓、ファサードのプロポーション、特徴的な敷地の特徴を維持します。 | 媒体、背景の単純化、景観の強調、およびパレットを変更します。 | [I030](../cases/i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.md#public-prompt) |
| ルームスタイルプレビュー / ルームデコレーションスタイルプレビュー | 壁、ドア、窓、天井、固定開口部、カメラの視点を維持します。 | 家具、仕上げ、装飾、パレット、照明の雰囲気を変更します。 | [I169](../cases/i169-preview-different-interior-styles-in-a-room-photo.md#public-prompt) |
| 庭の景観コンセプト / 中庭の景観改修 | 敷地境界、建物、勾配、アクセス、固定構造物を維持します。 | 植栽、舗装、家具、照明、アメニティのコンセプトを変更します。 | [I178](../cases/i178-create-a-landscape-makeover-concept-from-a-yard-photo.md#public-prompt) |
| 塗装、床材、壁紙のプレビュー / 壁塗装と床材の選択プレビュー | 部屋の構造、照明ロジック、オブジェクトの配置、および対象外の表面を維持します。 | 名前付きの壁、床、または壁紙の領域のみを変更します。 | [I171](../cases/i171-preview-wall-paint-flooring-and-wallpaper.md#public-prompt) |
| オフィスリニューアルコンセプト / オフィスリニューアルコンセプト | 現場の写真が提供された場合にのみ、目に見える構造と制約を維持します。 | ワークステーション、ゾーン、家具、ブランド、仕上げ、照明を変更します。 | [I172](../cases/i172-create-an-office-redesign-concept.md#public-prompt) |
| 空の部屋の仮想ステージング / 空の部屋の仮想ステージング | 実際の建築、部屋の状態、窓、ドア、カメラのビューを保持します。 | 可動家具、装飾品、ソフトグッズ、照明演出のみを変更します。 | [I175](../cases/i175-virtually-stage-an-empty-property-with-furniture-and-decor.md#public-prompt) |
| 整理整頓された物件の写真/整理整頓された物件の写真 | レイアウト、固定要素、表面、照明、および材料の欠陥を維持します。 | リストされた移動可能な乱雑な要素のみを削除し、制限されたプレゼンテーションの修正を行います。 | [I176](../cases/i176-turn-a-casual-room-photo-into-a-polished-property-listing-image.md#public-prompt) |
| 建築ファサードコンセプト / 建物ファサードコンセプト | スケッチまたはマス参照が存在する場合にのみ、指定されたマスと開口部を保持します。 | ファサードの素材、調音、環境、景観、光を変更します。 | [I177](../cases/i177-create-an-architectural-facade-concept-from-text-or-a-sketch.md#public-prompt) |
| スケッチからリアルな空間レンダリング / 建築スケッチからリアルな効果へ | 開口部、ジオメトリ、レイアウト関係、カメラのフレームを維持します。 | 素材、照明、家具、風景、雰囲気を変更します。 | [I179](../cases/i179-turn-an-interior-or-architectural-sketch-into-a-realistic-render.md#public-prompt) |
| インテリアまたは建築のムードボード / 空間デザインのムードボード | 参照が存在する場合にのみ、指定された参照カラーとマテリアル ID を保持します。 | レイアウト、階層、トリミング、注釈、およびサポートされる生成されたスウォッチを変更します。 | [I182](../cases/i182-create-a-mood-board-for-an-architecture-or-interior-project.md#public-prompt) |

## 参考資料と結果の方向性

### ルームスタイルのプレビュー

<table>
<thead><tr><th width="50%">参考資料</th><th width="50%">結果例</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>既存のお部屋の写真</strong><br><img src="../../../assets/cases/i169-before-1.webp" alt="部屋の写真でさまざまなインテリア スタイルをプレビュー — 参考写真 1" width="280"></p></td><td valign="top"><a href="https://dearsketch.com/ja/intent/i169-preview-different-interior-styles-in-a-room-photo.html?utm_source=github&amp;utm_medium=guide&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i169_image"><img src="../../../assets/cases/i169-after.webp" alt="部屋の写真でさまざまなインテリア スタイルをプレビュー — 結果の例" width="280"></a></td></tr></tbody>
</table>

[プロンプトを読んで要件を入力してください](../cases/i169-preview-different-interior-styles-in-a-room-photo.md#public-prompt) · [独自のマテリアルで試してください](https://dearsketch.com/ja/intent/i169-preview-different-interior-styles-in-a-room-photo.html?utm_source=github&utm_medium=guide&utm_campaign=dearsketch-public-cases&utm_content=i169_cta)

### ハウス水彩記念品

<table>
<thead><tr><th width="50%">参考資料</th><th width="50%">結果例</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>家の写真</strong><br><img src="../../../assets/cases/i030-before-1.webp" alt="家の写真を水彩画または線画の記念品に変える — 参考写真 1" width="280"></p></td><td valign="top"><a href="https://dearsketch.com/ja/intent/i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.html?utm_source=github&amp;utm_medium=guide&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i030_image"><img src="../../../assets/cases/i030-after.webp" alt="家の写真を水彩画または線画の記念品に変える — 結果例" width="280"></a></td></tr></tbody>
</table>

[プロンプトを読んで要件を入力してください](../cases/i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.md#public-prompt) · [独自のマテリアルで試してください](https://dearsketch.com/ja/intent/i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.html?utm_source=github&utm_medium=guide&utm_campaign=dearsketch-public-cases&utm_content=i030_cta)

これらは視覚的な例です。公開テンプレートは新しく作成されたもので、画像の入力に対してテストされていません。出力を使用する前に、ID、コンテンツ、およびファイルの要件を確認してください。画像用語: [コンテンツ ポリシー](../content-policy.md)。
