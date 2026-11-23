---
title: "Classe PdfOptions"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta le opzioni per il rendering di documenti PDF."
type: docs
url: /it/python-net/groupdocs.viewer.options/pdfoptions/
is_root: false
weight: 160
---


## PdfOptions class

Rappresenta le opzioni per il rendering di documenti PDF.

Per i dettagli, vedere la documentazione.

Il tipo PdfOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptions/__init__/) | Inizializza una nuova istanza della classe PdfOptions. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [disable_chars_grouping](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/) | La proprietà disabilita il raggruppamento dei simboli per un posizionamento preciso dei simboli durante il rendering della pagina. |
| [disable_copy_protection](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/) | La proprietà disabilita la protezione contro la copia del contenuto durante il rendering in HTML. |
| [disable_font_license_verifications](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/) | La proprietà disabilita qualsiasi restrizione di licenza per tutti i caratteri nel documento XPS/OXPS corrente. |
| [enable_font_hinting](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_font_hinting/) | La proprietà abilita il hinting dei caratteri. |
| [enable_layered_rendering](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/) | La proprietà abilita il rendering di testo e grafica nell'ordine Z del documento PDF originale durante il rendering in HTML. |
| [fixed_layout](/viewer/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/) | L'opzione layout fisso abilita il rendering di documenti PDF ed EPUB in HTML con un layout fisso. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptions/image_quality/) | La qualità dell'immagine di output per le risorse immagine durante il rendering in HTML. La qualità predefinita è `ImageQuality.LOW`. |
| [render_original_page_size](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/) | La dimensione della pagina di output è impostata per corrispondere alla dimensione della pagina del documento PDF sorgente. |
| [render_text_as_image](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/) | L'opzione abilita il rendering del testo nei file PDF come immagine nell'output HTML. |
| [wrap_images_in_svg](/viewer/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/) | La proprietà che abilita l'incapsulamento di ogni immagine nell'output HTML in un tag SVG per migliorare la qualità dell'output. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("sample.pdf") as viewer:
    view_options = PngViewOptions("output_{0}.png")
    # Abilita il hinting dei caratteri durante il rendering delle pagine PDF in immagini.
    view_options.pdf_options.enable_font_hinting = True
    viewer.view(view_options)
```

### Vedi anche
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
