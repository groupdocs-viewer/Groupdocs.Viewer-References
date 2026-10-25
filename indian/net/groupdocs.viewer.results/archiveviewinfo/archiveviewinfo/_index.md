---
title: "ArchiveViewInfo"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "ArchiveViewInfogroupdocs.viewer.results/archiveviewinfo क्लास का नया इंस्टेंस प्रारंभ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.viewer.results/archiveviewinfo/archiveviewinfo/
---

## ArchiveViewInfo() {#constructor}

[`ArchiveViewInfo`](../../archiveviewinfo) क्लास का नया इंस्टेंस प्रारंभ करता है।

```csharp
public ArchiveViewInfo()
```

### संबंधित देखें

* class [ArchiveViewInfo](../../archiveviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## ArchiveViewInfo(FileType, List&lt;Page&gt;, List&lt;string&gt;) {#constructor_1}

[`ArchiveViewInfo`](../../archiveviewinfo) क्लास का नया इंस्टेंस प्रारंभ करता है।

```csharp
public ArchiveViewInfo(FileType fileType, List<Page> pages, List<string> folders)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | FileType | फ़ाइल का प्रकार। |
| पृष्ठ | List`1 | देखने के लिए पृष्ठों की सूची। |
| फ़ोल्डर | List`1 | अभिलेख फ़ाइल में सम्मिलित फ़ोल्डरों की सूची। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *fileType* नल होने पर थ्रो किया जाता है। |
| ArgumentNullException | जब *pages* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *folders* null हो तो फेंका जाता है। |

### संबंधित देखें

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [ArchiveViewInfo](../../archiveviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
