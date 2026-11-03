# クイックスタート・ケースを選択し、素材を変更し、画像を作成します

[中文](../../README.md) · [English](../../README.en.md) · [Português](../../README.pt.md) · [Español](../../README.es.md) · [Français](../../README.fr.md) · [Deutsch](../../README.de.md) · [عربي](../../README.ar.md) · [русский](../../README.ru.md) · [日本語](../../README.ja.md) · [हिंदी](../../README.hi.md)


## プロンプトをコピーする

1. [50 テンプレート ](./prompts.md) からタスクを選択し、ケース ページを開きます。
2. 条件付き材料が適用されるかどうかを確認するには、材料テーブルに必要な入力を準備します。
3. Public prompt をコピーし、角かっこ内の内容を置き換えます。画像編集が必要な場合は、対応する画像をツールに添付します。テキストは実際の添付画像を置き換えることはできません。
4. 一度に 1 つの結果を生成し、そのケースのチェックポイントに従って結果を受け入れます。

テンプレートを選択し、画像ツールに必要な素材を添付し、プレースホルダーを入力して、結果を確認します。これらは新しい public prompt であり、デモ イメージのテスト済みの複製ではありません。

## Agent Skill

スキルは、「何をしたいのか」を明確な入力リストに変換し、キーポイントと完全なプロンプトワードを保持する責任を負い、デフォルトでは支払いインターフェースを呼び出しません。これには 50 個のテンプレートの独自の参照が含まれており、一度インストールされたライブラリ全体には依存しません。

### Codex

Codex の組み込みインストーラーを使用して、このウェアハウスのスキル ディレクトリを指定します。

```text
$skill-installer install the photo-editing skill from
https://github.com/jackclaw9527/awesome-photo-skills/tree/main/skills/photo-editing
```

ウェアハウスをダウンロードまたは複製して、完全な `skills/photo-editing` フォルダーをターゲット プロジェクトの `.agents/skills/` の下に置くこともできます。同名のスキルが存在する場合は、内容を比較してください。

次に、次を使用します。

```text
$photo-editing 把我的自拍做成自然的职业头像。
先告诉我需要哪些素材，再给我可复制的提示词。
```

英語の例:

```text
Use $photo-editing to prepare a clean product listing image.
Keep the exact product, tell me what to attach and return a complete prompt.
```

スキル カタログとインストーラーの使用方法は、[公式 OpenAI ドキュメント ](https://learn.chatgpt.com/docs/build-skills) に基づいています。 Agent Skill をサポートする他のツールの場合は、それぞれのスキル ディレクトリのルールに従ってフォルダー全体をインストールしてください。

## dearsketch で成功しましょう

自分でプロンプトワードを整理したくない場合は、対応するタスクを直接開き、Web サイトの要件に従って独自の素材を提供できます。

| ゴール | 直接タスク |
| --- | --- |
| Selfie → プロのヘッドショット / プロのヘッドショット | [スタート](https://dearsketch.com/ja/intent/i001-create-a-professional-linkedin-headshot-from-a-selfie.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i001_headshot) |
| ペットの写真 → アーティスティックポートレート / ペットのポートレート | [スタート](https://dearsketch.com/ja/intent/i026-turn-a-pet-photo-into-a-custom-portrait.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i026_pet) |
| 商品写真→白背景の商品画像 | [スタート](https://dearsketch.com/ja/intent/i065-turn-an-ordinary-product-photo-into-a-white-background-listing-image.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i065_product) |
| 部屋の写真 → 装飾プレビュー / 部屋の模様替え | [スタート](https://dearsketch.com/ja/intent/i169-preview-different-interior-styles-in-a-room-photo.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i169_room) |

ウェブサイトは独自の制作プロセスを維持しています。公開スキルでは、Web サイトのアカウントやサービス キーを引き渡す必要はなく、無料の生成割り当ても含まれません。利用できる機能や料金については、Webサイト上のその時点の記載に準じます。
