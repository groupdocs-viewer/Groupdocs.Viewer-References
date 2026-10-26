---
title: "CreateResourceStream"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Çıktı HTML kaynağı verilerini yazmak için kullanılan akışı örnekleyen yöntemi temsil eder."
type: docs
weight: 720
url: /tr/net/groupdocs.viewer.interfaces/createresourcestream/
---

## CreateResourceStream delegate

Çıktı HTML kaynağı verilerini yazmak için kullanılan akışı örnekleyen yöntemi temsil eder.

```csharp
public delegate Stream CreateResourceStream(int pageNumber, Resource resource);
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| pageNumber | Int32 | Sayfanın numarası. |
| resource | Kaynak | Yazı tipi, stil, resim veya grafik gibi HTML kaynağı. |

### Dönüş Değeri

Çıktı HTML kaynak verilerini yazmak için kullanılan akış.

### Ayrıca Bakınız

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
