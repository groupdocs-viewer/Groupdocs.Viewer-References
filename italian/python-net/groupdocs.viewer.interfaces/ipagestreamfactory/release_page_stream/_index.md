---
title: "metodo release_page_stream"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rilascia lo stream creato dal metodo IPageStreamFactory.createpagestream."
type: docs
url: /it/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream/
is_root: false
weight: 1030
---


## release_page_stream {#page_number-page_stream}

Rilascia il flusso creato dal metodo [`IPageStreamFactory.create_page_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/).

```python
def release_page_stream(self, page_number, page_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| page_number | `int` | Il numero di una pagina. |
| page_stream | `io.RawIOBase` | Stream creato dal metodo `IPageStreamFactory.create_page_stream`. |

### Vedi anche
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
