---
title: "metodo create_resource_stream"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Crea il flusso utilizzato per scrivere i dati della risorsa HTML di output."
type: docs
url: /it/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/
is_root: false
weight: 1010
---


## create_resource_stream {#page_number-resource}

Crea il flusso utilizzato per scrivere i dati della risorsa HTML di output.

```python
def create_resource_stream(self, page_number, resource):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| page_number | `int` | Il numero di una pagina. |
| resource | `Resource` | La risorsa HTML come font, stile, immagine o grafica. |

**Returns:** io.RawIOBase: Stream used to write output resource data.

### Esempio

```python
from groupdocs.viewer import Viewer

viewer = Viewer()
factory = viewer.resource_stream_factory

# Crea un flusso per una risorsa CSS nella pagina 1
stream = factory.create_resource_stream(pageNumber=1, resource="style.css")
with stream:
    stream.write(b"body { font-family: Arial; }")
```

### Vedi anche
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
