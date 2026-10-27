---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une nouvelle instance de PngViewOptions."
type: docs
url: /fr/python-net/groupdocs.viewer.options/pngviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initialise une nouvelle instance de [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

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

Initialise une instance de la classe [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Pour l'exemple de code, consultez la documentation.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | La méthode qui instancie un flux utilisé pour écrire les données de page de sortie. |
| release_page_stream | `ReleasePageStream` | La méthode qui libère un flux créé par la méthode assignée au délégué passé au paramètre `create_page_stream`. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `release_page_stream` est None. |

## __init__ {#page_stream_factory}

Initialise une nouvelle instance de [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Pour plus d'informations, voir la documentation.

```python
def __init__(self, page_stream_factory):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | La fabrique qui implémente les méthodes de création et de libération du flux de page de sortie. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `page_stream_factory` est `None`. |

## __init__

Initialise une instance de PngViewOptions.

Ce constructeur crée un [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) avec ``\"p_{0}.png\"`` comme format de chemin de fichier par défaut pour les fichiers de sortie. Les fichiers PNG générés sont enregistrés dans le répertoire de travail actuel de l'application.

```python
def __init__(self):
    ...
```

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

## __init__ {#file_path_format}

Initialise une nouvelle instance de [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Pour l'exemple de code, consultez la documentation.

```python
def __init__(self, file_path_format):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path_format | `str` | Le format du chemin de fichier, par ex. `'page_{0}.png'`. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `file_path_format` est None ou vide. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

### Voir aussi
* class [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
