---
title: "método release_resource_stream"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Libera el flujo creado por el método IResourceStreamFactory.createresourcestream."
type: docs
url: /es/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/release_resource_stream/
is_root: false
weight: 1050
---


## release_resource_stream {#page_number-resource-resource_stream}

Libera el flujo creado por el método [`IResourceStreamFactory.create_resource_stream`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/).

```python
def release_resource_stream(self, page_number, resource, resource_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| page_number | `int` | El número de una página. |
| resource | `Resource` | El recurso HTML como fuente, estilo, imagen o gráficos. |
| resource_stream | `io.RawIOBase` | Flujo creado por el método `IResourceStreamFactory.create_resource_stream`. |

**Returns:** None.

### Ver también
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
