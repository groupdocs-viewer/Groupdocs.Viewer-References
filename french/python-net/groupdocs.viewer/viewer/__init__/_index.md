---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une nouvelle instance de la classe Viewer."
type: docs
url: /fr/python-net/groupdocs.viewer/viewer/__init__/
is_root: false
weight: 10
---


## __init__ {#get_file_stream}

Initialise une nouvelle instance de la classe [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

En savoir plus

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | La méthode qui renvoie un flux lisible. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Déclenchée lorsque `get_file_stream` est None. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options}

Initialise une nouvelle instance de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

```python
def __init__(self, get_file_stream, get_load_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | La méthode qui renvoie un flux lisible. |
| get_load_options | `Func[LoadOptions]` | La méthode qui renvoie les options de chargement du document. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lancée lorsque `get_load_options` est None. |
| `Remarks` | - Plus d'informations sur les types de fichiers pris en charge par GroupDocs.Viewer : https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats - Plus d'informations sur les fonctionnalités de GroupDocs.Viewer pour .NET : https://docs.groupdocs.com/display/viewernet/Developer+Guide - Plus d'informations sur le chargement de documents chiffrés et la visualisation de fichiers depuis des stockages tiers avec GroupDocs.Viewer pour .NET : https://docs.groupdocs.com/display/viewernet/Loading |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#get_file_stream-settings}

Initialise une nouvelle instance de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream, settings):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | La méthode qui renvoie un flux lisible. |
| settings | `ViewerSettings` | Les paramètres du Viewer. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `settings` est None. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options-settings}

Initialise une nouvelle instance de Viewer.

Plus d'informations :

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, get_file_stream, get_load_options, settings):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Objet appelable qui renvoie un flux lisible. |
| get_load_options | `Func[LoadOptions]` | Objet appelable qui renvoie les options de chargement du document. |
| settings | `ViewerSettings` | Paramètres du Viewer. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `settings` est None. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#stream}

Initialise une nouvelle instance de la classe [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | Le flux de fichier. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Déclenchée lorsque `stream` est None. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-leave_open}

Initialise une nouvelle instance de Viewer.

En savoir plus:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, leave_open):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | Le flux de fichier. |
| leave_open | `bool` | Vrai pour laisser le flux ouvert après la libération de l'objet Viewer ; sinon, Faux. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `stream` est None. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML — the hello‑world example."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#stream-load_options}

Initialise une nouvelle instance de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

En savoir plus:

- More about file types supported by GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats>
- More about GroupDocs.Viewer for .NET features: <https://docs.groupdocs.com/display/viewernet/Developer+Guide>
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: <https://docs.groupdocs.com/display/viewernet/Loading>

```python
def __init__(self, stream, load_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | Le flux de fichier. |
| load_options | `LoadOptions` | Les options de chargement du document. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `load_options` est None. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-leave_open}

Initialise une nouvelle instance de Viewer.

```python
def __init__(self, stream, load_options, leave_open):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | Le flux de fichier. |
| load_options | `LoadOptions` | Les options de chargement du document. |
| leave_open | `bool` | Vrai pour laisser le flux ouvert après la libération de l'objet Viewer ; sinon, Faux. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `load_options` est None. |
| `Remarks` | - Plus d'informations sur les types de fichiers pris en charge par GroupDocs.Viewer : <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats> - Plus d'informations sur les fonctionnalités de GroupDocs.Viewer pour .NET : <https://docs.groupdocs.com/display/viewernet/Developer+Guide> - Plus d'informations sur le chargement de documents chiffrés et la visualisation de fichiers à partir de stockages tiers avec GroupDocs.Viewer pour .NET : <https://docs.groupdocs.com/display/viewernet/Loading> |

### Exemple

```python
import io
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream, loadOptions=None, leaveOpen=False)
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings}

Initialise une nouvelle instance de Viewer.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, settings):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | Le flux de fichier. |
| settings | `ViewerSettings` | Les paramètres du Viewer. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `settings` est None. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings-leave_open}

Initialise une nouvelle instance de Viewer.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

```python
def __init__(self, stream, settings, leave_open):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | Le flux de fichier. |
| settings | `ViewerSettings` | Les paramètres du Viewer. |
| leave_open | `bool` | Vrai pour laisser le flux ouvert après la libération de l'objet Viewer ; sinon, Faux. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `settings` est None. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-settings}

Initialise une nouvelle instance de Viewer.

Le constructeur nécessite un flux de fichier (`io.RawIOBase`) et accepte éventuellement les options de chargement du document ainsi que les paramètres du Viewer.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | Le flux de fichier. |
| load_options | `LoadOptions` | Les options de chargement du document. |
| settings | `ViewerSettings` | Les paramètres du Viewer. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `stream`, `load_options` ou `settings` est None. |

### Exemple

```python
from groupdocs.viewer import Viewer

# Ouvrez un fichier en tant que flux binaire et créez un Viewer
with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream)
    # Utilisez le viewer, p. ex., pour rendre en HTML
    # ...
```

## __init__ {#stream-load_options-settings-leave_open}

Initialise une nouvelle instance de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

En savoir plus:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings, leave_open):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | Le flux de fichier. |
| load_options | `LoadOptions` | Les options de chargement du document. |
| settings | `ViewerSettings` | Les paramètres du Viewer. |
| leave_open | `bool` | Vrai pour laisser le flux ouvert après la libération de l'objet Viewer ; sinon, Faux. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `settings` est None. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path}

Initialise une nouvelle instance de la classe [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier à rendre. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `file_path` est `None` ou vide. |

### Exemple

```python
from groupdocs.viewer import Viewer

# Initialisez le viewer avec le chemin d'un document
with Viewer("./sample.docx") as viewer:
    # Le viewer est prêt à rendre le document
    pass
```

## __init__ {#file_path-settings}

Initialise une nouvelle instance de la classe [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

En savoir plus:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier à rendre. |
| settings | `ViewerSettings` | Les paramètres du Viewer. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `settings` est null. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options}

Initialise une nouvelle instance de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: Document formats supported by GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: Developer Guide (https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: How to load and view document with GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier à rendre. |
| load_options | `LoadOptions` | Les options utilisées pour ouvrir le fichier. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `load_options` est None. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options-settings}

Initialise une nouvelle instance de Viewer.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier à rendre. |
| load_options | `LoadOptions` | Les options utilisées pour ouvrir le fichier. |
| settings | `ViewerSettings` | Les paramètres du Viewer. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `settings` est None. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Voir aussi
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
