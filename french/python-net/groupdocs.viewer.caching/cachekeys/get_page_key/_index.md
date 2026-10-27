---
title: "méthode get_page_key"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Renvoie un identifiant unique pour l'entrée du cache qui représente le fichier de page."
type: docs
url: /fr/python-net/groupdocs.viewer.caching/cachekeys/get_page_key/
is_root: false
weight: 1050
---


## get_page_key {#page_number-extension}

Renvoie un identifiant unique pour l'entrée du cache qui représente le fichier de page.

```python
def get_page_key(cls, page_number, extension):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| page_number | `int` | Le numéro de la page. |
| extension | `str` | Le suffixe du nom de fichier (y compris le point \".\") par ex. \".doc\". |

**Returns:** str: Unique identifier for the cache entry that represents page file.

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `extension` est None ou vide. |

### Voir aussi
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
