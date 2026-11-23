---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een nieuwe FileCache‑instantie."
type: docs
url: /nl/python-net/groupdocs.viewer.caching/filecache/__init__/
is_root: false
weight: 10
---


## __init__ {#cache_path}

Initialiseert een nieuwe FileCache‑instantie.

```python
def __init__(self, cache_path):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cache_path | `str` | Relatief of absoluut pad waar de documentcache wordt opgeslagen. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `cache_path` None is. |

## __init__ {#cache_path-cache_sub_folder}

Initialiseert een nieuwe instantie van de FileCache‑klasse.

```python
def __init__(self, cache_path, cache_sub_folder):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cache_path | `str` | Relatief of absoluut pad waar de documentcache wordt opgeslagen. |
| cache_sub_folder | `str` | De submap die moet worden toegevoegd aan `cache_path`. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `cache_sub_folder` None is. |

### Zie ook
* class [`FileCache`](/viewer/python-net/groupdocs.viewer.caching/filecache/)
