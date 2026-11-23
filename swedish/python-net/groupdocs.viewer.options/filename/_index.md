---
title: "FileName klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Filnamnet."
type: docs
url: /sv/python-net/groupdocs.viewer.options/filename/
is_root: false
weight: 60
---


## FileName class

Filnamnet.

FileName-typen exponerar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/filename/__init__/#file_name) | Initierar en instans av [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/) klass. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.options/filename/to_string/) | Returnerar en sträng som representerar det aktuella objektet. |

### Fält
| Fält | Beskrivning |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.options/filename/empty/) | Det tomma filnamnet. |
| [SOURCE](/viewer/python-net/groupdocs.viewer.options/filename/source/) | Namnet på källfilen. |

### Exempel

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

### Se även
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
