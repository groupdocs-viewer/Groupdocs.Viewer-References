---
title: "MboxViewInfo"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "MboxViewInfogroupdocs.viewer.results/mboxviewinfo क्लास का नया उदाहरण प्रारंभ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.viewer.results/mboxviewinfo/mboxviewinfo/
---

## MboxViewInfo() {#constructor}

`[`MboxViewInfo`](../../mboxviewinfo) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public MboxViewInfo()
```

### संबंधित देखें

* class [MboxViewInfo](../../mboxviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## MboxViewInfo(FileType, List&lt;Page&gt;, int) {#constructor_1}

`[`MboxViewInfo`](../../mboxviewinfo) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public MboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | FileType | फ़ाइल का प्रकार। |
| पृष्ठ | List`1 | देखने के लिए पृष्ठों की सूची। |
| notesCount | Int32 | Lotus डेटाबेस स्टोरेज फ़ाइल में निहित नोट्स की गिनती। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *fileType* नल होने पर थ्रो किया जाता है। |
| ArgumentNullException | जब *pages* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *notesCount* null हो तो फेंका जाता है। |

### संबंधित देखें

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [MboxViewInfo](../../mboxviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
