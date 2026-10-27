---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine Instanz der JpgViewOptions-Klasse."
type: docs
url: /de/python-net/groupdocs.viewer.options/jpgviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initialisiert eine Instanz der JpgViewOptions-Klasse.

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

Initialisiert eine Instanz der JpgViewOptions-Klasse.

Siehe das Codebeispiel in der Dokumentation.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Aufrufbare Funktion, die einen Stream erstellt, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| release_page_stream | `ReleasePageStream` | Aufrufbare Funktion, die einen Stream freigibt, der von der Methode erstellt wurde, die dem Delegaten zugewiesen ist, der an `create_page_stream` übergeben wird. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `release_page_stream` None ist. |

## __init__ {#page_stream_factory}

Initialisiert eine Instanz der [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) Klasse.

Für das Codebeispiel siehe die Dokumentation unter https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg.

```python
def __init__(self, page_stream_factory):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Die Fabrik, die Methoden zum Erstellen und Freigeben von Ausgabeseiten-Streams implementiert. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `page_stream_factory` None ist. |

## __init__

Initialisiert eine JpgViewOptions-Instanz.

Dieser Konstruktor initialisiert eine Instanz von [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) mit `\"p_{0}.jpg\"` als Dateipfadformat für die Ausgabedateien. Die Ausgabedateien werden im aktuellen Arbeitsverzeichnis der Anwendung abgelegt.

```python
def __init__(self):
    ...
```

### Beispiel

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

Initialisiert eine neue Instanz von [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/).

Siehe das Codebeispiel in der Dokumentation.

```python
def __init__(self, file_path_format):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path_format | `str` | Das Dateipfadformat, z. B. `'page_{0}.jpg'`. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `file_path_format` None oder leer ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

def render_to_jpg():
    # Laden Sie ein Dokument (z. B. eine Excel-Datei)
    with Viewer("invoice.xlsx") as viewer:
        # Erstellen Sie JPEG-Ansichtsoptionen mit einem Dateinamenmuster.
        view_options = JpgViewOptions("output/excel_page_{0}.jpg")
        view_options.width = 800
        view_options.height = 900
        viewer.view(view_options)

if __name__ == "__main__":
    render_to_jpg()
```

### Siehe auch
* class [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)
