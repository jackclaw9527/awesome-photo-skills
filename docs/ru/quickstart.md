# Быстрый старт · Выберите корпус, измените материалы и создайте картину

[中文](../../README.md) · [English](../../README.en.md) · [Português](../../README.pt.md) · [Español](../../README.es.md) · [Français](../../README.fr.md) · [Deutsch](../../README.de.md) · [عربي](../../README.ar.md) · [русский](../../README.ru.md) · [日本語](../../README.ja.md) · [हिंदी](../../README.hi.md)


## Скопируйте приглашение

1. Выберите задачи из шаблонов [50 ](./prompts.md) и откройте страницу обращения.
2. Подготовьте необходимые входные данные в таблице материалов, чтобы подтвердить, применим ли условный материал к вам.
3. Скопируйте Public prompt и замените содержимое в квадратных скобках. Если вам нужно отредактировать изображение, прикрепите соответствующее изображение к вашему инструменту; текст не может заменить фактическое вложение изображения.
4. Выдавайте по одному результату за раз и принимайте его в соответствии с контрольными точками для этого случая.

Выберите шаблон, прикрепите необходимые материалы в инструменте изображения, заполните заполнители и просмотрите результат. Это новые public prompt, а не проверенные копии демо-образов.

## Agent Skill

Skill отвечает за преобразование «Что я хочу сделать» в понятный список ввода, сохраняя ключевые моменты и полные слова подсказки, и по умолчанию не вызывает интерфейс оплаты. Он содержит собственный справочник из 50 шаблонов и не зависит от всей библиотеки после установки.

### Codex

Используйте встроенный установщик в Codex, чтобы указать каталог навыков этого склада:

```text
$skill-installer install the photo-editing skill from
https://github.com/jackclaw9527/awesome-photo-skills/tree/main/skills/photo-editing
```

Вы также можете загрузить или клонировать хранилище и поместить полную папку `skills/photo-editing` в `.agents/skills/` целевого проекта; если есть навык с таким же названием, сначала сравните его содержимое.

Затем используйте:

```text
$photo-editing 把我的自拍做成自然的职业头像。
先告诉我需要哪些素材，再给我可复制的提示词。
```

Английский пример:

```text
Use $photo-editing to prepare a clean product listing image.
Keep the exact product, tell me what to attach and return a complete prompt.
```

Каталог навыков и использование установщика основаны на [официальной документации OpenAI](https://learn.chatgpt.com/docs/build-skills). Для других инструментов, поддерживающих Agent Skill, установите всю папку в соответствии с правилами каталога соответствующих навыков.

## Сделайте это на dearsketch

Если вы не хотите самостоятельно организовывать слова-подсказки, вы можете напрямую открыть соответствующее задание и предоставить свои материалы в соответствии с требованиями сайта:

| Цель | Прямая задача |
| --- | --- |
| Селфи → Профессиональный снимок / Профессиональный снимок | [Начало](https://dearsketch.com/ru/intent/i001-create-a-professional-linkedin-headshot-from-a-selfie.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i001_headshot) |
| Фотографии домашних животных → Художественный портрет / Портрет домашнего животного | [Начало](https://dearsketch.com/ru/intent/i026-turn-a-pet-photo-into-a-custom-portrait.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i026_pet) |
| Фото товара → Изображение товара на белом фоне | [Начало](https://dearsketch.com/ru/intent/i065-turn-an-ordinary-product-photo-into-a-white-background-listing-image.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i065_product) |
| Фотографии комнат → Предварительный просмотр отделки / Редизайн комнаты | [Начало](https://dearsketch.com/ru/intent/i169-preview-different-interior-styles-in-a-room-photo.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i169_room) |

Веб-сайт поддерживает собственный производственный процесс; Общедоступные навыки не требуют от вас передачи учетной записи веб-сайта или служебного ключа и не включают в себя квоту на бесплатную генерацию. Доступные функции и стоимость зависят от текущего описания на веб-сайте.
