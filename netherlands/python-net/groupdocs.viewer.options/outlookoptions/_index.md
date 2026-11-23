---
title: "OutlookOptions klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Bevat opties voor het renderen van Outlook‑gegevensbestanden."
type: docs
url: /nl/python-net/groupdocs.viewer.options/outlookoptions/
is_root: false
weight: 130
---


## OutlookOptions class

Bevat opties voor het renderen van Outlook‑gegevensbestanden.

Voor details, zie de GroupDocs-documentatie.

Het type OutlookOptions bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/outlookoptions/__init__/) |  |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [address_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/address_filter/) | Het e-mailadres dat wordt gebruikt om berichten te filteren op afzender of ontvanger. |
| [folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/folder/) | De naam van de map (bijv. Inbox, Verzonden items of Verwijderde items) om weer te geven. |
| [max_items_in_folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/) | Het maximale aantal berichten of items dat uit één map kan worden weergegeven. |
| [text_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/text_filter/) | De trefwoorden die worden gebruikt om berichten te filteren. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_outlook():
    with Viewer("sample.pst") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "outlook.html"
        )
        # Beperk het aantal items dat per map wordt weergegeven.
        view_options.outlook_options.max_items_in_folder = 30
        viewer.view(view_options)
```

### Zie ook
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
