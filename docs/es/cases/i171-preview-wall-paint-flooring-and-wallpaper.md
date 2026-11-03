# Vista previa de pintura, pisos y papel tapiz · Vista previa de selección de pintura de pared y material de piso

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


Reemplace las superficies de la habitación especificadas utilizando una muestra suministrada o una descripción precisa del color y el material.

Obtenga una vista previa de los efectos de pintura de pared, suelo y papel tapiz. Se utiliza para la selección de materiales de decoración.

[Solicitud de copia](#public-prompt) · [ es producido por dearsketch / Pruebe en línea](https://dearsketch.com/es/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i171_cta) · [Volver al tema / Colección](../guides/spaces.md)

## Material de referencia y dirección de resultados.

<table>
<thead><tr><th width="50%">Material de referencia</th><th width="50%">Ejemplo de resultados</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>fotos de interior</strong><br><img src="../../../assets/cases/i171-before-1.webp" alt="Vista previa de la selección de pintura para paredes y materiales para pisos: material de referencia 1" width="320"></p>
<p><strong>Plantilla de material de destino</strong><br><img src="../../../assets/cases/i171-before-2.webp" alt="Vista previa de la selección de pintura para paredes y materiales para pisos: material de referencia 2" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/es/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i171_image"><img src="../../../assets/cases/i171-after.webp" alt="Vista previa de la selección de pintura para paredes y materiales para pisos: resultados de ejemplo" width="320"></a></td></tr></tbody>
</table>

Los materiales de referencia y los resultados se utilizan para ilustrar la dirección visual. La plantilla pública no es la instrucción de generación original de las imágenes adjuntas y no se garantiza la reproducción de los mismos resultados.

## Qué preparar/Insumos

| Material | Tipo / Tipo | Cantidad / Cantidad | Condición / Requisito |
| --- | --- | --- | --- |
| fotos de interior | Imagen/Imagen | 1 pieza | Requerido / Requerido |
| Plantilla de material de destino | Imagen/Imagen | 0–1 imagen; También se pueden utilizar texto exacto o datos de color. | Condicional: cuando necesitas reproducir texturas específicas o muestras de productos. |
| Reemplazar la superficie con el color/material objetivo | Carácter / Texto | 1 porción | Requerido / Requerido |

Sólo se genera una imagen a la vez.

## Conservar y cambiar / Editar resumen

- **Preservar / 保留：** Mantenga la estructura de la habitación, la lógica de iluminación, la ubicación de los objetos y las superficies no objetivo.
- **Cambiar / 改变：** Cambie solo las paredes, el piso o las áreas de papel tapiz con nombre.

## Public prompt

**Plantilla pública recién editada · Creación reciente · No probada en generación.** Reemplace los parámetros de corchetes y adjunte los materiales necesarios en la herramienta que admite la edición de imágenes; Las entradas opcionales y condicionales se preparan de acuerdo con la tabla anterior. Esta plantilla no se utilizó para generar los ejemplos de esta página.

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

[Hazlo en línea con tus propios materiales / Hazlo en línea](https://dearsketch.com/es/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i171_after-prompt) · [Deja que el agente te ayude a organizarlo / Usa la habilidad](../quickstart.md#agent-skill)

## Consulta los puntos clave/Revisión

Los productos especificados deben proporcionar muestras o información precisa sobre el color; La imagen de la pantalla no puede garantizar la misma diferencia de color que el producto real.

Compare con una muestra cuando exista y advierta que las pantallas no pueden garantizar el color real del material.

Dirección del resultado: Vista previa de efectos de materiales. Cuando se requiera texto exacto, archivos transparentes, vectores o entrega impresa, verifique el archivo real; Las funciones y tarifas disponibles están sujetas a la descripción del sitio web.

## Casos relacionados / Tareas relacionadas

- [Convierte la foto de una casa en un recuerdo de acuarela o arte lineal · Pintura conmemorativa de acuarela residencial ](./i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.md#public-prompt)
- [Vista previa de diferentes estilos interiores en una foto de habitación · Vista previa del estilo de decoración de la habitación](./i169-preview-different-interior-styles-in-a-room-photo.md#public-prompt)
- [Crear un concepto de cambio de paisaje a partir de una foto de jardín · Renovación del paisaje de jardín ](./i178-create-a-landscape-makeover-concept-from-a-yard-photo.md#public-prompt)

## Referencia de antecedentes de requisitos

- [LightXTodas las herramientas](https://www.lightxeditor.com/all-tools/all-tools/)
- [Concepto de hogar Adobe](https://www.adobe.com/products/firefly/features/ai-room-design/home-design.html)

Estos enlaces son solo para ayudar a comprender el propósito y no son prueba de la fuente o autorización de las imágenes en esta página.

Para conocer el alcance de uso de imágenes y materiales, consulte la descripción del contenido [ ](../content-policy.md). [Ver las 50 plantillas ](../prompts.md).
