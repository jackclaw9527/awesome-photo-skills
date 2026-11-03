# ポートレートと個人的なスタイル

[中文](../../../../README.md) · [English](../../../../README.en.md) · [Português](../../../../README.pt.md) · [Español](../../../../README.es.md) · [Français](../../../../README.fr.md) · [Deutsch](../../../../README.de.md) · [عربي](../../../../README.ar.md) · [русский](../../../../README.ru.md) · [日本語](../../../../README.ja.md) · [हिंदी](../../../../README.hi.md)


プロのポートレート、服装編集、仮想プレビュー、アバター、ステッカー、ポスターのコンセプト。これらは新しく作成された、テストされていない公開テンプレートです。ユーザーが指定した事実や資料を使用して括弧で囲まれたプレースホルダーをカスタマイズします。これらをリポジトリのサンプルを生成したプロンプトとして説明しないでください。

## 自撮り写真からのプロの顔写真 (I001)

1 枚の鮮明な自撮り写真を、信頼できるプロの顔写真に変えます。

- **入力:** 元の写真を理解しています — 必須
- **保存:** アイデンティティ、顔の形状、肌の色合い、年齢の手がかり、自然な質感を保存します。
- **変更:** トリミング、背景、照明、プロフェッショナルなワードローブ スタイルを変更します。
- **確認:** 認識可能性を確認し、捏造された制服、資格情報、または過度の修正を避けてください。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i001-create-a-professional-linkedin-headshot-from-a-selfie.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i001_prompt_i001)

```text
Create one professional headshot from [CLEAR SELFIE].
Preserve the person’s exact identity, facial geometry, skin tone, age cues, hairline, and natural skin texture.
Use a [HEAD-AND-SHOULDERS / HALF-BODY] crop with confident but natural posture.
Replace the background with [NEUTRAL OR WORK-APPROPRIATE BACKGROUND].
Apply soft, realistic [LIGHTING DIRECTION] and balanced color.
Style clothing as [PROFESSIONAL WARDROBE] without adding unrequested uniforms, badges, or credentials.
Keep glasses, facial hair, and visible accessories unless [SPECIFIC CHANGE] is requested.
Avoid face slimming, age reversal, plastic skin, or a generic stock-photo appearance.
Leave appropriate negative space for [PROFILE / RESUME USE].
Deliver one finished headshot image only.
```

---

## カジュアルな服装をプロフェッショナルな服装に置き換える (I015)

ポートレート内の服装のみを指定されたプロの服装に編集します。

- **入力:** カジュアルな服装をした人の肖像画 - 必須
- **保存:** 要求されない限り、身元、顔、髪、ポーズ、体型、手、背景を保存します。
- **変更:** 衣服の種類、色、フィット感、目に見える付属品を変更します。
- **チェック:** 襟、袖口、手、体の端がきれいに統合されているかどうかを検査します。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i015-replace-casual-clothing-with-professional-attire.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i015_prompt_i015)

```text
Edit [PORTRAIT PHOTO] to replace only the casual clothing with [PROFESSIONAL OUTFIT].
Preserve the person’s identity, face, skin tone, hair, expression, pose, body shape, and camera angle.
Keep the original background and lighting unless [BACKGROUND CHANGE] is explicitly requested.
Fit the new garment naturally around the neck, shoulders, torso, arms, and waist.
Use [FABRIC], [COLOR], and [FORMALITY LEVEL] appropriate to [PROFESSIONAL CONTEXT].
Retain or remove visible accessories only according to [ACCESSORY INSTRUCTION].
Do not add uniforms, employer logos, medals, or credentials that were not supplied.
Keep hands, collar, lapels, cuffs, seams, and body edges anatomically clean.
Avoid changing weight, age, makeup, or facial features.
Deliver one edited portrait image only.
```

---

## 歴史にインスピレーションを得た個人的なポートレート (I052)

実在の人物をオリジナルの王室、ビンテージ、または歴史にインスピレーションを得た肖像画として再スタイルします。

- **入力:** 元の写真を理解しています — 必須
- **保存:** その人のアイデンティティ、年齢の手がかり、肌の色、顔の構造を保存します。
- **変更:** 衣装、背景、小道具、照明、時代風の雰囲気を変更します。
- **チェック:** 身元を確認し、フィクションを本物の歴史的な写真として提示することは避けてください。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i052-turn-yourself-into-a-royal-vintage-or-historical-portrait.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i052_prompt_i052)

```text
Create one historical-inspired portrait from [PERSON PHOTO].
Preserve the person’s exact identity, facial proportions, skin tone, age cues, hair, and expression.
Dress the subject in an original [ERA-INSPIRED / ROYAL / VINTAGE] costume.
Use [SETTING], [PROPS], [PALETTE], and [LIGHTING] to support the chosen mood.
Keep garment construction, hands, jewelry, and posture visually coherent.
Do not copy a named artwork, protected character, or living artist’s distinctive style.
Do not add real titles, military honors, lineage, or historical claims unless confirmed.
Treat the result as creative fiction, not an authentic period document.
Include no text unless [EXACT CAPTION] is supplied.
Deliver one finished portrait image only.
```

