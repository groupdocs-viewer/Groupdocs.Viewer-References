---
title: "ReleaseResourceStream"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "CreateResourceStreamgroupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream yöntemi tarafından oluşturulan akışı serbest bırakır."
type: docs
weight: 30
url: /tr/net/groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream/
---

## IResourceStreamFactory.ReleaseResourceStream method

[`CreateResourceStream`](../createresourcestream) yöntemi tarafından oluşturulan akışı serbest bırakır.

```csharp
public void ReleaseResourceStream(int pageNumber, Resource resource, Stream resourceStream)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| pageNumber | Int32 | Bir sayfanın numarası. |
| resource | Kaynak | Yazı tipi, stil, resim veya grafik gibi HTML kaynağı. |
| resourceStream | Stream | [`CreateResourceStream`](../createresourcestream) yöntemi tarafından oluşturulan akış. |

### Ayrıca Bakınız

* class [Resource](../../../groupdocs.viewer.results/resource)
* interface [IResourceStreamFactory](../../iresourcestreamfactory)
* namespace [GroupDocs.Viewer.Interfaces](../../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
