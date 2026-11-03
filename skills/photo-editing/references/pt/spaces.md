# Casas e Espaços

[中文](../../../../README.md) · [English](../../../../README.en.md) · [Português](../../../../README.pt.md) · [Español](../../../../README.es.md) · [Français](../../../../README.fr.md) · [Deutsch](../../../../README.de.md) · [عربي](../../../../README.ar.md) · [русский](../../../../README.ru.md) · [日本語](../../../../README.ja.md) · [हिंदी](../../../../README.hi.md)


Lembranças de casas, visualizações de interiores, apresentação de propriedades, conceitos paisagísticos e visualização arquitetônica. Estes são modelos públicos recém-criados e não testados. Personalize espaços reservados entre colchetes com fatos e materiais fornecidos pelo usuário; não os descreva como os prompts que produziram exemplos de repositório.

## Lembrança em aquarela de casa (I030)

Transforme uma foto de casa em uma lembrança em aquarela ou arte linear.

- **Entradas:** Fotos da casa — obrigatório
- **Preservar:** Mantenha a linha do telhado, as portas, as janelas, as proporções da fachada e as características distintivas do local.
- **Alterar:** Altere o meio, a simplificação do plano de fundo, a ênfase do paisagismo e a paleta.
- **Confira:** Compare a silhueta e as aberturas do edifício para que não se torne uma casa diferente.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i030_prompt_i030)

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

## Visualização do estilo do ambiente (I169)

Visualize um novo estilo interior, mantendo a estrutura da sala fotografada.

- **Entradas:** Fotos de quartos existentes — obrigatório
- **Preservar:** Mantenha paredes, portas, janelas, teto, aberturas fixas e ponto de vista da câmera.
- **Alterar:** Altere móveis, acabamentos, decoração, paleta e clima de iluminação.
- **Verificar:** Verifique a estrutura e divulgue que as dimensões, o custo e a capacidade de construção não foram verificados.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i169-preview-different-interior-styles-in-a-room-photo.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i169_prompt_i169)

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

## Conceito de paisagem de quintal (I178)

Visualize uma reforma paisagística para um espaço ao ar livre fotografado.

- **Insumos:** Fotos do quintal ou espaço externo — obrigatório; requisitos de uso, clima ou localização - obrigatório
- **Preservar:** Mantenha os limites do lote, construção, declives, acessos e estruturas fixas.
- **Alteração:** Altere os conceitos de plantio, pavimentação, móveis, iluminação e comodidades.
- **Verificar:** Revise a adequação climática, drenagem, dimensões e construção separadamente.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i178-create-a-landscape-makeover-concept-from-a-yard-photo.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i178_prompt_i178)

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

## Visualização de pintura, piso e papel de parede (I171)

Substitua as superfícies especificadas da sala usando uma amostra fornecida ou uma descrição precisa de cor e material.

- **Entradas:** Fotos do interior — obrigatórias; Amostras de materiais alvo – condicionais (quando texturas específicas ou amostras de produtos precisam ser reproduzidas); Superfícies alternativas e cores/materiais alvo — obrigatório
- **Preservar:** Mantenha a estrutura da sala, a lógica de iluminação, o posicionamento dos objetos e as superfícies não desejadas.
- **Alterar:** Altere apenas áreas nomeadas de paredes, pisos ou papel de parede.
- **Verificar:** Compare com uma amostra quando existir e avise que as telas não podem garantir a cor real do material.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i171_prompt_i171)

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

## Conceito de reformulação do escritório (I172)

Visualize uma reformulação de um escritório existente a partir de uma foto do local ou de um conceito de local de trabalho baseado em texto.

- **Insumos:** Fotos do local do escritório — condicionais (ao reformar um escritório existente); descrições de equipe, área funcional, marca e filial - obrigatório
- **Preservar:** Mantenha a estrutura e as restrições visíveis somente quando uma foto do local for fornecida.
- **Alterar:** altere estações de trabalho, zonas, móveis, marca, acabamentos e iluminação.
- **Verificar:** Verifique a capacidade e o fluxo de trabalho e, em seguida, verifique separadamente o código, a acessibilidade e a segurança contra incêndio.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i172-create-an-office-redesign-concept.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i172_prompt_i172)

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

