---
title: "TextOverflowMode"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Establece el modo de desbordamiento de texto para renderizar documentos de hoja de cálculo en HTML."
type: docs
weight: 550
url: /es/net/groupdocs.viewer.options/textoverflowmode/
---

## TextOverflowMode enumeration

Establece el modo de desbordamiento de texto para renderizar documentos de hoja de cálculo en HTML.

```csharp
public enum TextOverflowMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Overlay | `0` | Superpone las celdas siguientes incluso si no están vacías. |
| OverlayIfNextIsEmpty | `1` | Superpone las celdas siguientes solo si están vacías. Valor predeterminado. |
| AutoFitColumn | `2` | Expande las columnas para que se ajuste el texto. |
| HideText | `3` | Oculta el texto que desborda. |

### Observaciones

Para más detalles, consulte la [documentación](https://docs.groupdocs.com/viewer/net/specify-rendering-options/#control-cell-text-overflow).

### Ver también

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
