---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een nieuw PngViewOptions‑object."
type: docs
url: /nl/python-net/groupdocs.viewer.options/pngviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initialiseert een nieuw [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) exemplaar.

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

Initialiseert een exemplaar van de [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) klasse.

Zie voor het codevoorbeeld de documentatie.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | De methode die een stream instantieert die wordt gebruikt om uitvoer‑pagedata te schrijven. |
| release_page_stream | `ReleasePageStream` | De methode die een stream vrijgeeft die is gemaakt door de methode die is toegewezen aan de delegate die is doorgegeven aan de parameter `create_page_stream`. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `release_page_stream` None is. |

## __init__ {#page_stream_factory}

Initialiseert een nieuw [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) exemplaar.

Voor meer informatie, zie de documentatie.

```python
def __init__(self, page_stream_factory):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | De factory die methoden implementeert voor het maken en vrijgeven van de uitvoer‑page‑stream. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `page_stream_factory` `None` is. |

## __init__

Initialiseert een PngViewOptions‑exemplaar.

Deze constructor maakt een [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) met ``"p_{0}.png"`` als het standaard bestandspadformaat voor de uitvoerbestanden. De gegenereerde PNG‑bestanden worden opgeslagen in de huidige werkmap van de applicatie.

```python
def __init__(self):
    ...
```

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

## __init__ {#file_path_format}

Initialiseert een nieuw [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) exemplaar.

Zie voor het codevoorbeeld de documentatie.

```python
def __init__(self, file_path_format):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path_format | `str` | Het bestandspadformaat, bijv. `'page_{0}.png'`. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `file_path_format` None of leeg is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

### Zie ook
* class [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
