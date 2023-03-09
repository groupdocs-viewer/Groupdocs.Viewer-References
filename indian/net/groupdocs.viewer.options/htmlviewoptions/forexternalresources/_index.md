---
title: ForExternalResources
second_title: .NET API संदर्भ के लिए GroupDocs.Viewer
description: क नय उदहरण शुरू करत हैHtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions बहर संसधनं के सथ HTML में रेंडर करने के लए क्लस.
type: docs
weight: 20
url: /hi/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---
## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

का नया उदाहरण शुरू करता है[`HtmlViewOptions`](../../htmlviewoptions) बाहरी संसाधनों के साथ HTML में रेंडर करने के लिए क्लास.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | आउटपुट पेज डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| createResourceStream | CreateResourceStream | वह विधि जो द्वारा बनाई गई स्ट्रीम को रिलीज़ करती है*createPageStream* तरीका। |
| createResourceUrl | CreateResourceUrl | वह विधि जो HTML संसाधन के लिए URL बनाती है। |

### प्रतिलाभ की मात्रा

का नया उदाहरण[`HtmlViewOptions`](../../htmlviewoptions) बाह्य संसाधनों के साथ HTML में प्रतिपादन के लिए वर्ग।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*createPageStream* शून्य है। |
| ArgumentNullException | कब फेंका*createResourceStream* शून्य है। |
| ArgumentNullException | कब फेंका*createResourceUrl* शून्य है। |

### यह सभी देखें

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* नाम स्थान [GroupDocs.Viewer.Options](../../htmlviewoptions)
* सभा [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

का नया उदाहरण शुरू करता है[`HtmlViewOptions`](../../htmlviewoptions) बाहरी संसाधनों के साथ HTML में रेंडर करने के लिए क्लास.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | आउटपुट पेज डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| createResourceStream | CreateResourceStream | आउटपुट HTML संसाधन डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| createResourceUrl | CreateResourceUrl | वह विधि जो HTML संसाधन के लिए URL बनाती है। |
| releasePageStream | ReleasePageStream | वह विधि जो उस विधि द्वारा बनाई गई स्ट्रीम को जारी करती है जिसे पारित करने वाले प्रतिनिधि को सौंपा गया है*createPageStream* पैरामीटर। |
| releaseResourceStream | ReleaseResourceStream | वह विधि जो उस विधि द्वारा बनाई गई स्ट्रीम को जारी करती है जिसे पारित करने वाले प्रतिनिधि को सौंपा गया है*createResourceStream* पैरामीटर। |

### प्रतिलाभ की मात्रा

का नया उदाहरण[`HtmlViewOptions`](../../htmlviewoptions) बाह्य संसाधनों के साथ HTML में प्रतिपादन के लिए वर्ग।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*createPageStream* शून्य है। |
| ArgumentNullException | कब फेंका*createResourceStream* शून्य है। |
| ArgumentNullException | कब फेंका*createResourceUrl* शून्य है। |
| ArgumentNullException | कब फेंका*releasePageStream* शून्य है। |
| ArgumentNullException | कब फेंका*releaseResourceStream* शून्य है। |

### यह सभी देखें

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* नाम स्थान [GroupDocs.Viewer.Options](../../htmlviewoptions)
* सभा [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

का नया उदाहरण शुरू करता है[`HtmlViewOptions`](../../htmlviewoptions) बाहरी संसाधनों के साथ HTML में रेंडर करने के लिए क्लास.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | फैक्ट्री जो आउटपुट पेज स्ट्रीम बनाने और जारी करने के तरीकों को लागू करती है। |
| resourceStreamFactory | IResourceStreamFactory | वह फ़ैक्टरी जो उन विधियों को लागू करती है जो संसाधन URL बनाने, आउटपुट HTML संसाधन स्ट्रीम को तत्काल और रिलीज़ करने के लिए आवश्यक हैं। |

### प्रतिलाभ की मात्रा

का नया उदाहरण[`HtmlViewOptions`](../../htmlviewoptions) बाह्य संसाधनों के साथ HTML में प्रतिपादन के लिए वर्ग।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*pageStreamFactory* शून्य है। |
| ArgumentNullException | कब फेंका*resourceStreamFactory* शून्य है। |

### यह सभी देखें

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* नाम स्थान [GroupDocs.Viewer.Options](../../htmlviewoptions)
* सभा [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

का नया उदाहरण शुरू करता है[`HtmlViewOptions`](../../htmlviewoptions) वर्ग.

```csharp
public static HtmlViewOptions ForExternalResources()
```

### टिप्पणियों

यह कंस्ट्रक्टर नए इंस्टेंस को इनिशियलाइज़ करता है[`HtmlViewOptions`](../../htmlviewoptions) - आउटपुट HTML फ़ाइलों के लिए फ़ाइल पथ प्रारूप के रूप में "p_{0}.html" के साथ; - आउटपुट HTML-संसाधन फ़ाइलों के लिए फ़ाइल पथ प्रारूप के रूप में "p_{0}_{1}" के साथ; - "के साथ" p_{0}_{1}" HTML-संसाधनों के लिए URL प्रारूप के रूप में; आउटपुट फ़ाइलों को एप्लिकेशन की वर्तमान कार्यशील निर्देशिका में रखा जाएगा।

### यह सभी देखें

* class [HtmlViewOptions](../../htmlviewoptions)
* नाम स्थान [GroupDocs.Viewer.Options](../../htmlviewoptions)
* सभा [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

का नया उदाहरण शुरू करता है[`HtmlViewOptions`](../../htmlviewoptions) वर्ग.

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | String | फ़ाइल पथ स्वरूप, उदाहरण के लिए 'page_{0}.html'। |
| resourceFilePathFormat | String | संसाधन फ़ाइल पथ स्वरूप जैसे 'पृष्ठ_{0}/संसाधन_{1}'। |
| resourceUrlFormat | String | संसाधन URL प्रारूप उदा 'पृष्ठ_{0}/संसाधन_{1}'। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentException | कब फेंका*filePathFormat* शून्य या खाली है। |
| ArgumentException | कब फेंका*resourceFilePathFormat* शून्य या खाली है। |
| ArgumentException | कब फेंका*resourceUrlFormat* शून्य या खाली है। |

### यह सभी देखें

* class [HtmlViewOptions](../../htmlviewoptions)
* नाम स्थान [GroupDocs.Viewer.Options](../../htmlviewoptions)
* सभा [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
