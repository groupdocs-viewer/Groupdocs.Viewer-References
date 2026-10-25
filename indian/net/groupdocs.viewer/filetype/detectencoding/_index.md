---
title: "DetectEncoding"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "पथ द्वारा TXTgroupdocs.viewer/filetype/txt, TSVgroupdocs.viewer/filetype/tsv और CSVgroupdocs.viewer/filetype/csv फ़ाइलों की एन्कोडिंग का पता लगाने का प्रयास करता है।"
type: docs
weight: 2060
url: /hi/net/groupdocs.viewer/filetype/detectencoding/
---

## DetectEncoding(string) {#detectencoding_1}

पथ द्वारा टेक्स्ट [`TXT`](../txt), [`TSV`](../tsv), और [`CSV`](../csv) फ़ाइलों की एन्कोडिंग का पता लगाने का प्रयास करता है।

```csharp
public static Encoding DetectEncoding(string filePath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | फ़ाइल नाम या फ़ाइल पथ। |

### वापसी मान

फ़ाइल एन्कोडिंग का पता न चलने पर एन्कोडिंग या null लौटाता है।

### उदाहरण

यह उदाहरण दिखाता है कि टेक्स्ट फ़ाइल एन्कोडिंग का पता कैसे लगाया जाए।

```csharp
Encoding encoding = FileType.DetectEncoding("message.txt");
```

### संबंधित देखें

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## DetectEncoding(Stream) {#detectencoding}

स्ट्रीम द्वारा टेक्स्ट [`TXT`](../txt), [`TSV`](../tsv), और [`CSV`](../csv) फ़ाइल की एन्कोडिंग का पता लगाने का प्रयास करता है।

```csharp
public static Encoding DetectEncoding(Stream stream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |

### वापसी मान

फ़ाइल एन्कोडिंग का पता न चलने पर एन्कोडिंग या null लौटाता है।

### उदाहरण

यह उदाहरण दिखाता है कि टेक्स्ट फ़ाइल एन्कोडिंग का पता कैसे लगाया जाए।

```csharp
Stream stream = File.OpenRead("message.txt");
Encoding encoding = FileType.DetectEncoding(stream);
```

### संबंधित देखें

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
