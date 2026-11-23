---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de PdfViewOptions."
type: docs
url: /es/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_file_stream}

Inicializa una instancia de [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/).

Para el ejemplo de código, consulte la documentación en https://docs.groupdocs.com/viewer/net/rendering-to-pdf/.

```python
def __init__(self, create_file_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | El método que instancia el flujo utilizado para escribir los datos del archivo de salida. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `create_file_stream` es `None`. |

## __init__ {#create_file_stream-release_file_stream}

Inicializa una nueva instancia de PdfViewOptions.

Para el ejemplo de código, consulte la documentación.

```python
def __init__(self, create_file_stream, release_file_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | Callable que devuelve un flujo `io.RawIOBase` utilizado para escribir los datos del archivo de salida. |
| release_file_stream | `ReleaseFileStream` | Callable que libera el flujo creado por el método asignado a `create_file_stream`. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `release_file_stream` es None. |

## __init__ {#file_stream_factory}

Inicializa una instancia de PdfViewOptions.

Para el ejemplo de código, consulte la documentación: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

```python
def __init__(self, file_stream_factory):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_stream_factory | `IFileStreamFactory` | La fábrica que implementa métodos para crear y liberar el flujo del archivo de salida. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Se lanza cuando `file_stream_factory` es None. |

## __init__

Inicializa una instancia de PdfViewOptions.

Este constructor inicializa un PdfViewOptions con `"output.pdf"` como el formato de ruta de archivo para el archivo de salida. El archivo de salida se colocará en el directorio de trabajo actual de la aplicación.

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

## __init__ {#output_file_path}

Inicializa una instancia de [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) clase.

Para el ejemplo de código, consulte la documentación.

```python
def __init__(self, output_file_path):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| output_file_path | `str` | La ruta del archivo PDF de salida. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `output_file_path` es None o está vacío. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### Ver también
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
