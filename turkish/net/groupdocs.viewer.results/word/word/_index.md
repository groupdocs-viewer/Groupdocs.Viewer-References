---
title: "Word"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Wordgroupdocs.viewer.results/word sınıfının yeni bir örneğini başlatır."
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.results/word/word/
---

## Word() {#constructor}

Yeni bir [`Word`](../../word) sınıfı örneği başlatır.

```csharp
public Word()
```

### Ayrıca Bakınız

* class [Word](../../word)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Word(string, double, double, double, double, List&lt;Character&gt;) {#constructor_1}

Yeni bir [`Word`](../../word) sınıfı örneği başlatır.

```csharp
public Word(string word, double x, double y, double width, double height, 
    List<Character> characters)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| kelime | String | Kelime. |
| x | Double | Kelimeyi içeren dikdörtgenin başladığı sayfa düzenindeki en üst sol noktanın X koordinatı. |
| y | Double | Kelimeyi içeren dikdörtgenin başladığı sayfa düzenindeki en üst sol noktanın Y koordinatı. |
| width | Double | Kelimeyi içeren dikdörtgenin genişliği. |
| height | Double | Kelimeyi içeren dikdörtgenin yüksekliği. |
| karakterler | List`1 | Kelime tarafından içerilen karakterler. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *word* null veya boş olduğunda fırlatılır. |
| ArgumentNullException | *characters* null olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [Character](../../character)
* class [Word](../../word)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
