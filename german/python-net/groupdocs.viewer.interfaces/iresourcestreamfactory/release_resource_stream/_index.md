---
title: "release_resource_stream Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Gibt den von IResourceStreamFactory.createresourcestream Methode erstellten Stream frei."
type: docs
url: /de/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/release_resource_stream/
is_root: false
weight: 1050
---


## release_resource_stream {#page_number-resource-resource_stream}

Gibt den durch die Methode [`IResourceStreamFactory.create_resource_stream`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/) erstellten Stream frei.

```python
def release_resource_stream(self, page_number, resource, resource_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_number | `int` | Die Nummer einer Seite. |
| resource | `Resource` | Die HTML-Ressource wie Schriftart, Stil, Bild oder Grafik. |
| resource_stream | `io.RawIOBase` | Stream, der von `IResourceStreamFactory.create_resource_stream` Methode erstellt wurde. |

**Returns:** None.

### Siehe auch
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
