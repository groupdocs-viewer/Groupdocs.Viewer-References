---
title: "Clase LoadOptions"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Las opciones usadas para abrir un archivo."
type: docs
url: /es/python-net/groupdocs.viewer.options/loadoptions/
is_root: false
weight: 110
---


## LoadOptions class

Las opciones usadas para abrir un archivo.

El tipo LoadOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/) | Inicializa una instancia de la clase [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/). |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/#file_type) | Inicializa una nueva instancia de LoadOptions. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/) | La propiedad permite la detección de codificación para los archivos [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), y [`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/). |
| [encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/) | La codificación utilizada al abrir archivos basados en texto o mensajes de correo electrónico como [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), y [`FileType.msg`](/viewer/python-net/groupdocs.viewer/filetype/msg/). El valor predeterminado es `utf-8`. |
| [file_type](/viewer/python-net/groupdocs.viewer.options/loadoptions/file_type/) | El tipo del archivo a abrir. |
| [password](/viewer/python-net/groupdocs.viewer.options/loadoptions/password/) | La contraseña para abrir un archivo cifrado. |
| [resource_loading_timeout](/viewer/python-net/groupdocs.viewer.options/loadoptions/resource_loading_timeout/) | El tiempo de espera para cargar recursos externos. |
| [skip_external_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) | La propiedad deshabilita la carga de todos los recursos externos como imágenes, excepto los listados en [`LoadOptions.whitelisted_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/). |
| [try_repair](/viewer/python-net/groupdocs.viewer.options/loadoptions/try_repair/) | La propiedad permite que GroupDocs.Viewer intente reparar la corrupción estructural en documentos PDF. El valor predeterminado es False. |
| [whitelisted_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) | La lista de fragmentos de URL correspondientes a recursos externos que deben cargarse cuando [`LoadOptions.skip_external_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) está configurado en `True`. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, LoadOptions

load_options = LoadOptions()
load_options.password = "12345"

with Viewer("protected.docx", load_options) as viewer:
    viewer.view(HtmlViewOptions.for_embedded_resources("page_{0}.html"))
```

### Ver también
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
