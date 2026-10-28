---
title: "Security-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "PDF-dokumentets säkerhetsalternativ."
type: docs
url: /sv/python-net/groupdocs.viewer.options/security/
is_root: false
weight: 260
---


## Security class

PDF-dokumentets säkerhetsalternativ.

För detaljer, se dokumentationen.

Security-typen visar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/security/__init__/) | Initialiserar en instans av [`Security`](/viewer/python-net/groupdocs.viewer.options/security/) klassen. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [document_open_password](/viewer/python-net/groupdocs.viewer.options/security/document_open_password/) | Lösenordet som krävs för att öppna PDF-dokumentet. |
| [permissions](/viewer/python-net/groupdocs.viewer.options/security/permissions/) | PDF-dokumentets behörigheter såsom utskrift, ändring och dataextraktion. |
| [permissions_password](/viewer/python-net/groupdocs.viewer.options/security/permissions_password/) | Lösenordet som krävs för att ändra behörighetsinställningar. |

### Exempel

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
Uppgiftsguider som använder `Security`:

* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)

### Se även
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
