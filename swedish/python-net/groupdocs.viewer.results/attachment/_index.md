---
title: "Attachment-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Representerar en bifogad fil som finns i ett e-postmeddelande, arkiv, PDF-dokument eller Outlook-datafil."
type: docs
url: /sv/python-net/groupdocs.viewer.results/attachment/
is_root: false
weight: 20
---


## Attachment class

Representerar en bifogad fil som finns i ett e-postmeddelande, arkiv, PDF-dokument eller Outlook-datafil.

Attachment-typen visar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/) | Initierar en ny [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/) instans. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#file_name-file_path) | Initierar en ny Attachment-instans. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-size) | Initierar en ny instans av Attachment-klassen. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-file_type-size) | Initierar en ny instans av Attachment-klassen. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/attachment/to_string/) | Returnerar en sträng som representerar det aktuella objektet. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.results/attachment/file_name/) | Bilagans filnamn. |
| [file_path](/viewer/python-net/groupdocs.viewer.results/attachment/file_path/) | Bilagans relativa sökväg, t.ex. `folder/file.docx`, eller filnamnet när filen finns i rotkatalogen i ett arkiv, i ett e‑mailmeddelande eller i en datafil. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/attachment/file_type/) | Bilagans filtyp. |
| [id](/viewer/python-net/groupdocs.viewer.results/attachment/id/) | Den unika identifieraren för bilagan i sammanhanget av en enskild fil som innehåller denna bilaga. |
| [size](/viewer/python-net/groupdocs.viewer.results/attachment/size/) | Bilagans filstorlek i byte. |

### Exempel

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Åtkomst till bilagans egenskaper, t.ex. filnamn
        print(attachment.file_name)
        # Spara bilagan till en filsökväg
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Se även
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
