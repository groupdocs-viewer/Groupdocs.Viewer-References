---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de la classe JpgViewOptions."
type: docs
url: /fr/python-net/groupdocs.viewer.options/jpgviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initialise une instance de la classe JpgViewOptions.

Pour l'exemple de code, consultez la documentation.

```python
def __init__(self, create_page_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | La méthode qui instancie un flux utilisé pour écrire les données de page de sortie. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `create_page_stream` est None. |

## __init__ {#create_page_stream-release_page_stream}

Initialise une instance de la classe JpgViewOptions.

Pour l'exemple de code, consultez la documentation.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Objet appelable qui instancie un flux utilisé pour écrire les données de page de sortie. |
| release_page_stream | `ReleasePageStream` | Objet appelable qui libère un flux créé par la méthode assignée au délégué passé à `create_page_stream`. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `release_page_stream` est None. |

## __init__ {#page_stream_factory}

Initialise une instance de la classe [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/).

Pour l'exemple de code, consultez la documentation à l'adresse https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg.

```python
def __init__(self, page_stream_factory):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | La fabrique qui implémente les méthodes de création et de libération du flux de page de sortie. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `page_stream_factory` est None. |

## __init__

Initialise une instance de JpgViewOptions.

Ce constructeur initialise une instance de [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) avec `\"p_{0}.jpg\"` comme format de chemin de fichier pour les fichiers de sortie. Les fichiers de sortie sont placés dans le répertoire de travail actuel de l'application.

```python
def __init__(self):
    ...
```

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = JpgViewOptions("render_excel_to_jpg/excel_to_jpg_{0}.jpg")
    view_options.width = 800
    view_options.height = 900
    viewer.view(view_options)
```

## __init__ {#file_path_format}

Initialise une nouvelle instance de [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/).

Pour l'exemple de code, consultez la documentation.

```python
def __init__(self, file_path_format):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path_format | `str` | Le format de chemin de fichier, par ex. `'page_{0}.jpg'`. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `file_path_format` est None ou vide. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

def render_to_jpg():
    # Chargez un document (p. ex., un fichier Excel)
    with Viewer("invoice.xlsx") as viewer:
        # Créez des options d'affichage JPEG avec un modèle de nom de fichier.
        view_options = JpgViewOptions("output/excel_page_{0}.jpg")
        view_options.width = 800
        view_options.height = 900
        viewer.view(view_options)

if __name__ == "__main__":
    render_to_jpg()
```

### Voir aussi
* class [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)
