---
title: "ForEmbeddedResources"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "HTML में एम्बेडेड संसाधनों के साथ रेंडर करने के लिए HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions क्लास का एक उदाहरण प्रारंभ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.viewer.options/htmlviewoptions/forembeddedresources/
---

## ForEmbeddedResources(CreatePageStream) {#forembeddedresources_1}

[`HtmlViewOptions`](../../htmlviewoptions) क्लास का एक उदाहरण प्रारंभ करता है जो एम्बेडेड संसाधनों के साथ HTML में रेंडर करता है।

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | वह मेथड जो आउटपुट पेज डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंशिएट करता है। |

### वापसी मान

एंबेडेड संसाधनों के साथ HTML में रेंडर करने के लिए नया [`HtmlViewOptions`](../../htmlviewoptions) क्लास का उदाहरण।

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *createPageStream* शून्य होने पर फेंका जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources) देखें।

### संबंधित देखें

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(CreatePageStream, ReleasePageStream) {#forembeddedresources_2}

[`HtmlViewOptions`](../../htmlviewoptions) क्लास का एक उदाहरण प्रारंभ करता है जो एम्बेडेड संसाधनों के साथ HTML में रेंडर करता है।

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | वह मेथड जो आउटपुट पेज डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंशिएट करता है। |
| releasePageStream | ReleasePageStream | *createPageStream* पैरामीटर को पास किए गए डेलीगेट को असाइन की गई विधि द्वारा बनाई गई स्ट्रीम को रिलीज़ करने वाली विधि। |

### वापसी मान

एंबेडेड संसाधनों के साथ HTML में रेंडर करने के लिए नया [`HtmlViewOptions`](../../htmlviewoptions) क्लास का उदाहरण।

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *createPageStream* शून्य होने पर फेंका जाता है। |
| ArgumentNullException | *releasePageStream* शून्य होने पर फेंका जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources) देखें।

### संबंधित देखें

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(IPageStreamFactory) {#forembeddedresources_3}

[`HtmlViewOptions`](../../htmlviewoptions) क्लास का एक उदाहरण प्रारंभ करता है जो एम्बेडेड संसाधनों के साथ HTML में रेंडर करता है।

```csharp
public static HtmlViewOptions ForEmbeddedResources(IPageStreamFactory pageStreamFactory)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | आउटपुट पेज स्ट्रीम बनाने और रिलीज़ करने के लिए विधियों को लागू करने वाला फ़ैक्टरी। |

### वापसी मान

एंबेडेड संसाधनों के साथ HTML में रेंडर करने के लिए नया [`HtmlViewOptions`](../../htmlviewoptions) क्लास का उदाहरण।

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *pageStreamFactory* शून्य होने पर फेंका जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources) देखें।

### संबंधित देखें

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources() {#forembeddedresources}

[`HtmlViewOptions`](../../htmlviewoptions) क्लास का एक उदाहरण इनिशियलाइज़ करता है।

```csharp
public static HtmlViewOptions ForEmbeddedResources()
```

### टिप्पणियाँ

कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources) देखें।

### संबंधित देखें

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(string) {#forembeddedresources_4}

[`HtmlViewOptions`](../../htmlviewoptions) क्लास का एक उदाहरण इनिशियलाइज़ करता है।

```csharp
public static HtmlViewOptions ForEmbeddedResources(string filePathFormat)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | String | फ़ाइल पाथ फ़ॉर्मेट, उदाहरण के लिए 'page_{0}.html'। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | *filePathFormat* null या खाली होने पर फेंका जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources) देखें।

### संबंधित देखें

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
