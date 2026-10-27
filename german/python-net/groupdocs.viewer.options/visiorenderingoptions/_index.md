---
title: "VisioRenderingOptions‑Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt Optionen für das Rendern von Visio-Dokumenten dar."
type: docs
url: /de/python-net/groupdocs.viewer.options/visiorenderingoptions/
is_root: false
weight: 350
---


## VisioRenderingOptions class

Stellt Optionen für das Rendern von Visio-Dokumenten dar.

Weitere Details finden Sie in der Dokumentation.

Der Typ VisioRenderingOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/__init__/) | Initialisiert eine Instanz der Klasse [`VisioRenderingOptions`](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/). |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [figure_width](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/figure_width/) | Die Breite der Figur; die Höhe wird automatisch berechnet. Der Standardwert ist 100. |
| [render_figures_only](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/render_figures_only/) | Die Eigenschaft rendert nur Visio‑Figuren, nicht ein Diagramm. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_visio_shapes_only():
    # Visio‑Dokument laden
    with Viewer("map.vsdx") as viewer:
        # Die Visio‑Datei in PDF konvertieren.
        view_options = PdfViewOptions("render_visio_shapes_only/visio_shapes_only.pdf")
        # Nur die Master‑Formen rendern.
        view_options.visio_rendering_options.render_figures_only = True
        # Formbreite in Pixeln angeben.
        view_options.visio_rendering_options.figure_width = 200
        viewer.view(view_options)

if __name__ == "__main__":
    render_visio_shapes_only()
```

### Siehe auch
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
