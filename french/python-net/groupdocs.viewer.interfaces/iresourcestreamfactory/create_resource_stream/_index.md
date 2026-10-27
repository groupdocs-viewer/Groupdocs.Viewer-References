---
title: "méthode create_resource_stream"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Crée le flux utilisé pour écrire les données de ressources HTML de sortie."
type: docs
url: /fr/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/
is_root: false
weight: 1010
---


## create_resource_stream {#page_number-resource}

Crée le flux utilisé pour écrire les données de ressources HTML de sortie.

```python
def create_resource_stream(self, page_number, resource):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| page_number | `int` | Le numéro d'une page. |
| resource | `Resource` | La ressource HTML telle que police, style, image ou graphique. |

**Returns:** io.RawIOBase: Stream used to write output resource data.

### Exemple

```python
from groupdocs.viewer import Viewer

viewer = Viewer()
factory = viewer.resource_stream_factory

# Créer un flux pour une ressource CSS à la page 1
stream = factory.create_resource_stream(pageNumber=1, resource="style.css")
with stream:
    stream.write(b"body { font-family: Arial; }")
```

### Voir aussi
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
