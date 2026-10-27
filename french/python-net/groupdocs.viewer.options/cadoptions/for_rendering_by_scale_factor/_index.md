---
title: "méthode for_rendering_by_scale_factor"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de CadOptions pour le rendu par facteur d'échelle."
type: docs
url: /fr/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/
is_root: false
weight: 1020
---


## for_rendering_by_scale_factor {#scale_factor}

Initialise une instance de CadOptions pour le rendu par facteur d'échelle.

Pour un exemple de code, consultez la documentation.

```python
def for_rendering_by_scale_factor(cls, scale_factor):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| scale_factor | `float` | Une valeur supérieure à 1 agrandit le résultat de sortie ; une valeur comprise entre 0 et 1 réduit le résultat de sortie. |

**Returns:** CadOptions: New instance of the CadOptions class for rendering by scale factor.

| Exceptions | Description |
| :- | :- |
| `ValueError` | Levée lorsque `scale_factor` est inférieur ou égal à zéro. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def set_image_size():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("set_image_size/image_with_size_limits.pdf")
        png_options.cad_options = CadOptions.for_rendering_by_scale_factor(0.5)
        viewer.view(png_options)

if __name__ == "__main__":
    set_image_size()
```

### Voir aussi
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
