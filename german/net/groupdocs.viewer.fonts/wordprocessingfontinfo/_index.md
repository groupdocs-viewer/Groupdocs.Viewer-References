---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Kapselt Metainformationen und Binärdaten einer Schriftart aus dem WordProcessing-Dokument, das in die Viewer../groupdocs.viewer/viewer-Instanz geladen wurde. Diese Schriftart wird im Dokumentinhalt verwendet und ist entweder im Dokument selbst eingebettet oder im Betriebssystem installiert, in dem GroupDocs.Viewer ausgeführt wird."
type: docs
weight: 880
url: /de/net/groupdocs.viewer.fonts/wordprocessingfontinfo/
---

## WordProcessingFontInfo structure

Kapselt Metainformationen und Binärdaten einer Schriftart aus dem WordProcessing-Dokument, das in die [`Viewer`](../../groupdocs.viewer/viewer)-Instanz geladen wurde. Diese Schriftart wird im Dokumentinhalt verwendet und ist entweder im Dokument selbst eingebettet oder im Betriebssystem installiert, in dem GroupDocs.Viewer ausgeführt wird.

```csharp
public struct WordProcessingFontInfo : IFontInfo
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AltFamilyName](../../groupdocs.viewer.fonts/wordprocessingfontinfo/altfamilyname) { get; } | Alternativer Familienname der Schriftart. Wenn nicht vorhanden, dann leere Zeichenkette. |
| [Charset](../../groupdocs.viewer.fonts/wordprocessingfontinfo/charset) { get; } | Zeichensatz dieser Schriftart |
| [Content](../../groupdocs.viewer.fonts/wordprocessingfontinfo/content) { get; } | Inhalt dieser Schrift als Byte‑Array. Wenn nur Metainformationen über diese Schrift vorliegen, deren Binärinhalt jedoch nicht verfügbar ist, gibt diese Eigenschaft `null` zurück. |
| [FamilyName](../../groupdocs.viewer.fonts/wordprocessingfontinfo/familyname) { get; } | Familienname der Schrift ohne Stil, ist niemals null oder ein leerer String. |
| [Format](../../groupdocs.viewer.fonts/wordprocessingfontinfo/format) { get; } | Format dieser Schrift. Dokumente können Schriften in den folgenden Formaten verwenden: TrueType, TrueType Collection, OpenType, Embedded Open Type. Wenn nur Metainformationen über diese Schrift vorliegen, deren Binärinhalt jedoch nicht verfügbar ist, gibt diese Eigenschaft einen Unknown‑Wert zurück. |
| [IsEmbedded](../../groupdocs.viewer.fonts/wordprocessingfontinfo/isembedded) { get; } | Gibt an, ob diese Schriftart im Dokument eingebettet ist, in die [`Viewer`](../../groupdocs.viewer/viewer)-Instanz geladen wurde (`true`), oder ob es sich um eine Systemschriftart handelt (`false`). |
| [Style](../../groupdocs.viewer.fonts/wordprocessingfontinfo/style) { get; } | Stil der Schrift — kann Regular, Bold, Italic oder Bold Italic sein. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/wordprocessingfontinfo/serializetocss)(TextWriter) | Serialisiert diese Schriftinformationen als @font-face‑At‑Rule und schreibt sie in den angegebenen Textwriter |
| override [ToString](../../groupdocs.viewer.fonts/wordprocessingfontinfo/tostring)() | Gibt Debug-Informationen zu diesen Schriftartdaten nach folgendem Muster zurück: "name style, embedded/system, format" |

### Bemerkungen

Unveränderliche Struktur. Ihre Instanzen werden von der öffentlichen API von GroupDocs.Viewer erzeugt und zurückgegeben und sollten normalerweise nicht vom Benutzer erstellt werden. Weitere Details finden Sie in der [Dokumentation](https://docs.groupdocs.com/viewer/net/getting-used-fonts/).

### Siehe auch

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
