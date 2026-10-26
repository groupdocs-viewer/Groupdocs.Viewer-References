---
title: "PresentationOptions"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Contiene opciones para renderizar presentaciones. Para más detalles, consulte la documentaciónhttps//docs.groupdocs.com/viewer/net/renderpresentations/."
type: docs
weight: 460
url: /es/net/groupdocs.viewer.options/presentationoptions/
---

## PresentationOptions class

Contiene opciones para renderizar presentaciones. Para más detalles, consulte la [documentación](https://docs.groupdocs.com/viewer/net/render-presentations/).

```csharp
public class PresentationOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PresentationOptions](presentationoptions)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [RenderHeaderFooterPlaceholders](../../groupdocs.viewer.options/presentationoptions/renderheaderfooterplaceholders) { get; set; } | Habilita la representación de marcadores de posición en el encabezado y pie de una diapositiva. Desactivado por defecto (`false`). Esta opción se aplica a los 4 modos de renderizado de presentaciones: HTML, PDF, PNG y JPEG. No es aplicable al renderizar la presentación a marcado HTML/CSS puro usando [`RenderToPureHtml`](./rendertopurehtml). |
| [RenderToPureHtml](../../groupdocs.viewer.options/presentationoptions/rendertopurehtml) { get; set; } | Habilita un nuevo modo de renderizado HTML para los documentos de Presentation — en este modo los archivos de Presentation se renderizan a **pure HTML/CSS markup**, sin imágenes SVG. Por defecto está desactivado (`false`) — se usa el renderizador HTML basado en SVG existente. |
| [Resolution](../../groupdocs.viewer.options/presentationoptions/resolution) { get; set; } | Resolución de las imágenes de la presentación (solo para renderizar a HTML/PDF). |

### Ver también

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
