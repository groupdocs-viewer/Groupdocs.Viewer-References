---
title: "release_page_stream-metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Frigör strömmen som skapats av IPageStreamFactory.createpagestream-metod."
type: docs
url: /sv/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream/
is_root: false
weight: 1030
---


## release_page_stream {#page_number-page_stream}

Frigör strömmen som skapats av metoden [`IPageStreamFactory.create_page_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/).

```python
def release_page_stream(self, page_number, page_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page_number | `int` | Sidans nummer. |
| page_stream | `io.RawIOBase` | Ström skapad av `IPageStreamFactory.create_page_stream`-metod. |

### Se även
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
