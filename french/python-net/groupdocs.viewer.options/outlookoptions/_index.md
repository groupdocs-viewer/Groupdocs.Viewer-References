---
title: "Classe OutlookOptions"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Contient des options pour le rendu des fichiers de données Outlook."
type: docs
url: /fr/python-net/groupdocs.viewer.options/outlookoptions/
is_root: false
weight: 130
---


## OutlookOptions class

Contient des options pour le rendu des fichiers de données Outlook.

Pour plus de détails, consultez la documentation GroupDocs.

Le type OutlookOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/outlookoptions/__init__/) |  |

### Propriétés
| Propriété | Description |
| :- | :- |
| [address_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/address_filter/) | L'adresse e‑mail utilisée pour filtrer les messages par expéditeur ou destinataire. |
| [folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/folder/) | Le nom du dossier (par ex. Boîte de réception, Élément envoyé ou Éléments supprimés) à rendre. |
| [max_items_in_folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/) | Le nombre maximal de messages ou d'éléments pouvant être rendus depuis un dossier. |
| [text_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/text_filter/) | Les mots‑clés utilisés pour filtrer les messages. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_outlook():
    with Viewer("sample.pst") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "outlook.html"
        )
        # Limitez le nombre d'éléments rendus par dossier.
        view_options.outlook_options.max_items_in_folder = 30
        viewer.view(view_options)
```

### Voir aussi
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
