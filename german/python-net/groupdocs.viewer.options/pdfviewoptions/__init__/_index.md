---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine Instanz von PdfViewOptions."
type: docs
url: /de/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_file_stream}

Initialisiert eine Instanz von [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/).

Für das Codebeispiel siehe die Dokumentation unter https://docs.groupdocs.com/viewer/net/rendering-to-pdf/.

```python
def __init__(self, create_file_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | Die Methode, die den Stream instanziiert, der zum Schreiben von Ausgabedateidaten verwendet wird. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `create_file_stream` `None` ist. |

## __init__ {#create_file_stream-release_file_stream}

Initialisiert eine neue PdfViewOptions-Instanz.

Siehe das Codebeispiel in der Dokumentation.

```python
def __init__(self, create_file_stream, release_file_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | Aufrufbare, die einen `io.RawIOBase`-Stream zurückgibt, der zum Schreiben von Ausgabedateidaten verwendet wird. |
| release_file_stream | `ReleaseFileStream` | Aufrufbare, die den von der Methode zugewiesenen `create_file_stream` erstellten Stream freigibt. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `release_file_stream` None ist. |

## __init__ {#file_stream_factory}

Initialisiert eine PdfViewOptions-Instanz.

Für das Codebeispiel siehe die Dokumentation: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

```python
def __init__(self, file_stream_factory):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_stream_factory | `IFileStreamFactory` | Die Fabrik, die Methoden zum Erstellen und Freigeben des Ausgabedatei‑Streams implementiert. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wird ausgelöst, wenn `file_stream_factory` None ist. |

## __init__

Initialisiert eine PdfViewOptions-Instanz.

Dieser Konstruktor initialisiert ein PdfViewOptions mit `\"output.pdf\"` als Dateipfadformat für die Ausgabedatei. Die Ausgabedatei wird im aktuellen Arbeitsverzeichnis der Anwendung abgelegt.

```python
def __init__(self):
    ...
```

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

## __init__ {#output_file_path}

Initialisiert eine Instanz der Klasse [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/).

Siehe das Codebeispiel in der Dokumentation.

```python
def __init__(self, output_file_path):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| output_file_path | `str` | Der Pfad für die Ausgabepdf‑Datei. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `output_file_path` None oder leer ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### Siehe auch
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
