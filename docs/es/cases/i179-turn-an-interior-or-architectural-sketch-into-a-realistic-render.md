# Representación de boceto a espacio realista · Conversión de bocetos arquitectónicos en efectos realistas

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


Renderice un dibujo lineal arquitectónico o interior suministrado sin cambiar su estructura prevista.

Convierta bocetos de interiores o arquitectónicos en representaciones realistas. Se utiliza para la comunicación con el cliente y la revisión del programa.

[Solicitud de copia](#public-prompt) · [ es producido por dearsketch / Pruebe en línea](https://dearsketch.com/es/intent/i179-turn-an-interior-or-architectural-sketch-into-a-realistic-render.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i179_cta) · [Volver al tema / Colección](../guides/spaces.md)

## Material de referencia y dirección de resultados.

<table>
<thead><tr><th width="50%">Material de referencia</th><th width="50%">Ejemplo de resultados</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>Bocetos interiores o arquitectónicos/estructuras alámbricas CAD</strong><br><img src="../../../assets/cases/i179-before-1.webp" alt="Boceto arquitectónico convertido en efecto realista - material de referencia 1" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/es/intent/i179-turn-an-interior-or-architectural-sketch-into-a-realistic-render.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i179_image"><img src="../../../assets/cases/i179-after.webp" alt="Boceto arquitectónico con efecto realista: ejemplo de resultados" width="320"></a></td></tr></tbody>
</table>

Los materiales de referencia y los resultados se utilizan para ilustrar la dirección visual. La plantilla pública no es la instrucción de generación original de las imágenes adjuntas y no se garantiza la reproducción de los mismos resultados.

## Qué preparar/Insumos

| Material | Tipo / Tipo | Cantidad / Cantidad | Condición / Requisito |
| --- | --- | --- | --- |
| Bocetos interiores o arquitectónicos/estructuras alámbricas CAD | Imagen/Imagen | 1 pieza | Requerido / Requerido |
| Uso del espacio y significado del boceto. | Carácter / Texto | 1 porción | Requerido / Requerido |

Sólo se genera una imagen a la vez.

## Conservar y cambiar / Editar resumen

- **Conservar / 保留：** Conserva las aberturas, la geometría, las relaciones de diseño y el encuadre de la cámara.
- **Cambiar / 改变：** Cambiar materiales, iluminación, mobiliario, paisaje y atmósfera.

## Public prompt

**Plantilla pública recién editada · Creación reciente · No probada en generación.** Reemplace los parámetros de corchetes y adjunte los materiales necesarios en la herramienta que admite la edición de imágenes; Las entradas opcionales y condicionales se preparan de acuerdo con la tabla anterior. Esta plantilla no se utilizó para generar los ejemplos de esta página.

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

[Hazlo en línea con tus propios materiales / Hazlo en línea](https://dearsketch.com/es/intent/i179-turn-an-interior-or-architectural-sketch-into-a-realistic-render.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i179_after-prompt) · [Deja que el agente te ayude a organizarlo / Usa la habilidad](../quickstart.md#agent-skill)

## Consulta los puntos clave/Revisión

Verifique la relación entre las aberturas y las estructuras en el boceto y no trate la representación visual como una verificación de ingeniería.

Compare el renderizado con las líneas de origen y no lo trate como una validación de ingeniería.

Dirección del resultado: representación espacial realista. Cuando se requiera texto exacto, archivos transparentes, vectores o entrega impresa, verifique el archivo real; Las funciones y tarifas disponibles están sujetas a la descripción del sitio web.

## Casos relacionados / Tareas relacionadas

- [Convierte la foto de una casa en un recuerdo de acuarela o arte lineal · Pintura conmemorativa de acuarela residencial ](./i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.md#public-prompt)
- [Vista previa de diferentes estilos interiores en una foto de habitación · Vista previa del estilo de decoración de la habitación](./i169-preview-different-interior-styles-in-a-room-photo.md#public-prompt)
- [Crear un concepto de cambio de paisaje a partir de una foto de jardín · Renovación del paisaje de jardín ](./i178-create-a-landscape-makeover-concept-from-a-yard-photo.md#public-prompt)

## Referencia de antecedentes de requisitos

- [Oboceto de OpenArt a imagen ](https://openart.ai/generator/sketch/)
- [Generación de edificios Adobe ](https://www.adobe.com/products/firefly/features/ai-architecture-generator.html)

Estos enlaces son solo para ayudar a comprender el propósito y no son prueba de la fuente o autorización de las imágenes en esta página.

Para conocer el alcance de uso de imágenes y materiales, consulte la descripción del contenido [ ](../content-policy.md). [Ver las 50 plantillas ](../prompts.md).
