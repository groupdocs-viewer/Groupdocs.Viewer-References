---
title: ReleaseResourceStream
second_title: .NET API Başvurusu için GroupDocs.Viewer
description: ile ilişkili yöntem tarafından örneklenen akışı serbest bırakırCreateResourceStream./createresourcestream temsilci.
type: docs
weight: 210
url: /tr/net/groupdocs.viewer.interfaces/releaseresourcestream/
---
## ReleaseResourceStream delegate

ile ilişkili yöntem tarafından örneklenen akışı serbest bırakır[`CreateResourceStream`](../createresourcestream) temsilci.

```csharp
public delegate void ReleaseResourceStream(int pageNumber, Resource resource, 
    Stream resourceStream);
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pageNumber | Int32 | Sayfa numarası. |
| resource | Resource | Yazı tipi, stil, resim veya grafikler gibi HTML kaynakları. |
| resourceStream | Stream | İlişkili yöntem tarafından oluşturulan akış[`CreateResourceStream`](../createresourcestream) temsilci. |

### Ayrıca bakınız

* class [Resource](../../groupdocs.viewer.results/resource)
* ad alanı [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* toplantı [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->