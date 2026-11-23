---
title: "Viewer‑Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt die Hauptklasse dar, die den Dokument‑Render‑Prozess steuert."
type: docs
url: /de/python-net/groupdocs.viewer/viewer/
is_root: false
weight: 100
---


## Viewer class

Stellt die Hauptklasse dar, die den Dokument‑Render‑Prozess steuert.

Der Viewer‑Typ stellt die folgenden Member bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream) | Initialisiert eine neue Instanz der Klasse [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options) | Initialisiert eine neue Instanz von [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-settings) | Initialisiert eine neue [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) Instanz. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options-settings) | Initialisiert eine neue Viewer‑Instanz. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream) | Initialisiert eine neue Instanz der [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) Klasse. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-leave_open) | Initialisiert eine neue Viewer‑Instanz. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options) | Initialisiert eine neue Instanz von [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-leave_open) | Initialisiert eine neue Viewer‑Instanz. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings) | Initialisiert eine neue Viewer‑Instanz. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings-leave_open) | Initialisiert eine neue Viewer‑Instanz. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings) | Initialisiert eine neue Viewer‑Instanz. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings-leave_open) | Initialisiert eine neue Instanz von [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path) | Initialisiert eine neue Instanz der Klasse [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-settings) | Initialisiert eine neue Instanz der [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) Klasse. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options) | Initialisiert eine neue Instanz von [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options-settings) | Initialisiert eine neue Viewer‑Instanz. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [dispose](/viewer/python-net/groupdocs.viewer/viewer/dispose/) | Gibt den Dateistream und verwaltete interne Ressourcen frei. |
| [get_all_fonts](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) | Gibt alle im geladenen Dokument verwendeten Schriftarten zurück, einschließlich eingebetteter Schriftarten und im Betriebssystem installierter Systemschriftarten. |
| [get_attachments](/viewer/python-net/groupdocs.viewer/viewer/get_attachments/) | Gibt die im Dokument enthaltenen Anhänge zurück. |
| [get_file_info](/viewer/python-net/groupdocs.viewer/viewer/get_file_info/) | Gibt Informationen über die Datei zurück, wie Dateityp und ein Flag, das angibt, ob die Datei verschlüsselt ist. |
| [get_view_info](/viewer/python-net/groupdocs.viewer/viewer/get_view_info/#options) | Gibt Informationen zur Ansicht und zum Dokument zurück. |
| [get_view_info_view_info_options](/viewer/python-net/groupdocs.viewer/viewer/get_view_info_view_info_options/) |  |
| [save_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment/#attachment-destination) | Speichert die Anhangdatei in den `destination`‑Stream. |
| [save_attachment_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_attachment/) |  |
| [save_attachment_stream](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_stream/) |  |
| [save_attachment_streams](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_streams/) |  |
| [search](/viewer/python-net/groupdocs.viewer/viewer/search/#options) | Führt eine Textsuche durch und hebt den gefundenen Text im geladenen Dokument gemäß den angegebenen Optionen hervor. |
| [search_search_highlight_options](/viewer/python-net/groupdocs.viewer/viewer/search_search_highlight_options/) |  |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options) | Erstellt eine Ansicht aller Dokumentseiten. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-page_numbers) | Erstellt eine Ansicht bestimmter Dokumentseiten. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-cancellation_token-page_numbers) | Erstellt eine Ansicht bestimmter Dokumentseiten. |
| [view_view_options](/viewer/python-net/groupdocs.viewer/viewer/view_view_options/) |  |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, PngViewOptions

# DOCX nach HTML rendern
with Viewer("./sample.docx") as viewer:
    html_opts = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(html_opts)

# PDF nach PNG rendern
with Viewer("document.pdf") as viewer:
    png_opts = PngViewOptions("page_{0}.png")
    viewer.view(png_opts)
```

### Guides
Aufgabenleitfäden, die `Viewer` verwenden:

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Get Document Information](/viewer/python-net/guides/get-document-info/)
* [Load document from local disk](/viewer/python-net/guides/load-document-from-local-disk/)
* [Load document from stream](/viewer/python-net/guides/load-document-from-stream/)
* [Load document from URL](/viewer/python-net/guides/load-document-from-url/)
* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)
* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)
* [Reorder pages](/viewer/python-net/guides/reorder-pages/)
* [Save attachments](/viewer/python-net/guides/how-to-extract-and-save-attachments/)

### Siehe auch
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
