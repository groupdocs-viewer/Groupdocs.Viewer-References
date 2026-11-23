---
title: "FileCache"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Yerel bir disk üzerindeki önbelleği temsil eder."
type: docs
weight: 990
url: /tr/net/groupdocs.viewer.caching/filecache/
---

## FileCache class

Yerel disk üzerindeki bir önbelleği temsil eder.

```csharp
public class FileCache : ICache
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [FileCache](filecache#constructor)(string) | Yeni bir [`FileCache`](../filecache) sınıfı örneği oluşturur. |
| [FileCache](filecache#constructor_1)(string, string) | Yeni bir [`FileCache`](../filecache) sınıfı örneği oluşturur. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [CachePath](../../groupdocs.viewer.caching/filecache/cachepath) { get; } | Önbellek klasörüne göreceli veya mutlak yol. |
| [CacheSubFolder](../../groupdocs.viewer.caching/filecache/cachesubfolder) { get; } | [`CachePath`](./cachepath) yoluna eklenecek alt klasör. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/filecache/getkeys)(string) | Dosya adında filtre içeren tüm dosya adlarını döndürür. |
| [Set](../../groupdocs.viewer.caching/filecache/set)(string, object) | Verileri yerel diske serileştirir. |
| [TryGetValue&lt;T&gt;](../../groupdocs.viewer.caching/filecache/trygetvalue)(string, out T) | Bu anahtarla ilişkili verileri mevcutsa seriden çıkarır. |

### Ayrıca Bakınız

* interface [ICache](../icache)
* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
