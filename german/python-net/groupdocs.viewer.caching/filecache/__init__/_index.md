---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine neue FileCache-Instanz."
type: docs
url: /de/python-net/groupdocs.viewer.caching/filecache/__init__/
is_root: false
weight: 10
---


## __init__ {#cache_path}

Initialisiert eine neue FileCache-Instanz.

```python
def __init__(self, cache_path):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cache_path | `str` | Relativer oder absoluter Pfad, in dem der Dokumenten-Cache gespeichert wird. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `cache_path` None ist. |

## __init__ {#cache_path-cache_sub_folder}

Initialisiert eine neue Instanz der FileCache-Klasse.

```python
def __init__(self, cache_path, cache_sub_folder):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cache_path | `str` | Relativer oder absoluter Pfad, in dem der Dokumenten-Cache gespeichert wird. |
| cache_sub_folder | `str` | Der Unterordner, der an `cache_path` angehängt wird. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `cache_sub_folder` None ist. |

### Siehe auch
* class [`FileCache`](/viewer/python-net/groupdocs.viewer.caching/filecache/)
