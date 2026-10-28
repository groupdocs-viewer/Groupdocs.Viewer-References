---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de la clase JpgViewOptions."
type: docs
url: /es/python-net/groupdocs.viewer.options/jpgviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Inicializa una instancia de la clase JpgViewOptions.

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

Inicializa una instancia de la clase JpgViewOptions.

Para el ejemplo de código, consulte la documentación.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable que instancia un flujo utilizado para escribir los datos de la página de salida. |
| release_page_stream | `ReleasePageStream` | Callable que libera un flujo creado por el método asignado al delegado pasado a `create_page_stream`. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `release_page_stream` es None. |

## __init__ {#page_stream_factory}

Inicializa una instancia de la clase [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/).

Para el ejemplo de código, consulta la documentación en https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg.

```python
def __init__(self, page_stream_factory):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | La fábrica que implementa métodos para crear y liberar la secuencia de página de salida. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `page_stream_factory` es None. |

## __init__

Inicializa una instancia de JpgViewOptions.

Este constructor inicializa una instancia de [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) con `"p_{0}.jpg"` como formato de ruta de archivo para los archivos de salida. Los archivos de salida se colocan en el directorio de trabajo actual de la aplicación.

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = JpgViewOptions("render_excel_to_jpg/excel_to_jpg_{0}.jpg")
    view_options.width = 800
    view_options.height = 900
    viewer.view(view_options)
```

## __init__ {#file_path_format}

Inicializa una nueva instancia de [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/).

Para el ejemplo de código, consulte la documentación.

```python
def __init__(self, file_path_format):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path_format | `str` | El formato de ruta de archivo, p. ej. `'page_{0}.jpg'`. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `file_path_format` es None o está vacío. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

def render_to_jpg():
    # Cargar un documento (p. ej., un archivo Excel)
    with Viewer("invoice.xlsx") as viewer:
        # Crear opciones de vista JPEG con un patrón de nombre de archivo.
        view_options = JpgViewOptions("output/excel_page_{0}.jpg")
        view_options.width = 800
        view_options.height = 900
        viewer.view(view_options)

if __name__ == "__main__":
    render_to_jpg()
```

### Ver también
* class [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)
