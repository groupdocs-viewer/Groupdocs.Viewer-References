---
title: "ForRenderingByScaleFactor"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Ölçek faktörüne göre render etmek için CadOptionsgroupdocs.viewer.options/cadoptions sınıfının bir örneğini başlatır."
type: docs
weight: 20
url: /tr/net/groupdocs.viewer.options/cadoptions/forrenderingbyscalefactor/
---

## CadOptions.ForRenderingByScaleFactor method

Ölçek faktörüne göre render etmek için [`CadOptions`](../../cadoptions) sınıfının bir örneğini başlatır.

```csharp
public static CadOptions ForRenderingByScaleFactor(float scaleFactor)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| scaleFactor | Tek | 1'den büyük değer çıktı sonucunu büyütür; 0 ile 1 arasındaki değer çıktı sonucunu azaltır. |

### Dönüş Değeri

Ölçek faktörüne göre render etmek için yeni bir [`CadOptions`](../../cadoptions) sınıfı örneği.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *scaleFactor* sıfırdan küçük veya eşit olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#configure-the-output-image-size) bakın.

### Ayrıca Bakınız

* class [CadOptions](../../cadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
