---
title: CadViewInfo
second_title: .NET API Başvurusu için GroupDocs.Viewer
description: Yeni örneğini başlatırCadViewInfogroupdocs.viewer.results/cadviewinfo sınıf.
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.results/cadviewinfo/cadviewinfo/
---
## CadViewInfo constructor

Yeni örneğini başlatır[`CadViewInfo`](../../cadviewinfo) sınıf.

```csharp
public CadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fileType | FileType | Dosyanın türü. |
| pages | List`1 | Görüntülenecek sayfaların listesi. |
| layers | List`1 | CAD çiziminin içerdiği katmanların listesi. |
| layouts | List`1 | CAD çiziminin içerdiği katmanların listesi. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*fileType* boş. |
| ArgumentNullException | Ne zaman atıldı*pages* boş. |
| ArgumentNullException | Ne zaman atıldı*layers* boş. |
| ArgumentNullException | Ne zaman atıldı*layouts* boş. |

### Ayrıca bakınız

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [Layer](../../layer)
* class [Layout](../../layout)
* class [CadViewInfo](../../cadviewinfo)
* ad alanı [GroupDocs.Viewer.Results](../../cadviewinfo)
* toplantı [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
