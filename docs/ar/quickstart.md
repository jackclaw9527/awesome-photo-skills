<div dir="rtl" align="right">

# بداية سريعة · حدد حالة، وقم بتغيير المواد، وقم بإنشاء صورة

[中文](../../README.md) · [English](../../README.en.md) · [Português](../../README.pt.md) · [Español](../../README.es.md) · [Français](../../README.fr.md) · [Deutsch](../../README.de.md) · [عربي](../../README.ar.md) · [русский](../../README.ru.md) · [日本語](../../README.ja.md) · [हिंदी](../../README.hi.md)


## انسخ مطالبة

1. حدد المهام من قوالب [50 ](./prompts.md) وافتح صفحة الحالة.
2. قم بإعداد المدخلات المطلوبة في جدول المواد للتأكد من أن المادة الشرطية تنطبق عليك.
3. انسخ Public prompt واستبدل المحتوى الموجود بين قوسين مربعين. عندما تحتاج إلى تحرير الصور، قم بإرفاق الصورة المقابلة لأداتك؛ لا يمكن للنص أن يحل محل مرفق الصورة الفعلي.
4. قم بإنتاج نتيجة واحدة في كل مرة واقبلها وفقًا لنقاط التفتيش الخاصة بهذه الحالة.

اختر قالبًا، وأرفق المواد المطلوبة في أداة الصور الخاصة بك، واملأ العناصر النائبة الخاصة به وراجع النتيجة. هذه هي صور public prompt الجديدة، ولم يتم اختبارها كنسخ من الصور التجريبية.

## Agent Skill

المهارة هي المسؤولة عن تحويل "ماذا أريد أن أفعل" إلى قائمة إدخال واضحة، مع الاحتفاظ بالنقاط الرئيسية والكلمات السريعة الكاملة، ولا تستدعي واجهة الدفع افتراضيًا. يحتوي على مرجع خاص به مكون من 50 قالبًا ولا يعتمد على المكتبة بأكملها بمجرد تثبيتها.

### Codex

استخدم المثبت المدمج في Codex لإعطاء دليل المهارات لهذا المستودع:

```text
$skill-installer install the photo-editing skill from
https://github.com/jackclaw9527/awesome-photo-skills/tree/main/skills/photo-editing
```

يمكنك أيضًا تنزيل المستودع أو استنساخه ووضع المجلد `skills/photo-editing` الكامل ضمن `.agents/skills/` للمشروع المستهدف؛ إذا كانت هناك مهارة بنفس الاسم، قارن المحتويات أولاً.

ثم استخدم:

```text
$photo-editing 把我的自拍做成自然的职业头像。
先告诉我需要哪些素材，再给我可复制的提示词。
```

مثال باللغة الإنجليزية:

```text
Use $photo-editing to prepare a clean product listing image.
Keep the exact product, tell me what to attach and return a complete prompt.
```

يعتمد كتالوج المهارات واستخدام أداة التثبيت على وثائق [ الرسمية OpenAI](https://learn.chatgpt.com/docs/build-skills). بالنسبة للأدوات الأخرى التي تدعم Agent Skills، يرجى تثبيت المجلد بأكمله وفقًا لقواعد دليل المهارات الخاصة بها.

## اصنعها على dearsketch

إذا كنت لا ترغب في تنظيم الكلمات السريعة بنفسك، فيمكنك فتح المهمة المقابلة مباشرةً وتوفير المواد الخاصة بك وفقًا لمتطلبات موقع الويب:

| هدف | مهمة مباشرة |
| --- | --- |
| صورة شخصية → لقطة رأس احترافية / لقطة رأس احترافية | [البدء](https://dearsketch.com/ar/intent/i001-create-a-professional-linkedin-headshot-from-a-selfie.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i001_headshot) |
| صور الحيوانات الأليفة → صورة فنية / صورة للحيوانات الأليفة | [البدء](https://dearsketch.com/ar/intent/i026-turn-a-pet-photo-into-a-custom-portrait.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i026_pet) |
| صورة المنتج → صورة المنتج بخلفية بيضاء | [البدء](https://dearsketch.com/ar/intent/i065-turn-an-ordinary-product-photo-into-a-white-background-listing-image.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i065_product) |
| صور الغرفة → معاينة الديكور / إعادة تصميم الغرفة | [البدء](https://dearsketch.com/ar/intent/i169-preview-different-interior-styles-in-a-room-photo.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i169_room) |

يحتفظ الموقع بعملية الإنتاج الخاصة به؛ لا تتطلب منك المهارات العامة تسليم حساب موقع الويب الخاص بك أو مفتاح الخدمة، ولا تتضمن حصة الجيل المجانية. تخضع الوظائف والرسوم المتاحة للوصف الحالي الموجود على الموقع.


</div>
