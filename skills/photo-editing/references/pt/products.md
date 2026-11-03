# Produtos e Comércio

[中文](../../../../README.md) · [English](../../../../README.en.md) · [Português](../../../../README.pt.md) · [Español](../../../../README.es.md) · [Français](../../../../README.fr.md) · [Deutsch](../../../../README.de.md) · [عربي](../../../../README.ar.md) · [русский](../../../../README.ru.md) · [日本語](../../../../README.ja.md) · [हिंदी](../../../../README.hi.md)


Listagem de ativos, recortes transparentes, imagens de estilo de vida e de estúdio, infográficos de roupas, alimentos e produtos. Estes são modelos públicos recém-criados e não testados. Personalize espaços reservados entre colchetes com fatos e materiais fornecidos pelo usuário; não os descreva como os prompts que produziram exemplos de repositório.

## Imagem da lista de produtos com fundo branco (I065)

Isole um produto real em uma imagem limpa de fundo branco, estilo mercado.

- **Entradas:** Fotos do produto tiradas com telefones celulares – obrigatório
- **Preservar:** Mantenha a forma, as proporções, a cor, os rótulos, os detalhes da superfície e as peças incluídas do produto.
- **Alterar:** Altere o plano de fundo, o corte, o equilíbrio de iluminação e a sombra restrita.
- **Verificar:** inspecione a fidelidade do rótulo e os requisitos de listagem específicos do canal.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i065-turn-an-ordinary-product-photo-into-a-white-background-listing-image.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i065_prompt_i065)

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

## Ativo de produto com plano de fundo transparente (I066)

Extraia um produto como um recorte reutilizável com um canal alfa real.

- **Insumos:** Fotos do produto — obrigatório
- **Preservar:** Mantenha todas as bordas, aberturas, rótulos, cores e detalhes transparentes ou reflexivos do produto.
- **Alteração:** Altere apenas a remoção do fundo, a limpeza das bordas e o tratamento opcional de sombras neutras.
- **Verificar:** Verifique o canal alfa do arquivo exportado; uma visualização em tabuleiro de xadrez não é prova.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i066-create-a-reusable-product-png-with-a-transparent-background.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i066_prompt_i066)

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

## Cena do produto de estilo de vida (I067)

Coloque um recorte de produto inalterado em um contexto de uso confiável.

- **Entradas:** Imagem de fundo branco do produto — obrigatório
- **Preservar:** Mantenha modelo, geometria, cor, rótulos, materiais e proporções do produto.
- **Alterar:** Altere o ambiente, o estilo, a luz, o contexto da câmera e os acessórios de suporte.
- **Verificar:** Verifique a escala física, o contato e se nenhum recurso do produto foi inventado.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i067-place-a-product-in-a-realistic-lifestyle-scene.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i067_prompt_i067)

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

## Fotografia de produto de estúdio (I068)

Reformule uma foto de produto com iluminação de estúdio profissional, mantendo os dados do produto.

- **Insumos:** Fotos do produto — obrigatório
- **Preservar:** Mantenha geometria, rótulos, cores, materiais, textura e componentes incluídos.
- **Alterar:** Altere o cenário, a disposição das luzes, o polimento da câmera e o tratamento das sombras.
- **Verificar:** Inspecione os reflexos e certifique-se de que nenhum detalhe do produto ou declaração de material foi alterado.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i068-turn-an-ordinary-photo-into-a-professional-studio-product-shot.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i068_prompt_i068)

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

## Imagem de campanha de produto sazonal (I069)

Crie um cenário de feriado ou temporada de vendas em torno de um produto real.

- **Insumos:** Fotos do produto — obrigatório; Temas promocionais ou de feriados – obrigatório
- **Preservar:** Mantenha a identidade do produto, design, rótulo, cor e informações promocionais fornecidas.
- **Alterar:** altere a decoração, o cenário, a luz, a paleta e a composição da campanha.
- **Verificar:** Verifique datas, descontos e textos; as decorações não devem obscurecer o produto.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i069-create-christmas-black-friday-or-seasonal-product-imagery.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i069_prompt_i069)

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

## Imagem comercial de alimentos ou bebidas (I080)

Crie uma imagem promocional apetitosa a partir de uma foto de comida ou de uma descrição explícita do produto.

- **Entradas:** Fotos de alimentos ou descrições de produtos — opcional (ramificação de texto simples pode ser omitida)
- **Preservar:** Mantenha a porção, ingredientes, embalagem e aparência reais no ramo de fotos.
- **Alterar:** Altere o revestimento, o cenário, a iluminação, o plano de fundo e o tratamento da câmera.
- **Verificar:** Não apresente um conceito baseado em texto como o produto real.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i080-create-commercial-photography-for-food-cakes-pizza-or-drinks.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i080_prompt_i080)

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

## Vestuário plano para imagem no modelo (I089)

Visualize uma peça de roupa fornecida em um modelo sem alterar o design da peça.

- **Entradas:** Peças de roupas — obrigatórias
- **Preservar:** Mantenha a silhueta, a construção, a cor, a estampa, os detalhes do tecido, os acabamentos e a marca.
- **Alterar:** altere a apresentação de configuração plana para modelo, pose, cenário e iluminação.
- **Verificar:** Verifique todos os detalhes da peça e indique que o ajuste e o tamanho não foram comprovados.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i089-turn-flat-lay-clothing-into-an-on-model-image.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i089_prompt_i089)

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

## Imagem de interação do produto em mãos (I075)

Mostre um produto real sendo segurado ou usado com escala e contato plausíveis.

- **Entradas:** Imagem do produto — obrigatório
- **Preservar:** Mantenha o design do produto, as indicações de tamanho, o rótulo, a cor e a verdade funcional.
- **Alterar:** Altere as mãos, o contexto do usuário, o ambiente, o ângulo da câmera e a luz.
- **Verificar:** Inspecione a anatomia da mão, a pegada, a escala e evite inventar a capacidade do produto.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i075-show-a-product-being-held-or-used.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i075_prompt_i075)

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

## Infográfico de recursos do produto (I076)

Crie um infográfico de produto único a partir de uma foto e especificações verificadas.

- **Insumos:** Fotos do produto — obrigatório; Dimensões, argumentos de venda e parâmetros precisos – obrigatórios
- **Preservar:** Mantenha a aparência do produto e todos os números, unidades e reivindicações fornecidos exatos.
- **Alterar:** altere o layout, as legendas, os ícones, a hierarquia e o plano de fundo de suporte.
- **Verificar:** Revise todo o texto e verifique o arquivo de produção final separadamente.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i076-create-a-product-infographic-with-dimensions-features-and-specifications.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i076_prompt_i076)

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

## Rascunho visual da página de detalhes de comércio eletrônico (I077)

Organize várias visualizações reais de produtos e cópias aprovadas em um conceito visual longo.

- **Entradas:** Mesmo grupo de imagens de produto — obrigatório; Pontos de venda e redação precisa – obrigatório
- **Preservar:** Mantenha todas as visualizações de produtos consistentes e todas as declarações e textos fornecidos exatos.
- **Alterar:** altere a ordem das seções, hierarquia gráfica, planos de fundo, textos explicativos e contexto de estilo de vida.
- **Verificar:** verifique cópia, dimensões, regras de canal e layout final em uma ferramenta de produção.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i077-create-a-long-form-e-commerce-detail-image-from-product-information.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i077_prompt_i077)

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
