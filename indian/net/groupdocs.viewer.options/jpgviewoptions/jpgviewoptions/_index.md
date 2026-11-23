---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "JpgViewOptionsgroupdocs.viewer.options/jpgviewoptions क्लास का एक इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.viewer.options/jpgviewoptions/jpgviewoptions/
---

## JpgViewOptions(CreatePageStream) {#constructor_1}

[`JpgViewOptions`](../../jpgviewoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public JpgViewOptions(CreatePageStream createPageStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | वह मेथड जो आउटपुट पेज डेटा लिखने के लिए स्ट्रीम बनाता है। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *createPageStream* शून्य होने पर फेंका जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, देखें [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg)।

### संबंधित देखें

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

[`JpgViewOptions`](../../jpgviewoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
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

कोड उदाहरण के लिए, देखें [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg)।

### संबंधित देखें

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(IPageStreamFactory) {#constructor_3}

[`JpgViewOptions`](../../jpgviewoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public JpgViewOptions(IPageStreamFactory pageStreamFactory)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | आउटपुट पेज स्ट्रीम बनाने और रिलीज़ करने के लिए विधियों को लागू करने वाला फ़ैक्टरी। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *pageStreamFactory* शून्य होने पर फेंका जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, देखें [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg)।

### संबंधित देखें

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions() {#constructor}

[`JpgViewOptions`](../../jpgviewoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public JpgViewOptions()
```

### टिप्पणियाँ

यह कंस्ट्रक्टर [`JpgViewOptions`](../../jpgviewoptions) का एक इंस्टेंस इनिशियलाइज़ करता है जिसमें आउटपुट फ़ाइलों के लिए "p_{0}.jpg" को फ़ाइल पाथ फ़ॉर्मेट के रूप में उपयोग किया जाता है। आउटपुट फ़ाइलें एप्लिकेशन की वर्तमान कार्य निर्देशिका में रखी जाती हैं।

कोड उदाहरण के लिए, देखें [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg)।

### संबंधित देखें

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(string) {#constructor_4}

[`JpgViewOptions`](../../jpgviewoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public JpgViewOptions(string filePathFormat)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | String | फ़ाइल पाथ फ़ॉर्मेट उदाहरण के लिए 'page_{0}.jpg'। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | *filePathFormat* null या खाली होने पर फेंका जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, देखें [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg)।

### संबंधित देखें

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
