---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "PdfViewOptionsgroupdocs.viewer.options/pdfviewoptions क्लास का एक उदाहरण प्रारंभ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.viewer.options/pdfviewoptions/pdfviewoptions/
---

## PdfViewOptions(CreateFileStream) {#constructor_1}

[`PdfViewOptions`](../../pdfviewoptions) क्लास का एक उदाहरण प्रारंभ करता है।

```csharp
public PdfViewOptions(CreateFileStream createFileStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createFileStream | CreateFileStream | वह विधि जो आउटपुट फ़ाइल डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करती है। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *createFileStream* शून्य हो तो फेंका जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, देखें [दस्तावेज़](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/)।

### संबंधित देखें

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(CreateFileStream, ReleaseFileStream) {#constructor_2}

[`PdfViewOptions`](../../pdfviewoptions) क्लास का एक उदाहरण प्रारंभ करता है।

```csharp
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createFileStream | CreateFileStream | वह विधि जो आउटपुट फ़ाइल डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करती है। |
| releaseFileStream | ReleaseFileStream | वह विधि जो *createFileStream* पैरामीटर को पास किए गए डेलीगेट को असाइन की गई विधि द्वारा निर्मित स्ट्रीम को रिलीज़ करती है। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *createFileStream* शून्य हो तो फेंका जाता है। |
| ArgumentNullException | जब *releaseFileStream* शून्य हो तो फेंका जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, देखें [दस्तावेज़](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/)।

### संबंधित देखें

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* delegate [ReleaseFileStream](../../../groupdocs.viewer.interfaces/releasefilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(IFileStreamFactory) {#constructor_3}

[`PdfViewOptions`](../../pdfviewoptions) क्लास का एक उदाहरण प्रारंभ करता है।

```csharp
public PdfViewOptions(IFileStreamFactory fileStreamFactory)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileStreamFactory | IFileStreamFactory | आउटपुट फ़ाइल स्ट्रीम बनाने और रिलीज़ करने के मेथड्स को लागू करने वाली फ़ैक्टरी। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *fileStreamFactory* जब null हो तो फेंका जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, देखें [दस्तावेज़](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/)।

### संबंधित देखें

* interface [IFileStreamFactory](../../../groupdocs.viewer.interfaces/ifilestreamfactory)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions() {#constructor}

[`PdfViewOptions`](../../pdfviewoptions) क्लास का एक उदाहरण प्रारंभ करता है।

```csharp
public PdfViewOptions()
```

### टिप्पणियाँ

यह कंस्ट्रक्टर [`PdfViewOptions`](../../pdfviewoptions) का एक इंस्टेंस "output.pdf" को आउटपुट फ़ाइल के फ़ाइल पाथ फ़ॉर्मेट के रूप में इनिशियलाइज़ करता है। आउटपुट फ़ाइल एप्लिकेशन की वर्तमान कार्य निर्देशिका में रखी जाएगी।

कोड उदाहरण के लिए, देखें [दस्तावेज़](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/)।

### संबंधित देखें

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(string) {#constructor_4}

[`PdfViewOptions`](../../pdfviewoptions) क्लास का एक उदाहरण प्रारंभ करता है।

```csharp
public PdfViewOptions(string outputFilePath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| outputFilePath | String | आउटपुट PDF फ़ाइल का पाथ। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | *outputFilePath* जब null या खाली हो तो फेंका जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, देखें [दस्तावेज़](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/)।

### संबंधित देखें

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
