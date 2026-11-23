---
title: "release_resource_stream-methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Geeft de stream vrij die is aangemaakt door de IResourceStreamFactory.createresourcestream-methode."
type: docs
url: /nl/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/release_resource_stream/
is_root: false
weight: 1050
---


## release_resource_stream {#page_number-resource-resource_stream}

Geeft de stream vrij die is aangemaakt door de methode [`IResourceStreamFactory.create_resource_stream`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/) methode.

```python
def release_resource_stream(self, page_number, resource, resource_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| page_number | `int` | Het paginanummer. |
| resource | `Resource` | De HTML-resource zoals lettertype, stijl, afbeelding of grafische elementen. |
| resource_stream | `io.RawIOBase` | Stream aangemaakt door de `IResourceStreamFactory.create_resource_stream`-methode. |

**Returns:** None.

### Zie ook
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
