---
title: "for_embedded_resources methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een HtmlViewOptions‑instantie voor het renderen van HTML met ingesloten bronnen."
type: docs
url: /nl/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/
is_root: false
weight: 1010
---


## for_embedded_resources {#create_page_stream}

Initialiseert een HtmlViewOptions‑instantie voor het renderen van HTML met ingesloten bronnen.

Voor meer details, zie de documentatie.

```python
def for_embedded_resources(cls, create_page_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | De methode die een stream instantieert die wordt gebruikt om uitvoer‑pagedata te schrijven. |

**Returns:** HtmlViewOptions: New instance configured for rendering HTML with embedded resources.

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `create_page_stream` None is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#create_page_stream-release_page_stream}

Initialiseert een instantie van de [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)‑klasse voor het renderen naar HTML met ingesloten bronnen.

```python
def for_embedded_resources(cls, create_page_stream, release_page_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | De methode die de stream instantieert die wordt gebruikt om uitvoer‑pagedata te schrijven. |
| release_page_stream | `ReleasePageStream` | De methode die de stream vrijgeeft die is gemaakt door de methode die is toegewezen aan de parameter `create_page_stream`. |

**Returns:** HtmlViewOptions: New instance of the `HtmlViewOptions` class for rendering into HTML with embedded resources.

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `release_page_stream` None is. Voor het code‑voorbeeld, zie de documentatie. |

## for_embedded_resources {#page_stream_factory}

Initialiseert een HtmlViewOptions‑instantie voor het renderen naar HTML met ingesloten bronnen.

Voor het code‑voorbeeld, zie de documentatie op https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources.

```python
def for_embedded_resources(cls, page_stream_factory):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | De factory die methoden implementeert voor het maken en vrijgeven van de uitvoer‑page‑stream. |

**Returns:** HtmlViewOptions: New instance of HtmlViewOptions for rendering into HTML with embedded resources.

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer page_stream_factory None is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources

Initialiseert een instantie van de [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)‑klasse met ingesloten bronnen.

Zie voor het codevoorbeeld de documentatie.

```python
def for_embedded_resources(cls):
    ...
```

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#file_path_format}

Initialiseert een HtmlViewOptions‑instantie voor ingesloten bronnen.

Zie voor het codevoorbeeld de documentatie.

```python
def for_embedded_resources(cls, file_path_format):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path_format | `str` | Het bestandspadformaat, bijv. 'page_{0}.html'. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `file_path_format` None of leeg is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Zie ook
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
