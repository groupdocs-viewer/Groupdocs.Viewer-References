---
title: "Attachment"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "Attachmentgroupdocs.viewer.results/attachment क्लास का नया इंस्टेंस प्रारंभ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.viewer.results/attachment/attachment/
---

## Attachment() {#constructor}

[`Attachment`](../../attachment) क्लास का नया इंस्टेंस प्रारंभ करता है।

```csharp
public Attachment()
```

### संबंधित देखें

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string) {#constructor_1}

[`Attachment`](../../attachment) क्लास का नया इंस्टेंस प्रारंभ करता है।

```csharp
public Attachment(string fileName, string filePath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileName | String | Attachment फ़ाइल का नाम। |
| filePath | String | Attachment सापेक्ष पथ, उदाहरण के लिए folder/file.docx या फ़ाइलनाम जब फ़ाइल आर्काइव की जड़ में, ई-मेल संदेश में या डेटा फ़ाइल में स्थित हो। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *fileName* null या खाली हो तो फेंका जाता है। |
| ArgumentException | जब *filePath* null या खाली हो तो फेंका जाता है। |

### संबंधित देखें

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, long) {#constructor_3}

[`Attachment`](../../attachment) क्लास का नया इंस्टेंस प्रारंभ करता है।

```csharp
public Attachment(string id, string fileName, string filePath, long size)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| आईडी | String | एकल फ़ाइल के संदर्भ में अनुलग्नक का अद्वितीय पहचानकर्ता। |
| fileName | String | Attachment फ़ाइल का नाम। |
| filePath | String | Attachment सापेक्ष पथ, उदाहरण के लिए folder/file.docx या फ़ाइलनाम जब फ़ाइल आर्काइव की जड़ में, ई-मेल संदेश में या डेटा फ़ाइल में स्थित हो। |
| आकार | Int64 | Attachment फ़ाइल आकार बाइट्स में। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *id* null या खाली हो तो फेंका जाता है। |
| ArgumentException | जब *fileName* null या खाली हो तो फेंका जाता है। |
| ArgumentException | जब *filePath* null या खाली हो तो फेंका जाता है। |

### संबंधित देखें

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, FileType, long) {#constructor_2}

[`Attachment`](../../attachment) क्लास का नया इंस्टेंस प्रारंभ करता है।

```csharp
public Attachment(string id, string fileName, string filePath, FileType fileType, long size)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| आईडी | String | एकल फ़ाइल के संदर्भ में अनुलग्नक का अद्वितीय पहचानकर्ता। |
| fileName | String | Attachment फ़ाइल का नाम। |
| filePath | String | Attachment सापेक्ष पथ, उदाहरण के लिए folder/file.docx या फ़ाइलनाम जब फ़ाइल आर्काइव की जड़ में, ई-मेल संदेश में या डेटा फ़ाइल में स्थित हो। |
| fileType | FileType | Attachment फ़ाइल प्रकार। |
| आकार | Int64 | Attachment फ़ाइल आकार बाइट्स में। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *id* null या खाली हो तो फेंका जाता है। |
| ArgumentException | जब *fileName* null या खाली हो तो फेंका जाता है। |
| ArgumentException | जब *filePath* null या खाली हो तो फेंका जाता है। |
| ArgumentNullException | *fileType* नल होने पर थ्रो किया जाता है। |

### संबंधित देखें

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
