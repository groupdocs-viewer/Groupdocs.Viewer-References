---
title: "PdfOptions-Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt Optionen zum Rendern in PDF‑Dokumente dar."
type: docs
url: /de/python-net/groupdocs.viewer.options/pdfoptions/
is_root: false
weight: 160
---


## PdfOptions class

Stellt Optionen zum Rendern in PDF‑Dokumente dar.

Weitere Details finden Sie in der Dokumentation.

Der PdfOptions-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptions/__init__/) | Initialisiert eine neue Instanz der PdfOptions-Klasse. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [disable_chars_grouping](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/) | Die Eigenschaft deaktiviert die Symbolgruppierung für eine präzise Symbolpositionierung während der Seitenrenderung. |
| [disable_copy_protection](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/) | Die Eigenschaft deaktiviert den Kopierschutz für Inhalte beim Rendern zu HTML. |
| [disable_font_license_verifications](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/) | Die Eigenschaft deaktiviert alle Lizenzbeschränkungen für alle Schriftarten im aktuellen XPS/OXPS-Dokument. |
| [enable_font_hinting](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_font_hinting/) | Die Eigenschaft aktiviert Font-Hinting. |
| [enable_layered_rendering](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/) | Die Eigenschaft aktiviert das Rendern von Text und Grafiken in der ursprünglichen Z-Reihenfolge des PDF-Dokuments beim Rendern zu HTML. |
| [fixed_layout](/viewer/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/) | Die Option für festes Layout ermöglicht das Rendern von PDF- und EPUB-Dokumenten zu HTML mit einem festen Layout. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptions/image_quality/) | Die Ausgabe‑Bildqualität für Bildressourcen beim Rendern zu HTML. Die Standardqualität ist `ImageQuality.LOW`. |
| [render_original_page_size](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/) | Die Ausgabe‑Seitengröße wird so eingestellt, dass sie der Seitengröße des Quell‑PDF‑Dokuments entspricht. |
| [render_text_as_image](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/) | Die Option ermöglicht das Rendern von Texten in PDF‑Dateien als Bild in der HTML‑Ausgabe. |
| [wrap_images_in_svg](/viewer/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/) | Die Eigenschaft, die das Einbetten jedes Bildes im HTML‑Ausgabedokument in ein SVG‑Tag ermöglicht, um die Ausgabequalität zu verbessern. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("sample.pdf") as viewer:
    view_options = PngViewOptions("output_{0}.png")
    # Schrift‑Hinting beim Rendern von PDF‑Seiten zu Bildern aktivieren.
    view_options.pdf_options.enable_font_hinting = True
    viewer.view(view_options)
```

### Siehe auch
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
