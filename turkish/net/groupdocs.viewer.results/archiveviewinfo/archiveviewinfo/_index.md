---
title: ArchiveViewInfo
second_title: .NET API Başvurusu için GroupDocs.Viewer
description: Yeni örneğini başlatırArchiveViewInfogroupdocs.viewer.results/archiveviewinfo sınıf.
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.results/archiveviewinfo/archiveviewinfo/
---
## ArchiveViewInfo constructor

Yeni örneğini başlatır[`ArchiveViewInfo`](../../archiveviewinfo) sınıf.

```csharp
public ArchiveViewInfo(FileType fileType, IList<Page> pages, IList<string> folders)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fileType | FileType | Dosyanın türü. |
| pages | IList`1 | Görüntülenecek sayfaların listesi. |
| folders | IList`1 | Arşiv dosyasının içerdiği klasörlerin listesi. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | ne zaman atıldı*fileType* boş. |
| ArgumentNullException | ne zaman atıldı*pages* boş. |
| ArgumentNullException | ne zaman atıldı*folders* boş. |

### Ayrıca bakınız

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [ArchiveViewInfo](../../archiveviewinfo)
* ad alanı [GroupDocs.Viewer.Results](../../archiveviewinfo)
* toplantı [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
