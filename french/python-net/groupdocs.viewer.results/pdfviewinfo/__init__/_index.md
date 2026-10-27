---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une nouvelle instance de PdfViewInfo."
type: docs
url: /fr/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de PdfViewInfo.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-printing_allowed}

Initialise une nouvelle instance de PdfViewInfo.

```python
def __init__(self, file_type, pages, printing_allowed):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_type | `FileType` | Le type du fichier. |
| pages | `List[Page]` | La liste des pages à afficher. |
| printing_allowed | `bool` | L'indicateur d'autorisation d'impression. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `pages` est None. |

### Voir aussi
* class [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/)
