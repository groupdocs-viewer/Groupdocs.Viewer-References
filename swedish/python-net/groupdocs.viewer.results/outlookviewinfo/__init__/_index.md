---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ny instans av OutlookViewInfo."
type: docs
url: /sv/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Initierar en ny OutlookViewInfo-instans.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_type | `FileType` | Filens typ. |
| pages | `List[Page]` | Listan över sidor att visa. |
| folders | `List[str]` | Listan över mappar som finns i Outlook Data-filen. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Kastas när `folders` är None. |

### Se även
* class [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/)
