---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una nueva instancia de PngViewOptions."
type: docs
url: /es/python-net/groupdocs.viewer.options/pngviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Inicializa una nueva instancia de [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Para el ejemplo de código, consulte la documentación.

```python
def __init__(self, create_page_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | El método que instancia una secuencia utilizada para escribir los datos de la página de salida. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `create_page_stream` es None. |

## __init__ {#create_page_stream-release_page_stream}

Inicializa una instancia de la clase [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Para el ejemplo de código, consulte la documentación.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | El método que instancia una secuencia utilizada para escribir los datos de la página de salida. |
| release_page_stream | `ReleasePageStream` | El método que libera un flujo creado por el método asignado al delegado pasado al parámetro `create_page_stream`. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `release_page_stream` es None. |

## __init__ {#page_stream_factory}

Inicializa una nueva instancia de [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Para obtener más información, consulte la documentación.

```python
def __init__(self, page_stream_factory):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | La fábrica que implementa métodos para crear y liberar la secuencia de página de salida. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `page_stream_factory` es `None`. |

## __init__

Inicializa una instancia de PngViewOptions.

Este constructor crea un [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) con ``\"p_{0}.png\"`` como el formato de ruta de archivo predeterminado para los archivos de salida. Los archivos PNG generados se guardan en el directorio de trabajo actual de la aplicación.

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

## __init__ {#file_path_format}

Inicializa una nueva instancia de [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Para el ejemplo de código, consulte la documentación.

```python
def __init__(self, file_path_format):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path_format | `str` | El formato de ruta de archivo, p. ej. `'page_{0}.png'`. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `file_path_format` es None o está vacío. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

### Ver también
* class [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
