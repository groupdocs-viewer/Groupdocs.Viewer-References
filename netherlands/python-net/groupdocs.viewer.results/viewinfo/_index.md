---
title: "ViewInfo klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stelt weergave-informatie voor een generiek document voor."
type: docs
url: /nl/python-net/groupdocs.viewer.results/viewinfo/
is_root: false
weight: 180
---


## ViewInfo class

Stelt weergave-informatie voor een generiek document voor.

Het ViewInfo-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/) | Initialiseert een nieuw exemplaar van [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/#file_type-pages) | Initialiseert een nieuw ViewInfo-exemplaar. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Retourneert een string die het huidige object vertegenwoordigt. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Het type van het bestand. |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | De lijst met pagina's om te bekijken. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("sample.docx") as viewer:
    options = ViewInfoOptions.for_html_view()
    view_info = viewer.get_view_info(options)
    for page in view_info.pages:
        print(f"Page {page.number}: {page.name}")
```

### Zie ook
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
