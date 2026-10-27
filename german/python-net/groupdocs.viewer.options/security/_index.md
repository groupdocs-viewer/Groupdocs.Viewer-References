---
title: "Security-Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Sicherheitsoptionen für PDF‑Dokumente."
type: docs
url: /de/python-net/groupdocs.viewer.options/security/
is_root: false
weight: 260
---


## Security class

Die Sicherheitsoptionen für PDF‑Dokumente.

Weitere Details finden Sie in der Dokumentation.

Der Security-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/security/__init__/) | Initialisiert eine Instanz der [`Security`](/viewer/python-net/groupdocs.viewer.options/security/) Klasse. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [document_open_password](/viewer/python-net/groupdocs.viewer.options/security/document_open_password/) | Das Passwort, das zum Öffnen des PDF-Dokuments erforderlich ist. |
| [permissions](/viewer/python-net/groupdocs.viewer.options/security/permissions/) | Die PDF-Dokumentberechtigungen wie Drucken, Ändern und Datenextraktion. |
| [permissions_password](/viewer/python-net/groupdocs.viewer.options/security/permissions_password/) | Das Passwort, das zum Ändern der Berechtigungseinstellungen erforderlich ist. |

### Beispiel

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
Aufgabenleitfäden, die `Security` verwenden:

* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)

### Siehe auch
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
