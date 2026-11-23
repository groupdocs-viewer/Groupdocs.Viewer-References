---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ny PngViewOptions‑instans."
type: docs
url: /sv/python-net/groupdocs.viewer.options/pngviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initierar en ny [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) instans.

För kodexemplet, se dokumentationen.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Metoden som instansierar en ström som används för att skriva utdata för siddata. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `create_page_stream` är None. |

## __init__ {#create_page_stream-release_page_stream}

Initierar en instans av klassen [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

För kodexemplet, se dokumentationen.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Metoden som instansierar en ström som används för att skriva utdata för siddata. |
| release_page_stream | `ReleasePageStream` | Metoden som frigör en ström som skapats av metoden som tilldelats delegaten som skickas till parametern `create_page_stream`. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `release_page_stream` är None. |

## __init__ {#page_stream_factory}

Initierar en ny [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) instans.

För mer information, se dokumentationen.

```python
def __init__(self, page_stream_factory):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Fabriken som implementerar metoder för att skapa och frigöra utdata sidström. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `page_stream_factory` är `None`. |

## __init__

Initierar en PngViewOptions-instans.

Denna konstruktor skapar en [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) med ``\"p_{0}.png\"`` som standardformat för filsökvägen för utdatafilerna. De genererade PNG-filerna sparas i applikationens aktuella arbetskatalog.

```python
def __init__(self):
    ...
```

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

## __init__ {#file_path_format}

Initierar en ny [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) instans.

För kodexemplet, se dokumentationen.

```python
def __init__(self, file_path_format):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path_format | `str` | Filsökvägsformatet, t.ex. `'page_{0}.png'`. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `file_path_format` är None eller tom. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

### Se även
* class [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
