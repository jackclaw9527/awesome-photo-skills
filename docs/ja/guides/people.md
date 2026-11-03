# ポートレートおよび個人的な写真の編集プロンプト · ポートレートの編集および個人的なイメージ

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


プロの顔写真、ターゲットを絞った服装の編集、仮想試着、またはイラスト付きのアイデンティティからお選びください。顔写真では自然な顔の特徴が保たれている必要があります。漫画は人物を認識し続けながら、媒体を変えることができます。

まず、衣服、アクセサリー、背景、または画像全体のプレゼンテーションを変更するかどうかを決定します。指定されたメガネやタトゥーのデザインを試着する場合は、漠然としたスタイルワードだけではなく、対応するオリジナルを提供する必要があります。

## 適切なタスクを選択してください

ローカル編集の場合は、変更する正確な領域と変更しないでおきたい領域に名前を付けます。特定のアクセサリーやタトゥーについては、その参照情報と人物の写真を添付し​​てください。

| タスク | 保存する | 変化 | プロンプトと入力 |
| --- | --- | --- | --- |
| セルフィーからのプロのヘッドショット / セルフィーからプロのヘッドショットへ | アイデンティティ、顔の形状、肌の色合い、年齢の手がかり、自然な質感を維持します。 | トリミング、背景、照明、プロ仕様のワードローブ スタイルを変更します。 | [I001](../cases/i001-create-a-professional-linkedin-headshot-from-a-selfie.md#public-prompt) |
| カジュアルな服装をプロフェッショナルな服装に置き換える / カジュアルな服装をプロフェッショナルな服装に置き換える | 要求されない限り、身元、顔、髪、ポーズ、体型、手、背景を保持します。 | 衣類のタイプ、色、フィット感、目に見えるアクセサリーを変更します。 | [I015](../cases/i015-replace-casual-clothing-with-professional-attire.md#public-prompt) |
| 歴史にインスピレーションを得た個人的なポートレート / 王室およびヴィンテージのポートレート | その人のアイデンティティ、年齢の手がかり、肌の色、顔の構造を維持します。 | 衣装、背景、小道具、照明、時代風の雰囲気を変更します。 | [I052](../cases/i052-turn-yourself-into-a-royal-vintage-or-historical-portrait.md#public-prompt) |
| バーチャルメガネプレビュー/メガネ試着プレビュー | アイデンティティ、顔の形、肌、目、および選択したブランチに指定されたフレームの詳細を保持します。 | フレームの配置、レンズの外観、最小限の照明の統合のみを変更します。 | [I036](../cases/i036-virtually-try-on-glasses.md#public-prompt) |
| タトゥー配置プレビュー / タトゥー上半身プレビュー | 人物、肌の質感、身体の構造、タトゥーのアートワークを変更しないでください。 | 配置、スケール、曲率、不透明度、統合のみを変更します。 | [I038](../cases/i038-preview-a-tattoo-on-a-body-photo.md#public-prompt) |
| ポートレートから漫画のアバター / 写真から漫画のアバターへ | 顔の形、髪、肌の色合い、目に見える特徴的なアクセサリーを維持します。 | レンダリング言語、簡略化、背景、パレットを変更します。 | [I047](../cases/i047-turn-a-portrait-photo-into-a-cartoon-avatar.md#public-prompt) |
| アニメにインスパイアされたアバター / アニメキャラクターの写真 | 顔の形、肌の色、髪、目の関係、アクセサリーの定義を維持します。 | 線画、シェーディング、パレット、背景、スタイルレベルを変更します。 | [I048](../cases/i048-turn-a-portrait-photo-into-an-anime-character.md#public-prompt) |
| パッケージアクションフィギュアコンセプト / パッケージアクションフィギュア | 本人の身元と要求された付属品リストを保管してください。 | 玩具のようなフィギュアへのボディ変更、パッケージング、カラーシステム、ディスプレイレイアウト。 | [I050](../cases/i050-turn-a-person-into-a-packaged-action-figure.md#public-prompt) |
| シングルチャットスタンプ / 写真からチャットスタンプ | 被写体を認識可能な状態に保ち、特徴的なマークや特徴を保持します。 | 表情の変更、ポーズの強調、輪郭、背景の除去、ステッカーのスタイル変更。 | [I056](../cases/i056-turn-a-photo-into-chat-stickers.md#public-prompt) |
| パーソナライズされた映画ポスター / 個人およびカップルの映画ポスター | すべての人の身元と確認されたすべての請求テキストを保管します。 | 映画の設定、ジャンルの扱い、照明、構成、タイポグラフィのコンセプトを変更します。 | [I252](../cases/i252-turn-a-personal-or-couple-photo-into-a-movie-poster.md#public-prompt) |

## 参考資料と結果の方向性

### 自撮り写真からのプロの顔写真

<table>
<thead><tr><th width="50%">参考資料</th><th width="50%">結果例</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>元の写真は知っています</strong><br><img src="../../../assets/cases/i001-before-1.webp" alt="自撮り写真からプロの LinkedIn 顔写真を作成します — 参考写真 1" width="280"></p></td><td valign="top"><a href="https://dearsketch.com/ja/intent/i001-create-a-professional-linkedin-headshot-from-a-selfie.html?utm_source=github&amp;utm_medium=guide&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i001_image"><img src="../../../assets/cases/i001-after.webp" alt="自撮り写真からプロの LinkedIn 顔写真を作成する — 結果の例" width="280"></a></td></tr></tbody>
</table>

[プロンプトを読んで要件を入力してください](../cases/i001-create-a-professional-linkedin-headshot-from-a-selfie.md#public-prompt) · [独自のマテリアルで試してください](https://dearsketch.com/ja/intent/i001-create-a-professional-linkedin-headshot-from-a-selfie.html?utm_source=github&utm_medium=guide&utm_campaign=dearsketch-public-cases&utm_content=i001_cta)

### 肖像画からの漫画のアバター

<table>
<thead><tr><th width="50%">参考資料</th><th width="50%">結果例</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>自分の頭のイメージがはっきりしている</strong><br><img src="../../../assets/cases/i047-before-1.webp" alt="ポートレート写真を漫画のアバターに変える — 参考写真 1" width="280"></p></td><td valign="top"><a href="https://dearsketch.com/ja/intent/i047-turn-a-portrait-photo-into-a-cartoon-avatar.html?utm_source=github&amp;utm_medium=guide&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i047_image"><img src="../../../assets/cases/i047-after.webp" alt="ポートレート写真を漫画のアバターに変える — 結果例" width="280"></a></td></tr></tbody>
</table>

[プロンプトを読んで要件を入力してください](../cases/i047-turn-a-portrait-photo-into-a-cartoon-avatar.md#public-prompt) · [独自のマテリアルで試してください](https://dearsketch.com/ja/intent/i047-turn-a-portrait-photo-into-a-cartoon-avatar.html?utm_source=github&utm_medium=guide&utm_campaign=dearsketch-public-cases&utm_content=i047_cta)

これらは視覚的な例です。公開テンプレートは新しく作成されたもので、画像の入力に対してテストされていません。出力を使用する前に、ID、コンテンツ、およびファイルの要件を確認してください。画像用語: [コンテンツ ポリシー](../content-policy.md)。
