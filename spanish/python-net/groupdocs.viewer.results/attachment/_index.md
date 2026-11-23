---
title: "Clase Attachment"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa un archivo adjunto contenido por un mensaje de correo electrónico, archivo comprimido, documento PDF o archivo de datos de Outlook."
type: docs
url: /es/python-net/groupdocs.viewer.results/attachment/
is_root: false
weight: 20
---


## Attachment class

Representa un archivo adjunto contenido por un mensaje de correo electrónico, archivo comprimido, documento PDF o archivo de datos de Outlook.

El tipo Attachment expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/) | Inicializa una nueva instancia de [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#file_name-file_path) | Inicializa una nueva instancia de Attachment. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-size) | Inicializa una nueva instancia de la clase Attachment. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-file_type-size) | Inicializa una nueva instancia de la clase Attachment. |

### Métodos
| Método | Descripción |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/attachment/to_string/) | Devuelve una cadena que representa el objeto actual. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.results/attachment/file_name/) | El nombre del archivo adjunto. |
| [file_path](/viewer/python-net/groupdocs.viewer.results/attachment/file_path/) | La ruta relativa del adjunto, p. ej. `folder/file.docx`, o el nombre del archivo cuando el archivo está ubicado en la raíz de un archivo comprimido, en un mensaje de correo electrónico o en un archivo de datos. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/attachment/file_type/) | El tipo de archivo adjunto. |
| [id](/viewer/python-net/groupdocs.viewer.results/attachment/id/) | El identificador único del adjunto en el contexto de un solo archivo que contiene este adjunto. |
| [size](/viewer/python-net/groupdocs.viewer.results/attachment/size/) | El tamaño del archivo adjunto en bytes. |

### Ejemplo

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Acceder a las propiedades del adjunto, por ejemplo, nombre de archivo
        print(attachment.file_name)
        # Guardar el adjunto en una ruta de archivo
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Ver también
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
