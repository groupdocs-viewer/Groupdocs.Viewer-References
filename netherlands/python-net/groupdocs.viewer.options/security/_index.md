---
title: "Security-klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De beveiligingsopties voor PDF‑documenten."
type: docs
url: /nl/python-net/groupdocs.viewer.options/security/
is_root: false
weight: 260
---


## Security class

De beveiligingsopties voor PDF‑documenten.

Zie voor details de documentatie.

Het Security-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/security/__init__/) | Initialiseert een instantie van de [`Security`](/viewer/python-net/groupdocs.viewer.options/security/) klasse. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [document_open_password](/viewer/python-net/groupdocs.viewer.options/security/document_open_password/) | Het wachtwoord dat nodig is om het PDF‑document te openen. |
| [permissions](/viewer/python-net/groupdocs.viewer.options/security/permissions/) | De PDF‑documentrechten, zoals afdrukken, wijzigen en gegevensextraheren. |
| [permissions_password](/viewer/python-net/groupdocs.viewer.options/security/permissions_password/) | Het wachtwoord dat nodig is om machtigingsinstellingen te wijzigen. |

### Voorbeeld

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
Taakgidsen die `Security` gebruiken:

* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)

### Zie ook
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
