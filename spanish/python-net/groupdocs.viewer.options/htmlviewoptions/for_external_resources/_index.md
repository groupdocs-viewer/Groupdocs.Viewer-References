---
title: "Método for_external_resources"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de la clase HtmlViewOptions para renderizar en HTML con recursos externos."
type: docs
url: /es/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/
is_root: false
weight: 1060
---


## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url}

Inicializa una instancia de la clase [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) para renderizar en HTML con recursos externos.

Para el ejemplo de código, consulte la documentación.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | El método que instancia el flujo usado para escribir los datos de la página de salida. |
| create_resource_stream | `CreateResourceStream` | El método que libera el flujo creado por el método `create_page_stream`. |
| create_resource_url | `CreateResourceUrl` | El método que crea la URL para el recurso HTML. |

**Returns:** New instance of the `HtmlViewOptions` class for rendering into HTML with external resources.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `create_resource_url` es None. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("sample.docx") as viewer:
    options = HtmlViewOptions.for_external_resources(
        "page_{0}.html",
        "page_{0}/resource_{0}_{1}",
        "page_{0}/resource_{0}_{1}"
    )
    viewer.view(options)
```

## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url-release_page_stream-release_resource_stream}

Inicializa una instancia de la clase HtmlViewOptions para renderizar en HTML con recursos externos.

Para ejemplos de uso adicionales, consulte la documentación de GroupDocs Viewer.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url, release_page_stream, release_resource_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | El método que instancia una secuencia utilizada para escribir los datos de la página de salida. |
| create_resource_stream | `CreateResourceStream` | El método que instancia un flujo usado para escribir los datos del recurso HTML de salida. |
| create_resource_url | `CreateResourceUrl` | El método que crea una URL para un recurso HTML. |
| release_page_stream | `ReleasePageStream` | El método que libera el flujo creado por el delegado pasado a `create_page_stream`. |
| release_resource_stream | `ReleaseResourceStream` | El método que libera el flujo creado por el delegado pasado a `create_resource_stream`. |

**Returns:** HtmlViewOptions: New instance of the HtmlViewOptions class for rendering into HTML with external resources.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `release_resource_stream` es None. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_excel_to_html_external():
    # Cargar hoja de cálculo de Excel
    with Viewer("invoice.xlsx") as viewer:
        # Convertir la hoja de cálculo a HTML con recursos externos.
        # {0} y {1} se reemplazan, respectivamente, con el número de página actual y el nombre del recurso.
        view_options = HtmlViewOptions.for_external_resources(
            "render_excel_to_html_external/pdf_page_{0}.html",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}"
        )
        viewer.view(view_options)

if __name__ == "__main__":
    render_excel_to_html_external()
```

## for_external_resources {#page_stream_factory-resource_stream_factory}

Inicializa una instancia de HtmlViewOptions para renderizar en HTML con recursos externos.

Para más detalles, consulte la documentación en línea.

```python
def for_external_resources(cls, page_stream_factory, resource_stream_factory):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | La fábrica que implementa métodos para crear y liberar el flujo de página de salida. |
| resource_stream_factory | `IResourceStreamFactory` | La fábrica que implementa los métodos necesarios para crear URLs de recursos, instanciar y liberar los flujos de recursos HTML de salida. |

**Returns:** HtmlViewOptions: A new HtmlViewOptions instance configured for external resources.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `resource_stream_factory` es None. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Cree un archivo HTML para cada página y almacene los recursos externos por separado.
    # {0} y {1} se reemplazan, respectivamente, con el número de página actual y el nombre del recurso.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

## for_external_resources

Inicializa una instancia de HtmlViewOptions configurada para generar archivos HTML con recursos externos.

La instancia usa las cadenas de formato proporcionadas:
- `html_file_path_format` – file path format for the output HTML files (e.g., `"page_{0}.html"`).
- `resources_path_format` – folder path format for external resource files (e.g., `"page_{0}/resource_{0}_{1}"`).
- `resources_url_format` – URL format for HTML resources (e.g., `"page_{0}/resource_{0}_{1}"`).

Los archivos de salida se colocan en el directorio de trabajo actual de la aplicación.

```python
def for_external_resources(cls):
    ...
```

**Returns:** HtmlViewOptions: Configured options for rendering HTML with external resources.

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html_external():
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html_external()
```

## for_external_resources {#file_path_format-resource_file_path_format-resource_url_format}

Inicializa una instancia de la clase [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/).

Para el ejemplo de código, consulte la documentación.

```python
def for_external_resources(cls, file_path_format, resource_file_path_format, resource_url_format):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path_format | `str` | El formato de ruta de archivo, p. ej. `'page_{0}.html'`. |
| resource_file_path_format | `str` | El formato de ruta de archivo de recurso, p. ej. `'page_{0}/resource_{1}'`. |
| resource_url_format | `str` | El formato de URL de recurso, p. ej. `'page_{0}/resource_{1}'`. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `resource_url_format` es None o está vacío. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Cargue un documento y renderice cada página a un archivo HTML con recursos externos.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

### Ver también
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
