---
title: "op_Explicit"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Convertit explicitement le Argb32Colorgroupdocs.viewer.drawing/argb32color 32 bits en Rgb24Colorgroupdocs.viewer.drawing/rgb24color 24 bits. Le canal alpha de la source Argb32Colorgroupdocs.viewer.drawing/argb32color sera perdu après la conversion car Rgb24Colorgroupdocs.viewer.drawing/rgb24color ne prend pas en charge la transparence."
type: docs
weight: 310
url: /fr/net/groupdocs.viewer.drawing/argb32color/op_explicit/
---

## Argb32Color Explicit operator

Convertit explicitement le 32 bits [`Argb32Color`](../../argb32color) en 24 bits [`Rgb24Color`](../../rgb24color). Le canal alpha de la source [`Argb32Color`](../../argb32color) sera perdu après la conversion, car [`Rgb24Color`](../../rgb24color) ne prend pas en charge la transparence.

```csharp
public static explicit operator Rgb24Color(Argb32Color argbColor)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| argbColor | Argb32Color | Source [`Argb32Color`](../../argb32color) à convertir |

### Voir aussi

* struct [Rgb24Color](../../rgb24color)
* struct [Argb32Color](../../argb32color)
* namespace [GroupDocs.Viewer.Drawing](../../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
