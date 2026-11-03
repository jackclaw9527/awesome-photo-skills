# त्वरित शुरुआत · एक केस चुनें, सामग्री बदलें और एक चित्र बनाएं

[中文](../../README.md) · [English](../../README.en.md) · [Português](../../README.pt.md) · [Español](../../README.es.md) · [Français](../../README.fr.md) · [Deutsch](../../README.de.md) · [عربي](../../README.ar.md) · [русский](../../README.ru.md) · [日本語](../../README.ja.md) · [हिंदी](../../README.hi.md)


## एक संकेत कॉपी करें

1. [50 टेम्प्लेट ](./prompts.md) से कार्य चुनें और केस पेज खोलें।
2. यह पुष्टि करने के लिए कि सशर्त सामग्री आप पर लागू होती है या नहीं, सामग्री तालिका में आवश्यक इनपुट तैयार करें।
3. Public prompt की प्रतिलिपि बनाएँ और सामग्री को वर्गाकार कोष्ठक में बदलें। जब आपको छवि संपादन की आवश्यकता हो, तो संबंधित छवि को अपने टूल में संलग्न करें; टेक्स्ट वास्तविक छवि अनुलग्नक को प्रतिस्थापित नहीं कर सकता.
4. एक समय में एक परिणाम तैयार करें और उस मामले की जांच बिंदुओं के अनुसार इसे स्वीकार करें।

एक टेम्प्लेट चुनें, अपने छवि टूल में आवश्यक सामग्री संलग्न करें, उसके प्लेसहोल्डर्स भरें और परिणाम की समीक्षा करें। ये नए public prompts हैं, डेमो छवियों की परीक्षण की गई प्रतिकृतियां नहीं हैं।

## Agent Skill

स्किल "मैं क्या करना चाहता हूं" को एक स्पष्ट इनपुट सूची में परिवर्तित करने, मुख्य बिंदुओं और पूर्ण त्वरित शब्दों को बनाए रखने के लिए जिम्मेदार है, और डिफ़ॉल्ट रूप से भुगतान इंटरफ़ेस को कॉल नहीं करता है। इसमें 50 टेम्प्लेट का अपना संदर्भ शामिल है और एक बार स्थापित होने के बाद यह पूरी लाइब्रेरी पर निर्भर नहीं होता है।

### Codex

इस वेयरहाउस की कौशल निर्देशिका देने के लिए Codex में अंतर्निहित इंस्टॉलर का उपयोग करें:

```text
$skill-installer install the photo-editing skill from
https://github.com/jackclaw9527/awesome-photo-skills/tree/main/skills/photo-editing
```

आप वेयरहाउस को डाउनलोड या क्लोन भी कर सकते हैं और संपूर्ण `skills/photo-editing` फ़ोल्डर को लक्ष्य प्रोजेक्ट के `.agents/skills/` के अंतर्गत रख सकते हैं; यदि समान नाम वाला कोई कौशल है, तो पहले सामग्री की तुलना करें।

फिर उपयोग करें:

```text
$photo-editing 把我的自拍做成自然的职业头像。
先告诉我需要哪些素材，再给我可复制的提示词。
```

अंग्रेजी उदाहरण:

```text
Use $photo-editing to prepare a clean product listing image.
Keep the exact product, tell me what to attach and return a complete prompt.
```

कौशल सूची और इंस्टॉलर का उपयोग [official OpenAI दस्तावेज़](https://learn.chatgpt.com/docs/build-skills) पर आधारित है। Agent Skills का समर्थन करने वाले अन्य टूल के लिए, कृपया संपूर्ण फ़ोल्डर को उनके संबंधित कौशल निर्देशिका नियमों के अनुसार स्थापित करें।

## इसे dearsketch पर बनाएं

यदि आप शीघ्र शब्दों को स्वयं व्यवस्थित नहीं करना चाहते हैं, तो आप सीधे संबंधित कार्य खोल सकते हैं और वेबसाइट की आवश्यकताओं के अनुसार अपनी सामग्री प्रदान कर सकते हैं:

| लक्ष्य | सीधा कार्य |
| --- | --- |
| सेल्फी → प्रोफेशनल हेडशॉट / प्रोफेशनल हेडशॉट | [Start](https://dearsketch.com/hi/intent/i001-create-a-professional-linkedin-headshot-from-a-selfie.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i001_headshot) |
| पालतू जानवरों की तस्वीरें → कलात्मक चित्र / पालतू जानवरों का चित्र | [Start](https://dearsketch.com/hi/intent/i026-turn-a-pet-photo-into-a-custom-portrait.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i026_pet) |
| उत्पाद फ़ोटो → सफ़ेद-पृष्ठभूमि उत्पाद छवि | [Start](https://dearsketch.com/hi/intent/i065-turn-an-ordinary-product-photo-into-a-white-background-listing-image.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i065_product) |
| कमरे की तस्वीरें → सजावट पूर्वावलोकन / कमरे का नया स्वरूप | [Start](https://dearsketch.com/hi/intent/i169-preview-different-interior-styles-in-a-room-photo.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i169_room) |

वेबसाइट अपनी स्वयं की उत्पादन प्रक्रिया बनाए रखती है; सार्वजनिक कौशल के लिए आपको अपना वेबसाइट खाता या सेवा कुंजी सौंपने की आवश्यकता नहीं है, और इसमें निःशुल्क पीढ़ी कोटा शामिल नहीं है। उपलब्ध कार्य और शुल्क वेबसाइट पर तत्कालीन विवरण के अधीन हैं।
