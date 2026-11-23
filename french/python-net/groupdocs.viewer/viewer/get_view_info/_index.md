---
title: "méthode get_view_info"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Renvoie les informations spécifiques à la vue et au document."
type: docs
url: /fr/python-net/groupdocs.viewer/viewer/get_view_info/
is_root: false
weight: 1050
---


## get_view_info {#options}

Renvoie les informations spécifiques à la vue et au document.

En savoir plus sur le document - type de fichier, nombre de pages et autres propriétés spécifiques au format :
- [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

```python
def get_view_info(self, options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | `ViewInfoOptions` | Les options d'informations de vue. |

**Returns:** Information about view and document specific information.

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `options` est None. |
| `PasswordRequiredException` | Lorsqu'un mot de passe est requis pour ouvrir le document. |
| `IncorrectPasswordException` | Lorsque le mot de passe spécifié est incorrect. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("document.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print(f"Pages: {len(info.pages)}")
    for page in info.pages:
        print(f"  Page {page.number}: {page.width}x{page.height}")
```

### Voir aussi
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
