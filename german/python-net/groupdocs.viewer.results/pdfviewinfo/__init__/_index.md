---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine neue PdfViewInfo-Instanz."
type: docs
url: /de/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue PdfViewInfo-Instanz.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-printing_allowed}

Initialisiert eine neue PdfViewInfo-Instanz.

```python
def __init__(self, file_type, pages, printing_allowed):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_type | `FileType` | Der Typ der Datei. |
| pages | `List[Page]` | Die Liste der anzuzeigenden Seiten. |
| printing_allowed | `bool` | Der Druckberechtigungsindikator. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `pages` None ist. |

### Siehe auch
* class [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/)
