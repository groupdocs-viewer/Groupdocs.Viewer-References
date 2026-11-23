---
title: "ForRenderingByWidthAndHeight"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "CadOptionsgroupdocs.viewer.options/cadoptions sınıfının genişlik ve yükseklik ile renderleme için bir örneğini başlatır."
type: docs
weight: 40
url: /tr/net/groupdocs.viewer.options/cadoptions/forrenderingbywidthandheight/
---

## CadOptions.ForRenderingByWidthAndHeight method

Genişlik ve yükseklik ile renderleme için bir [`CadOptions`](../../cadoptions) sınıfının örneğini başlatır.

```csharp
public static CadOptions ForRenderingByWidthAndHeight(int width, int height)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| width | Int32 | Çıktı sonucunun genişliği (piksel cinsinden). |
| height | Int32 | Çıktı sonucunun yüksekliği (piksel cinsinden). |

### Dönüş Değeri

Genişlik ve yükseklik ile renderleme için yeni bir [`CadOptions`](../../cadoptions) sınıfı örneği.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *width* sıfırdan küçük veya eşit olduğunda fırlatılır. |
| ArgumentException | *height* sıfırdan küçük veya eşit olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#configure-the-output-image-size) bakın.

### Ayrıca Bakınız

* class [CadOptions](../../cadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
