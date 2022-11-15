---
title: TextElement
second_title: .NET API Başvurusu için GroupDocs.Viewer
description: Yeni örneğini başlatırTextElementgroupdocs.viewer.results/textelement1 sınıf.
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.results/textelement-1/textelement/
---
## TextElement&lt;T&gt; constructor

Yeni örneğini başlatır[`TextElement`](../../textelement-1) sınıf.

```csharp
public TextElement(T value, double x, double y, double width, double height)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| value | T | Metin öğesi değeri. |
| x | Double | Sayfa düzeninde öğe içeren dikdörtgenin başladığı en yüksek sol noktanın X koordinatı. |
| y | Double | Sayfa düzeninde öğe içeren dikdörtgenin başladığı en yüksek sol noktanın Y koordinatı. |
| width | Double | Öğeyi içeren dikdörtgenin genişliği (piksel olarak). |
| height | Double | Öğeyi içeren dikdörtgenin yüksekliği (piksel olarak). |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | ne zaman atıldı*value* boş. |
| ArgumentException | ne zaman atıldı*width* sıfıra eşit veya küçüktür. |
| ArgumentException | ne zaman atıldı*height* sıfıra eşit veya küçüktür. |

### Ayrıca bakınız

* class [TextElement&lt;T&gt;](../../textelement-1)
* ad alanı [GroupDocs.Viewer.Results](../../textelement-1)
* toplantı [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->