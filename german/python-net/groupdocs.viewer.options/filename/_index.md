---
title: "FileName-Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Der Dateiname."
type: docs
url: /de/python-net/groupdocs.viewer.options/filename/
is_root: false
weight: 60
---


## FileName class

Der Dateiname.

Der FileName-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/filename/__init__/#file_name) | Initialisiert eine Instanz der Klasse [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/). |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.options/filename/to_string/) | Gibt einen String zurück, der das aktuelle Objekt repräsentiert. |

### Felder
| Feld | Beschreibung |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.options/filename/empty/) | Der leere Dateiname. |
| [SOURCE](/viewer/python-net/groupdocs.viewer.options/filename/source/) | Der Name der Quelldatei. |

### Beispiel

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

### Siehe auch
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
