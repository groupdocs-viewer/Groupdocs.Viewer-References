---
title: "método for_png_view"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de la clase ViewInfoOptions para obtener información de vista al renderizar en PNG."
type: docs
url: /es/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/
is_root: false
weight: 1060
---


## for_png_view

Inicializa una instancia de la clase [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) para obtener información de vista al renderizar en PNG.

```python
def for_png_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the `ViewInfoOptions` class.

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Crear opciones de información de vista para el formato PNG
view_info_options_png = ViewInfoOptions.for_png_view()

# Cargar un documento y obtener información de vista para PNG
with Viewer("sample.xml") as viewer:
    result_png = viewer.get_view_info(view_info_options_png)
```

## for_png_view {#extract_text}

Inicializa una instancia de la clase ViewInfoOptions para obtener información de vista al renderizar en PNG.

```python
def for_png_view(cls, extract_text):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| extract_text | `bool` | Habilita la extracción de texto. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Ejemplo

```python
from groupdocs.viewer.options import ViewInfoOptions

# Crear opciones de información de vista para el formato PNG con extracción de texto habilitada
options = ViewInfoOptions.for_png_view(extractText=True)
```

### Ver también
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
