---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Kapselt Metainformationen und Binärdaten einer Schrift aus dem PDF‑Dokument, das in die Viewer../groupdocs.viewer/viewer‑Instanz geladen wurde. Diese Schrift wird im Dokumentinhalt verwendet und ist entweder im Dokument selbst eingebettet oder im Betriebssystem installiert, auf dem GroupDocs.Viewer läuft."
type: docs
weight: 840
url: /de/net/groupdocs.viewer.fonts/pdffontinfo/
---

## PdfFontInfo structure

Kapselt Metainformationen und Binärdaten einer Schrift aus dem PDF‑Dokument, das in die [`Viewer`](../../groupdocs.viewer/viewer)‑Instanz geladen wurde. Diese Schrift wird im Dokumentinhalt verwendet und ist entweder im Dokument selbst eingebettet oder im Betriebssystem installiert, wo GroupDocs.Viewer läuft.

```csharp
public struct PdfFontInfo : IFontInfo
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/pdffontinfo/content) { get; } | Inhalt dieser Schrift als Byte‑Array. Wenn nur Metainformationen über diese Schrift vorliegen, deren Binärinhalt jedoch nicht verfügbar ist, gibt diese Eigenschaft `null` zurück. |
| [FamilyName](../../groupdocs.viewer.fonts/pdffontinfo/familyname) { get; } | Familienname der Schrift ohne Stil, ist niemals null oder ein leerer String. |
| [Format](../../groupdocs.viewer.fonts/pdffontinfo/format) { get; } | Format dieser Schrift. Dokumente können Schriften in den folgenden Formaten verwenden: TrueType, TrueType Collection, OpenType, Embedded Open Type. Wenn nur Metainformationen über diese Schrift vorliegen, deren Binärinhalt jedoch nicht verfügbar ist, gibt diese Eigenschaft einen Unknown‑Wert zurück. |
| [IsEmbedded](../../groupdocs.viewer.fonts/pdffontinfo/isembedded) { get; } | Gibt an, ob diese Schrift im PDF‑Dokument eingebettet ist, das in die [`Viewer`](../../groupdocs.viewer/viewer)‑Instanz geladen wurde (`true`), oder nicht. |
| [IsInstalled](../../groupdocs.viewer.fonts/pdffontinfo/isinstalled) { get; } | Gibt an, ob diese Schrift im Betriebssystem vorhanden (installiert) ist, auf dem GroupDocs.Viewer läuft. |
| [Style](../../groupdocs.viewer.fonts/pdffontinfo/style) { get; } | Stil der Schrift — kann Regular, Bold, Italic oder Bold Italic sein. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/pdffontinfo/serializetocss)(TextWriter) | Serialisiert diese Schriftinformationen als @font-face‑At‑Rule und schreibt sie in den angegebenen Textwriter |

### Siehe auch

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
