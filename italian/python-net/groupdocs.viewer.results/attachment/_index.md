---
title: "Classe Attachment"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta un file allegato contenuto in un messaggio email, archivio, documento PDF o file di dati Outlook."
type: docs
url: /it/python-net/groupdocs.viewer.results/attachment/
is_root: false
weight: 20
---


## Attachment class

Rappresenta un file allegato contenuto in un messaggio email, archivio, documento PDF o file di dati Outlook.

Il tipo Attachment espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/) | Inizializza una nuova istanza di [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#file_name-file_path) | Inizializza una nuova istanza di Attachment. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-size) | Inizializza una nuova istanza della classe Attachment. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-file_type-size) | Inizializza una nuova istanza della classe Attachment. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/attachment/to_string/) | Restituisce una stringa che rappresenta l'oggetto corrente. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.results/attachment/file_name/) | Il nome file dell'allegato. |
| [file_path](/viewer/python-net/groupdocs.viewer.results/attachment/file_path/) | Il percorso relativo dell'allegato, ad es. `folder/file.docx`, o il nome file quando il file si trova nella radice di un archivio, in un messaggio e‑mail o in un file dati. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/attachment/file_type/) | Il tipo di file dell'allegato. |
| [id](/viewer/python-net/groupdocs.viewer.results/attachment/id/) | L'identificatore univoco dell'allegato nel contesto di un singolo file che contiene questo allegato. |
| [size](/viewer/python-net/groupdocs.viewer.results/attachment/size/) | La dimensione del file dell'allegato in byte. |

### Esempio

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Accedi alle proprietà dell'allegato, ad es., nome file
        print(attachment.file_name)
        # Salva l'allegato in un percorso file
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Vedi anche
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
