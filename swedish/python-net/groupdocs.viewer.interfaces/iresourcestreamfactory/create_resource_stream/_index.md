---
title: "create_resource_stream metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Skapar strömmen som används för att skriva utdata för HTML-resursdata."
type: docs
url: /sv/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/
is_root: false
weight: 1010
---


## create_resource_stream {#page_number-resource}

Skapar strömmen som används för att skriva utdata för HTML-resursdata.

```python
def create_resource_stream(self, page_number, resource):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page_number | `int` | Sidans nummer. |
| resource | `Resource` | HTML-resursen såsom teckensnitt, stil, bild eller grafik. |

**Returns:** io.RawIOBase: Stream used to write output resource data.

### Exempel

```python
from groupdocs.viewer import Viewer

viewer = Viewer()
factory = viewer.resource_stream_factory

# Skapa en ström för en CSS-resurs på sida 1
stream = factory.create_resource_stream(pageNumber=1, resource="style.css")
with stream:
    stream.write(b"body { font-family: Arial; }")
```

### Se även
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
