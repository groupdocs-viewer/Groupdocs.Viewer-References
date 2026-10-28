---
title: "Clase Security"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Las opciones de seguridad del documento PDF."
type: docs
url: /es/python-net/groupdocs.viewer.options/security/
is_root: false
weight: 260
---


## Security class

Las opciones de seguridad del documento PDF.

Para obtener más detalles, consulte la documentación.

El tipo Security expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/security/__init__/) | Inicializa una instancia de la clase [`Security`](/viewer/python-net/groupdocs.viewer.options/security/). |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [document_open_password](/viewer/python-net/groupdocs.viewer.options/security/document_open_password/) | La contraseña requerida para abrir el documento PDF. |
| [permissions](/viewer/python-net/groupdocs.viewer.options/security/permissions/) | Los permisos del documento PDF, como imprimir, modificar y extraer datos. |
| [permissions_password](/viewer/python-net/groupdocs.viewer.options/security/permissions_password/) | La contraseña requerida para cambiar la configuración de permisos. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

with Viewer("sample.docx") as viewer:
    security = Security()
    security.document_open_password = "o123"
    security.permissions_password = "p123"
    security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

    pdf_options = PdfViewOptions("protected_document.pdf")
    pdf_options.security = security
    viewer.view(pdf_options)
```

### Guides
Guías de tareas que usan `Security`:

* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)

### Ver también
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
