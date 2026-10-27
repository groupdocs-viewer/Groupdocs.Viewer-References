---
title: "méthode release_resource_stream"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Libère le flux créé par la méthode IResourceStreamFactory.createresourcestream."
type: docs
url: /fr/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/release_resource_stream/
is_root: false
weight: 1050
---


## release_resource_stream {#page_number-resource-resource_stream}

Libère le flux créé par la méthode [`IResourceStreamFactory.create_resource_stream`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/).

```python
def release_resource_stream(self, page_number, resource, resource_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| page_number | `int` | Le numéro d'une page. |
| resource | `Resource` | La ressource HTML telle que police, style, image ou graphique. |
| resource_stream | `io.RawIOBase` | Flux créé par la méthode `IResourceStreamFactory.create_resource_stream`. |

**Returns:** None.

### Voir aussi
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
