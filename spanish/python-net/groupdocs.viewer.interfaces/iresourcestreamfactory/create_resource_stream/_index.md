---
title: "método create_resource_stream"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Crea el flujo utilizado para escribir los datos de recursos HTML de salida."
type: docs
url: /es/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/
is_root: false
weight: 1010
---


## create_resource_stream {#page_number-resource}

Crea el flujo utilizado para escribir los datos de recursos HTML de salida.

```python
def create_resource_stream(self, page_number, resource):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| page_number | `int` | El número de una página. |
| resource | `Resource` | El recurso HTML como fuente, estilo, imagen o gráficos. |

**Returns:** io.RawIOBase: Stream used to write output resource data.

### Ejemplo

```python
from groupdocs.viewer import Viewer

viewer = Viewer()
factory = viewer.resource_stream_factory

# Crear un flujo para un recurso CSS en la página 1
stream = factory.create_resource_stream(pageNumber=1, resource="style.css")
with stream:
    stream.write(b"body { font-family: Arial; }")
```

### Ver también
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
