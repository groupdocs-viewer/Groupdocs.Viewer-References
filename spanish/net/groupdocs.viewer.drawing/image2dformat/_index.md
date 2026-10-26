---
title: "Image2DFormat"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Representa los formatos de imagen 2D más comunes, admite tanto formatos raster como vectoriales."
type: docs
weight: 960
url: /es/net/groupdocs.viewer.drawing/image2dformat/
---

## Image2DFormat structure

Representa los formatos de imagen 2D más comunes, soporta tanto formatos raster como vectoriales.

```csharp
public struct Image2DFormat : IEquatable<Image2DFormat>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Bmp](../../groupdocs.viewer.drawing/image2dformat/bmp) { get; } | Tipo de imagen BMP |
| static [Emf](../../groupdocs.viewer.drawing/image2dformat/emf) { get; } | Tipo de imagen vectorial EMF (Enhanced MetaFile) |
| static [Gif](../../groupdocs.viewer.drawing/image2dformat/gif) { get; } | Tipo de imagen GIF |
| static [Icon](../../groupdocs.viewer.drawing/image2dformat/icon) { get; } | Tipo de imagen ICON |
| static [Jpeg](../../groupdocs.viewer.drawing/image2dformat/jpeg) { get; } | Tipo de imagen JPEG |
| static [Png](../../groupdocs.viewer.drawing/image2dformat/png) { get; } | Tipo de imagen PNG |
| static [Svg](../../groupdocs.viewer.drawing/image2dformat/svg) { get; } | Tipo de imagen vectorial SVG |
| static [Tiff](../../groupdocs.viewer.drawing/image2dformat/tiff) { get; } | Tipo de imagen raster TIFF (Tagged Image File Format) |
| static [Undefined](../../groupdocs.viewer.drawing/image2dformat/undefined) { get; } | Tipo de imagen indefinido - valor especial, que normalmente no debería ocurrir |
| static [Wmf](../../groupdocs.viewer.drawing/image2dformat/wmf) { get; } | Tipo de imagen vectorial WMF (Windows MetaFile) |
| [FileExtension](../../groupdocs.viewer.drawing/image2dformat/fileextension) { get; } | Extensión de archivo (sin el carácter de punto inicial) de un tipo de imagen particular en minúsculas. Para el valor [`Undefined`](./undefined) devuelve la cadena 'undefined'. |
| [IsVector](../../groupdocs.viewer.drawing/image2dformat/isvector) { get; } | Indica si este formato particular es vector (`true`) o raster (`false`) |
| [MimeCode](../../groupdocs.viewer.drawing/image2dformat/mimecode) { get; } | Código MIME de un tipo de imagen particular como una cadena. Para el tipo Undefined devuelve la cadena 'unsefined'. |
| [Name](../../groupdocs.viewer.drawing/image2dformat/name) { get; } | Devuelve un nombre formal de este formato de imagen. Nunca devuelve NULL. Si la instancia no está corrupta, nunca lanza una excepción. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.viewer.drawing/image2dformat/parsefromfilenamewithextension)(string) | Devuelve el valor ImageFormat, que es equivalente a la extensión del nombre de archivo, que se extrae del nombre de archivo especificado |
| static [ParseFromMime](../../groupdocs.viewer.drawing/image2dformat/parsefrommime)(string) | Devuelve el valor [`Image2DFormat`](../image2dformat), que es equivalente al código MIME especificado |
| [Equals](../../groupdocs.viewer.drawing/image2dformat/equals#equals)(Image2DFormat) | Determina si esta instancia es igual a la instancia especificada "[`Image2DFormat`](../image2dformat)" |
| override [Equals](../../groupdocs.viewer.drawing/image2dformat/equals#equals_1)(object) | Determina si esta instancia es igual al objeto no casteado especificado, que presumiblemente es otra instancia "[`Image2DFormat`](../image2dformat)" |
| override [GetHashCode](../../groupdocs.viewer.drawing/image2dformat/gethashcode)() | Devuelve un hash-code, que es un número inmutable para esta instancia específica |
| override [ToString](../../groupdocs.viewer.drawing/image2dformat/tostring)() | Devuelve la propiedad [`Name`](./name) |
| [operator ==](../../groupdocs.viewer.drawing/image2dformat/op_equality) | Define si dos instancias específicas de [`Image2DFormat`](../image2dformat) son iguales |
| [operator !=](../../groupdocs.viewer.drawing/image2dformat/op_inequality) | Define si dos instancias específicas de [`Image2DFormat`](../image2dformat) no son iguales |

### Ver también

* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
