---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de Viewer-klasse."
type: docs
url: /nl/python-net/groupdocs.viewer/viewer/__init__/
is_root: false
weight: 10
---


## __init__ {#get_file_stream}

Initialiseert een nieuwe instantie van de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-klasse.

Meer informatie

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | De methode die een leesbare stream retourneert. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wordt opgegooid wanneer `get_file_stream` None is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options}

Initialiseert een nieuwe instantie van [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

```python
def __init__(self, get_file_stream, get_load_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | De methode die een leesbare stream retourneert. |
| get_load_options | `Func[LoadOptions]` | De methode die documentlaadopties retourneert. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wordt gegooid wanneer `get_load_options` None is. |
| `Remarks` | - Meer over bestandstypen die worden ondersteund door GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats - Meer over GroupDocs.Viewer voor .NET-functies: https://docs.groupdocs.com/display/viewernet/Developer+Guide - Meer over het laden van versleutelde documenten en het bekijken van bestanden van externe opslagplaatsen met GroupDocs.Viewer voor .NET: https://docs.groupdocs.com/display/viewernet/Loading |

### Voorbeeld

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

Initialiseert een nieuwe [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-instantie.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream, settings):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | De methode die een leesbare stream retourneert. |
| settings | `ViewerSettings` | De Viewer-instellingen. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `settings` None is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options-settings}

Initialiseert een nieuwe Viewer-instantie.

Meer informatie:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, get_file_stream, get_load_options, settings):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Aanroepbaar object dat een leesbare stream retourneert. |
| get_load_options | `Func[LoadOptions]` | Aanroepbaar object dat documentlaadopties retourneert. |
| settings | `ViewerSettings` | Viewer-instellingen. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `settings` None is. |

### Voorbeeld

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

Initialiseert een nieuwe instantie van de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-klasse.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | `io.RawIOBase` | De bestandsstroom. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wordt opgegooid wanneer `stream` None is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-leave_open}

Initialiseert een nieuwe Viewer-instantie.

Meer informatie:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, leave_open):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | `io.RawIOBase` | De bestandsstroom. |
| leave_open | `bool` | True om de stream open te laten nadat het Viewer-object is vrijgegeven; anders False. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `stream` None is. |

### Voorbeeld

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

Initialiseert een nieuwe instantie van [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Meer informatie:

- More about file types supported by GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats>
- More about GroupDocs.Viewer for .NET features: <https://docs.groupdocs.com/display/viewernet/Developer+Guide>
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: <https://docs.groupdocs.com/display/viewernet/Loading>

```python
def __init__(self, stream, load_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | `io.RawIOBase` | De bestandsstroom. |
| load_options | `LoadOptions` | De documentlaadopties. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `load_options` None is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-leave_open}

Initialiseert een nieuwe Viewer-instantie.

```python
def __init__(self, stream, load_options, leave_open):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | `io.RawIOBase` | De bestandsstroom. |
| load_options | `LoadOptions` | De documentlaadopties. |
| leave_open | `bool` | True om de stream open te laten nadat het Viewer-object is vrijgegeven; anders False. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `load_options` None is. |
| `Remarks` | - Meer over bestandsformaten die worden ondersteund door GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats> - Meer over GroupDocs.Viewer voor .NET-functies: <https://docs.groupdocs.com/display/viewernet/Developer+Guide> - Meer over het laden van versleutelde documenten en het bekijken van bestanden van externe opslagplaatsen met GroupDocs.Viewer voor .NET: <https://docs.groupdocs.com/display/viewernet/Loading> |

### Voorbeeld

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

Initialiseert een nieuwe Viewer-instantie.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, settings):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | `io.RawIOBase` | De bestandsstroom. |
| settings | `ViewerSettings` | De Viewer-instellingen. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `settings` None is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings-leave_open}

Initialiseert een nieuwe Viewer-instantie.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

```python
def __init__(self, stream, settings, leave_open):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | `io.RawIOBase` | De bestandsstroom. |
| settings | `ViewerSettings` | De Viewer-instellingen. |
| leave_open | `bool` | True om de stream open te laten nadat het Viewer-object is vrijgegeven; anders False. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `settings` None is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-settings}

Initialiseert een nieuwe Viewer-instantie.

De constructor vereist een bestandsstream (`io.RawIOBase`) en accepteert optioneel documentlaadopties en Viewer-instellingen.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | `io.RawIOBase` | De bestandsstroom. |
| load_options | `LoadOptions` | De documentlaadopties. |
| settings | `ViewerSettings` | De Viewer-instellingen. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `stream`, `load_options` of `settings` None is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer

# Open een bestand als een binaire stream en maak een Viewer
with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream)
    # Gebruik viewer, bijv., renderen naar HTML
    # ...
```

## __init__ {#stream-load_options-settings-leave_open}

Initialiseert een nieuwe instantie van [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Meer informatie:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings, leave_open):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | `io.RawIOBase` | De bestandsstroom. |
| load_options | `LoadOptions` | De documentlaadopties. |
| settings | `ViewerSettings` | De Viewer-instellingen. |
| leave_open | `bool` | True om de stream open te laten nadat het Viewer-object is vrijgegeven; anders False. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `settings` None is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path}

Initialiseert een nieuwe instantie van de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-klasse.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het pad naar het bestand dat moet worden gerenderd. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `file_path` `None` of leeg is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer

# Initialiseer de viewer met een documentpad
with Viewer("./sample.docx") as viewer:
    # viewer is klaar om het document te renderen
    pass
```

## __init__ {#file_path-settings}

Initialiseert een nieuwe instantie van [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-klasse.

Meer informatie:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het pad naar het bestand dat moet worden gerenderd. |
| settings | `ViewerSettings` | De Viewer-instellingen. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `settings` null is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options}

Initialiseert een nieuwe instantie van [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: Document formats supported by GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: Developer Guide (https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: How to load and view document with GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het pad naar het bestand dat moet worden gerenderd. |
| load_options | `LoadOptions` | De opties die worden gebruikt om het bestand te openen. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `load_options` None is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options-settings}

Initialiseert een nieuwe Viewer-instantie.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het pad naar het bestand dat moet worden gerenderd. |
| load_options | `LoadOptions` | De opties die worden gebruikt om het bestand te openen. |
| settings | `ViewerSettings` | De Viewer-instellingen. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `settings` None is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Zie ook
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
