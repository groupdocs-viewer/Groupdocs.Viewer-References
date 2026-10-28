---
title: "método view"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Crea una vista de todas las páginas del documento."
type: docs
url: /es/python-net/groupdocs.viewer/viewer/view/
is_root: false
weight: 1130
---


## view {#options}

Crea una vista de todas las páginas del documento.

Más información

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | `ViewOptions` | Las opciones de vista. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `options` es None. |
| `PasswordRequiredException` | Cuando se requiere una contraseña para abrir el documento. |
| `IncorrectPasswordException` | Cuando la contraseña especificada es incorrecta. |
| `GroupDocsViewerException` | Cuando no se pudo encontrar un adjunto. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-page_numbers}

Crea una vista de páginas específicas del documento.

Más información

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, page_numbers):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | `ViewOptions` | Las opciones de vista. |
| page_numbers | `list[int]` | Los números de página a visualizar. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | cuando `page_numbers` está vacío. |
| `PasswordRequiredException` | cuando se requiere una contraseña para abrir el documento. |
| `IncorrectPasswordException` | cuando la contraseña especificada es incorrecta. |
| `GroupDocsViewerException` | cuando no se pudo encontrar el adjunto. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-cancellation_token-page_numbers}

Crea una vista de páginas específicas del documento.

Más información:

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, cancellation_token, page_numbers):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | `ViewOptions` | Las opciones de vista. |
| cancellation_token | `CancellationToken` | Token de cancelación para abortar el procesamiento. |
| page_numbers | `list[int]` | Los números de página a visualizar. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `page_numbers` está vacío. |
| `PasswordRequiredException` | Cuando se requiere una contraseña para abrir el documento. |
| `IncorrectPasswordException` | Cuando la contraseña especificada es incorrecta. |
| `GroupDocsViewerException` | Cuando no se pudo encontrar el adjunto. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Ver también
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
