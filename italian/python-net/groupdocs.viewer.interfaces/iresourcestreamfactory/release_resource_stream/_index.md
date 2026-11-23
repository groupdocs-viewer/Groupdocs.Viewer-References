---
title: "metodo release_resource_stream"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rilascia lo stream creato dal metodo IResourceStreamFactory.createresourcestream."
type: docs
url: /it/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/release_resource_stream/
is_root: false
weight: 1050
---


## release_resource_stream {#page_number-resource-resource_stream}

Rilascia il flusso creato dal metodo [`IResourceStreamFactory.create_resource_stream`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/).

```python
def release_resource_stream(self, page_number, resource, resource_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| page_number | `int` | Il numero di una pagina. |
| resource | `Resource` | La risorsa HTML come font, stile, immagine o grafica. |
| resource_stream | `io.RawIOBase` | Stream creato dal metodo `IResourceStreamFactory.create_resource_stream`. |

**Returns:** None.

### Vedi anche
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
