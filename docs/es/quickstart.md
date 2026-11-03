# Inicio rápido · Seleccione un estuche, cambie materiales y cree una imagen

[中文](../../README.md) · [English](../../README.en.md) · [Português](../../README.pt.md) · [Español](../../README.es.md) · [Français](../../README.fr.md) · [Deutsch](../../README.de.md) · [عربي](../../README.ar.md) · [русский](../../README.ru.md) · [日本語](../../README.ja.md) · [हिंदी](../../README.hi.md)


## Copiar un mensaje

1. Seleccione tareas de las plantillas [50 ](./prompts.md) y abra la página del caso.
2. Prepare los insumos requeridos en la tabla de materiales para confirmar si el material condicional se aplica a usted.
3. Copie Public prompt y reemplace el contenido entre corchetes. Cuando necesite editar imágenes, adjunte la imagen correspondiente a su herramienta; El texto no puede reemplazar la imagen adjunta real.
4. Produzca un resultado a la vez y acéptelo de acuerdo con los puntos de control para ese caso.

Elija una plantilla, adjunte los materiales necesarios en su herramienta de imágenes, complete sus marcadores de posición y revise el resultado. Estos son public prompt nuevos, no reproducciones probadas de las imágenes de demostración.

## Agent Skill

Skill es responsable de convertir "¿Qué quiero hacer?" en una lista de entrada clara, conservando puntos clave y palabras clave completas, y no llama a la interfaz de pago de forma predeterminada. Contiene su propia referencia de 50 plantillas y no depende de toda la biblioteca una vez instalada.

### Codex

Utilice el instalador integrado en Codex para proporcionar el directorio de habilidades de este almacén:

```text
$skill-installer install the photo-editing skill from
https://github.com/jackclaw9527/awesome-photo-skills/tree/main/skills/photo-editing
```

También puede descargar o clonar el almacén y colocar la carpeta `skills/photo-editing` completa en `.agents/skills/` del proyecto de destino; Si hay una habilidad con el mismo nombre, compare el contenido primero.

Luego usa:

```text
$photo-editing 把我的自拍做成自然的职业头像。
先告诉我需要哪些素材，再给我可复制的提示词。
```

Ejemplo en inglés:

```text
Use $photo-editing to prepare a clean product listing image.
Keep the exact product, tell me what to attach and return a complete prompt.
```

El catálogo de habilidades y el uso del instalador se basan en la documentación oficial [ OpenAI](https://learn.chatgpt.com/docs/build-skills). Para otras herramientas que admitan Agent Skills, instale la carpeta completa de acuerdo con sus respectivas reglas de directorio de habilidades.

## Hazlo en dearsketch

Si no desea organizar las palabras clave usted mismo, puede abrir directamente la tarea correspondiente y proporcionar sus propios materiales de acuerdo con los requisitos del sitio web:

| Meta | tarea directa |
| --- | --- |
| Selfie → Disparo a la cabeza profesional / Disparo a la cabeza profesional | [Inicio](https://dearsketch.com/es/intent/i001-create-a-professional-linkedin-headshot-from-a-selfie.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i001_headshot) |
| Fotos de mascotas → Retrato artístico / Retrato de mascotas | [Inicio](https://dearsketch.com/es/intent/i026-turn-a-pet-photo-into-a-custom-portrait.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i026_pet) |
| Foto del producto → Imagen del producto con fondo blanco | [Inicio](https://dearsketch.com/es/intent/i065-turn-an-ordinary-product-photo-into-a-white-background-listing-image.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i065_product) |
| Fotos de habitaciones → Vista previa de decoración / Rediseño de habitaciones | [Inicio](https://dearsketch.com/es/intent/i169-preview-different-interior-styles-in-a-room-photo.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i169_room) |

El sitio web mantiene su propio proceso de producción; Las habilidades públicas no requieren que usted entregue su cuenta de sitio web o clave de servicio, y no incluye cuota de generación gratuita. Las funciones y tarifas disponibles están sujetas a la descripción vigente en ese momento en el sitio web.
