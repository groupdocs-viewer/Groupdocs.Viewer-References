---
title: "ICache"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Renderlenen belge ve belge kaynakları önbelleğini depolamak için gerekli yöntemleri tanımlar."
type: docs
weight: 1000
url: /tr/net/groupdocs.viewer.caching/icache/
---

## ICache interface

Renderlenen belge ve belge kaynakları önbelleğini depolamak için gerekli yöntemleri tanımlar.

```csharp
public interface ICache
```

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/icache/getkeys)(string) | Filtreyle eşleşen tüm anahtarları döndürür. |
| [Set](../../groupdocs.viewer.caching/icache/set)(string, object) | Önbelleğe bir önbellek girdisi ekler. |
| [TryGetValue&lt;TEntry&gt;](../../groupdocs.viewer.caching/icache/trygetvalue)(string, out TEntry) | Bu anahtarla ilişkili girdiyi mevcutsa alır. |

### Ayrıca Bakınız

* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
