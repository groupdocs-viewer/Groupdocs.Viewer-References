---
title: "FromMediaType"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "फ़ाइल मीडिया प्रकार को फ़ाइल प्रकार में मैप करता है, उदाहरण के लिए application/pdf को PDFgroupdocs.viewer/filetype/pdf में मैप किया जाएगा।"
type: docs
weight: 1990
url: /hi/net/groupdocs.viewer/filetype/frommediatype/
---

## FileType.FromMediaType method

फ़ाइल मीडिया प्रकार को फ़ाइल प्रकार में मैप करता है, उदाहरण के लिए 'application/pdf' को [`PDF`](../pdf) में मैप किया जाएगा।

```csharp
public static FileType FromMediaType(string mediaType)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mediaType | String | फ़ाइल मीडिया प्रकार, उदाहरण के लिए application/pdf। |

### वापसी मान

यदि पाया जाए तो संबंधित मीडिया प्रकार लौटाता है, अन्यथा डिफ़ॉल्ट [`Unknown`](../unknown) फ़ाइल प्रकार लौटाता है।

### संबंधित देखें

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
