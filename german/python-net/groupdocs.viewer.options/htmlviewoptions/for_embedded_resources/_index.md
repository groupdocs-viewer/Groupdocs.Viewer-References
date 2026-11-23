---
title: "for_embedded_resources Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine HtmlViewOptions-Instanz zum Rendern von HTML mit eingebetteten Ressourcen."
type: docs
url: /de/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/
is_root: false
weight: 1010
---


## for_embedded_resources {#create_page_stream}

Initialisiert eine HtmlViewOptions-Instanz zum Rendern von HTML mit eingebetteten Ressourcen.

Weitere Details finden Sie in der Dokumentation.

```python
def for_embedded_resources(cls, create_page_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Die Methode, die einen Stream erzeugt, der zum Schreiben von Ausgabeseitendaten verwendet wird. |

**Returns:** HtmlViewOptions: New instance configured for rendering HTML with embedded resources.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `create_page_stream` None ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#create_page_stream-release_page_stream}

Initialisiert eine Instanz der [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) Klasse zum Rendern in HTML mit eingebetteten Ressourcen.

```python
def for_embedded_resources(cls, create_page_stream, release_page_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Die Methode, die den Stream erzeugt, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| release_page_stream | `ReleasePageStream` | Die Methode, die den Stream freigibt, der von der Methode erstellt wurde, die dem Parameter `create_page_stream` zugewiesen ist. |

**Returns:** HtmlViewOptions: New instance of the `HtmlViewOptions` class for rendering into HTML with embedded resources.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `release_page_stream` `None` ist. Für das Codebeispiel siehe die Dokumentation. |

## for_embedded_resources {#page_stream_factory}

Initialisiert eine HtmlViewOptions-Instanz zum Rendern in HTML mit eingebetteten Ressourcen.

Für das Codebeispiel siehe die Dokumentation unter https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources.

```python
def for_embedded_resources(cls, page_stream_factory):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Die Fabrik, die Methoden zum Erstellen und Freigeben von Ausgabeseiten-Streams implementiert. |

**Returns:** HtmlViewOptions: New instance of HtmlViewOptions for rendering into HTML with embedded resources.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn page_stream_factory None ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources

Initialisiert eine Instanz der [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) Klasse mit eingebetteten Ressourcen.

Siehe das Codebeispiel in der Dokumentation.

```python
def for_embedded_resources(cls):
    ...
```

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#file_path_format}

Initialisiert eine HtmlViewOptions-Instanz für eingebettete Ressourcen.

Siehe das Codebeispiel in der Dokumentation.

```python
def for_embedded_resources(cls, file_path_format):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path_format | `str` | Das Dateipfadformat, z. B. 'page_{0}.html'. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `file_path_format` None oder leer ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Siehe auch
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
