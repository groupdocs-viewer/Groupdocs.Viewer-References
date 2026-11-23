---
title: "VisioRenderingOptions klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stelt opties voor het renderen van Visio-documenten voor."
type: docs
url: /nl/python-net/groupdocs.viewer.options/visiorenderingoptions/
is_root: false
weight: 350
---


## VisioRenderingOptions class

Stelt opties voor het renderen van Visio-documenten voor.

Zie voor details de documentatie.

Het type VisioRenderingOptions bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/__init__/) | Initialiseert een instantie van de [`VisioRenderingOptions`](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/) klasse. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [figure_width](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/figure_width/) | De breedte van de figuur; de hoogte wordt automatisch berekend. Standaardwaarde is 100. |
| [render_figures_only](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/render_figures_only/) | De eigenschap rendert alleen Visio‑figuren, niet een diagram. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_visio_shapes_only():
    # Visio‑document laden
    with Viewer("map.vsdx") as viewer:
        # Converteer het Visio‑bestand naar PDF.
        view_options = PdfViewOptions("render_visio_shapes_only/visio_shapes_only.pdf")
        # Render alleen de master‑vormen.
        view_options.visio_rendering_options.render_figures_only = True
        # Geef de breedte van de vorm op in pixels.
        view_options.visio_rendering_options.figure_width = 200
        viewer.view(view_options)

if __name__ == "__main__":
    render_visio_shapes_only()
```

### Zie ook
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
