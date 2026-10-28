---
title: "Clase PdfOptimizationOptions"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa las opciones de optimización PDF para aplicar al archivo PDF de salida."
type: docs
url: /es/python-net/groupdocs.viewer.options/pdfoptimizationoptions/
is_root: false
weight: 150
---


## PdfOptimizationOptions class

Representa las opciones de optimización PDF para aplicar al archivo PDF de salida.

Para obtener detalles y ejemplos de código, consulte la página de documentación.

El tipo PdfOptimizationOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/) | Inicializa los valores predeterminados de la opción MaxResolution a 300 y de la opción ImageQuality a 100. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [compress_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images/) | La propiedad permite comprimir imágenes en el archivo PDF de salida. |
| [convert_to_gray_scale](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/convert_to_gray_scale/) | La propiedad permite la conversión del archivo PDF de salida a escala de grises. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/image_quality/) | La calidad de imagen en el archivo PDF de salida, expresada como un porcentaje. |
| [lineriaze](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/lineriaze/) | La propiedad permite la optimización del archivo PDF de salida para su visualización en línea con un navegador web. |
| [max_resolution](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/) | La resolución máxima en el archivo PDF de salida. |
| [optimize_spreadsheets](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/optimize_spreadsheets/) | La propiedad que permite la optimización de hojas de cálculo en archivos PDF. |
| [remove_annotations](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_annotations/) | La propiedad permite eliminar anotaciones del archivo PDF de salida. |
| [remove_form_fields](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_form_fields/) | La propiedad permite eliminar campos de formulario de un archivo PDF. |
| [remove_unused_objects](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/) | La propiedad elimina objetos no utilizados (huérfanos) de un archivo PDF. |
| [remove_unused_streams](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/) | La propiedad elimina flujos no utilizados (huérfanos) de un archivo PDF que están referenciados en el diccionario de recursos de la página pero nunca se usan en el contenido de la página. Deshabilitado por defecto (`False`); establecerlo en `True` reduce el tamaño del PDF de salida. |
| [resize_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/) | La propiedad permite establecer la resolución máxima en el archivo PDF de salida. |
| [subset_fonts](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/subset_fonts/) | La propiedad crea subconjuntos de fuentes en el archivo PDF de salida. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

def optimize_pdf():
    with Viewer("sample.docx") as viewer:
        view_options = PdfViewOptions("output/optimized.pdf")
        view_options.pdf_optimization_options = PdfOptimizationOptions()
        # Habilitar la linealización para una vista previa web más rápida
        view_options.pdf_optimization_options.lineriaze = True
        # Eliminar anotaciones y campos de formulario para reducir el tamaño.
        view_options.pdf_optimization_options.remove_annotations = True
        view_options.pdf_optimization_options.remove_form_fields = True

        viewer.view(view_options)
```

### Ver también
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
