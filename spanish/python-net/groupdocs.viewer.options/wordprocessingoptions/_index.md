---
title: "Clase WordProcessingOptions"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Contiene opciones para renderizar documentos Word."
type: docs
url: /es/python-net/groupdocs.viewer.options/wordprocessingoptions/
is_root: false
weight: 380
---


## WordProcessingOptions class

Contiene opciones para renderizar documentos Word.

Para más detalles, consulte la documentación en https://docs.groupdocs.com/viewer/net/render-word-documents/.

El tipo WordProcessingOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/) | Inicializa opciones para renderizar documentos de procesamiento de texto. |

### Métodos
| Método | Descripción |
| :- | :- |
| [clone](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/clone/) | Crea y devuelve una copia profunda completa de estas opciones. |
| [equals](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals/#options) | Determina si la instancia especificada [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/) es igual a esta instancia. |
| [equals_word_processing_options](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals_word_processing_options/) |  |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/bottom_margin/) | El margen inferior de una página. |
| [enable_open_type_features](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/enable_open_type_features/) | La opción habilita el kerning y otras características OpenType al renderizar scripts en árabe, hebreo, indio basados en latín o basados en cirílico. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/) | La resolución horizontal para imágenes generadas en puntos por pulgada. Esta opción se usa solo al renderizar documentos WordProcessing a formatos PNG o JPEG. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/left_margin/) | El margen izquierdo de una página. |
| [page_number_location](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_number_location/) | La ubicación de numeración de páginas para el documento WordProcessing cargado, que puede aplicar la numeración de páginas de forma forzada; por defecto es `WordsPageNumberLocation.not_apply`, dejando el documento intacto. |
| [page_size](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/) | El tamaño de la página de salida. |
| [render_tracked_changes](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/render_tracked_changes/) | La propiedad habilita la renderización de cambios rastreados (revisiones). |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/right_margin/) | El margen derecho de una página. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/top_margin/) | El margen superior de una página en puntos. |
| [unlink_table_of_contents](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/unlink_table_of_contents/) | La opción deshabilita la navegación desde la tabla de contenidos cuando se establece en True para la renderización HTML o PDF. |
| [update_fields](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/update_fields/) | La propiedad determina si los campos de ciertos tipos se actualizan antes de guardar el documento WordProcessing en formatos HTML, PDF, PNG o JPEG. El valor predeterminado es True, lo que significa que los campos se actualizan. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/) | La resolución vertical para imágenes generadas en puntos por pulgada, usada solo al renderizar documentos WordProcessing a formatos PNG o JPEG. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("with_tracked_changes.docx") as viewer:
    view_options = PdfViewOptions("output/word_with_tracked_changes.pdf")
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### Ver también
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
