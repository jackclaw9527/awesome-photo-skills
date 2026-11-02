# Products and Commerce

Listing assets, transparent cutouts, lifestyle and studio images, apparel, food, and product infographics. These are newly authored, untested public templates. Customize bracketed placeholders with user-supplied facts and materials; do not describe them as the prompts that produced repository examples.

## White-Background Product Listing Image (I065)

Isolate a real product into a clean marketplace-style white-background image.

- **Inputs:** 手机拍摄的商品照 — required
- **Preserve:** Keep product shape, proportions, color, labels, surface details, and included parts.
- **Change:** Change background, crop, lighting balance, and restrained shadow.
- **Check:** Inspect label fidelity and channel-specific listing requirements.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i065-turn-an-ordinary-product-photo-into-a-white-background-listing-image.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i065_prompt_i065)

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

## Transparent-Background Product Asset (I066)

Extract a product as a reusable cutout with a real alpha channel.

- **Inputs:** 商品照片 — required
- **Preserve:** Keep every product edge, opening, label, color, and transparent or reflective detail.
- **Change:** Change only background removal, edge cleanup, and optional neutral shadow handling.
- **Check:** Verify the exported file’s alpha channel; a checkerboard preview is not proof.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i066-create-a-reusable-product-png-with-a-transparent-background.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i066_prompt_i066)

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

## Lifestyle Product Scene (I067)

Place an unchanged product cutout in a believable use context.

- **Inputs:** 商品白底图 — required
- **Preserve:** Keep product model, geometry, color, labels, materials, and proportions.
- **Change:** Change environment, styling, light, camera context, and supporting props.
- **Check:** Check physical scale, contact, and that no product feature was invented.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i067-place-a-product-in-a-realistic-lifestyle-scene.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i067_prompt_i067)

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

## Studio Product Photograph (I068)

Restage a product photo with professional studio lighting while retaining product facts.

- **Inputs:** 商品照片 — required
- **Preserve:** Keep geometry, labels, colors, materials, texture, and included components.
- **Change:** Change backdrop, light arrangement, camera polish, and shadow treatment.
- **Check:** Inspect reflections and ensure no product detail or material claim changed.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i068-turn-an-ordinary-photo-into-a-professional-studio-product-shot.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i068_prompt_i068)

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

## Seasonal Product Campaign Image (I069)

Build a holiday or sales-season scene around a real product.

- **Inputs:** 商品照片 — required; 节日或促销主题 — required
- **Preserve:** Keep product identity, design, label, color, and supplied promotion facts.
- **Change:** Change decor, backdrop, light, palette, and campaign composition.
- **Check:** Verify dates, discounts, and wording; decorations must not obscure the product.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i069-create-christmas-black-friday-or-seasonal-product-imagery.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i069_prompt_i069)

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

## Food or Drink Commercial Image (I080)

Create one appetizing promotional image from either a food photo or an explicit product description.

- **Inputs:** 食品照片或产品描述 — optional (纯文字分支可省略)
- **Preserve:** Keep actual portion, ingredients, packaging, and appearance in the photo branch.
- **Change:** Change plating, set, lighting, background, and camera treatment.
- **Check:** Do not present a text-led concept as the actual product.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i080-create-commercial-photography-for-food-cakes-pizza-or-drinks.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i080_prompt_i080)

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

## Flat-Lay Garment to On-Model Image (I089)

Visualize a supplied garment on a model without changing the garment design.

- **Inputs:** 服装平铺图 — required
- **Preserve:** Keep silhouette, construction, color, print, fabric cues, trims, and branding.
- **Change:** Change presentation from flat lay to model, pose, setting, and lighting.
- **Check:** Check all garment details and state that fit and sizing are not proven.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i089-turn-flat-lay-clothing-into-an-on-model-image.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i089_prompt_i089)

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

## Product-in-Hand Interaction Image (I075)

Show a real product being held or used with plausible scale and contact.

- **Inputs:** 商品图片 — required
- **Preserve:** Keep product design, size cues, label, color, and functional truth.
- **Change:** Change hands, user context, environment, camera angle, and light.
- **Check:** Inspect hand anatomy, grip, scale, and avoid inventing product capability.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i075-show-a-product-being-held-or-used.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i075_prompt_i075)

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

## Product Feature Infographic (I076)

Create a single product infographic from a photo and verified specifications.

- **Inputs:** 商品照片 — required; 准确尺寸、卖点和参数 — required
- **Preserve:** Keep product appearance and every supplied number, unit, and claim exact.
- **Change:** Change layout, callouts, icons, hierarchy, and supporting background.
- **Check:** Proofread all text and verify the final production file separately.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i076-create-a-product-infographic-with-dimensions-features-and-specifications.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i076_prompt_i076)

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

## E-commerce Detail Page Visual Draft (I077)

Arrange multiple real product views and approved copy into one long-form visual concept.

- **Inputs:** 同一商品图片组 — required; 卖点与准确文案 — required
- **Preserve:** Keep all product views consistent and all supplied claims and wording exact.
- **Change:** Change section order, graphic hierarchy, backgrounds, callouts, and lifestyle context.
- **Check:** Verify copy, dimensions, channel rules, and final layout in a production tool.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i077-create-a-long-form-e-commerce-detail-image-from-product-information.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i077_prompt_i077)

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
