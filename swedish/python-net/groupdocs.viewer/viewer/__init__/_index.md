---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ny instans av Viewer-klassen."
type: docs
url: /sv/python-net/groupdocs.viewer/viewer/__init__/
is_root: false
weight: 10
---


## __init__ {#get_file_stream}

Initierar en ny instans av [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) klass.

Läs mer

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Metoden som returnerar en läsbar ström. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Uppstår när `get_file_stream` är None. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options}

Initierar en ny instans av [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

```python
def __init__(self, get_file_stream, get_load_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Metoden som returnerar en läsbar ström. |
| get_load_options | `Func[LoadOptions]` | Metoden som returnerar dokumentets laddningsalternativ. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Kastas när `get_load_options` är None. |
| `Remarks` | - Mer om filtyper som stöds av GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats - Mer om GroupDocs.Viewer för .NET-funktioner: https://docs.groupdocs.com/display/viewernet/Developer+Guide - Mer om att ladda krypterade dokument och visa filer från tredjepartslagringar med GroupDocs.Viewer för .NET: https://docs.groupdocs.com/display/viewernet/Loading |

### Exempel

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

Initierar en ny [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instans.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream, settings):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Metoden som returnerar en läsbar ström. |
| settings | `ViewerSettings` | Inställningarna för Viewer. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `settings` är None. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options-settings}

Initierar en ny Viewer-instans.

Mer information:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, get_file_stream, get_load_options, settings):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Anropbar som returnerar en läsbar ström. |
| get_load_options | `Func[LoadOptions]` | Anropbar som returnerar dokumentets laddningsalternativ. |
| settings | `ViewerSettings` | Viewer-inställningar. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `settings` är None. |

### Exempel

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

Initierar en ny instans av [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) klassen.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | `io.RawIOBase` | Filströmmen. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Utlöst när `stream` är None. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-leave_open}

Initierar en ny Viewer-instans.

Läs mer:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, leave_open):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | `io.RawIOBase` | Filströmmen. |
| leave_open | `bool` | True för att lämna strömmen öppen efter att Viewer-objektet har frigjorts; annars False. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `stream` är None. |

### Exempel

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

Initierar en ny instans av [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Läs mer:

- More about file types supported by GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats>
- More about GroupDocs.Viewer for .NET features: <https://docs.groupdocs.com/display/viewernet/Developer+Guide>
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: <https://docs.groupdocs.com/display/viewernet/Loading>

```python
def __init__(self, stream, load_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | `io.RawIOBase` | Filströmmen. |
| load_options | `LoadOptions` | Dokumentets laddningsalternativ. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `load_options` är None. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-leave_open}

Initierar en ny Viewer-instans.

```python
def __init__(self, stream, load_options, leave_open):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | `io.RawIOBase` | Filströmmen. |
| load_options | `LoadOptions` | Dokumentets laddningsalternativ. |
| leave_open | `bool` | True för att lämna strömmen öppen efter att Viewer-objektet har frigjorts; annars False. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `load_options` är None. |
| `Remarks` | - Mer om filtyper som stöds av GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats> - Mer om funktioner i GroupDocs.Viewer för .NET: <https://docs.groupdocs.com/display/viewernet/Developer+Guide> - Mer om att ladda krypterade dokument och visa filer från tredjepartslagringar med GroupDocs.Viewer för .NET: <https://docs.groupdocs.com/display/viewernet/Loading> |

### Exempel

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

Initierar en ny Viewer-instans.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, settings):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | `io.RawIOBase` | Filströmmen. |
| settings | `ViewerSettings` | Inställningarna för Viewer. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `settings` är None. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings-leave_open}

Initierar en ny Viewer-instans.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

```python
def __init__(self, stream, settings, leave_open):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | `io.RawIOBase` | Filströmmen. |
| settings | `ViewerSettings` | Inställningarna för Viewer. |
| leave_open | `bool` | True för att lämna strömmen öppen efter att Viewer-objektet har frigjorts; annars False. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `settings` är None. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-settings}

Initierar en ny Viewer-instans.

Konstruktorn kräver en filström (`io.RawIOBase`) och accepterar valfritt dokumentets laddningsalternativ och Viewer-inställningar.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | `io.RawIOBase` | Filströmmen. |
| load_options | `LoadOptions` | Dokumentets laddningsalternativ. |
| settings | `ViewerSettings` | Inställningarna för Viewer. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `stream`, `load_options` eller `settings` är None. |

### Exempel

```python
from groupdocs.viewer import Viewer

# Öppna en fil som en binär ström och skapa en Viewer
with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream)
    # Använd viewer, t.ex. rendera till HTML
    # ...
```

## __init__ {#stream-load_options-settings-leave_open}

Initierar en ny instans av [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Läs mer:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings, leave_open):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | `io.RawIOBase` | Filströmmen. |
| load_options | `LoadOptions` | Dokumentets laddningsalternativ. |
| settings | `ViewerSettings` | Inställningarna för Viewer. |
| leave_open | `bool` | True för att lämna strömmen öppen efter att Viewer-objektet har frigjorts; annars False. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `settings` är None. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path}

Initierar en ny instans av [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) klass.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Sökvägen till filen som ska renderas. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `file_path` är `None` eller tom. |

### Exempel

```python
from groupdocs.viewer import Viewer

# Initiera viewer med en dokumentväg
with Viewer("./sample.docx") as viewer:
    # viewer är redo att rendera dokumentet
    pass
```

## __init__ {#file_path-settings}

Initierar en ny instans av [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) klass.

Läs mer:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Sökvägen till filen som ska renderas. |
| settings | `ViewerSettings` | Inställningarna för Viewer. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `settings` är null. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options}

Initierar en ny instans av [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: Document formats supported by GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: Developer Guide (https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: How to load and view document with GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Sökvägen till filen som ska renderas. |
| load_options | `LoadOptions` | Alternativen som används för att öppna filen. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `load_options` är None. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options-settings}

Initierar en ny Viewer-instans.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Sökvägen till filen som ska renderas. |
| load_options | `LoadOptions` | Alternativen som används för att öppna filen. |
| settings | `ViewerSettings` | Inställningarna för Viewer. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `settings` är None. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Se även
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