---

## 仮想アイウェア プレビュー (I036)

正確な製品または説明されたアイウェアのコンセプトを正面のポートレートに配置します。

- **入力:** 人物の正面写真 — 必須。対象となるメガネの素材またはスタイルの説明 - 条件付き (製品を正確に試着するために必要。テキストで説明できるのは概念的なスタイルのみ)
- **保持:** 選択したブランチのアイデンティティ、顔の形、肌、目、および提供されたフレームの詳細を保持します。
- **変更:** フレームの配置、レンズの外観、最小限の照明の統合のみを変更します。
- **チェック:** ブリッジ、テンプル、遠近感をチェックしてください。フィット感と快適さは未検証であることに注意してください。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i036-virtually-try-on-glasses.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i036_prompt_i036)

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

---

## タトゥー配置プレビュー (I038)

付属のタトゥーのデザインを指定された体の領域に適用します。

- **入力:** キャラクターの肌の元の写真 — 必須。ターゲットのタトゥーのデザイン — 必須。タトゥーの位置 — 必須
- **保存:** 人物、肌の質感、身体の構造、タトゥーのアートワークを変更しないでください。
- **変更:** 配置、スケール、曲率、不透明度、統合のみを変更します。
- **チェック:** デザインの詳細と位置を確認します。画像はステンシルまたは医療プレビューではありません。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i038-preview-a-tattoo-on-a-body-photo.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i038_prompt_i038)

```text
Create one tattoo placement preview from [BODY PHOTO] and [TATTOO DESIGN IMAGE].
Place the design at [EXACT BODY LOCATION] with [SIZE] and [ORIENTATION].
Preserve the person’s identity, body anatomy, skin tone, texture, lighting, and pose.
Preserve the tattoo artwork’s line work, symbols, lettering, and proportions exactly.
Warp the design only enough to follow the body’s natural curvature and perspective.
Blend ink with plausible skin interaction while keeping the design readable.
Do not add extra symbols, alter lettering, remove scars, or reshape the body.
Keep boundaries clean and avoid floating, mirrored, or duplicated tattoo elements.
Treat the result as a visual preview, not a tattoo stencil, placement guarantee, or medical advice.
Deliver one edited preview image only.
```

---

## 肖像画からの漫画のアバター (I047)

撮影した人物として認識できるオリジナルの漫画アバターを作成します。

- **入力:** 鮮明な頭の写真があります — 必須
- **保存:** 顔の形、髪、肌の色、目に見える特徴的なアクセサリーを保存します。
- **変更:** レンダリング言語、簡略化、背景、パレットを変更します。
- **チェック:** 一般的な漫画の顔を受け入れるのではなく、認識可能性をチェックします。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i047-turn-a-portrait-photo-into-a-cartoon-avatar.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i047_prompt_i047)

```text
Create one original cartoon avatar from [CLEAR HEAD PHOTO].
Preserve the person’s recognizable face shape, skin tone, hairstyle, hair color, and visible signature accessories.
Translate features into [CARTOON TREATMENT] without replacing them with a generic character face.
Use [EXPRESSION] and a clean [HEADSHOT / BUST] composition.
Choose [COLOR PALETTE] and [BACKGROUND] suitable for [PROFILE OR GIFT USE].
Keep eyes, mouth, ears, glasses, and hairline internally consistent.
Avoid copying a protected character, franchise, or living artist’s distinctive style.
Do not add text, logos, or props unless [EXACT REQUEST] is supplied.
Keep edges clear and the silhouette readable at small avatar size.
Deliver one finished avatar image only.
```

---

## アニメ風のアバター (I048)

個人のアイデンティティを保ちながら、アニメにインスピレーションを得たオリジナルのポートレートを作成します。

- **入力:** 鮮明な頭の写真があります — 必須
- **保存:** 顔の形、肌の色、髪、目の位置、および特徴的なアクセサリーを保存します。
- **変更:** 線画、シェーディング、パレット、背景、様式化レベルを変更します。
- **チェック:** 結果が認識可能であり、コピーされたフランチャイズ キャラクターではないことを確認してください。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i048-turn-a-portrait-photo-into-an-anime-character.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i048_prompt_i048)

```text
Create one original anime-inspired avatar from [CLEAR HEAD PHOTO].
Preserve the person’s recognizable face shape, skin tone, hairstyle, hair color, and defining accessories.
Stylize the features with [LINE QUALITY], [SHADING METHOD], and [DETAIL LEVEL].
Keep the relationship between eyes, nose, mouth, jaw, and hair faithful enough for recognition.
Use [EXPRESSION], [PALETTE], and [BACKGROUND] for [INTENDED USE].
Do not turn the subject into a pre-existing anime or game character.
Do not imitate a named living artist or studio-specific signature look.
Keep anatomy, ears, hands if visible, and clothing edges coherent.
Add no writing unless [EXACT TEXT] is supplied.
Deliver one finished avatar image only.
```

