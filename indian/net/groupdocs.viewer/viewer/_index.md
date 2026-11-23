---
title: "व्यूअर"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "दस्तावेज़ रेंडरिंग प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास का प्रतिनिधित्व करता है।"
type: docs
weight: 50
url: /hi/net/groupdocs.viewer/viewer/
---

## Viewer class

दस्तावेज़ रेंडरिंग प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास का प्रतिनिधित्व करता है।

```csharp
public class Viewer : IDisposable
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [Viewer](viewer#constructor)(Func&lt;Stream&gt;) | नई इंस्टेंस को प्रारंभ करता है [`Viewer`](../viewer) क्लास की। |
| [Viewer](viewer#constructor_4)(Stream) | नई इंस्टेंस को प्रारंभ करता है [`Viewer`](../viewer) क्लास की। |
| [Viewer](viewer#constructor_12)(string) | नई इंस्टेंस को प्रारंभ करता है [`Viewer`](../viewer) क्लास की। |
| [Viewer](viewer#constructor_2)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | नई इंस्टेंस को प्रारंभ करता है [`Viewer`](../viewer) क्लास की। |
| [Viewer](viewer#constructor_1)(Func&lt;Stream&gt;, ViewerSettings) | नई इंस्टेंस को प्रारंभ करता है [`Viewer`](../viewer) क्लास की। |
| [Viewer](viewer#constructor_5)(Stream, bool) | नई इंस्टेंस को प्रारंभ करता है [`Viewer`](../viewer) क्लास की। |
| [Viewer](viewer#constructor_6)(Stream, LoadOptions) | नई इंस्टेंस को प्रारंभ करता है [`Viewer`](../viewer) क्लास की। |
| [Viewer](viewer#constructor_10)(Stream, ViewerSettings) | नई इंस्टेंस को प्रारंभ करता है [`Viewer`](../viewer) क्लास की। |
| [Viewer](viewer#constructor_13)(string, LoadOptions) | नई इंस्टेंस को प्रारंभ करता है [`Viewer`](../viewer) क्लास की। |
| [Viewer](viewer#constructor_15)(string, ViewerSettings) | नई इंस्टेंस को प्रारंभ करता है [`Viewer`](../viewer) क्लास की। |
| [Viewer](viewer#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) | नई इंस्टेंस को प्रारंभ करता है [`Viewer`](../viewer) क्लास की। |
| [Viewer](viewer#constructor_7)(Stream, LoadOptions, bool) | नई इंस्टेंस को प्रारंभ करता है [`Viewer`](../viewer) क्लास की। |
| [Viewer](viewer#constructor_8)(Stream, LoadOptions, ViewerSettings) | नई इंस्टेंस को प्रारंभ करता है [`Viewer`](../viewer) क्लास की। |
| [Viewer](viewer#constructor_11)(Stream, ViewerSettings, bool) | नई इंस्टेंस को प्रारंभ करता है [`Viewer`](../viewer) क्लास की। |
| [Viewer](viewer#constructor_14)(string, LoadOptions, ViewerSettings) | नई इंस्टेंस को प्रारंभ करता है [`Viewer`](../viewer) क्लास की। |
| [Viewer](viewer#constructor_9)(Stream, LoadOptions, ViewerSettings, bool) | नई इंस्टेंस को प्रारंभ करता है [`Viewer`](../viewer) क्लास की। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Dispose](../../groupdocs.viewer/viewer/dispose)() | फ़ाइल स्ट्रीम और प्रबंधित आंतरिक संसाधनों को रिलीज़ करता है। |
| [GetAllFonts](../../groupdocs.viewer/viewer/getallfonts)() | लोड किए गए दस्तावेज़ों में उपयोग किए गए सभी फ़ॉन्ट्स को लौटाता है, जिसमें वे भी शामिल हैं जो दस्तावेज़ के भीतर एम्बेडेड हैं और सिस्टम फ़ॉन्ट्स जो OS में स्थापित हैं और दस्तावेज़ में उपयोग होते हैं। |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments)() | दस्तावेज़ में सम्मिलित अटैचमेंट्स को लौटाता है। |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments_1)(CancellationToken) | दस्तावेज़ में सम्मिलित अटैचमेंट्स को लौटाता है। |
| [GetFileInfo](../../groupdocs.viewer/viewer/getfileinfo)() | फ़ाइल के बारे में जानकारी लौटाता है जैसे फ़ाइल प्रकार और वह फ़्लैग जो दर्शाता है कि फ़ाइल एन्क्रिप्टेड है या नहीं। |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo)(ViewInfoOptions) | व्यू और दस्तावेज़-विशिष्ट जानकारी के बारे में जानकारी लौटाता है। |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo_1)(ViewInfoOptions, CancellationToken) | व्यू और दस्तावेज़-विशिष्ट जानकारी के बारे में जानकारी लौटाता है। |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment)(Attachment, Stream) | अटैचमेंट फ़ाइल को *destination* स्ट्रीम में सहेजता है। |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment_1)(Attachment, Stream, CancellationToken) | अटैचमेंट फ़ाइल को *destination* स्ट्रीम में सहेजता है। |
| [Search](../../groupdocs.viewer/viewer/search)(SearchHighlightOptions) | लोड किए गए दस्तावेज़ में लोडेड विकल्पों के अनुसार टेक्स्ट खोज करता है और यदि मिला तो उसे हाइलाइट करता है। |
| [View](../../groupdocs.viewer/viewer/view#view)(ViewOptions) | सभी दस्तावेज़ पृष्ठों का व्यू बनाता है। |
| [View](../../groupdocs.viewer/viewer/view#view_2)(ViewOptions, CancellationToken) | सभी दस्तावेज़ पृष्ठों का व्यू बनाता है। |
| [View](../../groupdocs.viewer/viewer/view#view_1)(ViewOptions, params int[]) | विशिष्ट दस्तावेज़ पृष्ठों का व्यू बनाता है। |
| [View](../../groupdocs.viewer/viewer/view#view_3)(ViewOptions, CancellationToken, params int[]) | विशिष्ट दस्तावेज़ पृष्ठों का व्यू बनाता है। |

### संबंधित देखें

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