## Preparação virtual para uma sala vazia (I175)

Adicione móveis e decoração confiáveis ​​a uma foto de propriedade vazia.

- **Entradas:** Fotos dos quartos disponíveis — obrigatório
- **Preservar:** Mantenha a arquitetura real, as condições do ambiente, as janelas, as portas e a visão da câmera.
- **Alteração:** Altere apenas móveis móveis, decoração, bens de consumo e apresentação de iluminação.
- **Verifique:** Divulgue a encenação virtual e nunca insinue que os móveis mostrados estão incluídos.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i175-virtually-stage-an-empty-property-with-furniture-and-decor.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i175_prompt_i175)

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

## Foto da propriedade organizada (I176)

Limpe a desordem visível enquanto preserva a condição e a estrutura verdadeiras de uma sala.

- **Entradas:** Fotos aleatórias de salas bagunçadas — obrigatório
- **Preservar:** Manter layout, elementos fixos, superfícies, iluminação e defeitos de materiais.
- **Alteração:** Remova apenas a desordem móvel listada e faça correções restritas na apresentação.
- **Verificar:** Certifique-se de que nenhum dano ou recurso permanente esteja oculto ou alterado.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i176-turn-a-casual-room-photo-into-a-polished-property-listing-image.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i176_prompt_i176)

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

## Conceito de fachada arquitetônica (I177)

Desenvolva uma fachada a partir de um esboço opcional ou de um resumo de uso do edifício e direção do projeto.

- **Entradas:** Esboço arquitetônico ou diagrama de blocos — opcional (quando o usuário já possui um esboço de forma de construção, abertura ou terreno); Uso arquitetônico, palavras-chave de design – obrigatório
- **Preservar:** Mantenha a massa e as aberturas fornecidas somente quando existir um esboço ou referência de massa.
- **Alterar:** Altere os materiais da fachada, a articulação, o ambiente, a paisagem e a luz.
- **Verificar:** Trate o resultado como uma comunicação de conceito, não como um desenho para construção.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i177-create-an-architectural-facade-concept-from-text-or-a-sketch.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i177_prompt_i177)

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

## Renderização de espaço do esboço para o realista (I179)

Renderize um desenho arquitetônico ou de linhas internas fornecido sem alterar a estrutura pretendida.

- **Entradas:** Esboço interior ou arquitetônico/wireframe CAD — obrigatório; Uso de espaço e significado do esboço – obrigatório
- **Preservar:** mantenha aberturas, geometria, relações de layout e enquadramento da câmera.
- **Alterar:** Altere materiais, iluminação, móveis, paisagem e atmosfera.
- **Verificação:** Compare a renderização com as linhas de origem e não a trate como validação de engenharia.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i179-turn-an-interior-or-architectural-sketch-into-a-realistic-render.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i179_prompt_i179)

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

## Mood Board de Interiores ou Arquitetura (I182)

Crie um quadro de direção de design a partir de referências opcionais ou de um tipo de projeto e um resumo de palavras-chave.

- **Entradas:** Atmosfera espacial e placa de referência de materiais — opcional (caso o usuário já possua materiais direcionais); tipo de projeto e palavras-chave - obrigatório
- **Preservar:** Mantenha as cores de referência e as identidades dos materiais fornecidas somente quando existirem referências.
- **Alterar:** altere o layout, a hierarquia, os cortes, as anotações e o suporte às amostras geradas.
- **Verifique:** Trate o quadro como inspiração, não como um produto confirmado ou lista de compras.
- **Detalhes da tarefa:** [dearsketch](https://dearsketch.com/pt/intent/i182-create-a-mood-board-for-an-architecture-or-interior-project.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i182_prompt_i182)

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
