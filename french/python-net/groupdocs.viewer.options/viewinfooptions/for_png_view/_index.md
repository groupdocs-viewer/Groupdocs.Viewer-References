---
title: "méthode for_png_view"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de la classe ViewInfoOptions pour récupérer les informations de vue lors du rendu en PNG."
type: docs
url: /fr/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/
is_root: false
weight: 1060
---


## for_png_view

Initialise une instance de la classe [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) pour récupérer les informations de vue lors du rendu en PNG.

```python
def for_png_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the `ViewInfoOptions` class.

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Créer des options d'informations de vue pour le format PNG
view_info_options_png = ViewInfoOptions.for_png_view()

# Charger un document et obtenir les informations de vue pour PNG
with Viewer("sample.xml") as viewer:
    result_png = viewer.get_view_info(view_info_options_png)
```

## for_png_view {#extract_text}

Initialise une instance de la classe ViewInfoOptions pour récupérer les informations de vue lors du rendu en PNG.

```python
def for_png_view(cls, extract_text):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| extract_text | `bool` | Active l'extraction de texte. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Exemple

```python
from groupdocs.viewer.options import ViewInfoOptions

# Créer des options d'informations de vue pour le format PNG avec l'extraction de texte activée
options = ViewInfoOptions.for_png_view(extractText=True)
```

### Voir aussi
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
