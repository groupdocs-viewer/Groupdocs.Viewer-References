---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ny instans av ProjectManagementViewInfo."
type: docs
url: /sv/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-start_date-end_date}

Initierar en ny instans av ProjectManagementViewInfo.

```python
def __init__(self, file_type, pages, start_date, end_date):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_type | `FileType` | Filens typ. |
| pages | `List[Page]` | Listan över sidor att visa. |
| start_date | `datetime` | Datumet och tiden då projektet startade. |
| end_date | `datetime` | Datumet och tiden då projektet ska slutföras. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `pages` är None. |

### Se även
* class [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/)
