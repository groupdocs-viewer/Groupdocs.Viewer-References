---
title: "for_external_resources metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en instans av HtmlViewOptions-klassen för att rendera till HTML med externa resurser."
type: docs
url: /sv/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/
is_root: false
weight: 1060
---


## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url}

Initierar en instans av klassen [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) för att rendera till HTML med externa resurser.

För kodexemplet, se dokumentationen.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Metoden som instansierar strömmen som används för att skriva utdata siddata. |
| create_resource_stream | `CreateResourceStream` | Metoden som frigör strömmen som skapats av `create_page_stream`-metoden. |
| create_resource_url | `CreateResourceUrl` | Metoden som skapar URL för HTML-resurs. |

**Returns:** New instance of the `HtmlViewOptions` class for rendering into HTML with external resources.

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `create_resource_url` är None. |

### Exempel

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

Initierar en instans av HtmlViewOptions-klassen för att rendera till HTML med externa resurser.

För ytterligare användningsexempel, se GroupDocs Viewer-dokumentationen.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url, release_page_stream, release_resource_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Metoden som instansierar en ström som används för att skriva utdata för siddata. |
| create_resource_stream | `CreateResourceStream` | Metoden som instansierar en ström som används för att skriva utdata‑HTML‑resursdata. |
| create_resource_url | `CreateResourceUrl` | Metoden som skapar en URL för en HTML‑resurs. |
| release_page_stream | `ReleasePageStream` | Metoden som frigör strömmen som skapats av delegaten som skickas till `create_page_stream`. |
| release_resource_stream | `ReleaseResourceStream` | Metoden som frigör strömmen som skapats av delegaten som skickas till `create_resource_stream`. |

**Returns:** HtmlViewOptions: New instance of the HtmlViewOptions class for rendering into HTML with external resources.

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `release_resource_stream` är None. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_excel_to_html_external():
    # Läs in Excel‑kalkylblad
    with Viewer("invoice.xlsx") as viewer:
        # Konvertera kalkylbladet till HTML med externa resurser.
        # {0} och {1} ersätts med det aktuella sidnumret respektive resursnamnet.
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

Initierar en HtmlViewOptions-instans för att rendera till HTML med externa resurser.

För mer information, se den online‑dokumentationen.

```python
def for_external_resources(cls, page_stream_factory, resource_stream_factory):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Fabriken som implementerar metoder för att skapa och frigöra utdata‑sidströmmen. |
| resource_stream_factory | `IResourceStreamFactory` | Fabriken som implementerar metoder som krävs för att skapa resurs‑URL:er, instansiera och frigöra utdata‑HTML‑resursströmmar. |

**Returns:** HtmlViewOptions: A new HtmlViewOptions instance configured for external resources.

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `resource_stream_factory` är None. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Skapa en HTML‑fil för varje sida och lagra externa resurser separat.
    # {0} och {1} ersätts med det aktuella sidnumret respektive resursnamnet.
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

Initierar en HtmlViewOptions-instans konfigurerad för att generera HTML-filer med externa resurser.

Instansen använder de angivna formatsträngarna:
- `html_file_path_format` – file path format for the output HTML files (e.g., `"page_{0}.html"`).
- `resources_path_format` – folder path format for external resource files (e.g., `"page_{0}/resource_{0}_{1}"`).
- `resources_url_format` – URL format for HTML resources (e.g., `"page_{0}/resource_{0}_{1}"`).

Utdatafilerna placeras i applikationens aktuella arbetskatalog.

```python
def for_external_resources(cls):
    ...
```

**Returns:** HtmlViewOptions: Configured options for rendering HTML with external resources.

### Exempel

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

Initierar en instans av klassen [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/).

För kodexemplet, se dokumentationen.

```python
def for_external_resources(cls, file_path_format, resource_file_path_format, resource_url_format):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path_format | `str` | Filvägsformatet, t.ex. `'page_{0}.html'`. |
| resource_file_path_format | `str` | Resursfilvägsformatet, t.ex. `'page_{0}/resource_{1}'`. |
| resource_url_format | `str` | Resurs‑URL‑formatet, t.ex. `'page_{0}/resource_{1}'`. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `resource_url_format` är None eller tom. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Läs in ett dokument och rendera varje sida till en HTML‑fil med externa resurser.
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

### Se även
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
