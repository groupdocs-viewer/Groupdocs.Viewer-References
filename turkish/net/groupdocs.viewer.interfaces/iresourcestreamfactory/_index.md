---
title: "IResourceStreamFactory"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Çıktı HTML kaynak akışını oluşturmak, URL örneklemek ve serbest bırakmak için gereken yöntemleri tanımlar."
type: docs
weight: 770
url: /tr/net/groupdocs.viewer.interfaces/iresourcestreamfactory/
---

## IResourceStreamFactory interface

Kaynak URL'si oluşturmak, çıktı HTML kaynağı akışını örneklemek ve serbest bırakmak için gereken yöntemleri tanımlar.

```csharp
public interface IResourceStreamFactory
```

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [CreateResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream)(int, Resource) | Çıktı HTML kaynak verilerini yazmak için kullanılan akışı oluşturur. |
| [CreateResourceUrl](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourceurl)(int, Resource) | HTML kaynağı için URL'yi oluşturur. |
| [ReleaseResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream)(int, Resource, Stream) | [`CreateResourceStream`](./createresourcestream) yöntemi tarafından oluşturulan akışı serbest bırakır. |

### Ayrıca Bakınız

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
