---
title: "GetResourceKey"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Resourcegroupdocs.viewer.results/resource nesnesini temsil eden önbellek girdisi için benzersiz tanımlayıcıyı döndürür."
type: docs
weight: 70
url: /tr/net/groupdocs.viewer.caching/cachekeys/getresourcekey/
---

## CacheKeys.GetResourceKey method

`[`Resource`](../../../groupdocs.viewer.results/resource)` nesnesini temsil eden önbellek girdisi için benzersiz tanımlayıcıyı döndürür.

```csharp
public static string GetResourceKey(int pageNumber, Resource resource)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| pageNumber | Int32 | Sayfanın numarası. |
| resource | Kaynak | HTML kaynağı. |

### Dönüş Değeri

`[`Resource`](../../../groupdocs.viewer.results/resource)` nesnesini temsil eden önbellek girdisi için benzersiz tanımlayıcı.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *pageNumber* sıfırdan küçük veya eşit olduğunda fırlatılır. |
| ArgumentNullException | *resource* null olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [Resource](../../../groupdocs.viewer.results/resource)
* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
