---
title: "Classe FileName"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Il nome file."
type: docs
url: /it/python-net/groupdocs.viewer.options/filename/
is_root: false
weight: 60
---


## FileName class

Il nome file.

Il tipo FileName espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/filename/__init__/#file_name) | Inizializza un'istanza della classe [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/). |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.options/filename/to_string/) | Restituisce una stringa che rappresenta l'oggetto corrente. |

### Campi
| Campo | Descrizione |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.options/filename/empty/) | Il nome file vuoto. |
| [SOURCE](/viewer/python-net/groupdocs.viewer.options/filename/source/) | Il nome del file sorgente. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, FileName

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "output/archive_{0}.html"
    )
    view_options.archive_options.file_name = FileName("Sample Files")
    viewer.view(view_options)
```

### Vedi anche
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
