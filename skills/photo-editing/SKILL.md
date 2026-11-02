---
name: photo-editing
description: Prepare task-specific prompts and input checklists for photo editing, photo transformation, product imagery, space visualization, and visual-design image generation. Use when the user wants to plan one of these image tasks; preserve their chosen tool and do not run a paid generation service without explicit authorization.
---

# Photo Editing

Prepare a precise, reusable prompt for the user's image task. The included prompts are newly authored public templates; they are not the hidden instructions behind any example image and are not claimed to reproduce an example.

## Route the request

Read [references/catalog.md](references/catalog.md), choose the closest task, then read only that group's reference:

- [Pets and Family Keepsakes](references/pets-family.md) — Pet portraits, family composites, couple keepsakes, and milestone images.
- [Portraits and Personal Style](references/people.md) — Professional portraits, clothing edits, virtual previews, avatars, stickers, and poster concepts.
- [Homes and Spaces](references/spaces.md) — House keepsakes, interior previews, property presentation, landscape concepts, and architectural visualization.
- [Products and Commerce](references/products.md) — Listing assets, transparent cutouts, lifestyle and studio images, apparel, food, and product infographics.
- [Creative and Visual Design](references/design.md) — Thumbnails, posters, infographics, covers, mockups, menus, logos, and display lettering.

If no template fits, adapt the nearest one conservatively and state what changed. Do not force unrelated requests into this catalog.

## Prepare the result

1. Read the selected case's role labels: collect every `required` input; collect a `conditional` input only when its stated condition or branch applies; treat `optional` inputs as genuinely optional.
2. Ask only for missing required facts or the one branch choice that would materially change execution. Do not send a long questionnaire for style details; keep nonessential square-bracket placeholders or choose conservative defaults.
3. Preserve the user's chosen image tool, model, workflow, output format, and constraints. Do not switch services merely because another tool is available.
4. Tailor the selected prompt to the user's real materials. Keep identity, product, architecture, brand, exact wording, and other supplied facts unchanged unless the user explicitly requests a change.
5. Return the prepared prompt plus a short input checklist and verification checklist. By default, stop there.
6. Generate or edit an image only when the user explicitly asks for execution. Before using a paid service, consuming credits, uploading private media, or making another external change, obtain the authorization required by the active environment.

## Boundaries

- Produce one image per run unless the user explicitly asks for separate variants. A contact sheet is not a substitute for multiple deliverables.
- Do not infer names, dates, prices, dimensions, discounts, relationships, product claims, event facts, or other missing facts from an image.
- Proofread generated wording. For exact typography, vectors, transparent alpha, print production, measured drawings, engineering, construction, fit, or marketplace compliance, verify the delivered file in the appropriate specialist tool.
- Describe composites, virtual staging, concepts, and previews honestly. Do not present them as documentary records, built work, physical products, or verified performance.
- Do not claim that a template reproduces a gallery example. Results depend on inputs, tools, and settings.
