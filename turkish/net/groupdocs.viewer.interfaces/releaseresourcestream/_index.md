---
title: "ReleaseResourceStream"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "CreateResourceStream./createresourcestream temsilcisiyle ilişkili yöntem tarafından oluşturulan akışı serbest bırakır."
type: docs
weight: 730
url: /tr/net/groupdocs.viewer.interfaces/releaseresourcestream/
---

## ReleaseResourceStream delegate

[`CreateResourceStream`](../createresourcestream) temsilcisiyle ilişkili yöntem tarafından oluşturulan akışı serbest bırakır.

```csharp
public delegate void ReleaseResourceStream(int pageNumber, Resource resource, 
    Stream resourceStream);
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| pageNumber | Int32 | Sayfanın numarası. |
| resource | Kaynak | Yazı tipi, stil, resim veya grafik gibi HTML kaynağı. |
| resourceStream | Stream | [`CreateResourceStream`](../createresourcestream) temsilcisiyle ilişkili yöntem tarafından oluşturulan akış. |

### Ayrıca Bakınız

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
