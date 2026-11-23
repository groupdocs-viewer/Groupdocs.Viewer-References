---
title: "release_file_stream methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Geeft de stream vrij die is aangemaakt door IFileStreamFactory.createfilestream methode."
type: docs
url: /nl/python-net/groupdocs.viewer.interfaces/ifilestreamfactory/release_file_stream/
is_root: false
weight: 1020
---


## release_file_stream {#file_stream}

Geeft de stream vrij die is aangemaakt door de methode [`IFileStreamFactory.create_file_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ifilestreamfactory/create_file_stream/) methode.

```python
def release_file_stream(self, file_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_stream | `io.RawIOBase` | Stream aangemaakt door `IFileStreamFactory.create_file_stream` methode. |

**Returns:** None.

### Zie ook
* class [`IFileStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ifilestreamfactory/)
