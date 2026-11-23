---
title: "Classe PdfOptimizationOptions"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta le opzioni di ottimizzazione PDF da applicare al file PDF di output."
type: docs
url: /it/python-net/groupdocs.viewer.options/pdfoptimizationoptions/
is_root: false
weight: 150
---


## PdfOptimizationOptions class

Rappresenta le opzioni di ottimizzazione PDF da applicare al file PDF di output.

Per dettagli e esempi di codice, consulta la pagina della documentazione.

Il tipo PdfOptimizationOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/) | Inizializza i valori predefiniti dell'opzione MaxResolution a 300 e dell'opzione ImageQuality a 100. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [compress_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images/) | La proprietà consente la compressione delle immagini nel file PDF di output. |
| [convert_to_gray_scale](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/convert_to_gray_scale/) | La proprietà consente la conversione del file PDF di output in scala di grigi. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/image_quality/) | La qualità dell'immagine nel file PDF di output, espressa in percentuale. |
| [lineriaze](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/lineriaze/) | La proprietà consente l'ottimizzazione del file PDF di output per la visualizzazione online con un browser web. |
| [max_resolution](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/) | La risoluzione massima nel file PDF di output. |
| [optimize_spreadsheets](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/optimize_spreadsheets/) | La proprietà che consente l'ottimizzazione dei fogli di calcolo nei file PDF. |
| [remove_annotations](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_annotations/) | La proprietà consente la rimozione delle annotazioni dal file PDF di output. |
| [remove_form_fields](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_form_fields/) | La proprietà consente la rimozione dei campi modulo da un file PDF. |
| [remove_unused_objects](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/) | La proprietà rimuove gli oggetti inutilizzati (orfani) da un file PDF. |
| [remove_unused_streams](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/) | La proprietà rimuove i flussi inutilizzati (orfani) da un file PDF che sono referenziati nel dizionario delle risorse della pagina ma mai utilizzati nel contenuto della pagina. Disabilitata per impostazione predefinita (`False`); impostarla su `True` riduce la dimensione del PDF di output. |
| [resize_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/) | La proprietà consente di impostare la risoluzione massima nel file PDF di output. |
| [subset_fonts](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/subset_fonts/) | La proprietà crea sottoinsiemi di caratteri nel file PDF di output. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

def optimize_pdf():
    with Viewer("sample.docx") as viewer:
        view_options = PdfViewOptions("output/optimized.pdf")
        view_options.pdf_optimization_options = PdfOptimizationOptions()
        # Abilita la linearizzazione per una visualizzazione web più veloce
        view_options.pdf_optimization_options.lineriaze = True
        # Rimuovi annotazioni e campi modulo per ridurre le dimensioni
        view_options.pdf_optimization_options.remove_annotations = True
        view_options.pdf_optimization_options.remove_form_fields = True

        viewer.view(view_options)
```

### Vedi anche
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
