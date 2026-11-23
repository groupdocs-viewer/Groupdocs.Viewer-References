---
title: "release_resource_stream metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Släpper strömmen som skapats av IResourceStreamFactory.createresourcestream metod."
type: docs
url: /sv/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/release_resource_stream/
is_root: false
weight: 1050
---


## release_resource_stream {#page_number-resource-resource_stream}

Frigör strömmen som skapats av metoden [`IResourceStreamFactory.create_resource_stream`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/).

```python
def release_resource_stream(self, page_number, resource, resource_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page_number | `int` | Sidans nummer. |
| resource | `Resource` | HTML-resursen såsom teckensnitt, stil, bild eller grafik. |
| resource_stream | `io.RawIOBase` | Ström skapad av `IResourceStreamFactory.create_resource_stream` metod. |

**Returns:** None.

### Se även
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
