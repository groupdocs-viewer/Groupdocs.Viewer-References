---
title: "LoadOptions Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Optionen, die zum Öffnen einer Datei verwendet werden."
type: docs
url: /de/python-net/groupdocs.viewer.options/loadoptions/
is_root: false
weight: 110
---


## LoadOptions class

Die Optionen, die zum Öffnen einer Datei verwendet werden.

Der Typ LoadOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/) | Initialisiert eine Instanz der [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/) Klasse. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/#file_type) | Initialisiert eine neue LoadOptions-Instanz. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/) | Die Eigenschaft aktiviert die Erkennung der Kodierung für [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), und [`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/) Dateien. |
| [encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/) | Die beim Öffnen von textbasierten Dateien oder E-Mails wie [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), und [`FileType.msg`](/viewer/python-net/groupdocs.viewer/filetype/msg/) verwendete Kodierung. Der Standardwert ist `utf-8`. |
| [file_type](/viewer/python-net/groupdocs.viewer.options/loadoptions/file_type/) | Der Typ der zu öffnenden Datei. |
| [password](/viewer/python-net/groupdocs.viewer.options/loadoptions/password/) | Das Passwort zum Öffnen einer verschlüsselten Datei. |
| [resource_loading_timeout](/viewer/python-net/groupdocs.viewer.options/loadoptions/resource_loading_timeout/) | Der Timeout zum Laden externer Ressourcen. |
| [skip_external_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) | Die Eigenschaft deaktiviert das Laden aller externen Ressourcen wie Bilder, außer denen, die in [`LoadOptions.whitelisted_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) aufgeführt sind. |
| [try_repair](/viewer/python-net/groupdocs.viewer.options/loadoptions/try_repair/) | Die Eigenschaft ermöglicht es GroupDocs.Viewer, zu versuchen, strukturelle Beschädigungen in PDF-Dokumenten zu reparieren. Der Standardwert ist False. |
| [whitelisted_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) | Die Liste von URL‑Fragmenten, die externen Ressourcen entsprechen und geladen werden sollen, wenn [`LoadOptions.skip_external_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) auf `True` gesetzt ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, LoadOptions

load_options = LoadOptions()
load_options.password = "12345"

with Viewer("protected.docx", load_options) as viewer:
    viewer.view(HtmlViewOptions.for_embedded_resources("page_{0}.html"))
```

### Siehe auch
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
