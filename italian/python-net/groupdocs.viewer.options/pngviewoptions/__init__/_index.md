---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza una nuova istanza di PngViewOptions."
type: docs
url: /it/python-net/groupdocs.viewer.options/pngviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Inizializza una nuova istanza di [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Per l'esempio di codice, consulta la documentazione.

```python
def __init__(self, create_page_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Il metodo che istanzia uno stream utilizzato per scrivere i dati della pagina di output. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `create_page_stream` è None. |

## __init__ {#create_page_stream-release_page_stream}

Inizializza un'istanza della classe [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Per l'esempio di codice, consulta la documentazione.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Il metodo che istanzia uno stream utilizzato per scrivere i dati della pagina di output. |
| release_page_stream | `ReleasePageStream` | Il metodo che rilascia uno stream creato dal metodo assegnato al delegato passato al parametro `create_page_stream`. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `release_page_stream` è None. |

## __init__ {#page_stream_factory}

Inizializza una nuova istanza di [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Per ulteriori informazioni, consulta la documentazione.

```python
def __init__(self, page_stream_factory):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | La factory che implementa i metodi per creare e rilasciare lo stream della pagina di output. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `page_stream_factory` è `None`. |

## __init__

Inizializza un'istanza di PngViewOptions.

Questo costruttore crea un [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) con ``\"p_{0}.png\"`` come formato predefinito del percorso file per i file di output. I file PNG generati vengono salvati nella directory di lavoro corrente dell'applicazione.

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

## __init__ {#file_path_format}

Inizializza una nuova istanza di [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Per l'esempio di codice, consulta la documentazione.

```python
def __init__(self, file_path_format):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path_format | `str` | Il formato del percorso file, ad esempio `'page_{0}.png'`. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `file_path_format` è None o vuoto. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

### Vedi anche
* class [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
