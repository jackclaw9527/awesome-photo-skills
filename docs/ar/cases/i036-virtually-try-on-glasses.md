<div dir="rtl" align="right">

# معاينة النظارات الافتراضية · معاينة تجربة النظارات

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


ضع منتجًا محددًا أو مفهوم النظارات الموصوف على الصورة الأمامية.

حاول عمليا على النظارات. المستخدمة في قرارات الشراء.

[مطالبة النسخ](#public-prompt) · تم إنتاج [ بواسطة dearsketch / جرب عبر الإنترنت](https://dearsketch.com/ar/intent/i036-virtually-try-on-glasses.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i036_cta) · [العودة إلى الموضوع / المجموعة](../guides/people.md)

## المواد المرجعية واتجاه النتيجة

<table>
<thead><tr><th width="50%">المواد المرجعية</th><th width="50%">مثال على النتائج</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>صورة أمامية للشخص</strong><br><img src="../../../assets/cases/i036-before-1.webp" alt="معاينة تجربة النظارات - المادة المرجعية 1" width="320"></p>
<p><strong>صورة منتج النظارات المستهدفة</strong><br><img src="../../../assets/cases/i036-before-2.webp" alt="معاينة تجربة النظارات - المادة المرجعية 2" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/ar/intent/i036-virtually-try-on-glasses.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i036_image"><img src="../../../assets/cases/i036-after.webp" alt="معاينة تجربة النظارات - نتائج الأمثلة" width="320"></a></td></tr></tbody>
</table>

يتم استخدام المواد المرجعية والنتائج لتوضيح الاتجاه البصري. القالب العام ليس تعليمات الإنشاء الأصلية للصور المصاحبة، ولا يمكن ضمان إعادة إنتاج نفس النتائج.

## ما يجب إعداده/المدخلات

| مادة | النوع / النوع | الكمية / الكمية | الحالة/المتطلبات |
| --- | --- | --- | --- |
| صورة أمامية للشخص | صورة/صورة | 1 قطعة | مطلوب / مطلوب |
| مادة النظارات المستهدفة أو وصف النمط | صورة/صورة | 1 قطعة | مشروط/مشروط: مطلوب للتجربة الدقيقة للمنتج؛ يمكن وصف أنماط المفاهيم فقط بالنص |

يتم إنشاء صورة واحدة فقط في كل مرة.

## الاحتفاظ والتغيير/التحرير الموجز

- **الحفاظ / 保留:** احتفظ بالهوية وشكل الوجه والجلد والعينين وتفاصيل الإطار المرفقة للفرع المختار.
- **التغيير / 改变:** قم بتغيير موضع الإطار ومظهر العدسة والحد الأدنى من تكامل الإضاءة فقط.

## Public prompt

**قالب عام تم تحريره حديثًا · مؤلف حديثًا · لم يتم اختباره بواسطة الأجيال. ** استبدل معلمات القوس المربع وأرفق المواد المطلوبة في الأداة التي تدعم تحرير الصور؛ يتم إعداد المدخلات الاختيارية والشرطية حسب الجدول أعلاه. لم يتم استخدام هذا القالب لإنشاء الأمثلة في هذه الصفحة.

```text
Create one eyewear preview using [FRONT-FACING PERSON PHOTO].
Choose one eyewear branch: use [EYEWEAR PRODUCT IMAGE] for an exact product, or [FRAME STYLE DESCRIPTION] for a concept; do not require both.
Preserve the person’s identity, face shape, eyes, eyebrows, skin tone, hair, and expression.
For the product-image branch, preserve the frame silhouette, color, material, bridge, and temple design exactly.
For the description branch, create only the described frame characteristics without implying a real product match.
Align the frame to the eyes, nose bridge, ears, head angle, and camera perspective.
Render [CLEAR / TINTED / PRESCRIPTION-LIKE] lenses with plausible reflections.
Do not reshape the face or claim exact sizing, optical correction, comfort, or real-world fit.
Keep the original portrait background unless [BACKGROUND CHANGE] is requested.
Deliver one preview image only.
```

[ اجعله متصلاً بالإنترنت باستخدام المواد الخاصة بك / اجعله متصلاً بالإنترنت](https://dearsketch.com/ar/intent/i036-virtually-try-on-glasses.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i036_after-prompt) · [دع الوكيل يساعدك في تنظيمه / استخدم Skill](../quickstart.md#agent-skill)

## تحقق من النقاط الرئيسية/المراجعة

إذا كنت ترغب في تجربة منتج معين، فقدم صورة النمط المطابق؛ الصورة التي تم إنشاؤها لا يمكن أن تثبت الحجم الفعلي وراحة الارتداء.

تحقق من الجسر والمعابد والمنظور ولاحظ أن الملاءمة والراحة لم يتم التحقق منها بعد.

اتجاه النتيجة: مخطط تجربة النظارات. عندما يكون النص الدقيق أو الملفات الشفافة أو المتجهات أو تسليم الطباعة مطلوبًا، تحقق من الملف الفعلي؛ الميزات والرسوم المتاحة تخضع لوصف الموقع.

## الحالات ذات الصلة / المهام ذات الصلة

- [ إنشاء لقطة رأس احترافية على LinkedIn من صورة ذاتية · صورة شخصية إلى لقطة رأس احترافية ](./i001-create-a-professional-linkedin-headshot-from-a-selfie.md#public-prompt)
- [استبدل الملابس غير الرسمية بملابس احترافية · ](./i015-replace-casual-clothing-with-professional-attire.md#public-prompt)
- [حوّل نفسك إلى صورة ملكية أو قديمة أو تاريخية · صورة ملكية وعتيقة ](./i052-turn-yourself-into-a-royal-vintage-or-historical-portrait.md#public-prompt)

## متطلبات الخلفية المرجعية

- [ أداة Picsart AI](https://picsart.com/ai/)

تهدف هذه الروابط فقط إلى المساعدة في فهم الغرض وليست دليلاً على مصدر الصور الموجودة على هذه الصفحة أو ترخيصها.

للتعرف على نطاق استخدام الصور والمواد، راجع وصف محتوى [ ](../content-policy.md). [عرض جميع النماذج الخمسين ](../prompts.md).


</div>
