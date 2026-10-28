---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una nueva instancia de la clase Viewer."
type: docs
url: /es/python-net/groupdocs.viewer/viewer/__init__/
is_root: false
weight: 10
---


## __init__ {#get_file_stream}

Inicializa una nueva instancia de la clase [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Más información

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | El método que devuelve un flujo legible. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Se lanza cuando `get_file_stream` es None. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options}

Inicializa una nueva instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

```python
def __init__(self, get_file_stream, get_load_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | El método que devuelve un flujo legible. |
| get_load_options | `Func[LoadOptions]` | El método que devuelve opciones de carga del documento. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Se lanza cuando `get_load_options` es None. |
| `Remarks` | - Más información sobre los tipos de archivo compatibles con GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats - Más información sobre las características de GroupDocs.Viewer para .NET: https://docs.groupdocs.com/display/viewernet/Developer+Guide - Más información sobre la carga de documentos cifrados y la visualización de archivos desde almacenes de terceros con GroupDocs.Viewer para .NET: https://docs.groupdocs.com/display/viewernet/Loading |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#get_file_stream-settings}

Inicializa una nueva instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream, settings):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | El método que devuelve un flujo legible. |
| settings | `ViewerSettings` | La configuración del Viewer. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `settings` es None. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options-settings}

Inicializa una nueva instancia de Viewer.

Más información:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, get_file_stream, get_load_options, settings):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Callable que devuelve un flujo legible. |
| get_load_options | `Func[LoadOptions]` | Callable que devuelve opciones de carga del documento. |
| settings | `ViewerSettings` | Configuración del Viewer. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `settings` es None. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#stream}

Inicializa una nueva instancia de la clase [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | `io.RawIOBase` | El flujo del archivo. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Se lanza cuando `stream` es None. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-leave_open}

Inicializa una nueva instancia de Viewer.

Más información:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, leave_open):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | `io.RawIOBase` | El flujo del archivo. |
| leave_open | `bool` | True para dejar el flujo abierto después de que el objeto Viewer sea eliminado; de lo contrario, False. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `stream` es None. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML — the hello‑world example."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#stream-load_options}

Inicializa una nueva instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Más información:

- More about file types supported by GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats>
- More about GroupDocs.Viewer for .NET features: <https://docs.groupdocs.com/display/viewernet/Developer+Guide>
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: <https://docs.groupdocs.com/display/viewernet/Loading>

```python
def __init__(self, stream, load_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | `io.RawIOBase` | El flujo del archivo. |
| load_options | `LoadOptions` | Las opciones de carga del documento. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `load_options` es None. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-leave_open}

Inicializa una nueva instancia de Viewer.

```python
def __init__(self, stream, load_options, leave_open):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | `io.RawIOBase` | El flujo del archivo. |
| load_options | `LoadOptions` | Las opciones de carga del documento. |
| leave_open | `bool` | True para dejar el flujo abierto después de que el objeto Viewer sea eliminado; de lo contrario, False. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `load_options` es None. |
| `Remarks` | - Más información sobre los tipos de archivo compatibles con GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats> - Más información sobre las características de GroupDocs.Viewer para .NET: <https://docs.groupdocs.com/display/viewernet/Developer+Guide> - Más información sobre la carga de documentos cifrados y la visualización de archivos desde almacenes de terceros con GroupDocs.Viewer para .NET: <https://docs.groupdocs.com/display/viewernet/Loading> |

### Ejemplo

```python
import io
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream, loadOptions=None, leaveOpen=False)
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings}

Inicializa una nueva instancia de Viewer.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, settings):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | `io.RawIOBase` | El flujo del archivo. |
| settings | `ViewerSettings` | La configuración del Viewer. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `settings` es None. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings-leave_open}

Inicializa una nueva instancia de Viewer.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

```python
def __init__(self, stream, settings, leave_open):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | `io.RawIOBase` | El flujo del archivo. |
| settings | `ViewerSettings` | La configuración del Viewer. |
| leave_open | `bool` | True para dejar el flujo abierto después de que el objeto Viewer sea eliminado; de lo contrario, False. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `settings` es None. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-settings}

Inicializa una nueva instancia de Viewer.

El constructor requiere un flujo de archivo (`io.RawIOBase`) y opcionalmente acepta opciones de carga de documento y configuraciones del Viewer.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | `io.RawIOBase` | El flujo del archivo. |
| load_options | `LoadOptions` | Las opciones de carga del documento. |
| settings | `ViewerSettings` | La configuración del Viewer. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `stream`, `load_options` o `settings` es None. |

### Ejemplo

```python
from groupdocs.viewer import Viewer

# Abra un archivo como flujo binario y cree un Viewer
with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream)
    # Utilice el viewer, p.ej., renderice a HTML
    # ...
```

## __init__ {#stream-load_options-settings-leave_open}

Inicializa una nueva instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Más información:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings, leave_open):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | `io.RawIOBase` | El flujo del archivo. |
| load_options | `LoadOptions` | Las opciones de carga del documento. |
| settings | `ViewerSettings` | La configuración del Viewer. |
| leave_open | `bool` | True para dejar el flujo abierto después de que el objeto Viewer sea eliminado; de lo contrario, False. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `settings` es None. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path}

Inicializa una nueva instancia de la clase [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta al archivo a renderizar. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `file_path` es `None` o está vacío. |

### Ejemplo

```python
from groupdocs.viewer import Viewer

# Inicialice el viewer con una ruta de documento
with Viewer("./sample.docx") as viewer:
    # El viewer está listo para renderizar el documento
    pass
```

## __init__ {#file_path-settings}

Inicializa una nueva instancia de la clase [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Más información:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta al archivo a renderizar. |
| settings | `ViewerSettings` | La configuración del Viewer. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `settings` es null. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options}

Inicializa una nueva instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: Document formats supported by GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: Developer Guide (https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: How to load and view document with GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta al archivo a renderizar. |
| load_options | `LoadOptions` | Las opciones que se utilizan para abrir el archivo. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `load_options` es None. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options-settings}

Inicializa una nueva instancia de Viewer.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta al archivo a renderizar. |
| load_options | `LoadOptions` | Las opciones que se utilizan para abrir el archivo. |
| settings | `ViewerSettings` | La configuración del Viewer. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `settings` es None. |

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
