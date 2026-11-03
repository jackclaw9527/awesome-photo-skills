# वर्चुअल आईवियर पूर्वावलोकन · चश्मा ट्राई-ऑन पूर्वावलोकन

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


एक सटीक उत्पाद या वर्णित आईवियर अवधारणा को सामने वाले चित्र पर रखें।

वस्तुतः चश्मे पर प्रयास करें। क्रय निर्णयों में उपयोग किया जाता है।

[कॉपी प्रॉम्प्ट](#public-prompt) · [ dearsketch द्वारा निर्मित है / ऑनलाइन प्रयास करें](https://dearsketch.com/hi/intent/i036-virtually-try-on-glasses.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i036_cta) · [विषय पर लौटें / संग्रह](../guides/people.md)

## संदर्भ सामग्री एवं परिणाम दिशा

<table>
<thead><tr><th width="50%">संदर्भ सामग्री</th><th width="50%">परिणामों का उदाहरण</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>व्यक्ति की सामने की तस्वीर</strong><br><img src="../../../assets/cases/i036-before-1.webp" alt="चश्मे का प्रयास-पूर्वावलोकन - संदर्भ सामग्री 1" width="320"></p>
<p><strong>लक्ष्य चश्मा उत्पाद छवि</strong><br><img src="../../../assets/cases/i036-before-2.webp" alt="चश्मे का प्रयास-पूर्वावलोकन - संदर्भ सामग्री 2" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/hi/intent/i036-virtually-try-on-glasses.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i036_image"><img src="../../../assets/cases/i036-after.webp" alt="चश्मा आज़माने का पूर्वावलोकन - उदाहरण परिणाम" width="320"></a></td></tr></tbody>
</table>

दृश्य दिशा को स्पष्ट करने के लिए संदर्भ सामग्री और परिणामों का उपयोग किया जाता है। सार्वजनिक टेम्प्लेट संलग्न छवियों के लिए मूल पीढ़ी निर्देश नहीं है, और समान परिणामों को पुन: प्रस्तुत करने की गारंटी नहीं है।

## क्या तैयारी करनी है/इनपुट

| सामग्री | प्रकार/प्रकार | मात्रा/मात्रा | शर्त/आवश्यकता |
| --- | --- | --- | --- |
| व्यक्ति की सामने की तस्वीर | चित्र/छवि | 1 टुकड़ा | आवश्यक/आवश्यक |
| लक्ष्य चश्मे की सामग्री या शैली विवरण | चित्र/छवि | 1 टुकड़ा | सशर्त/सशर्त: सटीक उत्पाद परीक्षण के लिए आवश्यक; केवल अवधारणा शैलियों को पाठ के साथ वर्णित किया जा सकता है |

एक समय में केवल एक ही छवि उत्पन्न होती है।

## संक्षिप्त बनाए रखें और बदलें/संपादन करें

- **संरक्षित करें / संपादित करें:** चुनी गई शाखा के लिए पहचान, चेहरे का आकार, त्वचा, आंखें और आपूर्ति किए गए फ्रेम विवरण रखें।
- **बदलें / बदलाव:** केवल फ्रेम प्लेसमेंट, लेंस उपस्थिति और न्यूनतम प्रकाश एकीकरण बदलें।

## Public prompt

** नव संपादित सार्वजनिक टेम्पलेट · ​​नव लिखित · पीढ़ी-परीक्षण नहीं किया गया। ** वर्गाकार ब्रैकेट पैरामीटर बदलें और छवि संपादन का समर्थन करने वाले टूल में आवश्यक सामग्री संलग्न करें; उपरोक्त तालिका के अनुसार वैकल्पिक और सशर्त इनपुट तैयार किए जाते हैं। इस पृष्ठ पर उदाहरण उत्पन्न करने के लिए इस टेम्पलेट का उपयोग नहीं किया गया था।

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

[इसे अपनी सामग्री से ऑनलाइन बनाएं / इसे ऑनलाइन बनाएं](https://dearsketch.com/hi/intent/i036-virtually-try-on-glasses.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i036_after-prompt) · [एजेंट को इसे व्यवस्थित करने में मदद करने दें / कौशल का उपयोग करें](../quickstart.md#agent-skill)

## मुख्य बिंदुओं की जाँच करें/समीक्षा करें

यदि आप किसी विशिष्ट उत्पाद को आज़माना चाहते हैं, तो संबंधित शैली चित्र प्रदान करें; उत्पन्न चित्र वास्तविक आकार और पहनने के आराम को साबित नहीं कर सकता।

पुल, मंदिर, परिप्रेक्ष्य की जाँच करें और ध्यान दें कि फिट और आराम असत्यापित हैं।

परिणाम दिशा: चश्मा ट्राई-ऑन चार्ट। जब सटीक पाठ, पारदर्शी फ़ाइलें, वैक्टर या प्रिंट डिलीवरी की आवश्यकता हो, तो वास्तविक फ़ाइल की जाँच करें; उपलब्ध सुविधाएँ और शुल्क वेबसाइट विवरण के अधीन हैं।

## संबंधित मामले/संबंधित कार्य

- [सेल्फ़ी से पेशेवर लिंक्डइन हेडशॉट बनाएं · सेल्फी से पेशेवर हेडशॉट ](./i001-create-a-professional-linkedin-headshot-from-a-selfie.md#public-prompt)
- [ कैज़ुअल कपड़ों को पेशेवर पोशाक से बदलें · ](./i015-replace-casual-clothing-with-professional-attire.md#public-prompt)
- [अपने आप को एक शाही, पुराने या ऐतिहासिक चित्र में बदलें · शाही और पुराने चित्र ](./i052-turn-yourself-into-a-royal-vintage-or-historical-portrait.md#public-prompt)

## आवश्यकताएँ पृष्ठभूमि संदर्भ

- [Picsart AI टूल](https://picsart.com/ai/)

ये लिंक केवल उद्देश्य को समझने में सहायता के लिए हैं और इस पृष्ठ पर छवियों के स्रोत या प्राधिकरण का प्रमाण नहीं हैं।

चित्रों और सामग्रियों के उपयोग के दायरे के लिए, [ सामग्री विवरण ](../content-policy.md) देखें। [सभी 50 टेम्पलेट देखें ](../prompts.md).
