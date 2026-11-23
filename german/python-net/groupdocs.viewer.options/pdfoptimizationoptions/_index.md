---
title: "PdfOptimizationOptions-Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt die PDF‑Optimierungsoptionen dar, die auf die Ausgabedatei angewendet werden."
type: docs
url: /de/python-net/groupdocs.viewer.options/pdfoptimizationoptions/
is_root: false
weight: 150
---


## PdfOptimizationOptions class

Stellt die PDF‑Optimierungsoptionen dar, die auf die Ausgabedatei angewendet werden.

Weitere Details und Codebeispiele finden Sie auf der Dokumentationsseite.

Der PdfOptimizationOptions-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/) | Initialisiert die Standardwerte der Option MaxResolution auf 300 und der Option ImageQuality auf 100. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [compress_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images/) | Die Eigenschaft ermöglicht das Komprimieren von Bildern in der Ausgabedatei PDF. |
| [convert_to_gray_scale](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/convert_to_gray_scale/) | Die Eigenschaft ermöglicht die Umwandlung der Ausgabedatei PDF in Graustufen. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/image_quality/) | Die Bildqualität in der Ausgabedatei PDF, ausgedrückt als Prozentsatz. |
| [lineriaze](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/lineriaze/) | Die Eigenschaft ermöglicht die Optimierung der Ausgabedatei PDF für die Online-Anzeige im Webbrowser. |
| [max_resolution](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/) | Die maximale Auflösung in der Ausgabedatei PDF. |
| [optimize_spreadsheets](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/optimize_spreadsheets/) | Die Eigenschaft, die die Optimierung von Tabellenkalkulationen in PDF-Dateien ermöglicht. |
| [remove_annotations](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_annotations/) | Die Eigenschaft ermöglicht das Entfernen von Anmerkungen aus der Ausgabedatei PDF. |
| [remove_form_fields](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_form_fields/) | Die Eigenschaft ermöglicht das Entfernen von Formularfeldern aus einer PDF-Datei. |
| [remove_unused_objects](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/) | Die Eigenschaft entfernt ungenutzte (verwaiste) Objekte aus einer PDF-Datei. |
| [remove_unused_streams](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/) | Die Eigenschaft entfernt ungenutzte (verwaiste) Streams aus einer PDF-Datei, die im Seitenressourcen‑Wörterbuch referenziert, aber nie im Seiteninhalt verwendet werden. Standardmäßig deaktiviert (`False`); wird sie auf `True` gesetzt, reduziert dies die Größe der Ausgabe‑PDF. |
| [resize_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/) | Die Eigenschaft ermöglicht das Festlegen der maximalen Auflösung in der Ausgabe‑PDF. |
| [subset_fonts](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/subset_fonts/) | Die Eigenschaft erzeugt Teilmengen von Schriftarten in der Ausgabe‑PDF. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

def optimize_pdf():
    with Viewer("sample.docx") as viewer:
        view_options = PdfViewOptions("output/optimized.pdf")
        view_options.pdf_optimization_options = PdfOptimizationOptions()
        # Linearisation aktivieren für schnellere Web‑Vorschau
        view_options.pdf_optimization_options.lineriaze = True
        # Anmerkungen und Formularfelder entfernen, um die Größe zu reduzieren
        view_options.pdf_optimization_options.remove_annotations = True
        view_options.pdf_optimization_options.remove_form_fields = True

        viewer.view(view_options)
```

### Siehe auch
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
