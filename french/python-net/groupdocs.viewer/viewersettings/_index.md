---
title: "ViewerSettings classe"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Définit les paramètres pour personnaliser le comportement du Viewer."
type: docs
url: /fr/python-net/groupdocs.viewer/viewersettings/
is_root: false
weight: 110
---


## ViewerSettings class

Définit les paramètres pour personnaliser le comportement de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Le type ViewerSettings expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache-logger) | Initialise une nouvelle instance de ViewerSettings. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache) | Initialise une nouvelle instance de ViewerSettings. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#logger) | Initialise une nouvelle instance de ViewerSettings. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [cache](/viewer/python-net/groupdocs.viewer/viewersettings/cache/) | L'implémentation du cache utilisée pour stocker les résultats de rendu. |
| [logger](/viewer/python-net/groupdocs.viewer/viewersettings/logger/) | L'implémentation du logger utilisée pour la journalisation (Erreurs, Avertissements, Traces). |

### Exemple

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "example/page_{0}.html"
    )
    viewer.view(html_options)
```

### Voir aussi
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
