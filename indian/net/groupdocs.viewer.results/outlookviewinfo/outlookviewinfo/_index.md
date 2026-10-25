---
title: "OutlookViewInfo"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "OutlookViewInfogroupdocs.viewer.results/outlookviewinfo क्लास का नया उदाहरण प्रारंभ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.viewer.results/outlookviewinfo/outlookviewinfo/
---

## OutlookViewInfo() {#constructor}

`[`OutlookViewInfo`](../../outlookviewinfo) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public OutlookViewInfo()
```

### संबंधित देखें

* class [OutlookViewInfo](../../outlookviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## OutlookViewInfo(FileType, List&lt;Page&gt;, List&lt;string&gt;) {#constructor_1}

`[`OutlookViewInfo`](../../outlookviewinfo) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public OutlookViewInfo(FileType fileType, List<Page> pages, List<string> folders)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | FileType | फ़ाइल का प्रकार। |
| पृष्ठ | List`1 | देखने के लिए पृष्ठों की सूची। |
| फ़ोल्डर | List`1 | Outlook डेटा फ़ाइल में समाहित फ़ोल्डरों की सूची। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *fileType* नल होने पर थ्रो किया जाता है। |
| ArgumentNullException | जब *pages* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *folders* null हो तो फेंका जाता है। |

### संबंधित देखें

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [OutlookViewInfo](../../outlookviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
