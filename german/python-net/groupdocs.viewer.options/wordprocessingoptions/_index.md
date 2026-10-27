---
title: "WordProcessingOptions Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Enthält Optionen für das Rendern von Word-Dokumenten."
type: docs
url: /de/python-net/groupdocs.viewer.options/wordprocessingoptions/
is_root: false
weight: 380
---


## WordProcessingOptions class

Enthält Optionen für das Rendern von Word-Dokumenten.

Weitere Details finden Sie in der Dokumentation unter https://docs.groupdocs.com/viewer/net/render-word-documents/.

Der Typ WordProcessingOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/) | Initialisiert Optionen für die Darstellung von Textverarbeitungsdokumenten. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [clone](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/clone/) | Erstellt und gibt eine vollständige tiefe Kopie dieser Optionen zurück. |
| [equals](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals/#options) | Bestimmt, ob die angegebene [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/) Instanz dieser Instanz entspricht. |
| [equals_word_processing_options](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals_word_processing_options/) |  |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/bottom_margin/) | Der untere Rand einer Seite. |
| [enable_open_type_features](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/enable_open_type_features/) | Die Option aktiviert Kerning und andere OpenType‑Funktionen beim Rendern von Arabisch, Hebräisch, indisch‑lateinbasierten oder kyrillisch‑basierten Schriften. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/) | Die horizontale Auflösung für erzeugte Bilder in Punkten pro Zoll. Diese Option wird nur beim Rendern von WordProcessing‑Dokumenten in PNG‑ oder JPEG‑Formate verwendet. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/left_margin/) | Der linke Rand einer Seite. |
| [page_number_location](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_number_location/) | Der Ort der Seitennummerierung für das geladene WordProcessing‑Dokument, der die Seitennummerierung zwangsweise anwenden kann; standardmäßig ist es `WordsPageNumberLocation.not_apply`, wodurch das Dokument unverändert bleibt. |
| [page_size](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/) | Die Größe der Ausgabeseite. |
| [render_tracked_changes](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/render_tracked_changes/) | Die Eigenschaft aktiviert das Rendern von nachverfolgten Änderungen (Revisionen). |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/right_margin/) | Der rechte Rand einer Seite. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/top_margin/) | Der obere Rand einer Seite in Punkten. |
| [unlink_table_of_contents](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/unlink_table_of_contents/) | Die Option deaktiviert die Navigation vom Inhaltsverzeichnis, wenn sie für HTML‑ oder PDF‑Rendern auf True gesetzt ist. |
| [update_fields](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/update_fields/) | Die Eigenschaft bestimmt, ob Felder bestimmter Typen vor dem Speichern des WordProcessing‑Dokuments in HTML-, PDF-, PNG- oder JPEG‑Formate aktualisiert werden. Der Standardwert ist True, was bedeutet, dass Felder aktualisiert werden. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/) | Die vertikale Auflösung für erzeugte Bilder in Punkten pro Zoll, die nur beim Rendern von WordProcessing‑Dokumenten in PNG‑ oder JPEG‑Formate verwendet wird. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("with_tracked_changes.docx") as viewer:
    view_options = PdfViewOptions("output/word_with_tracked_changes.pdf")
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### Siehe auch
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
