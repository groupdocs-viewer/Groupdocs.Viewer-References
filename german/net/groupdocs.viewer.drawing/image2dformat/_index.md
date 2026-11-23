---
title: "Image2DFormat"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Stellt die gängigsten 2D-Bildformate dar, die sowohl Raster- als auch Vektorformate unterstützen"
type: docs
weight: 960
url: /de/net/groupdocs.viewer.drawing/image2dformat/
---

## Image2DFormat structure

Stellt die gängigsten 2D‑Bildformate dar, unterstützt sowohl Raster‑ als auch Vektorformate.

```csharp
public struct Image2DFormat : IEquatable<Image2DFormat>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Bmp](../../groupdocs.viewer.drawing/image2dformat/bmp) { get; } | BMP-Bildtyp |
| static [Emf](../../groupdocs.viewer.drawing/image2dformat/emf) { get; } | EMF (Enhanced MetaFile) Vektor-Bildtyp |
| static [Gif](../../groupdocs.viewer.drawing/image2dformat/gif) { get; } | GIF-Bildtyp |
| static [Icon](../../groupdocs.viewer.drawing/image2dformat/icon) { get; } | ICON-Bildtyp |
| static [Jpeg](../../groupdocs.viewer.drawing/image2dformat/jpeg) { get; } | JPEG-Bildtyp |
| static [Png](../../groupdocs.viewer.drawing/image2dformat/png) { get; } | PNG-Bildtyp |
| static [Svg](../../groupdocs.viewer.drawing/image2dformat/svg) { get; } | SVG-Vektor-Bildtyp |
| static [Tiff](../../groupdocs.viewer.drawing/image2dformat/tiff) { get; } | TIFF (Tagged Image File Format) Raster-Bildtyp |
| static [Undefined](../../groupdocs.viewer.drawing/image2dformat/undefined) { get; } | Undefinierter Bildtyp – spezieller Wert, der normalerweise nicht auftreten sollte |
| static [Wmf](../../groupdocs.viewer.drawing/image2dformat/wmf) { get; } | WMF (Windows MetaFile) Vektor-Bildtyp |
| [FileExtension](../../groupdocs.viewer.drawing/image2dformat/fileextension) { get; } | Dateierweiterung (ohne führenden Punkt) eines bestimmten Bildtyps in Kleinbuchstaben. Für den [`Undefined`](./undefined)-Wert wird die Zeichenkette 'undefined' zurückgegeben. |
| [IsVector](../../groupdocs.viewer.drawing/image2dformat/isvector) { get; } | Gibt an, ob dieses bestimmte Format ein Vektor (`true`) oder ein Raster (`false`) ist |
| [MimeCode](../../groupdocs.viewer.drawing/image2dformat/mimecode) { get; } | MIME-Code eines bestimmten Bildtyps als Zeichenkette. Für den Undefined-Typ wird die Zeichenkette 'unsefined' zurückgegeben. |
| [Name](../../groupdocs.viewer.drawing/image2dformat/name) { get; } | Gibt einen formellen Namen dieses Bildformats zurück. Gibt niemals NULL zurück. Wenn die Instanz nicht beschädigt ist, wird niemals eine Ausnahme ausgelöst. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.viewer.drawing/image2dformat/parsefromfilenamewithextension)(string) | Gibt den ImageFormat-Wert zurück, der dem Dateierweiterungswert entspricht, der aus dem angegebenen Dateinamen extrahiert wird |
| static [ParseFromMime](../../groupdocs.viewer.drawing/image2dformat/parsefrommime)(string) | Gibt den [`Image2DFormat`](../image2dformat)-Wert zurück, der dem angegebenen MIME-Code entspricht |
| [Equals](../../groupdocs.viewer.drawing/image2dformat/equals#equals)(Image2DFormat) | Bestimmt, ob diese Instanz mit der angegebenen "[`Image2DFormat`](../image2dformat)"-Instanz gleich ist |
| override [Equals](../../groupdocs.viewer.drawing/image2dformat/equals#equals_1)(object) | Bestimmt, ob diese Instanz mit dem angegebenen nicht gecasteten Objekt gleich ist, das vermutlich eine weitere "[`Image2DFormat`](../image2dformat)"-Instanz ist |
| override [GetHashCode](../../groupdocs.viewer.drawing/image2dformat/gethashcode)() | Gibt einen Hash-Code zurück, der eine unveränderliche Zahl für diese spezifische Instanz ist |
| override [ToString](../../groupdocs.viewer.drawing/image2dformat/tostring)() | Gibt die [`Name`](./name)-Eigenschaft zurück |
| [operator ==](../../groupdocs.viewer.drawing/image2dformat/op_equality) | Definiert, ob zwei bestimmte [`Image2DFormat`](../image2dformat)-Instanzen gleich sind |
| [operator !=](../../groupdocs.viewer.drawing/image2dformat/op_inequality) | Definiert, ob zwei bestimmte [`Image2DFormat`](../image2dformat)-Instanzen ungleich sind |

### Siehe auch

* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
