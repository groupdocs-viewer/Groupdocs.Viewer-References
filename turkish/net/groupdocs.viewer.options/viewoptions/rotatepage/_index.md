---
title: "RotatePage"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Bir sayfaya saat yönünde dönüş uygular."
type: docs
weight: 30
url: /tr/net/groupdocs.viewer.options/viewoptions/rotatepage/
---

## ViewOptions.RotatePage method

Bir sayfaya saat yönünde dönüş uygular.

```csharp
public void RotatePage(int pageNumber, Rotation rotation)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| pageNumber | Int32 | Sayfa numarası, 0'dan kesinlikle büyük olmalıdır. |
| rotasyon | Rotation | Dönüş değeri. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | *pageNumber* sıfırdan küçük veya eşit olduğunda fırlatılır. |
| ArgumentException | *pageNumber* numaralı sayfa için dönüş zaten eklendiğinde fırlatılır. |

### Açıklamalar

Ayrıntılar için [belgelere](https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/) bakın.

### Ayrıca Bakınız

* enum [Rotation](../../rotation)
* class [ViewOptions](../../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
