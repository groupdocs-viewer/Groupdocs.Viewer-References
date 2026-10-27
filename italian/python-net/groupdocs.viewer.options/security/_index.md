---
title: "Classe Security"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Le opzioni di sicurezza del documento PDF."
type: docs
url: /it/python-net/groupdocs.viewer.options/security/
is_root: false
weight: 260
---


## Security class

Le opzioni di sicurezza del documento PDF.

Per i dettagli, vedere la documentazione.

Il tipo Security espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/security/__init__/) | Inizializza un'istanza della classe [`Security`](/viewer/python-net/groupdocs.viewer.options/security/). |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [document_open_password](/viewer/python-net/groupdocs.viewer.options/security/document_open_password/) | La password richiesta per aprire il documento PDF. |
| [permissions](/viewer/python-net/groupdocs.viewer.options/security/permissions/) | Le autorizzazioni del documento PDF, come stampa, modifica ed estrazione dei dati. |
| [permissions_password](/viewer/python-net/groupdocs.viewer.options/security/permissions_password/) | La password necessaria per modificare le impostazioni dei permessi. |

### Esempio

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
Guide operative che utilizzano `Security`:

* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)

### Vedi anche
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
