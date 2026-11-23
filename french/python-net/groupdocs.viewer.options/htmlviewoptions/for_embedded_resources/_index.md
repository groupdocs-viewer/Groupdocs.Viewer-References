---
title: "Méthode for_embedded_resources"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de HtmlViewOptions pour le rendu HTML avec des ressources intégrées."
type: docs
url: /fr/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/
is_root: false
weight: 1010
---


## for_embedded_resources {#create_page_stream}

Initialise une instance de HtmlViewOptions pour le rendu HTML avec des ressources intégrées.

Pour plus de détails, consultez la documentation.

```python
def for_embedded_resources(cls, create_page_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | La méthode qui instancie un flux utilisé pour écrire les données de page de sortie. |

**Returns:** HtmlViewOptions: New instance configured for rendering HTML with embedded resources.

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `create_page_stream` est None. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#create_page_stream-release_page_stream}

Initialise une instance de la classe [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) pour le rendu en HTML avec des ressources intégrées.

```python
def for_embedded_resources(cls, create_page_stream, release_page_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | La méthode qui instancie le flux utilisé pour écrire les données de page de sortie. |
| release_page_stream | `ReleasePageStream` | La méthode qui libère le flux créé par la méthode assignée au paramètre `create_page_stream`. |

**Returns:** HtmlViewOptions: New instance of the `HtmlViewOptions` class for rendering into HTML with embedded resources.

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `release_page_stream` est `None`. Pour l'exemple de code, consultez la documentation. |

## for_embedded_resources {#page_stream_factory}

Initialise une instance de HtmlViewOptions pour le rendu en HTML avec des ressources intégrées.

Pour l'exemple de code, consultez la documentation à l'adresse https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources.

```python
def for_embedded_resources(cls, page_stream_factory):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | La fabrique qui implémente les méthodes de création et de libération du flux de page de sortie. |

**Returns:** HtmlViewOptions: New instance of HtmlViewOptions for rendering into HTML with embedded resources.

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque page_stream_factory est None. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources

Initialise une instance de la classe [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) avec des ressources intégrées.

Pour l'exemple de code, consultez la documentation.

```python
def for_embedded_resources(cls):
    ...
```

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#file_path_format}

Initialise une instance de HtmlViewOptions pour des ressources intégrées.

Pour l'exemple de code, consultez la documentation.

```python
def for_embedded_resources(cls, file_path_format):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path_format | `str` | Le format du chemin de fichier, par ex. 'page_{0}.html'. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `file_path_format` est None ou vide. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Voir aussi
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
