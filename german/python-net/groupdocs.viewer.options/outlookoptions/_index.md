---
title: "Klasse OutlookOptions"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Enthält Optionen zum Rendern von Outlook‑Datendateien."
type: docs
url: /de/python-net/groupdocs.viewer.options/outlookoptions/
is_root: false
weight: 130
---


## OutlookOptions class

Enthält Optionen zum Rendern von Outlook‑Datendateien.

Weitere Details finden Sie in der GroupDocs-Dokumentation.

Der Typ OutlookOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/outlookoptions/__init__/) |  |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [address_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/address_filter/) | Die E-Mail-Adresse, die zum Filtern von Nachrichten nach Absender oder Empfänger verwendet wird. |
| [folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/folder/) | Der Name des Ordners (z. B. Posteingang, Gesendete Elemente oder Gelöschte Elemente), der gerendert werden soll. |
| [max_items_in_folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/) | Die maximale Anzahl von Nachrichten oder Elementen, die aus einem Ordner gerendert werden können. |
| [text_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/text_filter/) | Die Schlüsselwörter, die zum Filtern von Nachrichten verwendet werden. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_outlook():
    with Viewer("sample.pst") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "outlook.html"
        )
        # Begrenzen Sie die Anzahl der pro Ordner gerenderten Elemente.
        view_options.outlook_options.max_items_in_folder = 30
        viewer.view(view_options)
```

### Siehe auch
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
