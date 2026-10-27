---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer/viewer/__init__/
is_root: false
weight: 10
---


## __init__ {#get_file_stream}

एक नया [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) क्लास का इंस्टेंस इनिशियलाइज़ करता है।

और अधिक जानें

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | वह मेथड जो एक पढ़ने योग्य स्ट्रीम लौटाता है। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | `get_file_stream` जब None हो तो उठाया जाता है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options}

एक नया [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self, get_file_stream, get_load_options):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | वह मेथड जो एक पढ़ने योग्य स्ट्रीम लौटाता है। |
| get_load_options | `Func[LoadOptions]` | वह मेथड जो दस्तावेज़ लोड विकल्प लौटाता है। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | `get_load_options` जब None हो तो फेंका जाता है। |
| `Remarks` | - GroupDocs.Viewer द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक जानकारी: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats - .NET के लिए GroupDocs.Viewer सुविधाओं के बारे में अधिक जानकारी: https://docs.groupdocs.com/display/viewernet/Developer+Guide - .NET के लिए GroupDocs.Viewer के साथ एन्क्रिप्टेड दस्तावेज़ लोड करने और तृतीय‑पक्ष स्टोरेज से फ़ाइलें देखने के बारे में अधिक जानकारी: https://docs.groupdocs.com/display/viewernet/Loading |

### उदाहरण

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

एक नया [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) इंस्टेंस इनिशियलाइज़ करता है।

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream, settings):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | वह मेथड जो एक पढ़ने योग्य स्ट्रीम लौटाता है। |
| settings | `ViewerSettings` | Viewer सेटिंग्स। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | `settings` जब None हो। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options-settings}

एक नया Viewer इंस्टेंस इनिशियलाइज़ करता है।

अधिक जानकारी:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, get_file_stream, get_load_options, settings):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | एक कॉलेबल जो पढ़ने योग्य स्ट्रीम लौटाता है। |
| get_load_options | `Func[LoadOptions]` | एक कॉलेबल जो दस्तावेज़ लोड विकल्प लौटाता है। |
| settings | `ViewerSettings` | Viewer सेटिंग्स। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `settings` None हो। |

### उदाहरण

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

[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| stream | `io.RawIOBase` | फ़ाइल स्ट्रीम। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | `stream` जब None हो तो उठाया जाता है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-leave_open}

एक नया Viewer इंस्टेंस इनिशियलाइज़ करता है।

और अधिक जानें:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, leave_open):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| stream | `io.RawIOBase` | फ़ाइल स्ट्रीम। |
| leave_open | `bool` | Viewer ऑब्जेक्ट नष्ट होने के बाद स्ट्रीम को खुला रखने के लिए True; अन्यथा False। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `stream` None हो। |

### उदाहरण

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

एक नया [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) इंस्टेंस इनिशियलाइज़ करता है।

और अधिक जानें:

- More about file types supported by GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats>
- More about GroupDocs.Viewer for .NET features: <https://docs.groupdocs.com/display/viewernet/Developer+Guide>
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: <https://docs.groupdocs.com/display/viewernet/Loading>

