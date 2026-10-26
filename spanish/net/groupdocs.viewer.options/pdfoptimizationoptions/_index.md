---
title: "PdfOptimizationOptions"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Contiene las opciones de optimización de PDF para aplicar al archivo PDF de salida. Para más detalles y ejemplos de código, vea esta página https//docs.groupdocs.com/viewer/net/optimizationpdfoptions/ y sus subpáginas."
type: docs
weight: 400
url: /es/net/groupdocs.viewer.options/pdfoptimizationoptions/
---

## PdfOptimizationOptions class

Contiene las opciones de optimización PDF para aplicar al archivo PDF de salida. Para más detalles y ejemplos de código, consulte esta [página](https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) y sus subpáginas.

```csharp
public class PdfOptimizationOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | Establece los valores predeterminados de la opción MaxResolution a 300 y de la opción ImageQuality a 100. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CompressImages](../../groupdocs.viewer.options/pdfoptimizationoptions/compressimages) { get; set; } | Habilita la compresión de imágenes en el archivo PDF de salida. |
| [ConvertToGrayScale](../../groupdocs.viewer.options/pdfoptimizationoptions/converttograyscale) { get; set; } | Habilita la conversión del archivo PDF de salida a escala de grises. |
| [ImageQuality](../../groupdocs.viewer.options/pdfoptimizationoptions/imagequality) { get; set; } | Establece la calidad de imagen en el archivo PDF de salida (en porcentaje). |
| [Lineriaze](../../groupdocs.viewer.options/pdfoptimizationoptions/lineriaze) { get; set; } | Habilita la optimización del archivo PDF de salida para su visualización en línea con un navegador web. |
| [MaxResolution](../../groupdocs.viewer.options/pdfoptimizationoptions/maxresolution) { get; set; } | Establece la resolución máxima en el archivo PDF de salida. |
| [OptimizeSpreadsheets](../../groupdocs.viewer.options/pdfoptimizationoptions/optimizespreadsheets) { get; set; } | Habilita la optimización de hojas de cálculo en los archivos PDF. |
| [RemoveAnnotations](../../groupdocs.viewer.options/pdfoptimizationoptions/removeannotations) { get; set; } | Habilita la eliminación de anotaciones del archivo PDF de salida. |
| [RemoveFormFields](../../groupdocs.viewer.options/pdfoptimizationoptions/removeformfields) { get; set; } | Permite eliminar campos de formulario de un archivo PDF. |
| [RemoveUnusedObjects](../../groupdocs.viewer.options/pdfoptimizationoptions/removeunusedobjects) { get; set; } | Elimina objetos no utilizados (huérfanos) de un archivo PDF, que están presentes en el documento PDF pero no están referenciados en los diccionarios de recursos de ninguna página y, por lo tanto, no se usan en absoluto. Activar esta propiedad (`true`) reducirá el tamaño del documento PDF de salida. Por defecto está deshabilitada (`false`). |
| [RemoveUnusedStreams](../../groupdocs.viewer.options/pdfoptimizationoptions/removeunusedstreams) { get; set; } | Elimina flujos no utilizados (huérfanos) de un archivo PDF, que aún están referenciados en el diccionario de recursos de la página, pero en realidad nunca se utilizan en el contenido de la página. Por defecto está deshabilitado (`false`), habilitarlo (`true`) reducirá el tamaño del documento PDF de salida. |
| [ResizeImages](../../groupdocs.viewer.options/pdfoptimizationoptions/resizeimages) { get; set; } | Permite establecer la resolución máxima en el archivo PDF de salida. |
| [SubsetFonts](../../groupdocs.viewer.options/pdfoptimizationoptions/subsetfonts) { get; set; } | Crea subconjuntos de fuentes en el archivo PDF de salida. |

### Ver también

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
