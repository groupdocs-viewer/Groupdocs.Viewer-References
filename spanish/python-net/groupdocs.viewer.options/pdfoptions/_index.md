---
title: "Clase PdfOptions"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa opciones para renderizar documentos PDF."
type: docs
url: /es/python-net/groupdocs.viewer.options/pdfoptions/
is_root: false
weight: 160
---


## PdfOptions class

Representa opciones para renderizar documentos PDF.

Para obtener más detalles, consulte la documentación.

El tipo PdfOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptions/__init__/) | Inicializa una nueva instancia de la clase PdfOptions. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [disable_chars_grouping](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/) | La propiedad desactiva la agrupación de símbolos para un posicionamiento preciso de los símbolos durante el renderizado de la página. |
| [disable_copy_protection](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/) | La propiedad desactiva la protección contra copia de contenido al renderizar a HTML. |
| [disable_font_license_verifications](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/) | La propiedad desactiva cualquier restricción de licencia para todas las fuentes en el documento XPS/OXPS actual. |
| [enable_font_hinting](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_font_hinting/) | La propiedad habilita el font hinting. |
| [enable_layered_rendering](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/) | La propiedad habilita el renderizado de texto y gráficos en el orden Z del documento PDF original al renderizar a HTML. |
| [fixed_layout](/viewer/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/) | La opción de diseño fijo habilita el renderizado de documentos PDF y EPUB a HTML con un diseño fijo. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptions/image_quality/) | La calidad de imagen de salida para los recursos de imagen al renderizar a HTML. La calidad predeterminada es `ImageQuality.LOW`. |
| [render_original_page_size](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/) | El tamaño de página de salida se establece para coincidir con el tamaño de página del documento PDF fuente. |
| [render_text_as_image](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/) | La opción habilita el renderizado de textos en archivos PDF como una imagen en la salida HTML. |
| [wrap_images_in_svg](/viewer/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/) | La propiedad que habilita envolver cada imagen en el documento HTML de salida en una etiqueta SVG para mejorar la calidad de salida. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("sample.pdf") as viewer:
    view_options = PngViewOptions("output_{0}.png")
    # Habilitar el font hinting al renderizar páginas PDF a imágenes.
    view_options.pdf_options.enable_font_hinting = True
    viewer.view(view_options)
```

### Ver también
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
