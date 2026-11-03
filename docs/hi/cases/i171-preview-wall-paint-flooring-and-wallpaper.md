# पेंट, फर्श और वॉलपेपर पूर्वावलोकन · दीवार पेंट और फर्श सामग्री चयन पूर्वावलोकन

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


निर्दिष्ट कमरे की सतहों को आपूर्ति किए गए नमूने या सटीक रंग और सामग्री विवरण का उपयोग करके बदलें।

दीवार पेंट, फर्श और वॉलपेपर प्रभावों का पूर्वावलोकन करें। सजावट सामग्री चयन के लिए उपयोग किया जाता है।

[कॉपी प्रॉम्प्ट](#public-prompt) · [ dearsketch द्वारा निर्मित है / ऑनलाइन प्रयास करें](https://dearsketch.com/hi/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i171_cta) · [विषय पर लौटें / संग्रह](../guides/spaces.md)

## संदर्भ सामग्री एवं परिणाम दिशा

<table>
<thead><tr><th width="50%">संदर्भ सामग्री</th><th width="50%">परिणामों का उदाहरण</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>इनडोर तस्वीरें</strong><br><img src="../../../assets/cases/i171-before-1.webp" alt="दीवार पेंट और फर्श सामग्री चयन पूर्वावलोकन - संदर्भ सामग्री 1" width="320"></p>
<p><strong>लक्ष्य सामग्री टेम्पलेट</strong><br><img src="../../../assets/cases/i171-before-2.webp" alt="दीवार पेंट और फर्श सामग्री चयन पूर्वावलोकन - संदर्भ सामग्री 2" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/hi/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i171_image"><img src="../../../assets/cases/i171-after.webp" alt="दीवार पेंट और फर्श सामग्री चयन पूर्वावलोकन - उदाहरण परिणाम" width="320"></a></td></tr></tbody>
</table>

दृश्य दिशा को स्पष्ट करने के लिए संदर्भ सामग्री और परिणामों का उपयोग किया जाता है। सार्वजनिक टेम्प्लेट संलग्न छवियों के लिए मूल पीढ़ी निर्देश नहीं है, और समान परिणामों को पुन: प्रस्तुत करने की गारंटी नहीं है।

## क्या तैयारी करनी है/इनपुट

| सामग्री | प्रकार/प्रकार | मात्रा/मात्रा | शर्त/आवश्यकता |
| --- | --- | --- | --- |
| इनडोर तस्वीरें | चित्र/छवि | 1 टुकड़ा | आवश्यक/आवश्यक |
| लक्ष्य सामग्री टेम्पलेट | चित्र/छवि | 0-1 छवि; सटीक पाठ या रंग डेटा का भी उपयोग किया जा सकता है | सशर्त: जब आपको विशिष्ट बनावट या उत्पाद के नमूनों को पुन: पेश करने की आवश्यकता होती है |
| सतह को लक्ष्य रंग/सामग्री से बदलें | चरित्र/पाठ | 1 सर्विंग | आवश्यक/आवश्यक |

एक समय में केवल एक ही छवि उत्पन्न होती है।

## संक्षिप्त बनाए रखें और बदलें/संपादन करें

- **संरक्षित करें / चेतावनी:** कमरे की संरचना, प्रकाश तर्क, वस्तु स्थान और अलक्षित सतहों को रखें।
- **बदलें / बदलाव:** केवल नामित दीवारें, फर्श, या वॉलपेपर क्षेत्र बदलें।

## Public prompt

** नव संपादित सार्वजनिक टेम्पलेट · ​​नव लिखित · पीढ़ी-परीक्षण नहीं किया गया। ** वर्गाकार ब्रैकेट पैरामीटर बदलें और छवि संपादन का समर्थन करने वाले टूल में आवश्यक सामग्री संलग्न करें; उपरोक्त तालिका के अनुसार वैकल्पिक और सशर्त इनपुट तैयार किए जाते हैं। इस पृष्ठ पर उदाहरण उत्पन्न करने के लिए इस टेम्पलेट का उपयोग नहीं किया गया था।

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

[इसे अपनी सामग्री से ऑनलाइन बनाएं / इसे ऑनलाइन बनाएं](https://dearsketch.com/hi/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i171_after-prompt) · [एजेंट को इसे व्यवस्थित करने में मदद करने दें / कौशल का उपयोग करें](../quickstart.md#agent-skill)

## मुख्य बिंदुओं की जाँच करें/समीक्षा करें

निर्दिष्ट उत्पादों को नमूने या सटीक रंग की जानकारी प्रदान करनी चाहिए; स्क्रीन छवि वास्तविक उत्पाद के समान रंग अंतर की गारंटी नहीं दे सकती।

जब कोई नमूना मौजूद हो तो उसकी तुलना करें और चेतावनी दें कि स्क्रीन वास्तविक भौतिक रंग की गारंटी नहीं दे सकती।

परिणाम दिशा: सामग्री प्रभाव पूर्वावलोकन. जब सटीक पाठ, पारदर्शी फ़ाइलें, वैक्टर या प्रिंट डिलीवरी की आवश्यकता हो, तो वास्तविक फ़ाइल की जाँच करें; उपलब्ध सुविधाएँ और शुल्क वेबसाइट विवरण के अधीन हैं।

## संबंधित मामले/संबंधित कार्य

- [घर की तस्वीर को जल रंग या रेखा-कला स्मृति चिन्ह में बदलें · आवासीय जल रंग स्मारक पेंटिंग ](./i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.md#public-prompt)
- [एक कमरे के फोटो में विभिन्न आंतरिक शैलियों का पूर्वावलोकन करें · कमरे की सजावट शैली का पूर्वावलोकन](./i169-preview-different-interior-styles-in-a-room-photo.md#public-prompt)
- [एक यार्ड फोटो से एक लैंडस्केप मेकओवर अवधारणा बनाएं · यार्ड लैंडस्केप नवीनीकरण ](./i178-create-a-landscape-makeover-concept-from-a-yard-photo.md#public-prompt)

## आवश्यकताएँ पृष्ठभूमि संदर्भ

- [LightXसभी टूल](https://www.lightxeditor.com/all-tools/all-tools/)
- [Adobe होम कॉन्सेप्ट](https://www.adobe.com/products/firefly/features/ai-room-design/home-design.html)

ये लिंक केवल उद्देश्य को समझने में सहायता के लिए हैं और इस पृष्ठ पर छवियों के स्रोत या प्राधिकरण का प्रमाण नहीं हैं।

चित्रों और सामग्रियों के उपयोग के दायरे के लिए, [ सामग्री विवरण ](../content-policy.md) देखें। [सभी 50 टेम्पलेट देखें ](../prompts.md).
