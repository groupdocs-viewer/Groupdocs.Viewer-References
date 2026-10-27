---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de PdfViewOptions."
type: docs
url: /fr/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_file_stream}

Initialise une instance de [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/).

Pour l'exemple de code, consultez la documentation à l'adresse https://docs.groupdocs.com/viewer/net/rendering-to-pdf/.

```python
def __init__(self, create_file_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | La méthode qui instancie le flux utilisé pour écrire les données du fichier de sortie. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `create_file_stream` est `None`. |

## __init__ {#create_file_stream-release_file_stream}

Initialise une nouvelle instance de PdfViewOptions.

Pour l'exemple de code, consultez la documentation.

```python
def __init__(self, create_file_stream, release_file_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | Callable qui renvoie un flux `io.RawIOBase` utilisé pour écrire les données du fichier de sortie. |
| release_file_stream | `ReleaseFileStream` | Callable qui libère le flux créé par la méthode assignée à `create_file_stream`. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `release_file_stream` est None. |

## __init__ {#file_stream_factory}

Initialise une instance de PdfViewOptions.

Pour l'exemple de code, consultez la documentation : https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

```python
def __init__(self, file_stream_factory):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_stream_factory | `IFileStreamFactory` | La fabrique qui implémente les méthodes de création et de libération du flux de fichier de sortie. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Levée lorsque `file_stream_factory` est None. |

## __init__

Initialise une instance de PdfViewOptions.

Ce constructeur initialise un PdfViewOptions avec `"output.pdf"` comme format de chemin de fichier pour le fichier de sortie. Le fichier de sortie sera placé dans le répertoire de travail actuel de l'application.

```python
def __init__(self):
    ...
```

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

## __init__ {#output_file_path}

Initialise une instance de la classe [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/).

Pour l'exemple de code, consultez la documentation.

```python
def __init__(self, output_file_path):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| output_file_path | `str` | Le chemin du fichier PDF de sortie. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `output_file_path` est None ou vide. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### Voir aussi
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
