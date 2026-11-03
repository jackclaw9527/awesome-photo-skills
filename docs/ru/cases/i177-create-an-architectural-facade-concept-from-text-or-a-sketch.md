# Концепция архитектурного фасада · Концепция фасада здания

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


Разработайте фасад на основе дополнительного эскиза или технического задания по использованию здания и проектированию.

Создавайте концепции фасадов зданий на основе текста или эскизов. Используется для конкурсов, предложений и отчетов.

[Скопировать ](#public-prompt) · [ создан dearsketch / Попробуйте онлайн](https://dearsketch.com/ru/intent/i177-create-an-architectural-facade-concept-from-text-or-a-sketch.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i177_cta) · [Вернуться к теме / Коллекция](../guides/spaces.md)

## Справочный материал и направление результата

<table>
<thead><tr><th width="50%">Справочный материал</th><th width="50%">Пример результатов</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>Архитектурные эскизы или массовые чертежи</strong><br><img src="../../../assets/cases/i177-before-1.webp" alt="Концепция фасада здания – справочный материал 1" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/ru/intent/i177-create-an-architectural-facade-concept-from-text-or-a-sketch.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i177_image"><img src="../../../assets/cases/i177-after.webp" alt="Концепция фасада здания – примеры результатов" width="320"></a></td></tr></tbody>
</table>

Справочные материалы и результаты используются для иллюстрации визуального направления. Общедоступный шаблон не является исходной инструкцией по созданию сопровождающих изображений, и воспроизведение тех же результатов не гарантируется.

## Что подготовить/Входы

| Материал | Тип/Тип | Количество / Количество | Условие/Требование |
| --- | --- | --- | --- |
| Архитектурные эскизы или массовые чертежи | Изображение/Изображение | 0–1; несколько материалов могут быть объединены в одну маркированную эталонную плату | Необязательно/Необязательно: если у пользователя уже есть форма здания, проем или эскиз участка. |
| Использование здания, ключевые слова дизайна | Символ/Текст | 1 порция | Требуется / Требуется |

Одновременно создается только одно изображение.

## Сохранить и изменить / Краткое описание редактирования

- **Сохранить / 保留：** Сохранять предоставленные формы и проемы только при наличии эскиза или ссылки на формы.
- **Изменить / 改变：** Измените материалы фасада, артикуляцию, окружающую среду, ландшафт и свет.

## Public prompt

**Недавно отредактированный общедоступный шаблон · Недавно созданный · Не проверенный поколением.** Замените параметры квадратных скобок и прикрепите необходимые материалы в инструменте, поддерживающем редактирование изображений; необязательные и условные входные данные подготавливаются в соответствии с таблицей выше. Этот шаблон не использовался для создания примеров на этой странице.

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

[Сделайте это онлайн, используя свои собственные материалы / Сделайте это онлайн](https://dearsketch.com/ru/intent/i177-create-an-architectural-facade-concept-from-text-or-a-sketch.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i177_after-prompt) · [Позвольте агенту помочь вам это организовать / Используйте навык](../quickstart.md#agent-skill)

## Проверьте ключевые моменты/обзор

Назначение здания и направление проектирования уточняются, а результаты используются для концептуальной коммуникации, а не для строительных чертежей.

Относитесь к результатам как к передаче концепции, а не как к чертежу для построения.

Направление результата: Рендеринг архитектурной концепции. Если требуется точный текст, прозрачные файлы, векторные изображения или распечатка, проверьте фактический файл; доступные функции и стоимость зависят от описания на веб-сайте.

## Связанные случаи/Связанные задачи

- [Превратите фотографию дома в акварельный или штриховой рисунок на память · Акварельная памятная картина для дома ](./i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.md#public-prompt)
- [Предварительный просмотр различных стилей интерьера на фотографии комнаты · Предварительный просмотр стиля оформления комнаты](./i169-preview-different-interior-styles-in-a-room-photo.md#public-prompt)
- [Создайте концепцию преображения ландшафта по фотографии двора · Обновление ландшафта двора ](./i178-create-a-landscape-makeover-concept-from-a-yard-photo.md#public-prompt)

## Справочная информация о требованиях

- [Создание здания Adobe ](https://www.adobe.com/products/firefly/features/ai-architecture-generator.html)

Эти ссылки предназначены только для облегчения понимания цели и не являются доказательством источника или авторизации изображений на этой странице.

Объем использования изображений и материалов см. в описании контента [ ](../content-policy.md). [Просмотреть все 50 шаблонов ](../prompts.md).
