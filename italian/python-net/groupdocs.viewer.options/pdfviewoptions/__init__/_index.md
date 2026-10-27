---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza un'istanza di PdfViewOptions."
type: docs
url: /it/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_file_stream}

Inizializza un'istanza di [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/).

Per l'esempio di codice, consulta la documentazione all'indirizzo https://docs.groupdocs.com/viewer/net/rendering-to-pdf/.

```python
def __init__(self, create_file_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | Il metodo che istanzia lo stream utilizzato per scrivere i dati del file di output. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `create_file_stream` è `None`. |

## __init__ {#create_file_stream-release_file_stream}

Inizializza una nuova istanza di PdfViewOptions.

Per l'esempio di codice, consulta la documentazione.

```python
def __init__(self, create_file_stream, release_file_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | Callable che restituisce uno stream `io.RawIOBase` utilizzato per scrivere i dati del file di output. |
| release_file_stream | `ReleaseFileStream` | Callable che rilascia lo stream creato dal metodo assegnato a `create_file_stream`. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `release_file_stream` è None. |

## __init__ {#file_stream_factory}

Inizializza un'istanza di PdfViewOptions.

Per l'esempio di codice, consulta la documentazione: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

```python
def __init__(self, file_stream_factory):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_stream_factory | `IFileStreamFactory` | La factory che implementa i metodi per creare e rilasciare lo stream del file di output. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Generato quando `file_stream_factory` è None. |

## __init__

Inizializza un'istanza di PdfViewOptions.

Questo costruttore inizializza un PdfViewOptions con `\"output.pdf\"` come formato del percorso file per il file di output. Il file di output sarà posizionato nella directory di lavoro corrente dell'applicazione.

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

## __init__ {#output_file_path}

Inizializza un'istanza della classe [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/).

Per l'esempio di codice, consulta la documentazione.

```python
def __init__(self, output_file_path):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| output_file_path | `str` | Il percorso per il file PDF di output. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `output_file_path` è None o vuoto. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### Vedi anche
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
