---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ny FileCache-instans."
type: docs
url: /sv/python-net/groupdocs.viewer.caching/filecache/__init__/
is_root: false
weight: 10
---


## __init__ {#cache_path}

Initierar en ny FileCache-instans.

```python
def __init__(self, cache_path):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cache_path | `str` | Relativ eller absolut sökväg där dokumentcachen kommer att lagras. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `cache_path` är None. |

## __init__ {#cache_path-cache_sub_folder}

Initierar en ny instans av FileCache-klassen.

```python
def __init__(self, cache_path, cache_sub_folder):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cache_path | `str` | Relativ eller absolut sökväg där dokumentcachen kommer att lagras. |
| cache_sub_folder | `str` | Undermappen som ska läggas till `cache_path`. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `cache_sub_folder` är None. |

### Se även
* class [`FileCache`](/viewer/python-net/groupdocs.viewer.caching/filecache/)
