# 製品とコマース

[中文](../../../../README.md) · [English](../../../../README.en.md) · [Português](../../../../README.pt.md) · [Español](../../../../README.es.md) · [Français](../../../../README.fr.md) · [Deutsch](../../../../README.de.md) · [عربي](../../../../README.ar.md) · [русский](../../../../README.ru.md) · [日本語](../../../../README.ja.md) · [हिंदी](../../../../README.hi.md)


アセット、透明なカットアウト、ライフスタイルとスタジオの画像、アパレル、食品、製品のインフォグラフィックをリストします。これらは新しく作成された、テストされていない公開テンプレートです。ユーザーが指定した事実や資料を使用して括弧で囲まれたプレースホルダーをカスタマイズします。これらをリポジトリのサンプルを生成したプロンプトとして説明しないでください。

## 白背景の製品リスト画像 (I065)

実際の製品を、きれいなマーケットプレイス スタイルの白い背景の画像に分離します。

- **入力:** 携帯電話で撮影した商品写真 - 必須
- **保存:** 製品の形状、比率、色、ラベル、表面の詳細、および付属の部品を保存します。
- **変更:** 背景、トリミング、照明バランス、影の抑制を変更します。
- **チェック:** ラベルの忠実性とチャンネル固有のリスト要件を検査します。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i065-turn-an-ordinary-product-photo-into-a-white-background-listing-image.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i065_prompt_i065)

```text
Create one white-background listing image from [PRODUCT PHOTO].
Preserve the product’s exact shape, proportions, color, material, label artwork, controls, openings, and included parts.
Remove the original surroundings and place the product on a clean [PURE WHITE / CHANNEL-SPECIFIED] background.
Correct perspective and lighting only enough to present the real product clearly.
Use a restrained contact shadow if permitted by [TARGET MARKETPLACE].
Do not redesign packaging, repair labels, add accessories, or invent product features.
Keep small edges, transparent parts, reflective surfaces, and fine details clean.
Use [CROP AND MARGIN REQUIREMENT] for the intended listing.
Verify final dimensions, background value, file format, and channel policy outside the generated preview.
Deliver one product image only.
```

---

## 透明背景の製品アセット (I066)

実際のアルファ チャネルを使用して、製品を再利用可能なカットアウトとして抽出します。

- **入力内容:** 製品写真 — 必須
- **保存:** すべての製品の端、開口部、ラベル、色、透明または反射の詳細を保存します。
- **変更:** 背景の削除、エッジのクリーンアップ、およびオプションのニュートラル シャドウ処理のみを変更します。
- **確認:** エクスポートされたファイルのアルファ チャネルを確認します。チェッカーボードのプレビューは証拠ではありません。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i066-create-a-reusable-product-png-with-a-transparent-background.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i066_prompt_i066)

```text
Create one reusable product cutout from [PRODUCT PHOTO].
Preserve the exact product shape, proportions, colors, labels, openings, fine edges, transparent parts, and reflective details.
Remove the entire background without removing real product pixels.
Refine hair-like, fabric, glass, glossy, perforated, and semi-transparent edges carefully.
Do not redesign the product, fill openings, straighten labels, or invent hidden geometry.
Keep or remove the contact shadow according to [SHADOW REQUIREMENT].
Avoid white halos, dark fringes, jagged edges, color spill, and artificial outlines.
Export as [PNG / OTHER ALPHA-CAPABLE FORMAT] at [REQUIRED SIZE].
Open the delivered file over dark and light backgrounds to verify a genuine alpha channel.
Deliver one cutout asset only; do not substitute a white-background image.
```

---

## ライフスタイル製品シーン (I067)

変更されていない製品の切り抜きを信頼できる使用状況に配置します。

- **入力:** 製品の白い背景画像 — 必須
- **保持:** 製品モデル、形状、色、ラベル、材質、比率を保持します。
- **変更:** 環境、スタイル、ライト、カメラ コンテキスト、サポート プロップを変更します。
- **確認:** 物理的なスケール、接触、および製品の機能が発明されていないことを確認してください。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i067-place-a-product-in-a-realistic-lifestyle-scene.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i067_prompt_i067)

```text
Create one lifestyle product image from [PRODUCT CUTOUT OR WHITE-BACKGROUND IMAGE].
Preserve the exact product model, geometry, color, labels, materials, controls, and proportions.
Place it in [LIFESTYLE SETTING] for [TARGET AUDIENCE OR USE CASE].
Use [CAMERA ANGLE], [LIGHTING], and [PALETTE] consistent with the intended brand mood.
Add only supporting props listed in [PROP LIST], keeping the product dominant.
Make scale, perspective, contact surfaces, reflections, and shadows physically believable.
Do not change the product design, add accessories, or imply unconfirmed functions.
Keep labels and packaging readable only where they are genuinely visible in the source.
Avoid environmental clutter or props that misrepresent product size or use.
Deliver one finished lifestyle product image only.
```

---

## スタジオ製品写真 (I068)

製品の事実を保持しながら、プロのスタジオ照明を使用して製品写真を再演出します。

