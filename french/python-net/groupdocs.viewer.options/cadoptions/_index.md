---
title: "Classe CadOptions"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Les options pour le rendu des dessins CAD."
type: docs
url: /fr/python-net/groupdocs.viewer.options/cadoptions/
is_root: false
weight: 30
---


## CadOptions class

Les options pour le rendu des dessins CAD.

Pour plus d'informations et d'exemples de code, consultez la documentation Render CAD drawings and models as HTML, PDF, and image files et Specify rendering options for CAD files.

Le type CadOptions expose les membres suivants :

### Méthodes
| Méthode | Description |
| :- | :- |
| [for_rendering_by_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/#height) | Initialise une instance de CadOptions pour le rendu par hauteur. |
| [for_rendering_by_scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/#scale_factor) | Initialise une instance de CadOptions pour le rendu par facteur d'échelle. |
| [for_rendering_by_width](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/#width) | Initialise une instance de la classe [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) pour le rendu par largeur. |
| [for_rendering_by_width_and_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/#width-height) | Initialise une instance de la classe CadOptions pour le rendu par largeur et hauteur. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [background_color](/viewer/python-net/groupdocs.viewer.options/cadoptions/background_color/) | La couleur d'arrière-plan de l'image. |
| [enable_performance_conversion_mode](/viewer/python-net/groupdocs.viewer.options/cadoptions/enable_performance_conversion_mode/) | Le drapeau qui active un mode de conversion orienté performance pour tous les formats CAD, où le définir sur True accélère la conversion au prix d'une qualité de sortie réduite ; la valeur par défaut est False pour une qualité maximale. |
| [height](/viewer/python-net/groupdocs.viewer.options/cadoptions/height/) | La hauteur du résultat de sortie (en pixels). |
| [layers](/viewer/python-net/groupdocs.viewer.options/cadoptions/layers/) | Les calques de dessin CAD à rendre. |
| [layout_name](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) | Le nom de la disposition spécifique à rendre. Le nom de la disposition est sensible à la casse. |
| [pc3_file](/viewer/python-net/groupdocs.viewer.options/cadoptions/pc3_file/) | Le fichier de configuration du traceur PC3. |
| [render_layouts](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) | Le drapeau indiquant si les dispositions du document CAD doivent être rendues. |
| [scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/scale_factor/) | Le facteur d'échelle. Une valeur supérieure à 1 agrandit le résultat de sortie ; une valeur comprise entre 0 et 1 réduit le résultat de sortie. |
| [tiles](/viewer/python-net/groupdocs.viewer.options/cadoptions/tiles/) | Les régions de dessin à rendre. |
| [width](/viewer/python-net/groupdocs.viewer.options/cadoptions/width/) | La largeur du résultat de sortie (en pixels). |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # Charger le fichier CAD
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        # Rendu par largeur et activer le mode performance
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True

        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### Voir aussi
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
