---
title: "TextElement"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der TextElementgroupdocs.viewer.results/textelement1 Klasse."
type: docs
weight: 10
url: /de/net/groupdocs.viewer.results/textelement-1/textelement/
---

## TextElement() {#constructor}

Initialisiert eine neue Instanz der [`TextElement`](../../textelement-1) Klasse.

```csharp
public TextElement()
```

### Siehe auch

* class [TextElement&lt;T&gt;](../../textelement-1)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## TextElement(T, double, double, double, double) {#constructor_1}

Initialisiert eine neue Instanz der [`TextElement`](../../textelement-1) Klasse.

```csharp
public TextElement(T value, double x, double y, double width, double height)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | T | Der Wert des Textelements. |
| x | Double | Die X‑Koordinate des höchsten linken Punktes im Seitenlayout, an dem das Rechteck, das das Element enthält, beginnt. |
| y | Double | Die Y‑Koordinate des höchsten linken Punktes im Seitenlayout, an dem das Rechteck, das das Element enthält, beginnt. |
| Breite | Double | Die Breite des Rechtecks, das das Element enthält (in Pixeln). |
| Höhe | Double | Die Höhe des Rechtecks, das das Element enthält (in Pixeln). |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *value* null ist. |
| ArgumentException | Wird ausgelöst, wenn *width* kleiner oder gleich Null ist. |
| ArgumentException | Wird ausgelöst, wenn *height* kleiner oder gleich Null ist. |

### Siehe auch

* class [TextElement&lt;T&gt;](../../textelement-1)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
