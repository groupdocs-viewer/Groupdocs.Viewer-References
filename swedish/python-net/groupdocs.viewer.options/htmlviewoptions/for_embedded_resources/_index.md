---
title: "for_embedded_resources-metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en HtmlViewOptions-instans för att rendera HTML med inbäddade resurser."
type: docs
url: /sv/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/
is_root: false
weight: 1010
---


## for_embedded_resources {#create_page_stream}

Initierar en HtmlViewOptions-instans för att rendera HTML med inbäddade resurser.

För mer detaljer, se dokumentationen.

```python
def for_embedded_resources(cls, create_page_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Metoden som instansierar en ström som används för att skriva utdata för siddata. |

**Returns:** HtmlViewOptions: New instance configured for rendering HTML with embedded resources.

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `create_page_stream` är None. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#create_page_stream-release_page_stream}

Initierar en instans av klassen [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) för att rendera till HTML med inbäddade resurser.

```python
def for_embedded_resources(cls, create_page_stream, release_page_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Metoden som instansierar strömmen som används för att skriva utdata siddata. |
| release_page_stream | `ReleasePageStream` | Metoden som frigör strömmen som skapats av metoden som tilldelats parametern `create_page_stream`. |

**Returns:** HtmlViewOptions: New instance of the `HtmlViewOptions` class for rendering into HTML with embedded resources.

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `release_page_stream` är `None`. För kodexemplet, se dokumentationen. |

## for_embedded_resources {#page_stream_factory}

Initierar en HtmlViewOptions-instans för att rendera till HTML med inbäddade resurser.

För kodexemplet, se dokumentationen på https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources.

```python
def for_embedded_resources(cls, page_stream_factory):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Fabriken som implementerar metoder för att skapa och frigöra utdata sidström. |

**Returns:** HtmlViewOptions: New instance of HtmlViewOptions for rendering into HTML with embedded resources.

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När page_stream_factory är None. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources

Initierar en instans av klassen [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) med inbäddade resurser.

För kodexemplet, se dokumentationen.

```python
def for_embedded_resources(cls):
    ...
```

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#file_path_format}

Initierar en HtmlViewOptions-instans för inbäddade resurser.

För kodexemplet, se dokumentationen.

```python
def for_embedded_resources(cls, file_path_format):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path_format | `str` | Filvägsformatet t.ex. 'page_{0}.html'. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `file_path_format` är None eller tom. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Se även
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
