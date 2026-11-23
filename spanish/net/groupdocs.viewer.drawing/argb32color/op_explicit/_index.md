---
title: "op_Explicit"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Convierte explícitamente el Argb32Colorgroupdocs.viewer.drawing/argb32color de 32 bits a Rgb24Colorgroupdocs.viewer.drawing/rgb24color de 24 bits. El canal alfa del Argb32Colorgroupdocs.viewer.drawing/argb32color de origen se perderá después de la conversión porque Rgb24Colorgroupdocs.viewer.drawing/rgb24color no admite transparencia."
type: docs
weight: 310
url: /es/net/groupdocs.viewer.drawing/argb32color/op_explicit/
---

## Argb32Color Explicit operator

Convierte explícitamente el [`Argb32Color`](../../argb32color) de 32 bits a [`Rgb24Color`](../../rgb24color) de 24 bits. El canal alfa del [`Argb32Color`](../../argb32color) de origen se perderá tras la conversión, porque [`Rgb24Color`](../../rgb24color) no admite transparencia.

```csharp
public static explicit operator Rgb24Color(Argb32Color argbColor)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| argbColor | Argb32Color | Origen [`Argb32Color`](../../argb32color) a convertir |

### Ver también

* struct [Rgb24Color](../../rgb24color)
* struct [Argb32Color](../../argb32color)
* namespace [GroupDocs.Viewer.Drawing](../../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
