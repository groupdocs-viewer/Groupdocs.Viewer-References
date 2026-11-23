---
title: "méthode release_page_stream"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Libère le flux créé par la méthode IPageStreamFactory.createpagestream."
type: docs
url: /fr/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream/
is_root: false
weight: 1030
---


## release_page_stream {#page_number-page_stream}

Libère le flux créé par la méthode [`IPageStreamFactory.create_page_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/).

```python
def release_page_stream(self, page_number, page_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| page_number | `int` | Le numéro d'une page. |
| page_stream | `io.RawIOBase` | Flux créé par la méthode `IPageStreamFactory.create_page_stream`. |

### Voir aussi
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
