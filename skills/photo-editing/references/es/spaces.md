# Hogares y Espacios

[中文](../../../../README.md) · [English](../../../../README.en.md) · [Português](../../../../README.pt.md) · [Español](../../../../README.es.md) · [Français](../../../../README.fr.md) · [Deutsch](../../../../README.de.md) · [عربي](../../../../README.ar.md) · [русский](../../../../README.ru.md) · [日本語](../../../../README.ja.md) · [हिंदी](../../../../README.hi.md)


Recuerdos de casas, vistas previas de interiores, presentación de propiedades, conceptos de paisaje y visualización arquitectónica. Estas son plantillas públicas no probadas y de nueva creación. Personalice los marcadores de posición entre corchetes con datos y materiales proporcionados por el usuario; no los describa como las indicaciones que produjeron ejemplos de repositorio.

## Recuerdo de acuarela de la casa (I030)

Transforme una foto de una casa en un recuerdo de acuarela o arte lineal.

- **Entradas:** Fotos de la casa: obligatorias
- **Preservar:** Mantenga la línea del techo, las puertas, las ventanas, las proporciones de la fachada y las características distintivas del sitio.
- **Cambio:** Cambia el medio, la simplificación del fondo, el énfasis del paisajismo y la paleta.
- **Comprueba:** Compara la silueta del edificio y las aberturas para que no se convierta en una casa diferente.
- **Detalles de la tarea:** [dearsketch](https://dearsketch.com/es/intent/i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i030_prompt_i030)

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

## Vista previa del estilo de la habitación (I169)

Obtenga una vista previa de un nuevo estilo interior conservando la estructura de la habitación fotografiada.

- **Entradas:** Fotos de habitaciones existentes: requeridas
- **Preservar:** Mantenga paredes, puertas, ventanas, techos, aberturas fijas y puntos de vista de las cámaras.
- **Cambio:** Cambie muebles, acabados, decoración, paleta y ambiente de iluminación.
- **Verificar:** Verificar la estructura e informar que las dimensiones, el costo y la edificabilidad no están verificados.
- **Detalles de la tarea:** [dearsketch](https://dearsketch.com/es/intent/i169-preview-different-interior-styles-in-a-room-photo.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i169_prompt_i169)

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

## Concepto de paisaje de jardín (I178)

Visualice un cambio de imagen del paisaje para un espacio al aire libre fotografiado.

- **Aportaciones:** Fotos del jardín o espacio exterior: obligatorias; requisitos de uso, clima o ubicación: requerido
- **Preservar:** Mantenga los límites del lote, la construcción, las pendientes, el acceso y las estructuras fijas.
- **Cambio:** Cambiar los conceptos de plantación, pavimento, mobiliario, iluminación y comodidades.
- **Verificar:** Revise la idoneidad climática, el drenaje, las dimensiones y la construcción por separado.
- **Detalles de la tarea:** [dearsketch](https://dearsketch.com/es/intent/i178-create-a-landscape-makeover-concept-from-a-yard-photo.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i178_prompt_i178)

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

## Vista previa de pintura, pisos y papel tapiz (I171)

Reemplace las superficies de la habitación especificadas utilizando una muestra suministrada o una descripción precisa del color y el material.

- **Entradas:** Fotos del interior: obligatorias; Muestras de material objetivo: condicionales (cuando es necesario reproducir texturas específicas o muestras de productos); Superficies alternativas y colores/materiales de destino: obligatorios
- **Preservar:** Mantenga la estructura de la habitación, la lógica de iluminación, la ubicación de los objetos y las superficies no objetivo.
- **Cambiar:** Cambie solo las paredes, el piso o las áreas de papel tapiz con nombre.
- **Compruebe:** Compare con una muestra cuando exista y advierta que las pantallas no pueden garantizar el color real del material.
- **Detalles de la tarea:** [dearsketch](https://dearsketch.com/es/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i171_prompt_i171)

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

## Concepto de rediseño de oficina (I172)

Visualice el rediseño de una oficina existente a partir de una fotografía del sitio o un concepto de lugar de trabajo basado en texto.

- **Entradas:** Fotografías del sitio de la oficina: condicional (cuando se remodela una oficina existente); descripciones de equipo, área funcional, marca y sucursal: obligatorias
- **Preservar:** Mantenga la estructura y las restricciones visibles solo cuando se proporcione una fotografía del sitio.
- **Cambio:** Cambia estaciones de trabajo, zonas, mobiliario, marca, acabados e iluminación.
- **Verificar:** Verifique la capacidad y el flujo de trabajo, luego verifique por separado el código, la accesibilidad y la seguridad contra incendios.
- **Detalles de la tarea:** [dearsketch](https://dearsketch.com/es/intent/i172-create-an-office-redesign-concept.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i172_prompt_i172)

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

## Puesta en escena virtual para una sala vacía (I175)

Agregue muebles y decoración creíbles a la foto de una propiedad vacía.

- **Entradas:** Fotos de las habitaciones disponibles: obligatorias
- **Preservar:** Mantenga la arquitectura real, el estado de la habitación, las ventanas, las puertas y la vista de la cámara.
- **Cambio:** Cambie únicamente el mobiliario móvil, la decoración, los artículos textiles y la presentación de la iluminación.
- **Verificar:** Divulgue la puesta en escena virtual y nunca dé a entender que los muebles mostrados están incluidos.
- **Detalles de la tarea:** [dearsketch](https://dearsketch.com/es/intent/i175-virtually-stage-an-empty-property-with-furniture-and-decor.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i175_prompt_i175)

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

## Foto de propiedad ordenada (I176)

Limpie el desorden visible mientras preserva la verdadera condición y estructura de una habitación.

- **Entradas:** Fotos aleatorias de habitaciones desordenadas: obligatorias
- **Conservar:** Conservar disposición, elementos fijos, superficies, iluminación y defectos de materiales.
- **Cambio:** Elimine solo el desorden móvil enumerado y realice correcciones restringidas en la presentación.
- **Verificar:** Asegúrese de que no se oculten o alteren ningún daño o característica permanente.
- **Detalles de la tarea:** [dearsketch](https://dearsketch.com/es/intent/i176-turn-a-casual-room-photo-into-a-polished-property-listing-image.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i176_prompt_i176)

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

## Concepto de fachada arquitectónica (I177)

Desarrolle una fachada a partir de un boceto opcional o de un resumen sobre el uso del edificio y la dirección del diseño.

- **Entradas:** Croquis arquitectónico o diagrama de bloques: opcional (cuando el usuario ya tiene la forma del edificio, la abertura o el croquis del sitio); Uso arquitectónico, palabras clave de diseño: obligatorio
- **Conservar:** Mantenga las masas y las aberturas proporcionadas solo cuando exista un boceto o una referencia de masa.
- **Cambio:** Cambia los materiales de la fachada, la articulación, el entorno, el paisaje y la luz.
- **Verificar:** Trate el resultado como comunicación conceptual, no como un dibujo para la construcción.
- **Detalles de la tarea:** [dearsketch](https://dearsketch.com/es/intent/i177-create-an-architectural-facade-concept-from-text-or-a-sketch.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i177_prompt_i177)

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

## Representación de boceto a espacio realista (I179)

Renderice un dibujo lineal arquitectónico o interior suministrado sin cambiar su estructura prevista.

- **Insumos:** Boceto interior o arquitectónico/estructura alámbrica CAD: obligatorio; Uso del espacio y significado del boceto: obligatorio
- **Conservar:** Conserva las aberturas, la geometría, las relaciones de diseño y el encuadre de la cámara.
- **Cambio:** Cambia materiales, iluminación, mobiliario, paisaje y atmósfera.
- **Verificar:** Compare el renderizado con las líneas de origen y no lo trate como una validación de ingeniería.
- **Detalles de la tarea:** [dearsketch](https://dearsketch.com/es/intent/i179-turn-an-interior-or-architectural-sketch-into-a-realistic-render.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i179_prompt_i179)

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

## Mood Board de Interiores o Arquitectura (I182)

Cree un tablero de dirección de diseño a partir de referencias opcionales o de un resumen del tipo de proyecto y de las palabras clave.

- **Entradas:** Atmósfera espacial y tablero de referencia de materiales: opcional (si el usuario ya tiene materiales de dirección); tipo de proyecto y palabras clave: obligatorio
- **Conservar:** Mantenga los colores de referencia suministrados y las identidades de los materiales solo cuando existan referencias.
- **Cambio:** Cambie el diseño, la jerarquía, los recortes, las anotaciones y el soporte de las muestras generadas.
- **Verificar:** Trate el tablero como inspiración, no como un producto confirmado o una lista de adquisiciones.
- **Detalles de la tarea:** [dearsketch](https://dearsketch.com/es/intent/i182-create-a-mood-board-for-an-architecture-or-interior-project.html?utm_source=github&utm_medium=skill&utm_campaign=dearsketch-public-cases&utm_content=i182_prompt_i182)

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
