---
title: "metodo for_embedded_resources"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza un'istanza di HtmlViewOptions per il rendering di HTML con risorse incorporate."
type: docs
url: /it/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/
is_root: false
weight: 1010
---


## for_embedded_resources {#create_page_stream}

Inizializza un'istanza di HtmlViewOptions per il rendering di HTML con risorse incorporate.

Per ulteriori dettagli, vedere la documentazione.

```python
def for_embedded_resources(cls, create_page_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Il metodo che istanzia uno stream utilizzato per scrivere i dati della pagina di output. |

**Returns:** HtmlViewOptions: New instance configured for rendering HTML with embedded resources.

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `create_page_stream` è None. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#create_page_stream-release_page_stream}

Inizializza un'istanza della classe [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) per il rendering in HTML con risorse incorporate.

```python
def for_embedded_resources(cls, create_page_stream, release_page_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Il metodo che istanzia lo stream utilizzato per scrivere i dati della pagina di output. |
| release_page_stream | `ReleasePageStream` | Il metodo che rilascia lo stream creato dal metodo assegnato al parametro `create_page_stream`. |

**Returns:** HtmlViewOptions: New instance of the `HtmlViewOptions` class for rendering into HTML with embedded resources.

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `release_page_stream` è None. Per l'esempio di codice, vedere la documentazione. |

## for_embedded_resources {#page_stream_factory}

Inizializza un'istanza di HtmlViewOptions per il rendering in HTML con risorse incorporate.

Per l'esempio di codice, vedere la documentazione all'indirizzo https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources.

```python
def for_embedded_resources(cls, page_stream_factory):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | La factory che implementa i metodi per creare e rilasciare lo stream della pagina di output. |

**Returns:** HtmlViewOptions: New instance of HtmlViewOptions for rendering into HTML with embedded resources.

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando page_stream_factory è None. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources

Inizializza un'istanza della classe [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) con risorse incorporate.

Per l'esempio di codice, consulta la documentazione.

```python
def for_embedded_resources(cls):
    ...
```

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#file_path_format}

Inizializza un'istanza di HtmlViewOptions per risorse incorporate.

Per l'esempio di codice, consulta la documentazione.

```python
def for_embedded_resources(cls, file_path_format):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path_format | `str` | Il formato del percorso file, ad es. 'page_{0}.html'. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `file_path_format` è None o vuoto. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Vedi anche
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
