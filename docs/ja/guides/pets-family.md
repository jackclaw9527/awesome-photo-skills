# ペットのポートレートと家族の写真のプロンプト · ペットのポートレートと家族の記念碑

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


すべての被写体を認識できるようにしながら、ペットや家族の写真をポートレートや記念品に変えます。単一の被写体のポートレート、カップルのアートワーク、または別々の写真を組み合わせた合成写真を選択します。

ペットのポートレートの場合は、目、耳の形、パターンを最初に保存する必要があります。複数人で合成する場合は、すべてのメンバー、関係、取り決めを最初にリストする必要があります。記念の日付と碑文はあなたが提供したものであり、写真から推測しないでください。

## 適切なタスクを選択してください

ペットのポートレートはペットの写真1枚で十分です。家族構成には、含めたいすべての人またはペットが必要です。名前や日付を入れた記念品の場合は、正確な文言を別途入力してください。

| タスク | 保存する | 変化 | プロンプトと入力 |
| --- | --- | --- | --- |
| カスタムペットポートレート / ペットカスタムポートレート | ペットの身元、模様、目の色、耳の形、体の比率を記録します。 | 設定、照明、パレット、芸術的な処理を変更します。 | [I026](../cases/i026-turn-a-pet-photo-into-a-custom-portrait.md#public-prompt) |
| ロイヤルペットのポートレート / ロイヤルペットのポートレート | ペットの顔、毛並み、目の色、種特有の解剖学的構造を記録します。 | 服装、小道具、背景、時代を感じさせる雰囲気を変更します。 | [I028](../cases/i028-turn-a-pet-into-a-royal-or-historical-portrait.md#public-prompt) |
| Playful Pet Scene / ペットの楽しいシーンの絵画 | 身元、毛皮の模様、解剖学的構造、スケールの一貫性を保ちます。 | 環境、ポーズのコンテキスト、遊び心のある小道具を変更します。 | [I029](../cases/i029-place-a-pet-in-a-playful-bathroom-or-kitchen-scene.md#public-prompt) |
| ペットメモリアルポートレイト / ペットメモリアルペインティング | ペットの身元、提供されたすべての名前と日付を正確に保ちます。 | 背景、光、花のディテール、記念ムードを変更します。 | [I027](../cases/i027-create-a-pet-memorial-portrait.md#public-prompt) |
| ペットとの家族ポートレート / 人とペットの家族ポートレート | 正しいカウントとマーキングにより、すべての人やペットを個別に認識できるようにします。 | 共有設定、ワードローブのコーディネート、照明、配置を変更します。 | [I021](../cases/i021-create-a-family-portrait-with-pets.md#public-prompt) |
| アニバーサリーカップルアートワーク / カップルアニバーサリーアートペインティング | アイデンティティ、関係性、ポーズのロジック、確認された名前または日付の両方を保持します。 | 芸術的な媒体、背景、パレット、お祝いの詳細を変更します。 | [I022](../cases/i022-turn-a-couple-s-photo-into-anniversary-artwork.md#public-prompt) |
| 家族ポートレートの合成 / 散らばった写真を家族ポートレートに合成 | 提供されたすべての ID、要求された数、関係、および配置を保持します。 | 共有設定、ポーズの統合、ライト、およびコーディネートされたスタイルを変更します。 | [I017](../cases/i017-combine-separate-family-photos-into-one-family-portrait.md#public-prompt) |
| ホリデーファミリーポートレート / ホリデーをテーマにした家族ポートレート | すべての人物、アイデンティティ、カウント、および隠されていない顔の特徴を保持します。 | 装飾、ワードローブのアクセント、背景、休日の雰囲気を変更します。 | [I020](../cases/i020-create-a-christmas-or-holiday-family-portrait.md#public-prompt) |
| ウェディングスタイルのカップルポートレート / 結婚式とウェディングスタイルのポートレート | アイデンティティ、自然な関係性、体のプロポーションの両方を維持します。 | ワードローブ、セッティング、花のスタイリング、セレモニーの雰囲気を変えてみましょう。 | [I023](../cases/i023-create-a-wedding-portrait-or-bridal-style-photo.md#public-prompt) |
| 赤ちゃんのマイルストーンポートレート / 赤ちゃんの成長のマイルストーン写真 | 赤ちゃんの身元、年齢に応じた解剖学的構造、確認されたマイルストーンの文言を維持します。 | 背景、小道具、カラーパレット、お祝いのレイアウトを変更します。 | [I025](../cases/i025-create-baby-milestone-or-monthly-growth-photos.md#public-prompt) |

## 参考資料と結果の方向性

### ロイヤルペットの肖像画

<table>
<thead><tr><th width="50%">参考資料</th><th width="50%">結果例</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>ペットの写真</strong><br><img src="../../../assets/cases/i028-before-1.webp" alt="ペットを王室または歴史上の肖像画に変える — 参考写真 1" width="280"></p></td><td valign="top"><a href="https://dearsketch.com/ja/intent/i028-turn-a-pet-into-a-royal-or-historical-portrait.html?utm_source=github&amp;utm_medium=guide&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i028_image"><img src="../../../assets/cases/i028-after.webp" alt="ペットを王室または歴史上の肖像画に変える — 結果例" width="280"></a></td></tr></tbody>
</table>

[プロンプトを読んで要件を入力してください](../cases/i028-turn-a-pet-into-a-royal-or-historical-portrait.md#public-prompt) · [独自のマテリアルで試してください](https://dearsketch.com/ja/intent/i028-turn-a-pet-into-a-royal-or-historical-portrait.html?utm_source=github&utm_medium=guide&utm_campaign=dearsketch-public-cases&utm_content=i028_cta)

### 家族の複合ポートレート

<table>
<thead><tr><th width="50%">参考資料</th><th width="50%">結果例</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>統合される個々のメンバーの写真</strong><br><img src="../../../assets/cases/i017-before-1.webp" alt="別々の家族写真を 1 枚の家族ポートレートに結合します — 参考写真 1" width="280"></p>
<p><strong>すでに家族が写真を撮っています</strong><br><img src="../../../assets/cases/i017-before-2.webp" alt="別々の家族写真を 1 枚の家族ポートレートに結合します — 参考写真 2" width="280"></p></td><td valign="top"><a href="https://dearsketch.com/ja/intent/i017-combine-separate-family-photos-into-one-family-portrait.html?utm_source=github&amp;utm_medium=guide&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i017_image"><img src="../../../assets/cases/i017-after.webp" alt="別々の家族の写真を 1 つの家族のポートレートに結合する — 結果の例" width="280"></a></td></tr></tbody>
</table>

[プロンプトを読んで要件を入力してください](../cases/i017-combine-separate-family-photos-into-one-family-portrait.md#public-prompt) · [独自のマテリアルで試してください](https://dearsketch.com/ja/intent/i017-combine-separate-family-photos-into-one-family-portrait.html?utm_source=github&utm_medium=guide&utm_campaign=dearsketch-public-cases&utm_content=i017_cta)

これらは視覚的な例です。公開テンプレートは新しく作成されたもので、画像の入力に対してテストされていません。出力を使用する前に、ID、コンテンツ、およびファイルの要件を確認してください。画像用語: [コンテンツ ポリシー](../content-policy.md)。
