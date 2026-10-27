---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der Viewer‑Klasse."
type: docs
url: /de/python-net/groupdocs.viewer/viewer/__init__/
is_root: false
weight: 10
---


## __init__ {#get_file_stream}

Initialisiert eine neue Instanz der Klasse [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Mehr erfahren

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Die Methode, die einen lesbaren Stream zurückgibt. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wird ausgelöst, wenn `get_file_stream` None ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options}

Initialisiert eine neue Instanz von [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

```python
def __init__(self, get_file_stream, get_load_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Die Methode, die einen lesbaren Stream zurückgibt. |
| get_load_options | `Func[LoadOptions]` | Die Methode, die Dokument-Ladeoptionen zurückgibt. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wird ausgelöst, wenn `get_load_options` None ist. |
| `Remarks` | - Mehr über von GroupDocs.Viewer unterstützte Dateitypen: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats - Mehr über GroupDocs.Viewer für .NET‑Funktionen: https://docs.groupdocs.com/display/viewernet/Developer+Guide - Mehr über das Laden verschlüsselter Dokumente und das Anzeigen von Dateien aus Drittanbieter‑Speichern mit GroupDocs.Viewer für .NET: https://docs.groupdocs.com/display/viewernet/Loading |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#get_file_stream-settings}

Initialisiert eine neue [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) Instanz.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream, settings):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Die Methode, die einen lesbaren Stream zurückgibt. |
| settings | `ViewerSettings` | Die Viewer‑Einstellungen. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `settings` None ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options-settings}

Initialisiert eine neue Viewer‑Instanz.

Weitere Informationen:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, get_file_stream, get_load_options, settings):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Aufrufbare Funktion, die einen lesbaren Stream zurückgibt. |
| get_load_options | `Func[LoadOptions]` | Aufrufbare Funktion, die Dokument‑Ladeoptionen zurückgibt. |
| settings | `ViewerSettings` | Viewer-Einstellungen. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `settings` None ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#stream}

Initialisiert eine neue Instanz der [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) Klasse.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | `io.RawIOBase` | Der Dateistream. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wird ausgelöst, wenn `stream` None ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-leave_open}

Initialisiert eine neue Viewer‑Instanz.

Mehr erfahren:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, leave_open):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | `io.RawIOBase` | Der Dateistream. |
| leave_open | `bool` | True, um den Stream nach der Entsorgung des Viewer-Objekts offen zu lassen; andernfalls False. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `stream` None ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML — the hello‑world example."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#stream-load_options}

Initialisiert eine neue Instanz von [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Mehr erfahren:

- More about file types supported by GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats>
- More about GroupDocs.Viewer for .NET features: <https://docs.groupdocs.com/display/viewernet/Developer+Guide>
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: <https://docs.groupdocs.com/display/viewernet/Loading>

```python
def __init__(self, stream, load_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | `io.RawIOBase` | Der Dateistream. |
| load_options | `LoadOptions` | Die Dokument-Ladeoptionen. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `load_options` None ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-leave_open}

Initialisiert eine neue Viewer‑Instanz.

```python
def __init__(self, stream, load_options, leave_open):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | `io.RawIOBase` | Der Dateistream. |
| load_options | `LoadOptions` | Die Dokument-Ladeoptionen. |
| leave_open | `bool` | True, um den Stream nach der Entsorgung des Viewer-Objekts offen zu lassen; andernfalls False. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `load_options` None ist. |
| `Remarks` | - Mehr über von GroupDocs.Viewer unterstützte Dateitypen: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats> - Mehr über Funktionen von GroupDocs.Viewer für .NET: <https://docs.groupdocs.com/display/viewernet/Developer+Guide> - Mehr über das Laden verschlüsselter Dokumente und das Anzeigen von Dateien aus Drittanbieter‑Speichern mit GroupDocs.Viewer für .NET: <https://docs.groupdocs.com/display/viewernet/Loading> |

### Beispiel

```python
import io
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream, loadOptions=None, leaveOpen=False)
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings}

Initialisiert eine neue Viewer‑Instanz.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, settings):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | `io.RawIOBase` | Der Dateistream. |
| settings | `ViewerSettings` | Die Viewer‑Einstellungen. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `settings` None ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings-leave_open}

Initialisiert eine neue Viewer‑Instanz.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

```python
def __init__(self, stream, settings, leave_open):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | `io.RawIOBase` | Der Dateistream. |
| settings | `ViewerSettings` | Die Viewer‑Einstellungen. |
| leave_open | `bool` | True, um den Stream nach der Entsorgung des Viewer-Objekts offen zu lassen; andernfalls False. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `settings` None ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-settings}

Initialisiert eine neue Viewer‑Instanz.

Der Konstruktor erfordert einen Dateistream (`io.RawIOBase`) und akzeptiert optional Dokument-Ladeoptionen und Viewer-Einstellungen.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | `io.RawIOBase` | Der Dateistream. |
| load_options | `LoadOptions` | Die Dokument-Ladeoptionen. |
| settings | `ViewerSettings` | Die Viewer‑Einstellungen. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `stream`, `load_options` oder `settings` None ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer

# Öffnen Sie eine Datei als Binärstream und erstellen Sie einen Viewer
with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream)
    # Verwenden Sie den Viewer, z. B. zum Rendern nach HTML
    # ...
```

## __init__ {#stream-load_options-settings-leave_open}

Initialisiert eine neue Instanz von [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Mehr erfahren:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings, leave_open):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | `io.RawIOBase` | Der Dateistream. |
| load_options | `LoadOptions` | Die Dokument-Ladeoptionen. |
| settings | `ViewerSettings` | Die Viewer‑Einstellungen. |
| leave_open | `bool` | True, um den Stream nach der Entsorgung des Viewer-Objekts offen zu lassen; andernfalls False. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `settings` None ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path}

Initialisiert eine neue Instanz der Klasse [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Pfad zur zu rendernden Datei. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `file_path` `None` oder leer ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer

# Initialisieren Sie den Viewer mit einem Dokumentpfad
with Viewer("./sample.docx") as viewer:
    # Viewer ist bereit, das Dokument zu rendern
    pass
```

## __init__ {#file_path-settings}

Initialisiert eine neue Instanz der [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) Klasse.

Mehr erfahren:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Pfad zur zu rendernden Datei. |
| settings | `ViewerSettings` | Die Viewer‑Einstellungen. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `settings` null ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options}

Initialisiert eine neue Instanz von [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: Document formats supported by GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: Developer Guide (https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: How to load and view document with GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Pfad zur zu rendernden Datei. |
| load_options | `LoadOptions` | Die Optionen, die zum Öffnen der Datei verwendet werden. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `load_options` None ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options-settings}

Initialisiert eine neue Viewer‑Instanz.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Pfad zur zu rendernden Datei. |
| load_options | `LoadOptions` | Die Optionen, die zum Öffnen der Datei verwendet werden. |
| settings | `ViewerSettings` | Die Viewer‑Einstellungen. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `settings` None ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Siehe auch
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
