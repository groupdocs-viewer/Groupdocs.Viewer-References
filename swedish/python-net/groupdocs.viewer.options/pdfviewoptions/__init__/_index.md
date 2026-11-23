---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en instans av PdfViewOptions."
type: docs
url: /sv/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_file_stream}

Initierar en instans av [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/).

För kodexemplet, se dokumentationen på https://docs.groupdocs.com/viewer/net/rendering-to-pdf/.

```python
def __init__(self, create_file_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | Metoden som skapar strömmen som används för att skriva utdatafilens data. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `create_file_stream` är `None`. |

## __init__ {#create_file_stream-release_file_stream}

Initierar en ny PdfViewOptions-instans.

För kodexemplet, se dokumentationen.

```python
def __init__(self, create_file_stream, release_file_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | Anropbar som returnerar en `io.RawIOBase`-ström som används för att skriva utdatafilens data. |
| release_file_stream | `ReleaseFileStream` | Anropbar som frigör strömmen som skapats av metoden som tilldelats `create_file_stream`. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `release_file_stream` är None. |

## __init__ {#file_stream_factory}

Initierar en PdfViewOptions-instans.

För kodexemplet, se dokumentationen: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

```python
def __init__(self, file_stream_factory):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_stream_factory | `IFileStreamFactory` | Fabriken som implementerar metoder för att skapa och frigöra utdatafilens ström. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Utlöst när `file_stream_factory` är None. |

## __init__

Initierar en PdfViewOptions-instans.

Denna konstruktor initierar en PdfViewOptions med `\"output.pdf\"` som filvägsformat för utdatafilen. Utdatafilen kommer att placeras i applikationens aktuella arbetskatalog.

```python
def __init__(self):
    ...
```

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

## __init__ {#output_file_path}

Initierar en instans av [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) klass.

För kodexemplet, se dokumentationen.

```python
def __init__(self, output_file_path):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| output_file_path | `str` | Sökvägen för utdata-PDF-filen. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `output_file_path` är None eller tom. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### Se även
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
