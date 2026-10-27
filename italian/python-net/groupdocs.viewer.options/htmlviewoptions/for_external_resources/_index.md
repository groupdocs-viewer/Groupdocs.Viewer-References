---
title: "Metodo for_external_resources"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza un'istanza della classe HtmlViewOptions per il rendering in HTML con risorse esterne."
type: docs
url: /it/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/
is_root: false
weight: 1060
---


## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url}

Inizializza un'istanza della classe [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) per il rendering in HTML con risorse esterne.

Per l'esempio di codice, consulta la documentazione.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Il metodo che istanzia lo stream utilizzato per scrivere i dati della pagina di output. |
| create_resource_stream | `CreateResourceStream` | Il metodo che rilascia lo stream creato dal metodo `create_page_stream`. |
| create_resource_url | `CreateResourceUrl` | Il metodo che crea l'URL per la risorsa HTML. |

**Returns:** New instance of the `HtmlViewOptions` class for rendering into HTML with external resources.

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `create_resource_url` è None. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("sample.docx") as viewer:
    options = HtmlViewOptions.for_external_resources(
        "page_{0}.html",
        "page_{0}/resource_{0}_{1}",
        "page_{0}/resource_{0}_{1}"
    )
    viewer.view(options)
```

## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url-release_page_stream-release_resource_stream}

Inizializza un'istanza della classe HtmlViewOptions per il rendering in HTML con risorse esterne.

Per ulteriori esempi d'uso, consultare la documentazione di GroupDocs Viewer.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url, release_page_stream, release_resource_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Il metodo che istanzia uno stream utilizzato per scrivere i dati della pagina di output. |
| create_resource_stream | `CreateResourceStream` | Il metodo che istanzia uno stream utilizzato per scrivere i dati della risorsa HTML di output. |
| create_resource_url | `CreateResourceUrl` | Il metodo che crea un URL per una risorsa HTML. |
| release_page_stream | `ReleasePageStream` | Il metodo che rilascia lo stream creato dal delegato passato a `create_page_stream`. |
| release_resource_stream | `ReleaseResourceStream` | Il metodo che rilascia lo stream creato dal delegato passato a `create_resource_stream`. |

**Returns:** HtmlViewOptions: New instance of the HtmlViewOptions class for rendering into HTML with external resources.

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `release_resource_stream` è None. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_excel_to_html_external():
    # Carica foglio di calcolo Excel
    with Viewer("invoice.xlsx") as viewer:
        # Converti il foglio di calcolo in HTML con risorse esterne.
        # {0} e {1} vengono sostituiti rispettivamente con il numero di pagina corrente e il nome della risorsa.
        view_options = HtmlViewOptions.for_external_resources(
            "render_excel_to_html_external/pdf_page_{0}.html",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}"
        )
        viewer.view(view_options)

if __name__ == "__main__":
    render_excel_to_html_external()
```

## for_external_resources {#page_stream_factory-resource_stream_factory}

Inizializza un'istanza di HtmlViewOptions per il rendering in HTML con risorse esterne.

Per ulteriori dettagli, consultare la documentazione online.

```python
def for_external_resources(cls, page_stream_factory, resource_stream_factory):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | La factory che implementa i metodi per creare e rilasciare lo stream della pagina di output. |
| resource_stream_factory | `IResourceStreamFactory` | La factory che implementa i metodi necessari per creare URL delle risorse, istanziare e rilasciare gli stream delle risorse HTML di output. |

**Returns:** HtmlViewOptions: A new HtmlViewOptions instance configured for external resources.

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `resource_stream_factory` è None. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Crea un file HTML per ogni pagina e archivia le risorse esterne separatamente.
    # {0} e {1} vengono sostituiti rispettivamente con il numero di pagina corrente e il nome della risorsa.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

## for_external_resources

Inizializza un'istanza di HtmlViewOptions configurata per generare file HTML con risorse esterne.

L'istanza utilizza le stringhe di formato fornite:
- `html_file_path_format` – file path format for the output HTML files (e.g., `"page_{0}.html"`).
- `resources_path_format` – folder path format for external resource files (e.g., `"page_{0}/resource_{0}_{1}"`).
- `resources_url_format` – URL format for HTML resources (e.g., `"page_{0}/resource_{0}_{1}"`).

I file di output vengono posizionati nella directory di lavoro corrente dell'applicazione.

```python
def for_external_resources(cls):
    ...
```

**Returns:** HtmlViewOptions: Configured options for rendering HTML with external resources.

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html_external():
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html_external()
```

## for_external_resources {#file_path_format-resource_file_path_format-resource_url_format}

Inizializza un'istanza della classe [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/).

Per l'esempio di codice, consulta la documentazione.

```python
def for_external_resources(cls, file_path_format, resource_file_path_format, resource_url_format):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path_format | `str` | Il formato del percorso file, ad es. `'page_{0}.html'`. |
| resource_file_path_format | `str` | Il formato del percorso del file risorsa, ad es. `'page_{0}/resource_{1}'`. |
| resource_url_format | `str` | Il formato dell'URL della risorsa, ad es. `'page_{0}/resource_{1}'`. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `resource_url_format` è None o vuoto. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Carica un documento e renderizza ogni pagina in un file HTML con risorse esterne.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

### Vedi anche
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
