---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "PngViewOptionsgroupdocs.viewer.options/pngviewoptions क्लास का एक उदाहरण प्रारंभ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.viewer.options/pngviewoptions/pngviewoptions/
---

## PngViewOptions(CreatePageStream) {#constructor_1}

[`PngViewOptions`](../../pngviewoptions) क्लास का एक उदाहरण प्रारंभ करता है।

```csharp
public PngViewOptions(CreatePageStream createPageStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | वह मेथड जो आउटपुट पेज डेटा लिखने के लिए स्ट्रीम बनाता है। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *createPageStream* शून्य होने पर फेंका जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png) देखें।

### संबंधित देखें

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

[`PngViewOptions`](../../pngviewoptions) क्लास का एक उदाहरण प्रारंभ करता है।

```csharp
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | वह मेथड जो आउटपुट पेज डेटा लिखने के लिए स्ट्रीम बनाता है। |
| releasePageStream | ReleasePageStream | वह मेथड जो *createPageStream* पैरामीटर को पास किए गए डेलीगेट को असाइन किए गए मेथड द्वारा बनाई गई स्ट्रीम को रिलीज़ करता है। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *createPageStream* शून्य होने पर फेंका जाता है। |
| ArgumentNullException | *releasePageStream* शून्य होने पर फेंका जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png) देखें।

### संबंधित देखें

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(IPageStreamFactory) {#constructor_3}

[`PngViewOptions`](../../pngviewoptions) क्लास का एक उदाहरण प्रारंभ करता है।

```csharp
public PngViewOptions(IPageStreamFactory pageStreamFactory)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | आउटपुट पेज स्ट्रीम बनाने और रिलीज़ करने के लिए विधियों को लागू करने वाला फ़ैक्टरी। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *pageStreamFactory* शून्य होने पर फेंका जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png) देखें।

### संबंधित देखें

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions() {#constructor}

[`PngViewOptions`](../../pngviewoptions) क्लास का एक उदाहरण प्रारंभ करता है।

```csharp
public PngViewOptions()
```

### टिप्पणियाँ

यह कंस्ट्रक्टर [`PngViewOptions`](../../pngviewoptions) का एक उदाहरण प्रारंभ करता है जिसमें आउटपुट फ़ाइलों के लिए "p_{0}.png" को फ़ाइल पथ प्रारूप के रूप में उपयोग किया जाता है। आउटपुट फ़ाइलें एप्लिकेशन की वर्तमान कार्य निर्देशिका में रखी जाती हैं।

कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png) देखें।

### संबंधित देखें

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(string) {#constructor_4}

[`PngViewOptions`](../../pngviewoptions) क्लास का एक उदाहरण प्रारंभ करता है।

```csharp
public PngViewOptions(string filePathFormat)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | String | फ़ाइल पथ प्रारूप, उदाहरण के लिए 'page_{0}.png'। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | *filePathFormat* null या खाली होने पर फेंका जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png) देखें।

### संबंधित देखें

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
