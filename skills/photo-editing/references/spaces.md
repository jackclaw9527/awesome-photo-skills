# Homes and Spaces

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


House keepsakes, interior previews, property presentation, landscape concepts, and architectural visualization. These are newly authored, untested public templates. Customize bracketed placeholders with user-supplied facts and materials; do not describe them as the prompts that produced repository examples.

## House Watercolor Keepsake (I030)

Transform a house photo into a watercolor or line-art keepsake.

- **Inputs:** 房屋照片 — required
- **Preserve:** Keep roofline, doors, windows, facade proportions, and distinctive site features.
- **Change:** Change medium, background simplification, landscaping emphasis, and palette.
- **Check:** Compare the building silhouette and openings so it does not become a different house.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i030_prompt_i030)

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

## Room Style Preview (I169)

Preview a new interior style while retaining the photographed room structure.

- **Inputs:** 现有房间照片 — required
- **Preserve:** Keep walls, doors, windows, ceiling, fixed openings, and camera viewpoint.
- **Change:** Change furniture, finishes, decor, palette, and lighting mood.
- **Check:** Check structure and disclose that dimensions, cost, and buildability are unverified.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i169-preview-different-interior-styles-in-a-room-photo.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i169_prompt_i169)

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

## Yard Landscape Concept (I178)

Visualize a landscape makeover for a photographed outdoor space.

- **Inputs:** 庭院或外部空间照片 — required; 使用需求、气候或所在地 — required
- **Preserve:** Keep lot boundaries, building, grades, access, and fixed structures.
- **Change:** Change planting, paving, furniture, lighting, and amenity concepts.
- **Check:** Review climate suitability, drainage, dimensions, and construction separately.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i178-create-a-landscape-makeover-concept-from-a-yard-photo.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i178_prompt_i178)

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

## Paint, Flooring, and Wallpaper Preview (I171)

Replace specified room surfaces using either a supplied sample or an accurate color and material description.

- **Inputs:** 室内照片 — required; 目标材料样板 — conditional (需要复现具体纹理或产品样时); 替换表面与目标颜色/材质 — required
- **Preserve:** Keep room structure, lighting logic, object placement, and untargeted surfaces.
- **Change:** Change only named walls, floor, or wallpaper areas.
- **Check:** Compare with a sample when one exists and warn that screens cannot guarantee real material color.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i171_prompt_i171)

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

## Office Redesign Concept (I172)

Visualize either an existing-office redesign from a site photo or a text-led workplace concept.

- **Inputs:** 办公室现场照片 — conditional (改造既有办公室时); 团队、功能区、品牌和分支说明 — required
- **Preserve:** Keep visible structure and constraints only when a site photo is supplied.
- **Change:** Change workstations, zones, furniture, branding, finishes, and lighting.
- **Check:** Check capacity and workflow, then separately verify code, accessibility, and fire safety.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i172-create-an-office-redesign-concept.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i172_prompt_i172)

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

## Virtual Staging for an Empty Room (I175)

Add believable furniture and decor to an empty property photo.

- **Inputs:** 空房照片 — required
- **Preserve:** Keep real architecture, room condition, windows, doors, and camera view.
- **Change:** Change only movable furnishings, decor, soft goods, and lighting presentation.
- **Check:** Disclose virtual staging and never imply shown furniture is included.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i175-virtually-stage-an-empty-property-with-furniture-and-decor.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i175_prompt_i175)

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

## Decluttered Property Photo (I176)

Clean up visible clutter while preserving the truthful condition and structure of a room.

- **Inputs:** 随手拍的有杂物房间照片 — required
- **Preserve:** Keep layout, fixed elements, surfaces, lighting, and material defects.
- **Change:** Remove only listed movable clutter and make restrained presentation corrections.
- **Check:** Ensure no damage or permanent feature is hidden or altered.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i176-turn-a-casual-room-photo-into-a-polished-property-listing-image.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i176_prompt_i176)

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

## Architectural Facade Concept (I177)

Develop a facade from an optional sketch or from a building-use and design-direction brief.

- **Inputs:** 建筑草图或体块图 — optional (用户已有建筑形体、开口或场地草图时); 建筑用途、设计关键词 — required
- **Preserve:** Keep supplied massing and openings only when a sketch or massing reference exists.
- **Change:** Change facade materials, articulation, environment, landscape, and light.
- **Check:** Treat output as concept communication, not a drawing for construction.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i177-create-an-architectural-facade-concept-from-text-or-a-sketch.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i177_prompt_i177)

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

## Sketch-to-Realistic Space Rendering (I179)

Render a supplied architectural or interior line drawing without changing its intended structure.

- **Inputs:** 室内或建筑草图/CAD线框 — required; 空间用途与草图含义 — required
- **Preserve:** Keep openings, geometry, layout relationships, and camera framing.
- **Change:** Change materials, lighting, furnishings, landscape, and atmosphere.
- **Check:** Compare the render to the source lines and do not treat it as engineering validation.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i179-turn-an-interior-or-architectural-sketch-into-a-realistic-render.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i179_prompt_i179)

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

## Interior or Architecture Mood Board (I182)

Build a design-direction board from optional references or from a project type and keyword brief.

- **Inputs:** 空间氛围与材料参考板 — optional (用户已有方向素材时); 项目类型与关键词 — required
- **Preserve:** Keep supplied reference colors and material identities only when references exist.
- **Change:** Change layout, hierarchy, crops, annotations, and supporting generated swatches.
- **Check:** Treat the board as inspiration, not a confirmed product or procurement list.
- **Task details:** [dearsketch](https://dearsketch.com/intent/i182-create-a-mood-board-for-an-architecture-or-interior-project.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i182_prompt_i182)

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
