---
title: "méthode de recherche"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Effectue une recherche de texte et met en surbrillance le texte trouvé dans le document chargé selon les options fournies."
type: docs
url: /fr/python-net/groupdocs.viewer/viewer/search/
is_root: false
weight: 1110
---


## search {#options}

Effectue une recherche de texte et met en surbrillance le texte trouvé dans le document chargé selon les options fournies.

```python
def search(self, options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | `SearchHighlightOptions` | Options de recherche et de mise en surbrillance, incluant la phrase texte à rechercher. Ne doit pas être None. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `options` est None. |

### Voir aussi
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
