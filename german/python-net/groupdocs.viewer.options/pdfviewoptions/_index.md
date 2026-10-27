---
title: "PdfViewOptions Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt Optionen zum Rendern von Dokumenten in das PDF-Format dar."
type: docs
url: /de/python-net/groupdocs.viewer.options/pdfviewoptions/
is_root: false
weight: 170
---


## PdfViewOptions class

Stellt Optionen zum Rendern von Dokumenten in das PDF-Format dar.

Weitere Details finden Sie in der Dokumentation.

Der Typ PdfViewOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#create_file_stream) | Initialisiert eine Instanz von [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/). |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#create_file_stream-release_file_stream) | Initialisiert eine neue PdfViewOptions-Instanz. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#file_stream_factory) | Initialisiert eine PdfViewOptions-Instanz. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/) | Initialisiert eine PdfViewOptions-Instanz. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#output_file_path) | Initialisiert eine Instanz der Klasse [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/). |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [rotate_page](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page/) | Wendet die Drehung im Uhrzeigersinn auf eine Seite an. (geerbt von [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [rotate_page_int32](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page_int32/) | (geerbt von [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [image_height](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_height/) | Die Höhe eines Ausgabebildes in Pixeln. |
| [image_max_height](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_height/) | Die maximale Höhe eines Ausgabebildes in Pixeln. |
| [image_max_width](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_width/) | Die maximale Breite eines Ausgabebildes in Pixeln. |
| [image_width](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_width/) | Die Breite des Ausgabebildes in Pixeln. |
| [pdf_optimization_options](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/pdf_optimization_options/) | Die Eigenschaft pdf_optimization_options bietet Zugriff auf eine [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/) Instanz, die die Größe der ausgegebenen PDF-Datei durch Anwendung von Optimierungstechniken reduziert. |
| [security](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/security/) | Die Sicherheitsoptionen für das ausgegebene PDF-Dokument. |
| [archive_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/archive_options/) | Die Ansichtoptionen für Archivdateien. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [cad_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/cad_options/) | Die Ansichtoptionen für CAD-Zeichnungen. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [default_font_name](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/default_font_name/) | Die Standardschriftart für ein Dokument, die während der Darstellung verwendet wird, wenn eine erforderliche Schriftart fehlt. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [email_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/email_options/) | Die Ansichtoptionen für E-Mail-Nachrichten. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [mail_storage_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/mail_storage_options/) | Die Ansichtoptionen für Mail-Storage-Datendateien. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [outlook_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/outlook_options/) | Die Ansichtoptionen für Microsoft Outlook-Datendateien. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [page_rotations](/viewer/python-net/groupdocs.viewer.options/viewoptions/page_rotations/) | Die Seitenrotation. (geerbt von [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [pdf_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/pdf_options/) | Die Ansichtoptionen für PDF-Dokumente. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [presentation_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/presentation_options/) | Die Ansichtoptionen für Präsentationsdateien. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [project_management_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/project_management_options/) | Die Ansichtoptionen für Projektmanagementdateien. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [remove_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/) | Die Eigenschaft deaktiviert das Rendern von Kommentaren, wenn sie auf True gesetzt ist. Standardmäßig ist sie False, sodass alle Kommentare angezeigt werden. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_comments/) | Die Eigenschaft aktiviert oder deaktiviert das Rendern von Kommentaren. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_hidden_pages](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_hidden_pages/) | Die Eigenschaft aktiviert das Rendern versteckter Seiten. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_notes](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/) | Die Eigenschaft aktiviert das Rendern von Notizen und Anmerkungen für einige Formate. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [spreadsheet_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/spreadsheet_options/) | Die Ansichtoptionen für Tabellenkalkulationsdateien. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [text_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/text_options/) | Die Textoptionen für das Rendern von Textdateien. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [visio_rendering_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/visio_rendering_options/) | Die Ansichtoptionen für Visio-Dateien. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [watermark](/viewer/python-net/groupdocs.viewer.options/viewoptions/watermark/) | Das Textwasserzeichen, das auf jeder Seite angewendet wird. (geerbt von [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [web_document_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/web_document_options/) | Die Ansichtoptionen für Webdateien. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [word_processing_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/word_processing_options/) | Die Ansichtoptionen für Textverarbeitungsdateien. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### Guides
Aufgabenleitfäden, die `PdfViewOptions` verwenden:

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)
* [Reorder pages](/viewer/python-net/guides/reorder-pages/)

### Siehe auch
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
