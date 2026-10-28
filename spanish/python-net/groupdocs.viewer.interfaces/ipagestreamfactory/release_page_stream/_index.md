---
title: "método release_page_stream"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Libera el flujo creado por el método IPageStreamFactory.createpagestream."
type: docs
url: /es/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream/
is_root: false
weight: 1030
---


## release_page_stream {#page_number-page_stream}

Libera el flujo creado por el método [`IPageStreamFactory.create_page_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/).

```python
def release_page_stream(self, page_number, page_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| page_number | `int` | El número de una página. |
| page_stream | `io.RawIOBase` | Flujo creado por el método `IPageStreamFactory.create_page_stream`. |

### Ver también
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
