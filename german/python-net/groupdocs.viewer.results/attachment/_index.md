---
title: "Attachment Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt eine Anhangsdatei dar, die in einer E‑Mail‑Nachricht, einem Archiv, PDF-Dokument oder Outlook-Datendatei enthalten ist."
type: docs
url: /de/python-net/groupdocs.viewer.results/attachment/
is_root: false
weight: 20
---


## Attachment class

Stellt eine Anhangsdatei dar, die in einer E‑Mail‑Nachricht, einem Archiv, PDF-Dokument oder Outlook-Datendatei enthalten ist.

Der Attachment-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/) | Initialisiert eine neue [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/) Instanz. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#file_name-file_path) | Initialisiert eine neue Attachment-Instanz. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-size) | Initialisiert eine neue Instanz der Klasse Attachment. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-file_type-size) | Initialisiert eine neue Instanz der Klasse Attachment. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/attachment/to_string/) | Gibt einen String zurück, der das aktuelle Objekt repräsentiert. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.results/attachment/file_name/) | Der Dateiname des Anhangs. |
| [file_path](/viewer/python-net/groupdocs.viewer.results/attachment/file_path/) | Der relative Pfad des Anhangs, z. B. `folder/file.docx`, oder der Dateiname, wenn die Datei im Stammverzeichnis eines Archivs, in einer E‑Mail‑Nachricht oder einer Datendatei liegt. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/attachment/file_type/) | Der Dateityp des Anhangs. |
| [id](/viewer/python-net/groupdocs.viewer.results/attachment/id/) | Der eindeutige Bezeichner des Anhangs im Kontext einer einzelnen Datei, die diesen Anhang enthält. |
| [size](/viewer/python-net/groupdocs.viewer.results/attachment/size/) | Die Dateigröße des Anhangs in Bytes. |

### Beispiel

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Zugriff auf Anhangseigenschaften, z. B. Dateiname
        print(attachment.file_name)
        # Speichere den Anhang an einem Dateipfad
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Siehe auch
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
