---
title: "CadViewInfo"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "CadViewInfogroupdocs.viewer.results/cadviewinfo क्लास का नया उदाहरण प्रारंभ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.viewer.results/cadviewinfo/cadviewinfo/
---

## CadViewInfo constructor

`[`CadViewInfo`](../../cadviewinfo) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public CadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | FileType | फ़ाइल का प्रकार। |
| पृष्ठ | List`1 | देखने के लिए पृष्ठों की सूची। |
| layers | List`1 | CAD ड्राइंग में शामिल लेयर्स की सूची। |
| layouts | List`1 | CAD ड्राइंग में शामिल लेयर्स की सूची। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *fileType* नल होने पर थ्रो किया जाता है। |
| ArgumentNullException | जब *pages* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *layers* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *layouts* null हो तो फेंका जाता है। |

### संबंधित देखें

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [Layer](../../layer)
* class [Layout](../../layout)
* class [CadViewInfo](../../cadviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
