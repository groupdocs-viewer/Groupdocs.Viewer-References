---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initialiserar en instans av JpgViewOptions-klassen."
type: docs
url: /sv/python-net/groupdocs.viewer.options/jpgviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initialiserar en instans av JpgViewOptions-klassen.

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

Initialiserar en instans av JpgViewOptions-klassen.

För kodexemplet, se dokumentationen.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Anropbar som skapar en ström som används för att skriva utdata för siddata. |
| release_page_stream | `ReleasePageStream` | Anropbar som frigör en ström som skapats av metoden som tilldelats delegaten som skickas till `create_page_stream`. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `release_page_stream` är None. |

## __init__ {#page_stream_factory}

Initialiserar en instans av [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) klassen.

För kodexemplet, se dokumentationen på https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg.

```python
def __init__(self, page_stream_factory):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Fabriken som implementerar metoder för att skapa och frigöra utdata sidström. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `page_stream_factory` är None. |

## __init__

Initialiserar en JpgViewOptions-instans.

Denna konstruktor initierar en instans av [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) med `\"p_{0}.jpg\"` som filnamnsformat för utdatafilerna. Utdatafilerna placeras i applikationens aktuella arbetskatalog.

```python
def __init__(self):
    ...
```

### Exempel

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

Initialiserar en ny instans av [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/).

För kodexemplet, se dokumentationen.

```python
def __init__(self, file_path_format):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path_format | `str` | Filnamnsformatet, t.ex. `'page_{0}.jpg'`. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `file_path_format` är None eller tom. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

def render_to_jpg():
    # Läs in ett dokument (t.ex. en Excel-fil)
    with Viewer("invoice.xlsx") as viewer:
        # Skapa JPEG‑visningsalternativ med ett filnamnsmönster.
        view_options = JpgViewOptions("output/excel_page_{0}.jpg")
        view_options.width = 800
        view_options.height = 900
        viewer.view(view_options)

if __name__ == "__main__":
    render_to_jpg()
```

### Se även
* class [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)