- **入力内容:** 製品写真 — 必須
- **保持:** ジオメトリ、ラベル、色、マテリアル、テクスチャ、および含まれるコンポーネントを保持します。
- **変更:** 背景、照明の配置、カメラの磨き、影の処理を変更します。
- **チェック:** 反射を検査し、製品の詳細や素材の主張が変更されていないことを確認してください。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i068-turn-an-ordinary-photo-into-a-professional-studio-product-shot.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i068_prompt_i068)

```text
Create one polished studio product image from [PRODUCT PHOTO].
Preserve the product’s exact geometry, proportions, colors, labels, material appearance, controls, openings, and included parts.
Use [STUDIO BACKDROP], [KEY LIGHT], [FILL], and [RIM OR ACCENT LIGHT] to clarify form.
Choose [CAMERA ANGLE] and [CROP] appropriate for [CATALOG OR BRAND USE].
Render contact shadow, reflections, translucency, and highlights consistently with the actual material.
Remove unrelated dust or capture distractions only when listed in [CLEANUP REQUEST].
Do not redesign packaging, sharpen unreadable text into invented words, or add features.
Avoid excessive gloss, fake texture, floating products, and impossible reflections.
Keep the result credible as a presentation of the supplied item.
Deliver one studio product image only.
```

---

## 季節商品キャンペーン画像 (I069)

実際の製品を中心にホリデーシーズンやセールシーズンのシーンを構築します。

- **入力:** 製品写真 — 必須。ホリデーまたはプロモーションのテーマ — 必須
- **保存:** 製品のアイデンティティ、デザイン、ラベル、色、および提供されたプロモーション情報を保存します。
- **変更:** 装飾、背景、ライト、パレット、キャンペーン構成を変更します。
- **確認:** 日付、割引、文言を確認してください。装飾が製品を隠してはいけません。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i069-create-christmas-black-friday-or-seasonal-product-imagery.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i069_prompt_i069)

```text
Create one seasonal campaign image from [PRODUCT PHOTO].
The confirmed campaign theme is [HOLIDAY OR SALES MOMENT].
Preserve the product’s exact design, proportions, colors, labels, materials, and included components.
Place it in [SEASONAL SETTING] using [PALETTE], [DECOR], and [LIGHTING].
Keep the product dominant and ensure decorations do not cover labels or important features.
Use only the confirmed offer “[EXACT PROMOTION]” and date “[EXACT VALID DATES]” if text is requested.
Do not invent prices, discounts, urgency, availability, endorsements, or product benefits.
Keep scale, contact, reflections, and shadows believable.
Treat generated campaign lettering as a draft requiring manual proofreading.
Deliver one finished promotional product image only.
```

---

## 食品または飲料のコマーシャル画像 (I080)

食べ物の写真または明確な製品説明から、食欲をそそるプロモーション画像を 1 つ作成します。

- **入力:** 食品の写真または製品の説明 — オプション (プレーンテキスト分岐は省略可能)
- **保存:** 実際の部分、成分、パッケージ、外観を写真ブランチに保存します。
- **変更:** メッキ、セット、照明、背景、カメラの処理を変更します。
- **確認:** テキスト主導のコンセプトを実際の製品として提示しないでください。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i080-create-commercial-photography-for-food-cakes-pizza-or-drinks.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i080_prompt_i080)

```text
Create one commercial food or drink image using exactly one starting branch.
For a real-item branch, use [FOOD PHOTO]; for a concept branch, use [EXACT PRODUCT DESCRIPTION] without requiring a photo.
In the photo branch, preserve the actual portion, ingredients, shape, packaging, garnish, and defining appearance.
In the text-only branch, clearly treat the image as a concept visualization rather than the actual item.
Style the scene for [MENU / DELIVERY / ADVERTISING USE] with [SURFACE], [PROPS], and [BACKGROUND].
Use [CAMERA ANGLE], [LIGHTING], and [COLOR MOOD] to make the item clear and appealing.
Keep steam, condensation, splashes, crumbs, and reflections plausible and restrained.
Do not add ingredients, increase portions, change packaging, or imply nutrition claims unless confirmed.
Add no price or wording unless [EXACT TEXT] is supplied and later proofread.
Deliver one finished food or beverage image only.
```

---

## 平置きの衣服からモデル上の画像へ (I089)

衣服のデザインを変更せずに、提供された衣服をモデル上で視覚化します。

- **入力:** 衣類タイル - 必須
- **保存:** シルエット、構造、色、プリント、生地のヒント、トリム、ブランドを維持します。
- **変更:** プレゼンテーションをフラット レイアウトからモデル、ポーズ、設定、照明に変更します。
- **確認してください:** 衣服の詳細をすべて確認し、フィット感とサイズが証明されていないことを明記してください。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i089-turn-flat-lay-clothing-into-an-on-model-image.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i089_prompt_i089)

