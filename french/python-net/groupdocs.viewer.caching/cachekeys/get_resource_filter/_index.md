---
title: "méthode get_resource_filter"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Renvoie une chaîne de filtre pour rechercher les entrées du cache qui représentent des objets Resource."
type: docs
url: /fr/python-net/groupdocs.viewer.caching/cachekeys/get_resource_filter/
is_root: false
weight: 1060
---


## get_resource_filter {#page_number}

Renvoie une chaîne de filtre pour rechercher les entrées du cache qui représentent des objets [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/).

```python
def get_resource_filter(cls, page_number):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| page_number | `int` | Le numéro de la page. |

**Returns:** str: Filter string to search for cache entries that represent `Resource` objects.

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `page_number` est inférieur ou égal à zéro. |

### Voir aussi
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
