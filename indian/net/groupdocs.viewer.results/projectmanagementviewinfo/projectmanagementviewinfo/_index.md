---
title: "ProjectManagementViewInfo"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "ProjectManagementViewInfogroupdocs.viewer.results/projectmanagementviewinfo क्लास का नया उदाहरण प्रारंभ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.viewer.results/projectmanagementviewinfo/projectmanagementviewinfo/
---

## ProjectManagementViewInfo() {#constructor}

[`ProjectManagementViewInfo`](../../projectmanagementviewinfo) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public ProjectManagementViewInfo()
```

### संबंधित देखें

* class [ProjectManagementViewInfo](../../projectmanagementviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## ProjectManagementViewInfo(FileType, List&lt;Page&gt;, DateTime, DateTime) {#constructor_1}

[`ProjectManagementViewInfo`](../../projectmanagementviewinfo) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public ProjectManagementViewInfo(FileType fileType, List<Page> pages, DateTime startDate, 
    DateTime endDate)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | FileType | फ़ाइल का प्रकार। |
| पृष्ठ | List`1 | देखने के लिए पृष्ठों की सूची। |
| startDate | DateTime | परियोजना के शुरू होने का तिथि‑समय। |
| endDate | DateTime | परियोजना के पूर्ण होने का तिथि‑समय। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *fileType* नल होने पर थ्रो किया जाता है। |
| ArgumentNullException | जब *pages* null हो तो फेंका जाता है। |

### संबंधित देखें

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [ProjectManagementViewInfo](../../projectmanagementviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
