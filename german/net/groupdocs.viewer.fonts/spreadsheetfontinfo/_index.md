---
title: "SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Kapselt Metainformationen und Binärdaten einer Schriftart aus dem Spreadsheet-Dokument, das in die Viewer../groupdocs.viewer/viewer‑Instanz geladen wurde. Spreadsheet‑Dokumente können keine eingebetteten Schriftarten enthalten, sodass diese bestimmte Schriftart, falls sie von der GetAllFonts../groupdocs.viewer/viewer/getallfonts‑Methode zurückgegeben wurde, im Betriebssystem installiert wird, in dem GroupDocs.Viewer ausgeführt wird."
type: docs
weight: 870
url: /de/net/groupdocs.viewer.fonts/spreadsheetfontinfo/
---

## SpreadsheetFontInfo structure

Kapselt Metainformationen und Binärdaten einer Schriftart aus dem Spreadsheet‑Dokument, das in die [`Viewer`](../../groupdocs.viewer/viewer)‑Instanz geladen wurde. Spreadsheet‑Dokumente können keine eingebetteten Schriftarten enthalten, sodass diese bestimmte Schriftart, falls sie von der [`GetAllFonts`](../../groupdocs.viewer/viewer/getallfonts)‑Methode zurückgegeben wurde, im Betriebssystem installiert wird, in dem GroupDocs.Viewer ausgeführt wird.

```csharp
public struct SpreadsheetFontInfo : IFontInfo
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Charset](../../groupdocs.viewer.fonts/spreadsheetfontinfo/charset) { get; } | Zeichensatz dieser Schriftart |
| [Color](../../groupdocs.viewer.fonts/spreadsheetfontinfo/color) { get; } | Farbe dieser Schriftart |
| [Content](../../groupdocs.viewer.fonts/spreadsheetfontinfo/content) { get; } | Inhalt dieser Schrift als Byte‑Array. Wenn nur Metainformationen über diese Schrift vorliegen, deren Binärinhalt jedoch nicht verfügbar ist, gibt diese Eigenschaft `null` zurück. |
| [FamilyName](../../groupdocs.viewer.fonts/spreadsheetfontinfo/familyname) { get; } | Familienname der Schrift ohne Stil, ist niemals null oder ein leerer String. |
| [Format](../../groupdocs.viewer.fonts/spreadsheetfontinfo/format) { get; } | Format dieser Schriftart |
| [IsStrikeout](../../groupdocs.viewer.fonts/spreadsheetfontinfo/isstrikeout) { get; } | Gibt an, ob die Schriftart ein einzelnes Durchstreichen aufweist |
| [IsUnderline](../../groupdocs.viewer.fonts/spreadsheetfontinfo/isunderline) { get; } | Gibt an, ob die Schriftart unterstrichen ist |
| [Style](../../groupdocs.viewer.fonts/spreadsheetfontinfo/style) { get; } | Stil dieser Schriftart — kann Regular, Bold, Italic oder Bold Italic sein |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/spreadsheetfontinfo/serializetocss)(TextWriter) | Serialisiert diese Schriftinformationen als @font-face‑At‑Rule und schreibt sie in den angegebenen Textwriter |

### Siehe auch

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
