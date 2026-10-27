---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een instantie van de JpgViewOptions-klasse."
type: docs
url: /nl/python-net/groupdocs.viewer.options/jpgviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initialiseert een instantie van de JpgViewOptions-klasse.

Zie voor het codevoorbeeld de documentatie.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | De methode die een stream instantieert die wordt gebruikt om uitvoer‑pagedata te schrijven. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `create_page_stream` None is. |

## __init__ {#create_page_stream-release_page_stream}

Initialiseert een instantie van de JpgViewOptions-klasse.

Zie voor het codevoorbeeld de documentatie.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Aanroepbaar dat een stream instantieert die wordt gebruikt om uitvoerpagina-gegevens te schrijven. |
| release_page_stream | `ReleasePageStream` | Aanroepbaar dat een stream vrijgeeft die is aangemaakt door de methode toegewezen aan de delegate die is doorgegeven aan `create_page_stream`. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `release_page_stream` None is. |

## __init__ {#page_stream_factory}

Initialiseert een instantie van de [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) klasse.

Zie de documentatie voor het codevoorbeeld op https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg.

```python
def __init__(self, page_stream_factory):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | De factory die methoden implementeert voor het maken en vrijgeven van de uitvoer‑page‑stream. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `page_stream_factory` None is. |

## __init__

Initialiseert een JpgViewOptions‑instantie.

Deze constructor initialiseert een instantie van [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) met \"p_{0}.jpg\" als het bestandsnaamformaat voor de uitvoerbestanden. De uitvoerbestanden worden geplaatst in de huidige werkmap van de applicatie.

```python
def __init__(self):
    ...
```

### Voorbeeld

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

Initialiseert een nieuwe instantie van [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/).

Zie voor het codevoorbeeld de documentatie.

```python
def __init__(self, file_path_format):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path_format | `str` | Het bestandsnaamformaat, bijv. 'page_{0}.jpg'. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `file_path_format` None of leeg is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

def render_to_jpg():
    # Laad een document (bijv. een Excel-bestand)
    with Viewer("invoice.xlsx") as viewer:
        # Maak JPEG-weergaveopties met een bestandsnaampatroon.
        view_options = JpgViewOptions("output/excel_page_{0}.jpg")
        view_options.width = 800
        view_options.height = 900
        viewer.view(view_options)

if __name__ == "__main__":
    render_to_jpg()
```

### Zie ook
* class [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)
