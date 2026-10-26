---
title: "CadOptions"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Contiene opciones para renderizar dibujos CAD. Para obtener más información y ejemplos de código, consulte Renderizar dibujos CAD y modelos como archivos HTML, PDF e imágenes https//docs.groupdocs.com/viewer/net/rendercaddrawingsandmodels/ y Especificar opciones de renderizado para archivos CAD https//docs.groupdocs.com/viewer/net/specifycadrenderingoptions/."
type: docs
weight: 280
url: /es/net/groupdocs.viewer.options/cadoptions/
---

## CadOptions class

Contiene opciones para renderizar dibujos CAD. Para más información y ejemplos de código, consulte el [Render CAD drawings and models as HTML, PDF, and image files](https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) y el [Specify rendering options for CAD files](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/).

```csharp
public class CadOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackgroundColor](../../groupdocs.viewer.options/cadoptions/backgroundcolor) { get; set; } | Color de fondo de la imagen. |
| [EnablePerformanceConversionMode](../../groupdocs.viewer.options/cadoptions/enableperformanceconversionmode) { get; set; } | Establecer este indicador a `true` habilita un modo de conversión especial orientado al rendimiento para todos los formatos dentro de la familia CAD — en este modo la velocidad de conversión es mucho más rápida, pero la calidad de los documentos resultantes es significativamente peor. Por defecto está deshabilitado (`false`) — la calidad de los documentos resultantes es la mejor posible a costa del rendimiento. |
| [Height](../../groupdocs.viewer.options/cadoptions/height) { get; } | La altura del resultado de salida (en píxeles). |
| [Layers](../../groupdocs.viewer.options/cadoptions/layers) { get; set; } | Las capas de dibujo CAD a renderizar. |
| [LayoutName](../../groupdocs.viewer.options/cadoptions/layoutname) { get; set; } | El nombre del diseño específico a renderizar. El nombre del diseño distingue entre mayúsculas y minúsculas. |
| [Pc3File](../../groupdocs.viewer.options/cadoptions/pc3file) { get; set; } | PC3 - archivo de configuración del plotter |
| [RenderLayouts](../../groupdocs.viewer.options/cadoptions/renderlayouts) { get; set; } | Marcar si los diseños del documento CAD deben renderizarse. |
| [ScaleFactor](../../groupdocs.viewer.options/cadoptions/scalefactor) { get; } | Un valor mayor que 1 amplía el resultado de salida; un valor entre 0 y 1 reduce el resultado de salida. |
| [Tiles](../../groupdocs.viewer.options/cadoptions/tiles) { get; set; } | Las regiones de dibujo a renderizar. |
| [Width](../../groupdocs.viewer.options/cadoptions/width) { get; } | El ancho del resultado de salida (en píxeles). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ForRenderingByHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbyheight)(int) | Inicializa una instancia de la clase [`CadOptions`](../cadoptions) para renderizar por altura. |
| static [ForRenderingByScaleFactor](../../groupdocs.viewer.options/cadoptions/forrenderingbyscalefactor)(float) | Inicializa una instancia de la clase [`CadOptions`](../cadoptions) para renderizar por factor de escala. |
| static [ForRenderingByWidth](../../groupdocs.viewer.options/cadoptions/forrenderingbywidth)(int) | Inicializa una instancia de la clase [`CadOptions`](../cadoptions) para renderizar por ancho. |
| static [ForRenderingByWidthAndHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbywidthandheight)(int, int) | Inicializa una instancia de la clase [`CadOptions`](../cadoptions) para renderizar por ancho y altura. |

### Ver también

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
