---
title: "méthode get_file_key"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Renvoie un identifiant unique pour l'entrée du cache qui représente le fichier."
type: docs
url: /fr/python-net/groupdocs.viewer.caching/cachekeys/get_file_key/
is_root: false
weight: 1040
---


## get_file_key {#extension}

Renvoie un identifiant unique pour l'entrée du cache qui représente le fichier.

```python
def get_file_key(cls, extension):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| extension | `str` | Le suffixe du nom de fichier (y compris le point \".\") par ex. \".doc\". |

**Returns:** str: Unique identifier for the cache entry that represents file.

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `extension` est None ou vide. |

### Voir aussi
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
