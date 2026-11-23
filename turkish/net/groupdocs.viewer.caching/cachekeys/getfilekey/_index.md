---
title: "GetFileKey"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Dosyayı temsil eden önbellek girdisi için benzersiz tanımlayıcıyı döndürür."
type: docs
weight: 40
url: /tr/net/groupdocs.viewer.caching/cachekeys/getfilekey/
---

## CacheKeys.GetFileKey method

Dosyayı temsil eden önbellek girdisi için benzersiz tanımlayıcıyı döndürür.

```csharp
public static string GetFileKey(string extension)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| extension | String | Dosya adı eki (nokta "." dahil) ör. ".doc". |

### Dönüş Değeri

Dosyayı temsil eden önbellek girdisi için benzersiz tanımlayıcı.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *extension* null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
