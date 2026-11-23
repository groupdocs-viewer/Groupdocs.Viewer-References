---
title: "create_resource_stream methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Maakt de stream aan die wordt gebruikt om uitvoer‑HTML‑resource‑gegevens te schrijven."
type: docs
url: /nl/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/
is_root: false
weight: 1010
---


## create_resource_stream {#page_number-resource}

Maakt de stream aan die wordt gebruikt om uitvoer‑HTML‑resource‑gegevens te schrijven.

```python
def create_resource_stream(self, page_number, resource):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| page_number | `int` | Het paginanummer. |
| resource | `Resource` | De HTML-resource zoals lettertype, stijl, afbeelding of grafische elementen. |

**Returns:** io.RawIOBase: Stream used to write output resource data.

### Voorbeeld

```python
from groupdocs.viewer import Viewer

viewer = Viewer()
factory = viewer.resource_stream_factory

# Maak een stream voor een CSS‑resource op pagina 1
stream = factory.create_resource_stream(pageNumber=1, resource="style.css")
with stream:
    stream.write(b"body { font-family: Arial; }")
```

### Zie ook
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
