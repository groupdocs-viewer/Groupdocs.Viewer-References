---
title: "méthode get_resource_key"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Renvoie un identifiant unique pour l'entrée du cache qui représente l'objet Resource."
type: docs
url: /fr/python-net/groupdocs.viewer.caching/cachekeys/get_resource_key/
is_root: false
weight: 1070
---


## get_resource_key {#page_number-resource}

Renvoie un identifiant unique pour l'entrée du cache qui représente l'objet [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/).

```python
def get_resource_key(cls, page_number, resource):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| page_number | `int` | Le numéro de la page. |
| resource | `Resource` | La ressource HTML. |

**Returns:** str: Unique identifier for the cache entry that represents `Resource` object.

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `page_number` est inférieur ou égal à zéro, ou si `resource` est None. |

### Voir aussi
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
