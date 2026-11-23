---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert ein neues ProjectManagementViewInfo."
type: docs
url: /de/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz von [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-start_date-end_date}

Initialisiert ein neues ProjectManagementViewInfo.

```python
def __init__(self, file_type, pages, start_date, end_date):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_type | `FileType` | Der Typ der Datei. |
| pages | `List[Page]` | Die Liste der anzuzeigenden Seiten. |
| start_date | `datetime` | Das Datum und die Uhrzeit, zu der das Projekt gestartet wurde. |
| end_date | `datetime` | Das Datum und die Uhrzeit, zu der das Projekt abgeschlossen sein soll. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `pages` None ist. |

### Siehe auch
* class [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/)
