# Quick start · Select a case, change materials, and create a picture

[中文](../../README.md) · [English](../../README.en.md) · [Português](../../README.pt.md) · [Español](../../README.es.md) · [Français](../../README.fr.md) · [Deutsch](../../README.de.md) · [عربي](../../README.ar.md) · [русский](../../README.ru.md) · [日本語](../../README.ja.md) · [हिंदी](../../README.hi.md)


## Copy a prompt

1. Select tasks from [50 templates ](./prompts.md) and open the case page.
2. Prepare the required inputs in the material table to confirm whether the conditional material applies to you.
3. Copy Public prompt and replace the content in square brackets. When you need image editing, attach the corresponding image to your tool; text cannot replace the actual image attachment.
4. Produce one result at a time and accept it according to the checkpoints for that case.

Choose a template, attach the required materials in your image tool, fill in its placeholders and review the result. These are new public prompts, not tested reproductions of the demo images.

## Agent Skill

Skill is responsible for converting "What do I want to do" into a clear input list, retaining key points and complete prompt words, and does not call the payment interface by default. It contains its own reference of 50 templates and does not rely on the entire library once installed.

### Codex

Use the built-in installer in Codex to give the skill directory of this warehouse:

```text
$skill-installer install the photo-editing skill from
https://github.com/jackclaw9527/awesome-photo-skills/tree/main/skills/photo-editing
```

You can also download or clone the warehouse and put the complete `skills/photo-editing` folder under `.agents/skills/` of the target project; if there is a skill with the same name, compare the contents first.

Then use:

```text
$photo-editing 把我的自拍做成自然的职业头像。
先告诉我需要哪些素材，再给我可复制的提示词。
```

English example:

```text
Use $photo-editing to prepare a clean product listing image.
Keep the exact product, tell me what to attach and return a complete prompt.
```

The skills catalog and installer usage are based on [official OpenAI documentation](https://learn.chatgpt.com/docs/build-skills). For other tools that support Agent Skills, please install the entire folder according to their respective skill directory rules.

## Make it on dearsketch

If you don’t want to organize prompt words by yourself, you can directly open the corresponding task and provide your own materials according to the website’s requirements:

| Goal | Direct task |
| --- | --- |
| Selfie → Professional headshot / Professional headshot | [Start](https://dearsketch.com/en/intent/i001-create-a-professional-linkedin-headshot-from-a-selfie.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i001_headshot) |
| Pet photos → Artistic portrait / Pet portrait | [Start](https://dearsketch.com/en/intent/i026-turn-a-pet-photo-into-a-custom-portrait.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i026_pet) |
| Product photo → White-background product image | [Start](https://dearsketch.com/en/intent/i065-turn-an-ordinary-product-photo-into-a-white-background-listing-image.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i065_product) |
| Room photos → Decoration preview / Room redesign | [Start](https://dearsketch.com/en/intent/i169-preview-different-interior-styles-in-a-room-photo.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i169_room) |

The website maintains its own production process; public skills do not require you to hand over your website account or service key, and it does not include free generation quota. Available functions and fees are subject to the then-current description on the website.
