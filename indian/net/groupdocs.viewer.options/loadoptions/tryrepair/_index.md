---
title: "TryRepair"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "सक्रिय होने पर GroupDocs.Viewer PDF दस्तावेज़ों में संरचनात्मक भ्रष्टाचार को ठीक करने का प्रयास करता है। डिफ़ॉल्ट मान false है।"
type: docs
weight: 80
url: /hi/net/groupdocs.viewer.options/loadoptions/tryrepair/
---

## LoadOptions.TryRepair property

सक्षम होने पर GroupDocs.Viewer PDF दस्तावेज़ों में संरचनात्मक भ्रष्टाचार को ठीक करने का प्रयास करता है। डिफ़ॉल्ट मान `false` है।

```csharp
public bool TryRepair { get; set; }
```

### टिप्पणियाँ

यह सुविधा PDF दस्तावेज़ में निम्नलिखित समस्याओं को संबोधित करती है:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).

### संबंधित देखें

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
