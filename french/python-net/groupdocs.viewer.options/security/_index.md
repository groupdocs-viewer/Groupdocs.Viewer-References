---
title: "Classe Security"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Les options de sécurité du document PDF."
type: docs
url: /fr/python-net/groupdocs.viewer.options/security/
is_root: false
weight: 260
---


## Security class

Les options de sécurité du document PDF.

Pour plus de détails, consultez la documentation.

Le type Security expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/security/__init__/) | Initialise une instance de la classe [`Security`](/viewer/python-net/groupdocs.viewer.options/security/). |

### Propriétés
| Propriété | Description |
| :- | :- |
| [document_open_password](/viewer/python-net/groupdocs.viewer.options/security/document_open_password/) | Le mot de passe requis pour ouvrir le document PDF. |
| [permissions](/viewer/python-net/groupdocs.viewer.options/security/permissions/) | Les autorisations du document PDF telles que l’impression, la modification et l’extraction de données. |
| [permissions_password](/viewer/python-net/groupdocs.viewer.options/security/permissions_password/) | Le mot de passe requis pour modifier les paramètres d'autorisation. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

with Viewer("sample.docx") as viewer:
    security = Security()
    security.document_open_password = "o123"
    security.permissions_password = "p123"
    security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

    pdf_options = PdfViewOptions("protected_document.pdf")
    pdf_options.security = security
    viewer.view(pdf_options)
```

### Guides
Guides de tâches qui utilisent `Security`:

* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)

### Voir aussi
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
