---
title: "méthode for_html_view"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de ViewInfoOptions pour récupérer les informations de vue lors du rendu en HTML."
type: docs
url: /fr/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/
is_root: false
weight: 1010
---


## for_html_view

Initialise une instance de ViewInfoOptions pour récupérer les informations de vue lors du rendu en HTML.

```python
def for_html_view(cls):
    ...
```

**Returns:** ViewInfoOptions: A new ViewInfoOptions instance.

### Exemple

```python
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import ViewInfoOptions

    # Crée des options d'information de vue pour le format HTML (page unique)
    options = ViewInfoOptions.for_html_view(True)

    # Chargez un document et récupérez les informations de vue
    with Viewer("sample.xml") as viewer:
        info = viewer.get_view_info(options)
    ```

## for_html_view {#render_single_page}

Initialise une instance de ViewInfoOptions pour récupérer les informations de vue lors du rendu en HTML.

```python
def for_html_view(cls, render_single_page):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| render_single_page | `bool` | Active le rendu du contenu HTML sur une page unique. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Récupérer les informations de vue pour HTML avec une seule page
options = ViewInfoOptions.for_html_view(True)

with Viewer("sample.xml") as viewer:
    info = viewer.get_view_info(options)
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### Voir aussi
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
