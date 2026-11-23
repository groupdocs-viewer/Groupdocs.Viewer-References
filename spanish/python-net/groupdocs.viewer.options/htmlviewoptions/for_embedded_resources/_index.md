---
title: "método for_embedded_resources"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de HtmlViewOptions para renderizar HTML con recursos incrustados."
type: docs
url: /es/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/
is_root: false
weight: 1010
---


## for_embedded_resources {#create_page_stream}

Inicializa una instancia de HtmlViewOptions para renderizar HTML con recursos incrustados.

Para obtener más detalles, consulte la documentación.

```python
def for_embedded_resources(cls, create_page_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | El método que instancia una secuencia utilizada para escribir los datos de la página de salida. |

**Returns:** HtmlViewOptions: New instance configured for rendering HTML with embedded resources.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `create_page_stream` es None. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#create_page_stream-release_page_stream}

Inicializa una instancia de la clase [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) para renderizar en HTML con recursos incrustados.

```python
def for_embedded_resources(cls, create_page_stream, release_page_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | El método que instancia la secuencia utilizada para escribir los datos de la página de salida. |
| release_page_stream | `ReleasePageStream` | El método que libera la secuencia creada por el método asignado al parámetro `create_page_stream`. |

**Returns:** HtmlViewOptions: New instance of the `HtmlViewOptions` class for rendering into HTML with embedded resources.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `release_page_stream` es `None`. Para el ejemplo de código, consulte la documentación. |

## for_embedded_resources {#page_stream_factory}

Inicializa una instancia de HtmlViewOptions para renderizar en HTML con recursos incrustados.

Para el ejemplo de código, consulte la documentación en https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources.

```python
def for_embedded_resources(cls, page_stream_factory):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | La fábrica que implementa métodos para crear y liberar la secuencia de página de salida. |

**Returns:** HtmlViewOptions: New instance of HtmlViewOptions for rendering into HTML with embedded resources.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando page_stream_factory es None. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources

Inicializa una instancia de la clase [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) con recursos incrustados.

Para el ejemplo de código, consulte la documentación.

```python
def for_embedded_resources(cls):
    ...
```

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#file_path_format}

Inicializa una instancia de HtmlViewOptions para recursos incrustados.

Para el ejemplo de código, consulte la documentación.

```python
def for_embedded_resources(cls, file_path_format):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path_format | `str` | El formato de ruta de archivo, p. ej., 'page_{0}.html'. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `file_path_format` es None o está vacío. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Ver también
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
