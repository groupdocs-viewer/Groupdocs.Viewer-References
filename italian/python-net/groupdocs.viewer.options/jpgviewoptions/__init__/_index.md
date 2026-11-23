---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza un'istanza della classe JpgViewOptions."
type: docs
url: /it/python-net/groupdocs.viewer.options/jpgviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Inizializza un'istanza della classe JpgViewOptions.

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

Inizializza un'istanza della classe JpgViewOptions.

Per l'esempio di codice, consulta la documentazione.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable che istanzia uno stream utilizzato per scrivere i dati della pagina di output. |
| release_page_stream | `ReleasePageStream` | Callable che rilascia uno stream creato dal metodo assegnato al delegato passato a `create_page_stream`. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `release_page_stream` è None. |

## __init__ {#page_stream_factory}

Inizializza un'istanza della classe [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/).

Per l'esempio di codice, consulta la documentazione all'indirizzo https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg.

```python
def __init__(self, page_stream_factory):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | La factory che implementa i metodi per creare e rilasciare lo stream della pagina di output. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `page_stream_factory` è None. |

## __init__

Inizializza un'istanza di JpgViewOptions.

Questo costruttore inizializza un'istanza di [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) con `"p_{0}.jpg"` come formato del percorso file per i file di output. I file di output vengono posizionati nella directory di lavoro corrente dell'applicazione.

```python
def __init__(self):
    ...
```

### Esempio

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

Inizializza una nuova istanza di [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/).

Per l'esempio di codice, consulta la documentazione.

```python
def __init__(self, file_path_format):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path_format | `str` | Il formato del percorso file, ad es. `'page_{0}.jpg'`. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `file_path_format` è None o vuoto. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

def render_to_jpg():
    # Carica un documento (ad es., un file Excel)
    with Viewer("invoice.xlsx") as viewer:
        # Crea le opzioni di visualizzazione JPEG con un modello di nome file.
        view_options = JpgViewOptions("output/excel_page_{0}.jpg")
        view_options.width = 800
        view_options.height = 900
        viewer.view(view_options)

if __name__ == "__main__":
    render_to_jpg()
```

### Vedi anche
* class [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)
