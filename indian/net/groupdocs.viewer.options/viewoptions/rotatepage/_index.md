---
title: "RotatePage"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "एक पृष्ठ पर घड़ी की दिशा में घुमाव लागू करता है।"
type: docs
weight: 30
url: /hi/net/groupdocs.viewer.options/viewoptions/rotatepage/
---

## ViewOptions.RotatePage method

एक पृष्ठ पर घड़ी की दिशा में घुमाव लागू करता है।

```csharp
public void RotatePage(int pageNumber, Rotation rotation)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageNumber | Int32 | पृष्ठ संख्या, 0 से अधिक होनी चाहिए। |
| rotation | Rotation | घूर्णन मान। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | जब *pageNumber* शून्य या उससे कम हो तो फेंका जाता है। |
| ArgumentException | जब पृष्ठ संख्या *pageNumber* के लिए घूर्णन पहले ही जोड़ा जा चुका हो तो फेंका जाता है। |

### टिप्पणियाँ

विस्तार के लिए, देखें [दस्तावेज़](https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/)।

### संबंधित देखें

* enum [Rotation](../../rotation)
* class [ViewOptions](../../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
