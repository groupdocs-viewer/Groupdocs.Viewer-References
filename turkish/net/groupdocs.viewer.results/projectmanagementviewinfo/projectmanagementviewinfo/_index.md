---
title: "ProjectManagementViewInfo"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "ProjectManagementViewInfogroupdocs.viewer.results/projectmanagementviewinfo sınıfının yeni bir örneğini başlatır."
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.results/projectmanagementviewinfo/projectmanagementviewinfo/
---

## ProjectManagementViewInfo() {#constructor}

[`ProjectManagementViewInfo`](../../projectmanagementviewinfo) sınıfının yeni bir örneğini başlatır.

```csharp
public ProjectManagementViewInfo()
```

### Ayrıca Bakınız

* class [ProjectManagementViewInfo](../../projectmanagementviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## ProjectManagementViewInfo(FileType, List&lt;Page&gt;, DateTime, DateTime) {#constructor_1}

[`ProjectManagementViewInfo`](../../projectmanagementviewinfo) sınıfının yeni bir örneğini başlatır.

```csharp
public ProjectManagementViewInfo(FileType fileType, List<Page> pages, DateTime startDate, 
    DateTime endDate)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| fileType | FileType | Dosyanın türü. |
| sayfalar | List`1 | Görüntülenecek sayfaların listesi. |
| startDate | DateTime | Projenin başlatıldığı tarih ve saat. |
| endDate | DateTime | Projenin tamamlanması gereken tarih ve saat. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *fileType* null olduğunda fırlatılır. |
| ArgumentNullException | *pages* null olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [ProjectManagementViewInfo](../../projectmanagementviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
