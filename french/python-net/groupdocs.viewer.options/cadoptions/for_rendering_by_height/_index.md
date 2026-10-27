---
title: "méthode for_rendering_by_height"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de CadOptions pour le rendu par hauteur."
type: docs
url: /fr/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/
is_root: false
weight: 1010
---


## for_rendering_by_height {#height}

Initialise une instance de CadOptions pour le rendu par hauteur.

Pour un exemple de code, consultez la documentation.

```python
def for_rendering_by_height(cls, height):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| height | `int` | La hauteur du résultat de sortie (en pixels). |

**Returns:** CadOptions: New instance configured for rendering by height.

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `height` est inférieur ou égal à zéro. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def render_by_height():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("output_by_height.png")
        png_options.cad_options = CadOptions.for_rendering_by_height(1500)
        viewer.view(png_options)
```

### Voir aussi
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