---

## パッケージ化されたアクションフィギュアのコンセプト (I050)

人物を架空のパッケージ化されたアクションフィギュアのコンセプトイメージに変えます。

- **入力:** 人物の写真 — 必須
- **保存:** 個人の身元と要求されたアクセサリのリストを保存します。
- **変更:** 本体をおもちゃのようなフィギュア、パッケージ、カラーシステム、ディスプレイレイアウトに変更します。
- **確認:** 手足と付属品を数え、パッケージのテキストを校正し、コンセプトとしてラベルを付けます。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i050-turn-a-person-into-a-packaged-action-figure.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i050_prompt_i050)

```text
Create one fictional packaged action-figure concept from [PERSON PHOTO].
Preserve the person’s recognizable face, hair, skin tone, and defining clothing cues.
Render a toy-like full figure in [POSE] inside [PACKAGING STYLE].
Include exactly these accessories: [ACCESSORY LIST]; do not duplicate or invent extras.
Use [PACKAGE COLOR SYSTEM] and [BACKGROUND GRAPHICS] with a clear retail-display hierarchy.
If supplied, reproduce the exact package title “[EXACT TITLE]” and subtitle “[EXACT SUBTITLE]”.
Keep limbs, hands, joints, accessory compartments, plastic reflections, and shadows coherent.
Do not use third-party logos, franchise marks, or claims that a physical product exists.
Treat all package lettering as artwork that must be manually proofread.
Deliver one concept image only, not manufacturing artwork or a product specification.
```

---

## シングルチャットステッカー (I056)

人物、ペット、物の写真を表情豊かな 1 枚のステッカーに変えます。

- **入力:** 人物、ペット、または物体の写真 — 必須。このステッカーのアクションまたは感情 - オプション
- **保存:** 被写体を認識可能な状態に保ち、定義的なマーキングや特徴を保持します。
- **変更:** 表情、ポーズの強調、輪郭、背景の削除、ステッカーのスタイルを変更します。
- **確認:** 小さいサイズの読みやすさを確認し、プラットフォームのパッケージ化が別であることを忘れないでください。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i056-turn-a-photo-into-chat-stickers.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i056_prompt_i056)

```text
Create one chat sticker from [SUBJECT PHOTO].
Preserve the subject’s identity, silhouette, colors, markings, and defining features.
Express [ACTION OR EMOTION] through a clear pose and readable facial or object cues.
Use [STICKER STYLE], a bold clean outline, and simple shading suitable for small display.
Keep hands, paws, limbs, and object edges coherent and uncluttered.
Use a transparent-looking or plain preview background according to [BACKGROUND REQUEST].
If text is requested, reproduce “[EXACT SHORT TEXT]” exactly and keep it legible.
Do not create a sheet, pack, or multiple emotional variants in this run.
If a transparent file is required, verify the exported alpha channel rather than trusting a checkerboard preview.
Deliver one sticker image only; platform sizing and pack assembly are separate steps.
```

---

## パーソナライズされた映画ポスター (I252)

提供された人物とタイトルを中心にオリジナルの架空の映画ポスターを作成します。

- **入力内容:** 個人、カップル、またはグループのオリジナル写真 — 必須。元のポスターの件名とタイトル — 必須。署名と日付 — オプション
- **保存:** すべての人の身元と確認されたすべての請求テキストを保存します。
- **変更:** 映画の設定、ジャンルの扱い、照明、構成、タイポグラフィのコンセプトを変更します。
- **チェック:** すべての文言を校正し、実際の映画のリリースを暗示することは避けてください。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i252-turn-a-personal-or-couple-photo-into-a-movie-poster.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i252_prompt_i252)

```text
Create one original fictional movie poster from [PERSON / COUPLE / GROUP PHOTO].
Use the genre and premise [ORIGINAL POSTER CONCEPT] and the exact title “[EXACT MOVIE TITLE]”.
Preserve every supplied person’s identity, count, facial features, skin tone, hair, and relationship.
Compose a cinematic [PORTRAIT / LANDSCAPE] layout with [SETTING], [PALETTE], and [LIGHTING].
If provided, include only the confirmed credit line “[EXACT CREDIT]” and date “[EXACT DATE]”.
Do not invent actors, studios, reviews, awards, ratings, or release claims.
Do not copy an existing movie poster, franchise character, logo, or signature composition.
Keep hands, overlaps, scale, and atmospheric effects coherent.
Treat generated lettering as a draft requiring manual proofreading and final typesetting.
Deliver one poster concept image only, not print-ready production artwork.
```
