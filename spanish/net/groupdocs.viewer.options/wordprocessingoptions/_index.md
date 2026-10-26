---
title: "WordProcessingOptions"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Contiene opciones para renderizar documentos Word. Para más detalles, consulte la documentaciónhttps//docs.groupdocs.com/viewer/net/renderworddocuments/."
type: docs
weight: 630
url: /es/net/groupdocs.viewer.options/wordprocessingoptions/
---

## WordProcessingOptions class

Contiene opciones para renderizar documentos Word. Para más detalles, consulte la [documentación](https://docs.groupdocs.com/viewer/net/render-word-documents/).

```csharp
public class WordProcessingOptions : ICloneable, IEquatable<WordProcessingOptions>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WordProcessingOptions](wordprocessingoptions)() | Contiene opciones para renderizar documentos de procesamiento de texto. Para más detalles, vea la [documentación](https://docs.groupdocs.com/viewer/net/render-word-documents/). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/wordprocessingoptions/bottommargin) { get; set; } | Establece el margen inferior de una página. |
| [EnableOpenTypeFeatures](../../groupdocs.viewer.options/wordprocessingoptions/enableopentypefeatures) { get; set; } | Esta opción habilita el kerning y otras características OpenType al renderizar scripts árabes, hebreos, basados en latín indio o basados en cirílico. |
| [HorizontalResolution](../../groupdocs.viewer.options/wordprocessingoptions/horizontalresolution) { get; set; } | Obtiene o establece la resolución horizontal para las imágenes generadas en puntos por pulgada. Esta opción se usa al renderizar documentos WordProcessing a formatos PNG o JPEG únicamente. |
| [LeftMargin](../../groupdocs.viewer.options/wordprocessingoptions/leftmargin) { get; set; } | Establece el margen izquierdo de una página. |
| [PageNumberLocation](../../groupdocs.viewer.options/wordprocessingoptions/pagenumberlocation) { get; set; } | Permite aplicar forzadamente la numeración de páginas al documento WordProcessing cargado. Por defecto es NotApply — el documento permanece intacto. |
| [PageSize](../../groupdocs.viewer.options/wordprocessingoptions/pagesize) { get; set; } | El tamaño de la página de salida. El valor predeterminado es Unspecified, lo que significa que se utiliza un tamaño de página establecido en la configuración de página (Configuración de página). Al renderizar archivos HTM y HTML, el tamaño de página predeterminado se establece en Letter 792 x 612 puntos. Como resultado, parte del contenido puede no caber en el marco de la página. Establezca un tamaño de página mayor, por ejemplo A3, para que el contenido quepa. |
| [RenderTrackedChanges](../../groupdocs.viewer.options/wordprocessingoptions/rendertrackedchanges) { get; set; } | Habilita la renderización de cambios rastreados (revisiones). |
| [RightMargin](../../groupdocs.viewer.options/wordprocessingoptions/rightmargin) { get; set; } | Establece el margen derecho de una página. |
| [TopMargin](../../groupdocs.viewer.options/wordprocessingoptions/topmargin) { get; set; } | Establece el margen superior de una página. |
| [UnlinkTableOfContents](../../groupdocs.viewer.options/wordprocessingoptions/unlinktableofcontents) { get; set; } | Al renderizar a HTML o PDF, puede establecer esta opción en `true` para desactivar la navegación desde la tabla de contenido. Para la renderización HTML, las etiquetas `a` con enlaces relativos se reemplazarán por etiquetas `span`, eliminando la funcionalidad pero conservando la apariencia visual. Para la renderización PDF, la tabla de contenido se renderizará como texto plano sin enlaces a secciones del documento. |
| [UpdateFields](../../groupdocs.viewer.options/wordprocessingoptions/updatefields) { get; set; } | Obtiene o establece un valor que determina si los campos de ciertos tipos deben actualizarse antes de guardar el documento WordProcessing de entrada en los formatos de salida HTML, PDF, PNG o JPEG. El valor predeterminado para esta propiedad es `true` — los campos se actualizarán antes de guardar. |
| [VerticalResolution](../../groupdocs.viewer.options/wordprocessingoptions/verticalresolution) { get; set; } | Obtiene o establece la resolución vertical para las imágenes generadas en puntos por pulgada. Esta opción se usa al renderizar documentos WordProcessing a formatos PNG o JPEG únicamente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.viewer.options/wordprocessingoptions/clone)() | Crea y devuelve una copia profunda completa de estas opciones. |
| [Equals](../../groupdocs.viewer.options/wordprocessingoptions/equals#equals)(WordProcessingOptions) | Determina si la instancia especificada de [`WordProcessingOptions`](../wordprocessingoptions) es igual a esta. |

### Ver también

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
