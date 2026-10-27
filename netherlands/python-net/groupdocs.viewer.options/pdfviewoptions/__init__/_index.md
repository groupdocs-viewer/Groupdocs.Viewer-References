---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een instantie van PdfViewOptions."
type: docs
url: /nl/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_file_stream}

Initialiseert een instantie van [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/).

Zie voor het codevoorbeeld de documentatie op https://docs.groupdocs.com/viewer/net/rendering-to-pdf/.

```python
def __init__(self, create_file_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | De methode die de stream instantieert die wordt gebruikt om uitvoerbestandsgegevens te schrijven. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `create_file_stream` `None` is. |

## __init__ {#create_file_stream-release_file_stream}

Initialiseert een nieuwe PdfViewOptions-instantie.

Zie voor het codevoorbeeld de documentatie.

```python
def __init__(self, create_file_stream, release_file_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | Aanroepbaar object dat een `io.RawIOBase`-stream retourneert die wordt gebruikt om uitvoerbestandsgegevens te schrijven. |
| release_file_stream | `ReleaseFileStream` | Aanroepbaar object dat de stream vrijgeeft die is gemaakt door de methode die is toegewezen aan `create_file_stream`. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `release_file_stream` None is. |

## __init__ {#file_stream_factory}

Initialiseert een PdfViewOptions-instantie.

Zie voor het codevoorbeeld de documentatie: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

```python
def __init__(self, file_stream_factory):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_stream_factory | `IFileStreamFactory` | De fabriek die methoden implementeert voor het maken en vrijgeven van de uitvoerbestandsstream. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wordt opgegooid wanneer `file_stream_factory` None is. |

## __init__

Initialiseert een PdfViewOptions-instantie.

Deze constructor initialiseert een PdfViewOptions met `"output.pdf"` als het bestandsnaamformaat voor het uitvoerbestand. Het uitvoerbestand wordt geplaatst in de huidige werkmap van de applicatie.

```python
def __init__(self):
    ...
```

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

## __init__ {#output_file_path}

Initialiseert een instantie van [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) klasse.

Zie voor het codevoorbeeld de documentatie.

```python
def __init__(self, output_file_path):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| output_file_path | `str` | Het pad voor het uitvoer‑PDF‑bestand. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `output_file_path` None of leeg is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### Zie ook
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
