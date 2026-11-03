<div dir="rtl" align="right">

# ملصق دردشة واحد · ملصق صورة للدردشة

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


قم بتحويل صورة شخص أو حيوان أليف أو كائن إلى ملصق واحد معبر.

تحويل الصور إلى ملصقات الدردشة. يستخدم للواتساب، التليجرام، وسائل التواصل الاجتماعي.

[مطالبة النسخ](#public-prompt) · تم إنتاج [ بواسطة dearsketch / جرب عبر الإنترنت](https://dearsketch.com/ar/intent/i056-turn-a-photo-into-chat-stickers.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i056_cta) · [العودة إلى الموضوع / المجموعة](../guides/people.md)

## المواد المرجعية واتجاه النتيجة

<table>
<thead><tr><th width="50%">المواد المرجعية</th><th width="50%">مثال على النتائج</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>صور الأشخاص أو الحيوانات الأليفة أو الأشياء</strong><br><img src="../../../assets/cases/i056-before-1.webp" alt="ملصق صورة للدردشة - المادة المرجعية 1" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/ar/intent/i056-turn-a-photo-into-chat-stickers.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i056_image"><img src="../../../assets/cases/i056-after.webp" alt="ملصق صورة للدردشة - نتائج نموذجية" width="320"></a></td></tr></tbody>
</table>

يتم استخدام المواد المرجعية والنتائج لتوضيح الاتجاه البصري. القالب العام ليس تعليمات الإنشاء الأصلية للصور المصاحبة، ولا يمكن ضمان إعادة إنتاج نفس النتائج.

## ما يجب إعداده/المدخلات

| مادة | النوع / النوع | الكمية / الكمية | الحالة/المتطلبات |
| --- | --- | --- | --- |
| صور الأشخاص أو الحيوانات الأليفة أو الأشياء | صورة/صورة | 1 قطعة | مطلوب / مطلوب |
| العمل أو العاطفة لهذا الملصق | الحرف / النص | 0 أو 1 عنصر | اختياري / اختياري |

يتم إنشاء الصورة المحددة حاليًا فقط في المرة الواحدة؛ يتم تنفيذ الصور الأخرى في السلسلة بشكل منفصل.

## الاحتفاظ والتغيير/التحرير الموجز

- **الحفاظ / 保留:** حافظ على إمكانية التعرف على الموضوع واحتفظ بالعلامات أو الميزات المحددة.
- **التغيير / الصورة:** تغيير التعبير، والتركيز على الوضع، والمخطط التفصيلي، وإزالة الخلفية، وتصميم الملصقات.

## Public prompt

**قالب عام تم تحريره حديثًا · مؤلف حديثًا · لم يتم اختباره بواسطة الأجيال. ** استبدل معلمات القوس المربع وأرفق المواد المطلوبة في الأداة التي تدعم تحرير الصور؛ يتم إعداد المدخلات الاختيارية والشرطية حسب الجدول أعلاه. لم يتم استخدام هذا القالب لإنشاء الأمثلة في هذه الصفحة.

```text
Create one chat sticker from [SUBJECT PHOTO].
Preserve the subject’s identity, silhouette, colors, markings, and defining features.
Express [ACTION OR EMOTION] through a clear pose and readable facial or object cues.
Use [STICKER STYLE], a bold clean outline, and simple shading suitable for small display.
Keep hands, paws, limbs, and object edges coherent and uncluttered.
Use a transparent-looking or plain preview background according to [BACKGROUND REQUEST].
If text is requested, reproduce “[EXACT SHORT TEXT]” exactly and keep it legible.
Do not create a sheet, pack, or multiple emotional variants in this run.
If a transparent file is required, verify the exported alpha channel rather than trusting a checkerboard preview.
Deliver one sticker image only; platform sizing and pack assembly are separate steps.
```

[ اجعله متصلاً بالإنترنت باستخدام المواد الخاصة بك / اجعله متصلاً بالإنترنت](https://dearsketch.com/ar/intent/i056-turn-a-photo-into-chat-stickers.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i056_after-prompt) · [دع الوكيل يساعدك في تنظيمه / استخدم Skill](../quickstart.md#agent-skill)

## تحقق من النقاط الرئيسية/المراجعة

يتم تنفيذ الخيار المحدد حاليًا فقط في المرة الواحدة؛ يجب فحص تناسق السلسلة وتغليف ملصق المنصة بشكل منفصل.

تحقق من إمكانية قراءة الحجم الصغير وتذكر أن عبوة المنصة منفصلة.

اتجاه النتيجة: حزمة ملصقات الدردشة. عندما يكون النص الدقيق أو الملفات الشفافة أو المتجهات أو تسليم الطباعة مطلوبًا، تحقق من الملف الفعلي؛ الميزات والرسوم المتاحة تخضع لوصف الموقع.

## الحالات ذات الصلة / المهام ذات الصلة

- [ إنشاء لقطة رأس احترافية على LinkedIn من صورة ذاتية · صورة شخصية إلى لقطة رأس احترافية ](./i001-create-a-professional-linkedin-headshot-from-a-selfie.md#public-prompt)
- [استبدل الملابس غير الرسمية بملابس احترافية · ](./i015-replace-casual-clothing-with-professional-attire.md#public-prompt)
- [حوّل نفسك إلى صورة ملكية أو قديمة أو تاريخية · صورة ملكية وعتيقة ](./i052-turn-yourself-into-a-royal-vintage-or-historical-portrait.md#public-prompt)

## متطلبات الخلفية المرجعية

- [LightXجميع الأدوات](https://www.lightxeditor.com/all-tools/all-tools/)

تهدف هذه الروابط فقط إلى المساعدة في فهم الغرض وليست دليلاً على مصدر الصور الموجودة على هذه الصفحة أو ترخيصها.

للتعرف على نطاق استخدام الصور والمواد، راجع وصف محتوى [ ](../content-policy.md). [عرض جميع النماذج الخمسين ](../prompts.md).


</div>
