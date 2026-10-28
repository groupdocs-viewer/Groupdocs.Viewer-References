---
title: "Clase Viewer"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa la clase principal que controla el proceso de renderizado del documento."
type: docs
url: /es/python-net/groupdocs.viewer/viewer/
is_root: false
weight: 100
---


## Viewer class

Representa la clase principal que controla el proceso de renderizado del documento.

El tipo Viewer expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream) | Inicializa una nueva instancia de la clase [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options) | Inicializa una nueva instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-settings) | Inicializa una nueva instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options-settings) | Inicializa una nueva instancia de Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream) | Inicializa una nueva instancia de la clase [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-leave_open) | Inicializa una nueva instancia de Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options) | Inicializa una nueva instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-leave_open) | Inicializa una nueva instancia de Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings) | Inicializa una nueva instancia de Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings-leave_open) | Inicializa una nueva instancia de Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings) | Inicializa una nueva instancia de Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings-leave_open) | Inicializa una nueva instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path) | Inicializa una nueva instancia de la clase [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-settings) | Inicializa una nueva instancia de la clase [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options) | Inicializa una nueva instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options-settings) | Inicializa una nueva instancia de Viewer. |

### Métodos
| Método | Descripción |
| :- | :- |
| [dispose](/viewer/python-net/groupdocs.viewer/viewer/dispose/) | Libera el flujo de archivo y los recursos internos gestionados. |
| [get_all_fonts](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) | Devuelve todas las fuentes utilizadas en el documento cargado, incluidas las fuentes incrustadas y las fuentes del sistema instaladas en el SO. |
| [get_attachments](/viewer/python-net/groupdocs.viewer/viewer/get_attachments/) | Devuelve los archivos adjuntos contenidos en el documento. |
| [get_file_info](/viewer/python-net/groupdocs.viewer/viewer/get_file_info/) | Devuelve información sobre el archivo, como el tipo de archivo y una señal que indica si el archivo está cifrado. |
| [get_view_info](/viewer/python-net/groupdocs.viewer/viewer/get_view_info/#options) | Devuelve información específica de la vista y del documento. |
| [get_view_info_view_info_options](/viewer/python-net/groupdocs.viewer/viewer/get_view_info_view_info_options/) |  |
| [save_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment/#attachment-destination) | Guarda el archivo adjunto en el flujo `destination`. |
| [save_attachment_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_attachment/) |  |
| [save_attachment_stream](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_stream/) |  |
| [save_attachment_streams](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_streams/) |  |
| [search](/viewer/python-net/groupdocs.viewer/viewer/search/#options) | Realiza una búsqueda de texto y resalta el texto encontrado en el documento cargado según las opciones proporcionadas. |
| [search_search_highlight_options](/viewer/python-net/groupdocs.viewer/viewer/search_search_highlight_options/) |  |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options) | Crea una vista de todas las páginas del documento. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-page_numbers) | Crea una vista de páginas específicas del documento. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-cancellation_token-page_numbers) | Crea una vista de páginas específicas del documento. |
| [view_view_options](/viewer/python-net/groupdocs.viewer/viewer/view_view_options/) |  |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, PngViewOptions

# Renderiza DOCX a HTML
with Viewer("./sample.docx") as viewer:
    html_opts = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(html_opts)

# Renderiza PDF a PNG
with Viewer("document.pdf") as viewer:
    png_opts = PngViewOptions("page_{0}.png")
    viewer.view(png_opts)
```

### Guides
Guías de tareas que usan `Viewer`:

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Get Document Information](/viewer/python-net/guides/get-document-info/)
* [Load document from local disk](/viewer/python-net/guides/load-document-from-local-disk/)
* [Load document from stream](/viewer/python-net/guides/load-document-from-stream/)
* [Load document from URL](/viewer/python-net/guides/load-document-from-url/)
* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)
* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)
* [Reorder pages](/viewer/python-net/guides/reorder-pages/)
* [Save attachments](/viewer/python-net/guides/how-to-extract-and-save-attachments/)

### Ver también
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
