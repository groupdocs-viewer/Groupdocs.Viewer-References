---
title: "for_external_resources-methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een instantie van de HtmlViewOptions‑klasse voor het renderen naar HTML met externe bronnen."
type: docs
url: /nl/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/
is_root: false
weight: 1060
---


## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url}

Initialiseert een instantie van de [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)‑klasse voor het renderen naar HTML met externe bronnen.

Zie voor het codevoorbeeld de documentatie.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | De methode die de stream instantieert die wordt gebruikt om uitvoerpagina‑gegevens te schrijven. |
| create_resource_stream | `CreateResourceStream` | De methode die de stream vrijgeeft die is gemaakt door de `create_page_stream`-methode. |
| create_resource_url | `CreateResourceUrl` | De methode die een URL maakt voor een HTML‑resource. |

**Returns:** New instance of the `HtmlViewOptions` class for rendering into HTML with external resources.

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `create_resource_url` None is. |

### Voorbeeld

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

Initialiseert een instantie van de HtmlViewOptions‑klasse voor het renderen naar HTML met externe bronnen.

Voor extra gebruiksvoorbeelden, zie de documentatie van GroupDocs Viewer.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url, release_page_stream, release_resource_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | De methode die een stream instantieert die wordt gebruikt om uitvoer‑pagedata te schrijven. |
| create_resource_stream | `CreateResourceStream` | De methode die een stream instantieert die wordt gebruikt om uitvoer‑HTML‑resource‑gegevens te schrijven. |
| create_resource_url | `CreateResourceUrl` | De methode die een URL maakt voor een HTML‑resource. |
| release_page_stream | `ReleasePageStream` | De methode die de stream vrijgeeft die is gemaakt door de delegate die aan `create_page_stream` is doorgegeven. |
| release_resource_stream | `ReleaseResourceStream` | De methode die de stream vrijgeeft die is gemaakt door de delegate die aan `create_resource_stream` is doorgegeven. |

**Returns:** HtmlViewOptions: New instance of the HtmlViewOptions class for rendering into HTML with external resources.

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `release_resource_stream` None is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_excel_to_html_external():
    # Excel‑werkblad laden
    with Viewer("invoice.xlsx") as viewer:
        # Converteer het werkblad naar HTML met externe resources.
        # {0} en {1} worden respectievelijk vervangen door het huidige paginanummer en de resource‑naam.
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

Initialiseert een HtmlViewOptions‑instantie voor het renderen naar HTML met externe bronnen.

Voor meer details, zie de online documentatie.

```python
def for_external_resources(cls, page_stream_factory, resource_stream_factory):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | De fabriek die methoden implementeert voor het maken en vrijgeven van de uitvoer‑pagina‑stream. |
| resource_stream_factory | `IResourceStreamFactory` | De fabriek die de benodigde methoden implementeert voor het maken van resource‑URL's, het instantieren en vrijgeven van uitvoer‑HTML‑resource‑streams. |

**Returns:** HtmlViewOptions: A new HtmlViewOptions instance configured for external resources.

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `resource_stream_factory` None is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Maak een HTML-bestand voor elke pagina en sla externe bronnen apart op.
    # {0} en {1} worden respectievelijk vervangen door het huidige paginanummer en de resource‑naam.
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

Initialiseert een HtmlViewOptions‑instantie geconfigureerd om HTML‑bestanden met externe bronnen te genereren.

De instantie gebruikt de opgegeven opmaak-strings:
- `html_file_path_format` – file path format for the output HTML files (e.g., `"page_{0}.html"`).
- `resources_path_format` – folder path format for external resource files (e.g., `"page_{0}/resource_{0}_{1}"`).
- `resources_url_format` – URL format for HTML resources (e.g., `"page_{0}/resource_{0}_{1}"`).

De uitvoerbestanden worden geplaatst in de huidige werkmap van de applicatie.

```python
def for_external_resources(cls):
    ...
```

**Returns:** HtmlViewOptions: Configured options for rendering HTML with external resources.

### Voorbeeld

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

Initialiseert een instantie van de [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)‑klasse.

Zie voor het codevoorbeeld de documentatie.

```python
def for_external_resources(cls, file_path_format, resource_file_path_format, resource_url_format):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path_format | `str` | Het bestands-padformaat, bijv. `'page_{0}.html'`. |
| resource_file_path_format | `str` | Het resource-bestandspadformaat, bijv. `'page_{0}/resource_{1}'`. |
| resource_url_format | `str` | Het resource-URL-formaat, bijv. `'page_{0}/resource_{1}'`. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `resource_url_format` None of leeg is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Laad een document en render elke pagina naar een HTML-bestand met externe bronnen.
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

### Zie ook
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
