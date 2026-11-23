---
title: "IFontInfo"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Gemeinsame Schnittstelle für alle Schriftarten, die aus allen unterstützten Familien von Dokumentformaten PDF, Textverarbeitung, Tabellenkalkulation und Präsentation extrahiert werden können."
type: docs
weight: 820
url: /de/net/groupdocs.viewer.fonts/ifontinfo/
---

## IFontInfo interface

Gemeinsame Schnittstelle für alle Schriften, die aus allen unterstützten Familien von Dokumentformaten extrahiert werden können: PDF, WordProcessing, Spreadsheet und Presentation.

```csharp
public interface IFontInfo
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/ifontinfo/content) { get; } | Binärer Inhalt der Schriftart als Byte‑Array, falls verfügbar, oder `null`, falls nicht. |
| [FamilyName](../../groupdocs.viewer.fonts/ifontinfo/familyname) { get; } | Familienname der Schriftart als Zeichenkette |
| [Format](../../groupdocs.viewer.fonts/ifontinfo/format) { get; } | Format dieser Schriftart als Aufzählung — TrueType, TrueType Collection, OpenType, Embedded OpenType oder Unknown. |
| [Style](../../groupdocs.viewer.fonts/ifontinfo/style) { get; } | Stil der Schriftart als Aufzählung — Regular, Bold, Italic oder Bold Italic. Einige Dokumentformate können nur Schriftarten mit dem Stil [`Regular`](../fontstyles/regular) besitzen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/ifontinfo/serializetocss)(TextWriter) | Serialisiert diese Schriftinformationen als @font-face‑At‑Rule und schreibt sie in den angegebenen Textwriter |

### Siehe auch

* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
