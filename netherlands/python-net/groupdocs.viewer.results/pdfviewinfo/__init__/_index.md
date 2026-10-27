---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een nieuw PdfViewInfo-exemplaar."
type: docs
url: /nl/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw PdfViewInfo-exemplaar.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-printing_allowed}

Initialiseert een nieuw PdfViewInfo-exemplaar.

```python
def __init__(self, file_type, pages, printing_allowed):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_type | `FileType` | Het type van het bestand. |
| pages | `List[Page]` | De lijst met pagina's om te bekijken. |
| printing_allowed | `bool` | De afdrukmachtiging indicator. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `pages` None is. |

### Zie ook
* class [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/)
