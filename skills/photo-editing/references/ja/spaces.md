# 家と空間

[中文](../../../../README.md) · [English](../../../../README.en.md) · [Português](../../../../README.pt.md) · [Español](../../../../README.es.md) · [Français](../../../../README.fr.md) · [Deutsch](../../../../README.de.md) · [عربي](../../../../README.ar.md) · [русский](../../../../README.ru.md) · [日本語](../../../../README.ja.md) · [हिंदी](../../../../README.hi.md)


家の記念品、インテリアの内見、物件のプレゼンテーション、景観のコンセプト、建築のビジュアライゼーション。これらは新しく作成された、テストされていない公開テンプレートです。ユーザーが指定した事実や資料を使用して括弧で囲まれたプレースホルダーをカスタマイズします。これらをリポジトリのサンプルを生成したプロンプトとして説明しないでください。

## ハウス水彩記念品 (I030)

家の写真を水彩画や線画の記念品に変えます。

- **入力内容:** 家の写真 — 必須
- **保存:** 屋根のライン、ドア、窓、ファサードのプロポーション、および特徴的な敷地の特徴を維持します。
- **変更:** 媒体、背景の簡略化、景観の強調、およびパレットを変更します。
- **Check:** 違う家にならないよう、建物のシルエットや開口部などを比較してみましょう。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i030_prompt_i030)

```text
Create one house keepsake artwork from [HOUSE PHOTO].
Preserve the exact roofline, facade proportions, doors, windows, porch, chimney, and distinctive architectural features.
Render the building in [WATERCOLOR / INK LINE / MIXED MEDIA] with [PALETTE].
Simplify distracting cars, bins, or background clutter only as requested in [REMOVAL LIST].
Retain meaningful landscaping and site features listed in [KEEP LIST].
Keep perspective, number of stories, and placement of openings faithful to the reference.
Use a clean [PAPER / MINIMAL BACKGROUND] suitable for [PRINT OR GIFT].
Do not invent extensions, alter the property design, or present this as a measured drawing.
Add an address or caption only when [EXACT TEXT] is supplied and proofread it.
Deliver one finished keepsake image only.
```

---

## ルーム スタイル プレビュー (I169)

写真の部屋の構造を維持しながら、新しいインテリア スタイルをプレビューします。

- **入力:** 既存の部屋の写真 — 必須
- **保存:** 壁、ドア、窓、天井、固定開口部、カメラの視点を保存します。
- **変更:** 家具、仕上げ、装飾、パレット、照明の雰囲気を変更します。
- **確認:** 構造を確認し、寸法、コスト、構築可能性が未検証であることを明らかにします。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i169-preview-different-interior-styles-in-a-room-photo.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i169_prompt_i169)

```text
Create one interior style preview from [ROOM PHOTO].
Preserve the room geometry, walls, doors, windows, ceiling height, fixed openings, and camera viewpoint.
Apply [TARGET INTERIOR STYLE] with [PALETTE], [MATERIAL DIRECTION], and [LIGHTING MOOD].
Replace or add only the furniture and decor described in [CHANGE LIST].
Keep circulation paths, perspective, furniture scale, shadows, and floor contact believable.
Do not move structural elements or enlarge the room unless [EXPLICIT STRUCTURAL CHANGE] is supplied.
Retain items listed in [KEEP LIST] and remove only items in [REMOVE LIST].
Treat materials and colors as a visual concept, not a guaranteed product match.
Do not claim measured dimensions, budget accuracy, code compliance, or construction feasibility.
Deliver one single-view room concept image only.
```

---

## 庭の景観コンセプト (I178)

撮影された屋外スペースの風景の変化を視覚化します。

- **入力内容:** 庭または屋外スペースの写真 — 必須。使用要件、気候または場所 - 必須
- **保存:** 敷地境界、建物、勾配、アクセス、固定構造物を保存します。
- **変更:** 植栽、舗装、家具、照明、アメニティのコンセプトを変更します。
- **確認:** 気候適合性、排水、寸法、構造を個別に確認してください。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i178-create-a-landscape-makeover-concept-from-a-yard-photo.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i178_prompt_i178)

```text
Create one landscape makeover concept from [YARD OR EXTERIOR PHOTO].
Preserve property boundaries, building facade, grade cues, gates, paths, utilities, and fixed structures.
Design for [USE NEEDS] in [CLIMATE OR LOCATION] using [LANDSCAPE STYLE].
Add [PLANTING DIRECTION], [PAVING], [FURNITURE], and [REQUESTED AMENITIES].
Keep scale, perspective, access routes, shadows, and transitions physically plausible.
Do not hide drainage points, exits, hazards, or existing constraints visible in the photo.
Use plants appropriate in appearance to [CLIMATE], but do not claim horticultural suitability without review.
Treat the result as concept visualization, not a planting plan or construction document.
Flag grading, drainage, structural, utility, and local-code questions for professionals.
Deliver one finished exterior concept image only.
```

---

## ペイント、床材、壁紙のプレビュー (I171)

付属のサンプルまたは正確な色と材質の説明を使用して、指定された部屋の表面を交換します。