```text
Create one on-model image from [FLAT-LAY GARMENT PHOTO].
Preserve the garment’s exact silhouette, construction, color, print placement, fabric cues, seams, trims, closures, and branding.
Show it on [MODEL DESCRIPTION] in [POSE] and [SETTING].
Keep the garment’s front/back orientation and layering consistent with [WEAR INSTRUCTION].
Render drape, folds, tension, shadows, and body contact appropriate to the visible fabric.
Do not redesign the garment, alter the print, add pockets, remove labels, or invent unseen details.
Keep hands, limbs, neckline, hem, and garment boundaries anatomically coherent.
Do not claim exact fit, size accuracy, comfort, or real-world appearance on a buyer.
Treat the image as merchandising visualization, not a fitting-room guarantee.
Deliver one on-model image only.
```

---

## 製品と手元のインタラクション画像 (I075)

実際の製品が保持または使用されている様子を、納得のいくスケールと接触で示します。

- **入力:** 製品画像 — 必須
- **保存:** 製品のデザイン、サイズのヒント、ラベル、色、機能上の真実を保存します。
- **変更:** 手、ユーザーのコンテキスト、環境、カメラの角度、光を変更します。
- **チェック:** 手の解剖学的構造、グリップ、スケールを検査し、製品の機能をでっち上げないようにしてください。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i075-show-a-product-being-held-or-used.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i075_prompt_i075)

```text
Create one interaction image from [PRODUCT IMAGE].
Preserve the product’s exact shape, dimensions relative to known cues, color, labels, materials, controls, and attachments.
Show [PERSON OR HAND DESCRIPTION] [HOLDING / USING] it in [CONTEXT].
Use [CAMERA ANGLE], [LIGHTING], and [BACKGROUND] appropriate to [MARKETING USE].
Make fingers, grip, pressure, contact points, occlusion, perspective, and shadows anatomically plausible.
Keep the product at a believable scale and orientation.
Do not redesign the item, hide important parts, add accessories, or imply an unsupported function.
Avoid extra fingers, fused hands, floating objects, and impossible use positions.
If the context suggests performance, show only behavior confirmed in [PRODUCT FACTS].
Deliver one finished interaction image only.
```

---

## 製品機能のインフォグラフィック (I076)

写真と確認された仕様から単一の製品インフォグラフィックを作成します。

- **入力:** 製品写真 — 必須。正確な寸法、セールスポイント、パラメータ - 必須
- **保存:** 製品の外観、提供されたすべての数量、単位、および表示内容を正確に保ってください。
- **変更:** レイアウト、吹き出し、アイコン、階層、およびサポートする背景を変更します。
- **チェック:** すべてのテキストを校正し、最終的な制作ファイルを個別に検証します。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i076-create-a-product-infographic-with-dimensions-features-and-specifications.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i076_prompt_i076)

```text
Create one product-feature infographic from [PRODUCT PHOTO] and [VERIFIED DIMENSIONS, FEATURES, AND SPECIFICATIONS].
Preserve the product’s exact geometry, color, labels, materials, and visible components.
Use a clear [LAYOUT FORMAT] with product image, callout lines, icons, and concise information hierarchy.
Reproduce every supplied number, unit, feature, and qualifier exactly; do not calculate or infer missing values.
Include only these approved claims: [APPROVED CLAIMS].
Use [BRAND PALETTE], [TYPE DIRECTION], and [BACKGROUND] without obscuring the product.
Keep callout lines attached to the correct feature and maintain readable spacing.
Do not invent certifications, compatibility, performance, warranty, or comparative claims.
Treat generated text as a visual draft: manually proofread and typeset the final file.
Deliver one infographic preview image only, not a verified vector or print-production file.
```

---

## E コマース詳細ページのビジュアル ドラフト (I077)

複数の実際の製品ビューと承認済みのコピーを 1 つの長い形式のビジュアル コンセプトに配置します。

- **入力:** 同じ製品画像グループ - 必須。セールスポイントと正確なコピーライティング - 必須
- **保持:** すべての製品ビューに一貫性を持たせ、提供されるすべての主張と文言を正確に保ちます。
- **変更:** セクションの順序、グラフィック階層、背景、吹き出し、ライフスタイル コンテキストを変更します。
- **確認:** 制作ツールでコピー、寸法、チャネル ルール、および最終レイアウトを確認します。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i077-create-a-long-form-e-commerce-detail-image-from-product-information.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i077_prompt_i077)

```text
Create one long-form e-commerce detail-page visual draft from [LABELED PRODUCT IMAGE SET] and [APPROVED COPY].
Preserve the same product model, shape, color, labels, materials, and components across every section.
Organize the page into [SECTION ORDER] for [TARGET CHANNEL AND AUDIENCE].
Use [BRAND PALETTE], [GRAPHIC STYLE], and a consistent spacing system.
Reproduce supplied headlines, dimensions, claims, and qualifiers exactly; do not invent missing copy.
Use lifestyle or detail panels only where supported by the provided product images and facts.
Keep callouts connected to the correct features and avoid contradictory product views.
Do not invent certifications, comparisons, warranties, prices, or performance results.
Treat this as a visual preview; rebuild and proofread precise text, vectors, dimensions, and channel specs in a layout tool.
Deliver one long-page concept image only.
```
