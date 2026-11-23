---
title: "ForExternalResources"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "HTML में बाहरी संसाधनों के साथ रेंडर करने के लिए HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions क्लास का एक इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
weight: 20
url: /hi/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

HtmlViewOptions क्लास का एक इंस्टेंस इनिशियलाइज़ करता है [`HtmlViewOptions`](../../htmlviewoptions) के लिए, जो बाहरी संसाधनों के साथ HTML में रेंडर करने हेतु उपयोग होता है।

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | वह मेथड जो आउटपुट पेज डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंशिएट करता है। |
| createResourceStream | CreateResourceStream | वह मेथड जो *createPageStream* मेथड द्वारा निर्मित स्ट्रीम को रिलीज़ करता है। |
| createResourceUrl | CreateResourceUrl | HTML संसाधन के लिए URL बनाने वाली विधि। |

### वापसी मान

बाहरी संसाधनों के साथ HTML में रेंडर करने के लिए [`HtmlViewOptions`](../../htmlviewoptions) क्लास का नया उदाहरण।

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *createPageStream* शून्य होने पर फेंका जाता है। |
| ArgumentNullException | *createResourceStream* शून्य होने पर फेंका जाता है। |
| ArgumentNullException | *createResourceUrl* शून्य होने पर फेंका जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources) देखें।

### संबंधित देखें

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

HtmlViewOptions क्लास का एक इंस्टेंस इनिशियलाइज़ करता है [`HtmlViewOptions`](../../htmlviewoptions) के लिए, जो बाहरी संसाधनों के साथ HTML में रेंडर करने हेतु उपयोग होता है।

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | वह मेथड जो आउटपुट पेज डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंशिएट करता है। |
| createResourceStream | CreateResourceStream | आउटपुट HTML संसाधन डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंसिएट करने वाली विधि। |
| createResourceUrl | CreateResourceUrl | HTML संसाधन के लिए URL बनाने वाली विधि। |
| releasePageStream | ReleasePageStream | *createPageStream* पैरामीटर को पास किए गए डेलीगेट को असाइन की गई विधि द्वारा बनाई गई स्ट्रीम को रिलीज़ करने वाली विधि। |
| releaseResourceStream | ReleaseResourceStream | *createResourceStream* पैरामीटर को पास किए गए डेलीगेट को असाइन की गई विधि द्वारा बनाई गई स्ट्रीम को रिलीज़ करने वाली विधि। |

### वापसी मान

बाहरी संसाधनों के साथ HTML में रेंडर करने के लिए [`HtmlViewOptions`](../../htmlviewoptions) क्लास का नया उदाहरण।

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *createPageStream* शून्य होने पर फेंका जाता है। |
| ArgumentNullException | *createResourceStream* शून्य होने पर फेंका जाता है। |
| ArgumentNullException | *createResourceUrl* शून्य होने पर फेंका जाता है। |
| ArgumentNullException | *releasePageStream* शून्य होने पर फेंका जाता है। |
| ArgumentNullException | *releaseResourceStream* शून्य होने पर फेंका जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources) देखें।

### संबंधित देखें

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

HtmlViewOptions क्लास का एक इंस्टेंस इनिशियलाइज़ करता है [`HtmlViewOptions`](../../htmlviewoptions) के लिए, जो बाहरी संसाधनों के साथ HTML में रेंडर करने हेतु उपयोग होता है।

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | आउटपुट पेज स्ट्रीम बनाने और रिलीज़ करने के लिए विधियों को लागू करने वाला फ़ैक्टरी। |
| resourceStreamFactory | IResourceStreamFactory | संसाधन URL बनाने, इंस्टैंसिएट करने और आउटपुट HTML संसाधन स्ट्रीम को रिलीज़ करने के लिए आवश्यक विधियों को लागू करने वाला फ़ैक्टरी। |

### वापसी मान

बाहरी संसाधनों के साथ HTML में रेंडर करने के लिए [`HtmlViewOptions`](../../htmlviewoptions) क्लास का नया उदाहरण।

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *pageStreamFactory* शून्य होने पर फेंका जाता है। |
| ArgumentNullException | *resourceStreamFactory* शून्य होने पर फेंका जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources) देखें।

### संबंधित देखें

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

[`HtmlViewOptions`](../../htmlviewoptions) क्लास का एक उदाहरण इनिशियलाइज़ करता है।

```csharp
public static HtmlViewOptions ForExternalResources()
```

### टिप्पणियाँ

यह कन्स्ट्रक्टर [`HtmlViewOptions`](../../htmlviewoptions) का एक उदाहरण इनिशियलाइज़ करता है।

* with "p_{0}.html" as file path format for the output HTML files
* with "p_{0}_{1}" as file path format for the output HTML-resource files
* with "p_{0}_{1}" as URL format for HTML-resources

आउटपुट फ़ाइलें एप्लिकेशन की वर्तमान कार्य निर्देशिका में रखी जाएँगी।

कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources) देखें।

### संबंधित देखें

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

[`HtmlViewOptions`](../../htmlviewoptions) क्लास का एक उदाहरण इनिशियलाइज़ करता है।

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | String | फ़ाइल पाथ फ़ॉर्मेट, उदाहरण के लिए 'page_{0}.html'। |
| resourceFilePathFormat | String | संसाधन फ़ाइल पथ प्रारूप, उदाहरण के लिए 'page_{0}/resource_{1}'। |
| resourceUrlFormat | String | संसाधन URL प्रारूप, उदाहरण के लिए 'page_{0}/resource_{1}'। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | *filePathFormat* null या खाली होने पर फेंका जाता है। |
| ArgumentException | *resourceFilePathFormat* null या खाली होने पर फेंका जाता है। |
| ArgumentException | *resourceUrlFormat* null या खाली होने पर फेंका जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources) देखें।

### संबंधित देखें

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
