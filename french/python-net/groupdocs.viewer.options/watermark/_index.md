---
title: "Classe Watermark"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Représente un filigrane texte."
type: docs
url: /fr/python-net/groupdocs.viewer.options/watermark/
is_root: false
weight: 360
---


## Watermark class

Représente un filigrane texte.

Consultez la documentation en ligne pour plus d'informations.

Le type Watermark expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/watermark/__init__/#text) | Initialise une instance de la classe [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/). |

### Propriétés
| Propriété | Description |
| :- | :- |
| [color](/viewer/python-net/groupdocs.viewer.options/watermark/color/) | La couleur du filigrane. La valeur par défaut est `Rgb24Color.known_colors.css_level1.red`. |
| [font_name](/viewer/python-net/groupdocs.viewer.options/watermark/font_name/) | Le nom de police utilisé pour le filigrane. |
| [position](/viewer/python-net/groupdocs.viewer.options/watermark/position/) | La position du filigrane. La valeur par défaut est `Position.diagonal`. |
| [size](/viewer/python-net/groupdocs.viewer.options/watermark/size/) | La taille du filigrane. La valeur par défaut est [`Size.full_size`](/viewer/python-net/groupdocs.viewer.options/size/full_size/). |
| [text](/viewer/python-net/groupdocs.viewer.options/watermark/text/) | Le texte du filigrane. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # Charger le document
    with Viewer("sample.docx") as viewer:
        # Créer un fichier HTML.
        viewOptions = HtmlViewOptions.for_embedded_resources(
            "add_text_watermark/output-watermark.html"
        )
        # Ajouter un filigrane.
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```

### Guides
Guides de tâches qui utilisent `Watermark` :

* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)

### Voir aussi
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
