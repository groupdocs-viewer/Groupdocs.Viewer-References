---
title: "Line"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Linegroupdocs.viewer.results/line sınıfının yeni bir örneğini başlatır."
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.results/line/line/
---

## Line() {#constructor}

Yeni bir [`Line`](../../line) sınıfı örneği başlatır.

```csharp
public Line()
```

### Ayrıca Bakınız

* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Line(string, double, double, double, double, List&lt;Word&gt;) {#constructor_1}

Yeni bir [`Line`](../../line) sınıfı örneği başlatır.

```csharp
public Line(string line, double x, double y, double width, double height, List<Word> words)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| satır | String | Satır. |
| x | Double | Satırı içeren dikdörtgenin başladığı sayfa düzenindeki en üst sol noktanın X koordinatı. |
| y | Double | Satırı içeren dikdörtgenin başladığı sayfa düzenindeki en üst sol noktanın Y koordinatı. |
| width | Double | Satırı içeren dikdörtgenin genişliği (piksel cinsinden). |
| height | Double | Satırı içeren dikdörtgenin yüksekliği (piksel cinsinden). |
| kelimeler | List`1 | Satır tarafından içerilen kelimeler. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *line* null veya boş olduğunda fırlatılır. |
| ArgumentNullException | *words* null olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [Word](../../word)
* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
