---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ny PdfViewInfo-instans."
type: docs
url: /sv/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny PdfViewInfo-instans.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-printing_allowed}

Initierar en ny PdfViewInfo-instans.

```python
def __init__(self, file_type, pages, printing_allowed):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_type | `FileType` | Filens typ. |
| pages | `List[Page]` | Listan över sidor att visa. |
| printing_allowed | `bool` | Utskriftsbehörighetsindikatorn. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `pages` är None. |

### Se även
* class [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/)
