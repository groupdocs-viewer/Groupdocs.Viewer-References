---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza una nuova istanza di Attachment."
type: docs
url: /it/python-net/groupdocs.viewer.results/attachment/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza di [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/).

```python
def __init__(self):
    ...
```

## __init__ {#file_name-file_path}

Inizializza una nuova istanza di Attachment.

```python
def __init__(self, file_name, file_path):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_name | `str` | Nome file dell'allegato. |
| file_path | `str` | Percorso relativo dell'allegato, ad es. "folder/file.docx" o nome file quando il file si trova nella radice di un archivio, in un messaggio e‑mail o in un file dati. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `file_path` è None o vuoto. |

## __init__ {#id-file_name-file_path-size}

Inizializza una nuova istanza della classe Attachment.

```python
def __init__(self, id, file_name, file_path, size):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| id | `str` | Identificatore unico (nel contesto di un singolo file) dell'allegato. |
| file_name | `str` | Nome file dell'allegato. |
| file_path | `str` | Percorso relativo dell'allegato, ad es. `folder/file.docx` o nome file quando il file si trova nella radice di un archivio, in un messaggio e‑mail o in un file dati. |
| size | `int` | Dimensione del file di allegato in byte. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `file_path` è nullo o vuoto. |

## __init__ {#id-file_name-file_path-file_type-size}

Inizializza una nuova istanza della classe Attachment.

```python
def __init__(self, id, file_name, file_path, file_type, size):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| id | `str` | Identificatore unico (nel contesto di un singolo file) dell'allegato. |
| file_name | `str` | Nome file dell'allegato. |
| file_path | `str` | Percorso relativo dell'allegato, ad es. `folder/file.docx` o nome file quando il file si trova nella radice di un archivio, in un messaggio e‑mail o in un file dati. |
| file_type | `FileType` | Tipo di file di allegato. |
| size | `int` | Dimensione del file di allegato in byte. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `file_type` è nullo. |

### Vedi anche
* class [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/)
