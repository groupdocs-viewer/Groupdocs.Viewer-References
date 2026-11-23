---
title: "CadViewInfo"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "CadViewInfogroupdocs.viewer.results/cadviewinfo sınıfının yeni bir örneğini başlatır."
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.results/cadviewinfo/cadviewinfo/
---

## CadViewInfo constructor

[`CadViewInfo`](../../cadviewinfo) sınıfının yeni bir örneğini başlatır.

```csharp
public CadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| fileType | FileType | Dosyanın türü. |
| sayfalar | List`1 | Görüntülenecek sayfaların listesi. |
| layers | List`1 | CAD çiziminde bulunan katmanların listesi. |
| layouts | List`1 | CAD çiziminde bulunan katmanların listesi. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *fileType* null olduğunda fırlatılır. |
| ArgumentNullException | *pages* null olduğunda fırlatılır. |
| ArgumentNullException | *layers* null olduğunda fırlatılır. |
| ArgumentNullException | *layouts* null olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [Layer](../../layer)
* class [Layout](../../layout)
* class [CadViewInfo](../../cadviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
