---
title: "Wort"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der Klasse Wordgroupdocs.viewer.results/word."
type: docs
weight: 10
url: /de/net/groupdocs.viewer.results/word/word/
---

## Word() {#constructor}

Initialisiert eine neue Instanz der Klasse [`Word`](../../word).

```csharp
public Word()
```

### Siehe auch

* class [Word](../../word)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Word(string, double, double, double, double, List&lt;Character&gt;) {#constructor_1}

Initialisiert eine neue Instanz der Klasse [`Word`](../../word).

```csharp
public Word(string word, double x, double y, double width, double height, 
    List<Character> characters)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wort | String | Das Wort. |
| x | Double | Die X‑Koordinate des höchsten linken Punktes im Seitenlayout, an dem das Rechteck, das das Wort enthält, beginnt. |
| y | Double | Die Y‑Koordinate des höchsten linken Punktes im Seitenlayout, an dem das Rechteck, das das Wort enthält, beginnt. |
| Breite | Double | Die Breite des Rechtecks, das das Wort enthält. |
| Höhe | Double | Die Höhe des Rechtecks, das das Wort enthält. |
| Zeichen | List`1 | Die Zeichen, die im Wort enthalten sind. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *word* null oder leer ist. |
| ArgumentNullException | Wird ausgelöst, wenn *characters* null ist. |

### Siehe auch

* class [Character](../../character)
* class [Word](../../word)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
