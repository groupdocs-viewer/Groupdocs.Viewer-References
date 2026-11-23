---
title: "método for_html_view"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de ViewInfoOptions para obtener información de vista al renderizar a HTML."
type: docs
url: /es/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/
is_root: false
weight: 1010
---


## for_html_view

Inicializa una instancia de ViewInfoOptions para obtener información de vista al renderizar a HTML.

```python
def for_html_view(cls):
    ...
```

**Returns:** ViewInfoOptions: A new ViewInfoOptions instance.

### Ejemplo

```python
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import ViewInfoOptions

    # Crea opciones de información de vista para formato HTML (una sola página)
    options = ViewInfoOptions.for_html_view(True)

    # Cargue un documento y recupere información de vista
    with Viewer("sample.xml") as viewer:
        info = viewer.get_view_info(options)
    ```

## for_html_view {#render_single_page}

Inicializa una instancia de ViewInfoOptions para obtener información de vista al renderizar a HTML.

```python
def for_html_view(cls, render_single_page):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| render_single_page | `bool` | Habilita la renderización de contenido HTML en una sola página. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Recuperar información de vista para HTML con una sola página
options = ViewInfoOptions.for_html_view(True)

with Viewer("sample.xml") as viewer:
    info = viewer.get_view_info(options)
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### Ver también
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
