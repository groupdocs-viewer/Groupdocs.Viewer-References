---
title: "méthode for_rendering_by_width"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de la classe CadOptions pour le rendu par largeur."
type: docs
url: /fr/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/
is_root: false
weight: 1030
---


## for_rendering_by_width {#width}

Initialise une instance de la classe [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) pour le rendu par largeur.

```python
def for_rendering_by_width(cls, width):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| width | `int` | La largeur du résultat de sortie (en pixels). |

**Returns:** CadOptions: New instance of the `CadOptions` class for rendering by width.

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `width` est inférieur ou égal à zéro. |

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
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True
        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### Voir aussi
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
