---
title: "Attachment‑klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stelt een bijlagebestand voor dat is opgenomen in een e‑mailbericht, archief, PDF‑document of Outlook‑databestand."
type: docs
url: /nl/python-net/groupdocs.viewer.results/attachment/
is_root: false
weight: 20
---


## Attachment class

Stelt een bijlagebestand voor dat is opgenomen in een e‑mailbericht, archief, PDF‑document of Outlook‑databestand.

Het type Attachment bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/) | Initialiseert een nieuw [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/) exemplaar. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#file_name-file_path) | Initialiseert een nieuw Attachment‑exemplaar. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-size) | Initialiseert een nieuw exemplaar van de Attachment‑klasse. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-file_type-size) | Initialiseert een nieuw exemplaar van de Attachment‑klasse. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/attachment/to_string/) | Retourneert een string die het huidige object vertegenwoordigt. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.results/attachment/file_name/) | De bestandsnaam van de bijlage. |
| [file_path](/viewer/python-net/groupdocs.viewer.results/attachment/file_path/) | Het relatieve pad van de bijlage, bijv. `folder/file.docx`, of de bestandsnaam wanneer het bestand zich in de hoofdmap van een archief, in een e‑mailbericht of in een gegevensbestand bevindt. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/attachment/file_type/) | Het bestandstype van de bijlage. |
| [id](/viewer/python-net/groupdocs.viewer.results/attachment/id/) | De unieke identifier van de bijlage in de context van een enkel bestand dat deze bijlage bevat. |
| [size](/viewer/python-net/groupdocs.viewer.results/attachment/size/) | De bestandsgrootte van de bijlage in bytes. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Toegang tot bijlage-eigenschappen, bijv., bestandsnaam
        print(attachment.file_name)
        # Sla de bijlage op naar een bestandspad
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Zie ook
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
