---
title: "classe VisioRenderingOptions"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Représente les options de rendu des documents Visio."
type: docs
url: /fr/python-net/groupdocs.viewer.options/visiorenderingoptions/
is_root: false
weight: 350
---


## VisioRenderingOptions class

Représente les options de rendu des documents Visio.

Pour plus de détails, consultez la documentation.

Le type VisioRenderingOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/__init__/) | Initialise une instance de la classe [`VisioRenderingOptions`](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/). |

### Propriétés
| Propriété | Description |
| :- | :- |
| [figure_width](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/figure_width/) | La largeur de la figure ; la hauteur est calculée automatiquement. La valeur par défaut est 100. |
| [render_figures_only](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/render_figures_only/) | La propriété rend uniquement les figures Visio, pas un diagramme. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_visio_shapes_only():
    # Charger le document Visio
    with Viewer("map.vsdx") as viewer:
        # Convertir le fichier Visio en PDF.
        view_options = PdfViewOptions("render_visio_shapes_only/visio_shapes_only.pdf")
        # Rendre uniquement les formes maîtres.
        view_options.visio_rendering_options.render_figures_only = True
        # Spécifier la largeur de la forme en pixels.
        view_options.visio_rendering_options.figure_width = 200
        viewer.view(view_options)

if __name__ == "__main__":
    render_visio_shapes_only()
```

### Voir aussi
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
