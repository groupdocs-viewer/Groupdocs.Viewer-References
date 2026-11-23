---
title: "FileName-klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De bestandsnaam."
type: docs
url: /nl/python-net/groupdocs.viewer.options/filename/
is_root: false
weight: 60
---


## FileName class

De bestandsnaam.

Het FileName-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/filename/__init__/#file_name) | Initialiseert een instantie van de [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/) klasse. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.options/filename/to_string/) | Retourneert een string die het huidige object vertegenwoordigt. |

### Velden
| Veld | Beschrijving |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.options/filename/empty/) | De lege bestandsnaam. |
| [SOURCE](/viewer/python-net/groupdocs.viewer.options/filename/source/) | De naam van het bronbestand. |

### Voorbeeld

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

### Zie ook
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
