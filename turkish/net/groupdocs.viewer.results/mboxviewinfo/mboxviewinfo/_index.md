---
title: "MboxViewInfo"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "MboxViewInfogroupdocs.viewer.results/mboxviewinfo sınıfının yeni bir örneğini başlatır."
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.results/mboxviewinfo/mboxviewinfo/
---

## MboxViewInfo() {#constructor}

[`MboxViewInfo`](../../mboxviewinfo) sınıfının yeni bir örneğini başlatır.

```csharp
public MboxViewInfo()
```

### Ayrıca Bakınız

* class [MboxViewInfo](../../mboxviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## MboxViewInfo(FileType, List&lt;Page&gt;, int) {#constructor_1}

[`MboxViewInfo`](../../mboxviewinfo) sınıfının yeni bir örneğini başlatır.

```csharp
public MboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| fileType | FileType | Dosyanın türü. |
| sayfalar | List`1 | Görüntülenecek sayfaların listesi. |
| notesCount | Int32 | Lotus veritabanı depolama dosyası tarafından tutulan not sayısı. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *fileType* null olduğunda fırlatılır. |
| ArgumentNullException | *pages* null olduğunda fırlatılır. |
| ArgumentNullException | *notesCount* null olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [MboxViewInfo](../../mboxviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
