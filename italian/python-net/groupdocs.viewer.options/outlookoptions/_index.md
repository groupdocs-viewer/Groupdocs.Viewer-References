---
title: "classe OutlookOptions"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Contiene opzioni per il rendering dei file di dati Outlook."
type: docs
url: /it/python-net/groupdocs.viewer.options/outlookoptions/
is_root: false
weight: 130
---


## OutlookOptions class

Contiene opzioni per il rendering dei file di dati Outlook.

Per ulteriori dettagli, vedere la documentazione di GroupDocs.

Il tipo OutlookOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/outlookoptions/__init__/) |  |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [address_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/address_filter/) | L'indirizzo email utilizzato per filtrare i messaggi per mittente o destinatario. |
| [folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/folder/) | Il nome della cartella (ad es. Posta in arrivo, Posta inviata o Elementi eliminati) da rendere. |
| [max_items_in_folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/) | Il numero massimo di messaggi o elementi che possono essere renderizzati da una cartella. |
| [text_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/text_filter/) | Le parole chiave utilizzate per filtrare i messaggi. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_outlook():
    with Viewer("sample.pst") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "outlook.html"
        )
        # Limita il numero di elementi renderizzati per cartella.
        view_options.outlook_options.max_items_in_folder = 30
        viewer.view(view_options)
```

### Vedi anche
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
