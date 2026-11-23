---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une nouvelle instance de FileCache."
type: docs
url: /fr/python-net/groupdocs.viewer.caching/filecache/__init__/
is_root: false
weight: 10
---


## __init__ {#cache_path}

Initialise une nouvelle instance de FileCache.

```python
def __init__(self, cache_path):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| cache_path | `str` | Chemin relatif ou absolu où le cache du document sera stocké. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `cache_path` est None. |

## __init__ {#cache_path-cache_sub_folder}

Initialise une nouvelle instance de la classe FileCache.

```python
def __init__(self, cache_path, cache_sub_folder):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| cache_path | `str` | Chemin relatif ou absolu où le cache du document sera stocké. |
| cache_sub_folder | `str` | Le sous-dossier à ajouter à `cache_path`. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `cache_sub_folder` est None. |

### Voir aussi
* class [`FileCache`](/viewer/python-net/groupdocs.viewer.caching/filecache/)
