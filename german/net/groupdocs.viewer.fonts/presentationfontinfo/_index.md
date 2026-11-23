---
title: "PresentationFontInfo"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Kapselt Metainformationen und Binärdaten einer Schriftart aus dem Präsentationsdokument, das in die Viewer../groupdocs.viewer/viewer-Instanz geladen wurde. Diese Schriftart wird im Dokumentinhalt verwendet und ist entweder im Dokument selbst eingebettet oder im Betriebssystem installiert, in dem GroupDocs.Viewer ausgeführt wird."
type: docs
weight: 850
url: /de/net/groupdocs.viewer.fonts/presentationfontinfo/
---

## PresentationFontInfo structure

Kapselt Metainformationen und Binärdaten einer Schriftart aus dem Präsentationsdokument, das in die [`Viewer`](../../groupdocs.viewer/viewer)-Instanz geladen wurde. Diese Schriftart wird im Dokumentinhalt verwendet und ist entweder im Dokument selbst eingebettet oder im Betriebssystem installiert, in dem GroupDocs.Viewer ausgeführt wird.

```csharp
public struct PresentationFontInfo : IFontInfo
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/presentationfontinfo/content) { get; } | Inhalt dieser Schrift als Byte‑Array. Wenn nur Metainformationen über diese Schrift vorliegen, deren Binärinhalt jedoch nicht verfügbar ist, gibt diese Eigenschaft `null` zurück. |
| [FamilyName](../../groupdocs.viewer.fonts/presentationfontinfo/familyname) { get; } | Familienname der Schrift ohne Stil, ist niemals null oder ein leerer String. |
| [Format](../../groupdocs.viewer.fonts/presentationfontinfo/format) { get; } | Format dieser Schrift. Dokumente können Schriften in den folgenden Formaten verwenden: TrueType, TrueType Collection, OpenType, Embedded Open Type. Wenn nur Metainformationen über diese Schrift vorliegen, deren Binärinhalt jedoch nicht verfügbar ist, gibt diese Eigenschaft einen Unknown‑Wert zurück. |
| [IsEmbedded](../../groupdocs.viewer.fonts/presentationfontinfo/isembedded) { get; } | Gibt an, ob diese Schriftart im Dokument eingebettet ist, in die [`Viewer`](../../groupdocs.viewer/viewer)-Instanz geladen wurde (`true`), oder ob es sich um eine Systemschriftart handelt (`false`). Tabellenkalkulationsdokumente können keine eingebetteten Schriftarten enthalten, daher gibt diese Eigenschaft für sie stets `false` zurück. |
| [Style](../../groupdocs.viewer.fonts/presentationfontinfo/style) { get; } | Stil der Schriftart — kann Regular, Bold, Italic oder Bold Italic sein |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/presentationfontinfo/serializetocss)(TextWriter) | Serialisiert diese Schriftinformationen als @font-face‑At‑Rule und schreibt sie in den angegebenen Textwriter |

### Siehe auch

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
