---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza una nuova istanza della classe Viewer."
type: docs
url: /it/python-net/groupdocs.viewer/viewer/__init__/
is_root: false
weight: 10
---


## __init__ {#get_file_stream}

Inizializza una nuova istanza della classe [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Per saperne di più

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Il metodo che restituisce un flusso leggibile. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Generato quando `get_file_stream` è None. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options}

Inizializza una nuova istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

```python
def __init__(self, get_file_stream, get_load_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Il metodo che restituisce un flusso leggibile. |
| get_load_options | `Func[LoadOptions]` | Il metodo che restituisce le opzioni di caricamento del documento. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Lanciato quando `get_load_options` è None. |
| `Remarks` | - Maggiori informazioni sui tipi di file supportati da GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats - Maggiori informazioni sulle funzionalità di GroupDocs.Viewer per .NET: https://docs.groupdocs.com/display/viewernet/Developer+Guide - Maggiori informazioni sul caricamento di documenti crittografati e sulla visualizzazione di file da archivi di terze parti con GroupDocs.Viewer per .NET: https://docs.groupdocs.com/display/viewernet/Loading |

### Esempio

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

Inizializza una nuova istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream, settings):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Il metodo che restituisce un flusso leggibile. |
| settings | `ViewerSettings` | Le impostazioni del Viewer. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `settings` è None. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options-settings}

Inizializza una nuova istanza di Viewer.

Maggiori informazioni:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, get_file_stream, get_load_options, settings):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Callable che restituisce un flusso leggibile. |
| get_load_options | `Func[LoadOptions]` | Callable che restituisce le opzioni di caricamento del documento. |
| settings | `ViewerSettings` | Impostazioni del Viewer. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `settings` è None. |

### Esempio

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

Inizializza una nuova istanza della classe [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | `io.RawIOBase` | Il flusso del file. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Generato quando `stream` è None. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-leave_open}

Inizializza una nuova istanza di Viewer.

Per saperne di più:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, leave_open):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | `io.RawIOBase` | Il flusso del file. |
| leave_open | `bool` | True per lasciare il flusso aperto dopo che l'oggetto Viewer è stato eliminato; altrimenti, False. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `stream` è None. |

### Esempio

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

Inizializza una nuova istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Per saperne di più:

- More about file types supported by GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats>
- More about GroupDocs.Viewer for .NET features: <https://docs.groupdocs.com/display/viewernet/Developer+Guide>
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: <https://docs.groupdocs.com/display/viewernet/Loading>

```python
def __init__(self, stream, load_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | `io.RawIOBase` | Il flusso del file. |
| load_options | `LoadOptions` | Le opzioni di caricamento del documento. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `load_options` è None. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-leave_open}

Inizializza una nuova istanza di Viewer.

```python
def __init__(self, stream, load_options, leave_open):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | `io.RawIOBase` | Il flusso del file. |
| load_options | `LoadOptions` | Le opzioni di caricamento del documento. |
| leave_open | `bool` | True per lasciare il flusso aperto dopo che l'oggetto Viewer è stato eliminato; altrimenti, False. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `load_options` è None. |
| `Remarks` | - Maggiori informazioni sui tipi di file supportati da GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats> - Maggiori informazioni sulle funzionalità di GroupDocs.Viewer per .NET: <https://docs.groupdocs.com/display/viewernet/Developer+Guide> - Maggiori informazioni su come caricare documenti crittografati e visualizzare file da archivi di terze parti con GroupDocs.Viewer per .NET: <https://docs.groupdocs.com/display/viewernet/Loading> |

### Esempio

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

Inizializza una nuova istanza di Viewer.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, settings):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | `io.RawIOBase` | Il flusso del file. |
| settings | `ViewerSettings` | Le impostazioni del Viewer. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `settings` è None. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings-leave_open}

Inizializza una nuova istanza di Viewer.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

```python
def __init__(self, stream, settings, leave_open):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | `io.RawIOBase` | Il flusso del file. |
| settings | `ViewerSettings` | Le impostazioni del Viewer. |
| leave_open | `bool` | True per lasciare il flusso aperto dopo che l'oggetto Viewer è stato eliminato; altrimenti, False. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `settings` è None. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-settings}

Inizializza una nuova istanza di Viewer.

Il costruttore richiede un flusso di file (`io.RawIOBase`) e accetta facoltativamente le opzioni di caricamento del documento e le impostazioni del Viewer.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | `io.RawIOBase` | Il flusso del file. |
| load_options | `LoadOptions` | Le opzioni di caricamento del documento. |
| settings | `ViewerSettings` | Le impostazioni del Viewer. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `stream`, `load_options` o `settings` è None. |

### Esempio

```python
from groupdocs.viewer import Viewer

# Apri un file come flusso binario e crea un Viewer
with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream)
    # Usa il viewer, ad esempio, rendi in HTML
    # ...
```

## __init__ {#stream-load_options-settings-leave_open}

Inizializza una nuova istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Per saperne di più:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings, leave_open):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | `io.RawIOBase` | Il flusso del file. |
| load_options | `LoadOptions` | Le opzioni di caricamento del documento. |
| settings | `ViewerSettings` | Le impostazioni del Viewer. |
| leave_open | `bool` | True per lasciare il flusso aperto dopo che l'oggetto Viewer è stato eliminato; altrimenti, False. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `settings` è None. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path}

Inizializza una nuova istanza della classe [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso del file da renderizzare. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `file_path` è `None` o vuoto. |

### Esempio

```python
from groupdocs.viewer import Viewer

# Inizializza il viewer con un percorso del documento
with Viewer("./sample.docx") as viewer:
    # Il viewer è pronto per renderizzare il documento
    pass
```

## __init__ {#file_path-settings}

Inizializza una nuova istanza della classe [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Per saperne di più:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso del file da renderizzare. |
| settings | `ViewerSettings` | Le impostazioni del Viewer. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `settings` è null. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options}

Inizializza una nuova istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: Document formats supported by GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: Developer Guide (https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: How to load and view document with GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso del file da renderizzare. |
| load_options | `LoadOptions` | Le opzioni utilizzate per aprire il file. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `load_options` è None. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options-settings}

Inizializza una nuova istanza di Viewer.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso del file da renderizzare. |
| load_options | `LoadOptions` | Le opzioni utilizzate per aprire il file. |
| settings | `ViewerSettings` | Le impostazioni del Viewer. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `settings` è None. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Vedi anche
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
