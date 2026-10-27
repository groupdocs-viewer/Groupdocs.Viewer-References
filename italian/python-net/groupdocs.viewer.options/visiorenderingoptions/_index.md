---
title: "VisioRenderingOptions classe"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta le opzioni per il rendering dei documenti Visio."
type: docs
url: /it/python-net/groupdocs.viewer.options/visiorenderingoptions/
is_root: false
weight: 350
---


## VisioRenderingOptions class

Rappresenta le opzioni per il rendering dei documenti Visio.

Per i dettagli, vedere la documentazione.

Il tipo VisioRenderingOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/__init__/) | Inizializza un'istanza della classe [`VisioRenderingOptions`](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/). |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [figure_width](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/figure_width/) | La larghezza della figura; l'altezza è calcolata automaticamente. Il valore predefinito è 100. |
| [render_figures_only](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/render_figures_only/) | La proprietà rende solo figure Visio, non un diagramma. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_visio_shapes_only():
    # Carica documento Visio
    with Viewer("map.vsdx") as viewer:
        # Converti il file Visio in PDF.
        view_options = PdfViewOptions("render_visio_shapes_only/visio_shapes_only.pdf")
        # Renderizza solo le master shapes.
        view_options.visio_rendering_options.render_figures_only = True
        # Specifica la larghezza della forma in pixel.
        view_options.visio_rendering_options.figure_width = 200
        viewer.view(view_options)

if __name__ == "__main__":
    render_visio_shapes_only()
```

### Vedi anche
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