- **入力内容:** 内部の写真 — 必須。ターゲット素材サンプル — 条件付き (特定のテクスチャまたは製品サンプルを再現する必要がある場合)。代替のサーフェスとターゲットの色/マテリアル — 必須
- **保持:** 部屋の構造、照明ロジック、オブジェクトの配置、および対象外の表面を保持します。
- **変更:** 名前付きの壁、床、または壁紙の領域のみを変更します。
- **確認:** サンプルが存在する場合はそれと比較し、画面では実際の素材の色を保証できないことを警告します。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i171_prompt_i171)

```text
Create one material preview from [INTERIOR PHOTO].
Choose one target branch: use [TARGET MATERIAL OR COLOR SAMPLE] when matching a specific texture or product, or use [ACCURATE COLOR AND MATERIAL DESCRIPTION] when no sample exists.
Apply the chosen [PAINT / FLOORING / WALLPAPER] only to [EXACT SURFACES TO REPLACE].
Preserve doors, windows, trim, furniture, room geometry, camera angle, and all untargeted surfaces.
When a sample is supplied, retain its dominant color, pattern scale, grain direction, and finish as closely as possible.
Respect corners, occlusion, seams, perspective, reflections, and existing light falloff.
Do not recolor furnishings, skin, artwork, or adjacent surfaces.
Do not invent named-product availability, dimensions, finish, or performance claims.
Treat the preview as an approximation; verify physical samples and measured quantities before purchase or installation.
Deliver one edited material-preview image only.
```

---

## オフィス再設計コンセプト (I172)

現場の写真から既存のオフィスの再設計を視覚化するか、テキスト主導の職場コンセプトを視覚化します。

- **入力:** オフィス敷地の写真 — 条件付き (既存のオフィスを改装する場合)。チーム、機能分野、ブランド、支店の説明 — 必須
- **保持:** 現場の写真が提供された場合にのみ、表示される構造と制約を保持します。
- **変更:** ワークステーション、ゾーン、家具、ブランド、仕上げ、照明を変更します。
- **確認:** 容量とワークフローを確認し、コード、アクセシビリティ、火災安全性を個別に確認します。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i172-create-an-office-redesign-concept.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i172_prompt_i172)

```text
Create one office concept for [TEAM SIZE], [WORK MODES], and [FUNCTIONAL ZONES].
Choose one branch: use [OFFICE SITE PHOTO] when redesigning an existing office, or use [TEXT-ONLY SPACE BRIEF] for a new generic concept.
For the site-photo branch, preserve visible walls, columns, windows, doors, exits, ceiling, fixed services, and camera view.
For the text-only branch, do not claim to preserve or represent an unknown existing structure.
Use [BRAND DIRECTION], [PALETTE], [MATERIALS], and [FURNITURE STYLE].
Arrange workstations, meeting areas, storage, and circulation with plausible scale and access.
Do not invent confirmed floor area, site constraints, or compliance facts absent from the brief.
Show only brand names or logos supplied in [APPROVED BRAND ASSET].
Treat the result as a concept, not a measured plan, budget, accessibility review, or fire-code approval.
Deliver one office concept image only and flag technical questions for professional verification.
```

---

## 空の部屋の仮想ステージング (I175)

空き物件の写真に、本物らしい家具や装飾品を追加します。

- **入力:** 利用可能な部屋の写真 — 必須
- **保存:** 実際の建築、部屋の状態、窓、ドア、カメラのビューを保存します。
- **変更:** 可動家具、装飾品、ソフトグッズ、および照明プレゼンテーションのみを変更します。
- **確認:** バーチャル ステージングを公開し、展示されている家具が含まれていることを示唆しないでください。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i175-virtually-stage-an-empty-property-with-furniture-and-decor.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i175_prompt_i175)

```text
Create one virtually staged property image from [EMPTY ROOM PHOTO].
Preserve the real walls, floor, ceiling, windows, doors, built-ins, fixtures, room proportions, and camera viewpoint.
Furnish the room for [ROOM FUNCTION] in [INTERIOR STYLE].
Add [FURNITURE LIST], restrained decor, and [PALETTE] at believable scale.
Keep perspective, floor contact, shadows, reflections, and circulation realistic.
Do not alter the room layout, hide damage, change views, or add permanent architectural features.
Do not imply that furniture, decor, or upgrades are physically present or included with the property.
Leave the result plausible rather than overfilled or luxury-inflated.
Require a clear virtual-staging disclosure wherever the image is published.
Deliver one staged room image only.
```

---

## 整理整頓された物件の写真 (I176)

部屋の実際の状態と構造を維持しながら、目に見える散らかったものを片付けます。

- **入力:** 散らかった部屋のランダムな写真 — 必須
- **保存:** レイアウト、固定要素、表面、照明、および材料の欠陥を保存します。
- **変更:** リストされた移動可能なクラッタのみを削除し、制限されたプレゼンテーションの修正を行います。
- **チェック:** 損傷や永続的な機能が隠されたり変更されたりしていないことを確認してください。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i176-turn-a-casual-room-photo-into-a-polished-property-listing-image.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i176_prompt_i176)

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

