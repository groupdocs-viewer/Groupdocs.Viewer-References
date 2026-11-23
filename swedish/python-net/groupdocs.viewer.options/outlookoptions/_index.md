---
title: "OutlookOptions klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Innehåller alternativ för att rendera Outlook-datafiler."
type: docs
url: /sv/python-net/groupdocs.viewer.options/outlookoptions/
is_root: false
weight: 130
---


## OutlookOptions class

Innehåller alternativ för att rendera Outlook-datafiler.

För detaljer, se GroupDocs-dokumentationen.

OutlookOptions-typen visar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/outlookoptions/__init__/) |  |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [address_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/address_filter/) | E-postadressen som används för att filtrera meddelanden efter avsändare eller mottagare. |
| [folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/folder/) | Namnet på mappen (t.ex. Inkorg, Skickade objekt eller Borttagna objekt) som ska renderas. |
| [max_items_in_folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/) | Det maximala antalet meddelanden eller objekt som kan renderas från en mapp. |
| [text_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/text_filter/) | Nyckelorden som används för att filtrera meddelanden. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_outlook():
    with Viewer("sample.pst") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "outlook.html"
        )
        # Begränsa antalet objekt som renderas per mapp.
        view_options.outlook_options.max_items_in_folder = 30
        viewer.view(view_options)
```

### Se även
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
