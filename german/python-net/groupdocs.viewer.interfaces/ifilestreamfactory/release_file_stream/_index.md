---
title: "release_file_stream Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Gibt den von IFileStreamFactory.createfilestream Methode erstellten Stream frei."
type: docs
url: /de/python-net/groupdocs.viewer.interfaces/ifilestreamfactory/release_file_stream/
is_root: false
weight: 1020
---


## release_file_stream {#file_stream}

Gibt den durch die Methode [`IFileStreamFactory.create_file_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ifilestreamfactory/create_file_stream/) erstellten Stream frei.

```python
def release_file_stream(self, file_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_stream | `io.RawIOBase` | Stream, der von `IFileStreamFactory.create_file_stream` Methode erstellt wurde. |

**Returns:** None.

### Siehe auch
* class [`IFileStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ifilestreamfactory/)
