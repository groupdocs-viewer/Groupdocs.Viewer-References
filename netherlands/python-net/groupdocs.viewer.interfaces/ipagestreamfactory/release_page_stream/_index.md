---
title: "release_page_stream-methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Geeft de stream vrij die is aangemaakt door de IPageStreamFactory.createpagestream-methode."
type: docs
url: /nl/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream/
is_root: false
weight: 1030
---


## release_page_stream {#page_number-page_stream}

Geeft de stream vrij die is aangemaakt door de methode [`IPageStreamFactory.create_page_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/) methode.

```python
def release_page_stream(self, page_number, page_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| page_number | `int` | Het paginanummer. |
| page_stream | `io.RawIOBase` | Stream aangemaakt door de `IPageStreamFactory.create_page_stream`-methode. |

### Zie ook
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
