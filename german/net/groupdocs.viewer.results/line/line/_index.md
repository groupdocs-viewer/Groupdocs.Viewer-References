---
title: "Zeile"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der Linegroupdocs.viewer.results/line Klasse."
type: docs
weight: 10
url: /de/net/groupdocs.viewer.results/line/line/
---

## Line() {#constructor}

Initialisiert eine neue Instanz der [`Line`](../../line) Klasse.

```csharp
public Line()
```

### Siehe auch

* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Line(string, double, double, double, double, List&lt;Word&gt;) {#constructor_1}

Initialisiert eine neue Instanz der [`Line`](../../line) Klasse.

```csharp
public Line(string line, double x, double y, double width, double height, List<Word> words)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Zeile | String | Die Zeile. |
| x | Double | Die X-Koordinate des höchsten linken Punktes im Seitenlayout, an dem das Rechteck, das die Zeile enthält, beginnt. |
| y | Double | Die Y-Koordinate des höchsten linken Punktes im Seitenlayout, an dem das Rechteck, das die Zeile enthält, beginnt. |
| Breite | Double | Die Breite des Rechtecks, das die Zeile enthält (in Pixeln). |
| Höhe | Double | Die Höhe des Rechtecks, das die Zeile enthält (in Pixeln). |
| Wörter | List`1 | Die von der Zeile enthaltenen Wörter. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *line* null oder leer ist. |
| ArgumentNullException | Wird ausgelöst, wenn *words* null ist. |

### Siehe auch

* class [Word](../../word)
* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
