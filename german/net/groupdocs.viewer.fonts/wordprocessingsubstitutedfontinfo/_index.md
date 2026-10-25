---
title: "WordProcessingSubstitutedFontInfo"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Kapselt Metainformationen und Binärdaten einer Schrift aus einem WordProcessing‑Dokument, die ursprünglich im in die Viewer../groupdocs.viewer/viewer‑Instanz geladene Dokument nicht verwendet wird, aber als Ersatzschrift für diejenigen dient, die auf dem Zielsystem nicht gefunden werden können. Ersetzte Schriften existieren nur für die WordProcessing‑Formatefamilie."
type: docs
weight: 890
url: /de/net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---

## WordProcessingSubstitutedFontInfo structure

Kapselt Metainformationen und Binärdaten einer Schrift aus einem WordProcessing‑Dokument, die ursprünglich im in die [`Viewer`](../../groupdocs.viewer/viewer)‑Instanz geladene Dokument nicht verwendet wird, aber als Ersatzschrift für diejenigen dient, die auf dem Zielsystem nicht gefunden werden können. Ersetzte Schriften existieren nur für die WordProcessing‑Formatefamilie.

```csharp
public struct WordProcessingSubstitutedFontInfo : IFontInfo
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content) { get; } | Inhalt dieser ersetzten Schrift als Byte‑Array. Ist niemals `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/familyname) { get; } | Familienname der **substituted** Schrift ohne Stil, ist niemals null oder ein leerer String. |
| [Format](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format) { get; } | Format dieser ersetzten (nicht originalen) Schrift. Kann TrueType, TrueType Collection, OpenType, Embedded Open Type sein. Da der Binärinhalt der ersetzten Schrift per Definition verfügbar ist, gibt diese Eigenschaft niemals einen Unknown‑Wert zurück. |
| [OriginalFamilyName](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/originalfamilyname) { get; } | Familienname der Originalschrift, die auf einem Zielsystem nicht gefunden werden kann, ohne Stil, ist niemals null oder ein leerer String. |
| [Style](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style) { get; } | Stil der Originalschrift — kann Regular, Bold, Italic oder Bold Italic sein. Ersetzte Schrift ist in der Regel (aber nicht immer) im gleichen Stil. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serializetocss)(TextWriter) | Serialisiert diese Schriftinformationen als @font-face‑At‑Rule und schreibt sie in den angegebenen Textwriter |
| override [ToString](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/tostring)() | Gibt Debug‑Informationen zu diesen Schrift­daten im folgenden Format zurück: "original-name -&gt; substituted-name style, format" |

### Bemerkungen

Unveränderliche Struktur. Ihre Instanzen werden von der öffentlichen API von GroupDocs.Viewer erzeugt und zurückgegeben und sollten normalerweise nicht vom Benutzer erstellt werden. Weitere Details finden Sie in der [Dokumentation](https://docs.groupdocs.com/viewer/net/getting-used-fonts/).

### Siehe auch

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
