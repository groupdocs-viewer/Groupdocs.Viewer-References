---
title: "VisioRenderingOptions-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Representerar alternativ för rendering av Visio-dokument."
type: docs
url: /sv/python-net/groupdocs.viewer.options/visiorenderingoptions/
is_root: false
weight: 350
---


## VisioRenderingOptions class

Representerar alternativ för rendering av Visio-dokument.

För detaljer, se dokumentationen.

VisioRenderingOptions-typen exponerar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/__init__/) | Initierar en instans av [`VisioRenderingOptions`](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/) klassen. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [figure_width](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/figure_width/) | Figurens bredd; höjden beräknas automatiskt. Standardvärdet är 100. |
| [render_figures_only](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/render_figures_only/) | Egenskapen renderar endast Visio-figurer, inte ett diagram. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_visio_shapes_only():
    # Läs in Visio-dokument
    with Viewer("map.vsdx") as viewer:
        # Konvertera Visio-filen till PDF.
        view_options = PdfViewOptions("render_visio_shapes_only/visio_shapes_only.pdf")
        # Rendera endast huvudformerna.
        view_options.visio_rendering_options.render_figures_only = True
        # Ange formens bredd i pixlar.
        view_options.visio_rendering_options.figure_width = 200
        viewer.view(view_options)

if __name__ == "__main__":
    render_visio_shapes_only()
```

### Se även
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
