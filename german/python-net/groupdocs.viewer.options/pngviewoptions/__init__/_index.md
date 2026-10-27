---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine neue PngViewOptions-Instanz."
type: docs
url: /de/python-net/groupdocs.viewer.options/pngviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initialisiert eine neue [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) Instanz.

Siehe das Codebeispiel in der Dokumentation.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Die Methode, die einen Stream erzeugt, der zum Schreiben von Ausgabeseitendaten verwendet wird. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `create_page_stream` None ist. |

## __init__ {#create_page_stream-release_page_stream}

Initialisiert eine Instanz der [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) Klasse.

Siehe das Codebeispiel in der Dokumentation.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Die Methode, die einen Stream erzeugt, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| release_page_stream | `ReleasePageStream` | Die Methode, die einen Stream freigibt, der von der Methode erstellt wurde, die dem an den Parameter `create_page_stream` übergebenen Delegaten zugewiesen ist. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `release_page_stream` None ist. |

## __init__ {#page_stream_factory}

Initialisiert eine neue [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) Instanz.

Weitere Informationen finden Sie in der Dokumentation.

```python
def __init__(self, page_stream_factory):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Die Fabrik, die Methoden zum Erstellen und Freigeben von Ausgabeseiten-Streams implementiert. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `page_stream_factory` `None` ist. |

## __init__

Initialisiert eine PngViewOptions-Instanz.

Dieser Konstruktor erstellt ein [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) mit ``\"p_{0}.png\"`` als Standard-Dateipfaddformat für die Ausgabedateien. Die erzeugten PNG-Dateien werden im aktuellen Arbeitsverzeichnis der Anwendung gespeichert.

```python
def __init__(self):
    ...
```

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

## __init__ {#file_path_format}

Initialisiert eine neue [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) Instanz.

Siehe das Codebeispiel in der Dokumentation.

```python
def __init__(self, file_path_format):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path_format | `str` | Das Dateipfaddformat, z. B. `'page_{0}.png'`. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `file_path_format` None oder leer ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

### Siehe auch
* class [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
