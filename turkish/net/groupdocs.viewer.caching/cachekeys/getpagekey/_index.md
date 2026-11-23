---
title: "GetPageKey"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Sayfa dosyasını temsil eden önbellek girdisi için benzersiz tanımlayıcıyı döndürür."
type: docs
weight: 50
url: /tr/net/groupdocs.viewer.caching/cachekeys/getpagekey/
---

## CacheKeys.GetPageKey method

Sayfa dosyasını temsil eden önbellek girdisi için benzersiz tanımlayıcıyı döndürür.

```csharp
public static string GetPageKey(int pageNumber, string extension)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| pageNumber | Int32 | Sayfanın numarası. |
| extension | String | Dosya adı eki (nokta "." dahil) ör. ".doc". |

### Dönüş Değeri

Sayfa dosyasını temsil eden önbellek girdisi için benzersiz tanımlayıcı.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *pageNumber* sıfırdan küçük veya eşit olduğunda fırlatılır. |
| ArgumentException | *extension* null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
