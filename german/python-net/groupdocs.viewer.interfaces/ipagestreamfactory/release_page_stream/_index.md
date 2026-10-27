---
title: "release_page_stream Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Gibt den von IPageStreamFactory.createpagestream Methode erstellten Stream frei."
type: docs
url: /de/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream/
is_root: false
weight: 1030
---


## release_page_stream {#page_number-page_stream}

Gibt den durch die Methode [`IPageStreamFactory.create_page_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/) erstellten Stream frei.

```python
def release_page_stream(self, page_number, page_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_number | `int` | Die Nummer einer Seite. |
| page_stream | `io.RawIOBase` | Stream erstellt von `IPageStreamFactory.create_page_stream` Methode. |

### Siehe auch
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