```python
def __init__(self, stream, load_options):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| stream | `io.RawIOBase` | फ़ाइल स्ट्रीम। |
| load_options | `LoadOptions` | दस्तावेज़ लोड विकल्प। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `load_options` None है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-leave_open}

एक नया Viewer इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self, stream, load_options, leave_open):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| stream | `io.RawIOBase` | फ़ाइल स्ट्रीम। |
| load_options | `LoadOptions` | दस्तावेज़ लोड विकल्प। |
| leave_open | `bool` | Viewer ऑब्जेक्ट नष्ट होने के बाद स्ट्रीम को खुला रखने के लिए True; अन्यथा False। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `load_options` None है। |
| `Remarks` | - GroupDocs.Viewer द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक जानकारी: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats> - .NET के लिए GroupDocs.Viewer की सुविधाओं के बारे में अधिक जानकारी: <https://docs.groupdocs.com/display/viewernet/Developer+Guide> - .NET के लिए GroupDocs.Viewer के साथ एन्क्रिप्टेड दस्तावेज़ लोड करने और तृतीय‑पक्ष स्टोरेज से फ़ाइलें देखने के बारे में अधिक जानकारी: <https://docs.groupdocs.com/display/viewernet/Loading> |

### उदाहरण

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

एक नया Viewer इंस्टेंस इनिशियलाइज़ करता है।

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, settings):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| stream | `io.RawIOBase` | फ़ाइल स्ट्रीम। |
| settings | `ViewerSettings` | Viewer सेटिंग्स। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `settings` None हो। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings-leave_open}

एक नया Viewer इंस्टेंस इनिशियलाइज़ करता है।

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

```python
def __init__(self, stream, settings, leave_open):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| stream | `io.RawIOBase` | फ़ाइल स्ट्रीम। |
| settings | `ViewerSettings` | Viewer सेटिंग्स। |
| leave_open | `bool` | Viewer ऑब्जेक्ट नष्ट होने के बाद स्ट्रीम को खुला रखने के लिए True; अन्यथा False। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | `settings` जब None हो। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-settings}

एक नया Viewer इंस्टेंस इनिशियलाइज़ करता है।

कंस्ट्रक्टर को एक फ़ाइल स्ट्रीम (`io.RawIOBase`) चाहिए और वैकल्पिक रूप से दस्तावेज़ लोड विकल्प और Viewer सेटिंग्स स्वीकार करता है।

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| stream | `io.RawIOBase` | फ़ाइल स्ट्रीम। |
| load_options | `LoadOptions` | दस्तावेज़ लोड विकल्प। |
| settings | `ViewerSettings` | Viewer सेटिंग्स। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `stream`, `load_options`, या `settings` None है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer

# फ़ाइल को बाइनरी स्ट्रीम के रूप में खोलें और एक Viewer बनाएं
with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream)
    # Viewer का उपयोग करें, उदाहरण के लिए, HTML में रेंडर करें
    # ...
```

## __init__ {#stream-load_options-settings-leave_open}

एक नया [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) इंस्टेंस इनिशियलाइज़ करता है।

और अधिक जानें:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings, leave_open):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| stream | `io.RawIOBase` | फ़ाइल स्ट्रीम। |
| load_options | `LoadOptions` | दस्तावेज़ लोड विकल्प। |
| settings | `ViewerSettings` | Viewer सेटिंग्स। |
| leave_open | `bool` | Viewer ऑब्जेक्ट नष्ट होने के बाद स्ट्रीम को खुला रखने के लिए True; अन्यथा False। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `settings` None हो। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path}

एक नया [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) क्लास का इंस्टेंस इनिशियलाइज़ करता है।

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_path | `str` | फ़ाइल को रेंडर करने का पथ। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `file_path` `None` या खाली है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer

# दस्तावेज़ पथ के साथ Viewer को प्रारंभ करें
with Viewer("./sample.docx") as viewer:
    # Viewer दस्तावेज़ को रेंडर करने के लिए तैयार है
    pass
```

## __init__ {#file_path-settings}

नया [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) क्लास का इंस्टेंस इनिशियलाइज़ करता है।

और अधिक जानें:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_path | `str` | फ़ाइल को रेंडर करने का पथ। |
| settings | `ViewerSettings` | Viewer सेटिंग्स। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `settings` null है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options}

एक नया [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) इंस्टेंस इनिशियलाइज़ करता है।

- More about file types supported by GroupDocs.Viewer: Document formats supported by GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: Developer Guide (https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: How to load and view document with GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_path | `str` | फ़ाइल को रेंडर करने का पथ। |
| load_options | `LoadOptions` | फ़ाइल खोलने के लिए उपयोग किए जाने वाले विकल्प। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `load_options` None है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options-settings}

एक नया Viewer इंस्टेंस इनिशियलाइज़ करता है।

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_path | `str` | फ़ाइल को रेंडर करने का पथ। |
| load_options | `LoadOptions` | फ़ाइल खोलने के लिए उपयोग किए जाने वाले विकल्प। |
| settings | `ViewerSettings` | Viewer सेटिंग्स। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `settings` None हो। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### साथ में देखें
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
