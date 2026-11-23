---
title: "ViewOptions Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Rendering-Optionen."
type: docs
url: /de/python-net/groupdocs.viewer.options/viewoptions/
is_root: false
weight: 340
---


## ViewOptions class

Die Rendering-Optionen.

Der ViewOptions-Typ stellt die folgenden Mitglieder bereit:

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [rotate_page](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page/#page_number-rotation) | Wendet die Drehung im Uhrzeigersinn auf eine Seite an. |
| [rotate_page_int32](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page_int32/) |  |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [page_rotations](/viewer/python-net/groupdocs.viewer.options/viewoptions/page_rotations/) | Die Seitendrehung. |
| [watermark](/viewer/python-net/groupdocs.viewer.options/viewoptions/watermark/) | Das Textwasserzeichen, das auf jeder Seite angewendet wird. |
| [archive_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/archive_options/) | Die Ansichtoptionen für Archivdateien. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [cad_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/cad_options/) | Die Ansichtoptionen für CAD-Zeichnungen. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [default_font_name](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/default_font_name/) | Die Standardschriftart für ein Dokument, die während der Darstellung verwendet wird, wenn eine erforderliche Schriftart fehlt. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [email_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/email_options/) | Die Ansichtoptionen für E-Mail-Nachrichten. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [mail_storage_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/mail_storage_options/) | Die Ansichtoptionen für Mail-Storage-Datendateien. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [outlook_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/outlook_options/) | Die Ansichtoptionen für Microsoft Outlook-Datendateien. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
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
| [web_document_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/web_document_options/) | Die Ansichtoptionen für Webdateien. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [word_processing_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/word_processing_options/) | Die Ansichtoptionen für Textverarbeitungsdateien. (geerbt von [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("sample.pptx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.render_notes = True
    viewer.view(view_options)
```

### Siehe auch
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
