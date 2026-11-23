---
title: "TextElement"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "TextElementgroupdocs.viewer.results/textelement1 sınıfının yeni bir örneğini başlatır."
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.results/textelement-1/textelement/
---

## TextElement() {#constructor}

Yeni bir örnek başlatır [`TextElement`](../../textelement-1) sınıfı.

```csharp
public TextElement()
```

### Ayrıca Bakınız

* class [TextElement&lt;T&gt;](../../textelement-1)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## TextElement(T, double, double, double, double) {#constructor_1}

Yeni bir örnek başlatır [`TextElement`](../../textelement-1) sınıfı.

```csharp
public TextElement(T value, double x, double y, double width, double height)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| değer | T | Metin öğesi değeri. |
| x | Double | Öğeyi içeren dikdörtgenin başladığı sayfa düzenindeki en üst sol noktanın X koordinatı. |
| y | Double | Öğeyi içeren dikdörtgenin başladığı sayfa düzenindeki en üst sol noktanın Y koordinatı. |
| width | Double | Öğeyi içeren dikdörtgenin genişliği (piksel cinsinden). |
| height | Double | Öğeyi içeren dikdörtgenin yüksekliği (piksel cinsinden). |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *value* null olduğunda fırlatılır. |
| ArgumentException | *width* sıfırdan küçük veya eşit olduğunda fırlatılır. |
| ArgumentException | *height* sıfırdan küçük veya eşit olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [TextElement&lt;T&gt;](../../textelement-1)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