---

## 建築ファサードのコンセプト (I177)

オプションのスケッチ、または建物の用途とデザイン方向の概要からファサードを作成します。

- **入力:** 建築スケッチまたはブロック図 — オプション (ユーザーがすでに建物の形状、開口部、または敷地スケッチを持っている場合)。建築用途、デザインキーワード — 必須
- **保持:** スケッチまたはマス参照が存在する場合にのみ、指定されたマスと開口部を保持します。
- **変更:** ファサードの素材、関節、環境、景観、光を変更します。
- **確認:** 出力を建設用の図面ではなく、コンセプトの伝達として扱います。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i177-create-an-architectural-facade-concept-from-text-or-a-sketch.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i177_prompt_i177)

```text
Create one architectural facade concept for [BUILDING USE] with [DESIGN KEYWORDS].
Choose one branch: follow [OPTIONAL SKETCH OR MASSING IMAGE] when supplied, or create a text-led concept from the brief when no image exists.
For the reference branch, preserve the supplied massing, floor count, principal openings, roof form, proportions, and camera view.
For the text-only branch, do not claim that any generated geometry reproduces an existing design.
Develop [FACADE MATERIALS], [OPENING TREATMENT], [SHADING ELEMENTS], and [ENTRY EXPRESSION].
Add a restrained [SITE CONTEXT], [LANDSCAPE], and [LIGHTING CONDITION] for scale.
Keep perspective, material joints, shadows, and human scale coherent.
Do not invent planning approval, structural feasibility, energy performance, or code compliance.
Do not treat generated details as measured dimensions or construction assemblies.
Deliver one facade concept rendering only for design discussion.
```

---

## スケッチからリアリスティック空間へのレンダリング (I179)

意図された構造を変更せずに、提供された建築またはインテリアの線画をレンダリングします。

- **入力:** インテリアまたは建築スケッチ/CAD ワイヤーフレーム — 必須。スペースの使用法とスケッチの意味 — 必須
- **保持:** 開口部、ジオメトリ、レイアウト関係、カメラのフレームを保持します。
- **変更:** 素材、照明、家具、風景、雰囲気を変更します。
- **確認:** レンダリングをソース行と比較し、エンジニアリング検証として扱わないでください。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i179-turn-an-interior-or-architectural-sketch-into-a-realistic-render.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i179_prompt_i179)

```text
Create one realistic rendering from [ARCHITECTURAL OR INTERIOR SKETCH / CAD VIEW].
Interpret the space as [SPACE USE] according to [SKETCH LEGEND OR EXPLANATION].
Preserve all indicated walls, openings, levels, roof lines, built forms, and camera framing.
Apply [MATERIALS], [COLOR PALETTE], [LIGHTING], and [ENVIRONMENT].
Add only the furniture, fixtures, landscape, or people listed in [ADD LIST].
Keep perspective, scale, structural relationships, shadows, and material transitions coherent.
Do not erase ambiguous source lines; resolve uncertainty conservatively or flag it.
Do not claim engineering accuracy, measured dimensions, buildability, or code compliance.
The source drawing remains authoritative when the rendering conflicts with it.
Deliver one realistic concept rendering only.
```

---

## インテリアまたは建築のムードボード (I182)

オプションの参考資料、またはプロジェクト タイプとキーワードの概要から設計方向ボードを作成します。

- **入力:** 空間雰囲気とマテリアルのリファレンス ボード — オプション (ユーザーがすでに方向マテリアルを持っている場合)。プロジェクトのタイプとキーワード — 必須
- **保持:** 参照が存在する場合にのみ、指定された参照色とマテリアル ID を保持します。
- **変更:** レイアウト、階層、トリミング、注釈、サポートされる生成されたスウォッチを変更します。
- **ご確認ください:** ボードは確認済みの製品や調達リストではなく、インスピレーションとして扱ってください。
- **タスクの詳細:** [dearsketch](https://dearsketch.com/ja/intent/i182-create-a-mood-board-for-an-architecture-or-interior-project.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i182_prompt_i182)

```text
Create one mood board for [PROJECT TYPE] using [DESIGN KEYWORDS].
Choose one branch: organize [OPTIONAL REFERENCE BOARD OR LABELED IMAGES] when supplied, or develop a text-led direction when no references exist.
For the reference branch, preserve recognizable colors, textures, material identities, and atmosphere.
For the text-only branch, use [PALETTE], [MATERIAL DIRECTION], [FORM LANGUAGE], and [LIGHTING MOOD] without implying specific sourced products.
Use a clear [EDITORIAL / MATERIAL-LIBRARY / COLLAGE] hierarchy with clean spacing.
Label only confirmed generic material names or exact product names supplied by the user.
Do not invent manufacturers, product codes, prices, availability, dimensions, or performance claims.
Do not imply that visually similar generated materials are actual specified products.
Treat the board as direction-setting inspiration; procurement and physical samples require separate confirmation.
Deliver one self-contained mood-board image only.
```
