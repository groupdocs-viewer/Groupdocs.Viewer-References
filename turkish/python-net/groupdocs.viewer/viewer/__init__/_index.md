---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Viewer sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer/viewer/__init__/
is_root: false
weight: 10
---


## __init__ {#get_file_stream}

Yeni bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) sınıfının örneğini başlatır.

Daha fazla bilgi edinin

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Okunabilir bir akış döndüren yöntem. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `get_file_stream` None olduğunda fırlatılır. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options}

Yeni bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örneği başlatır.

```python
def __init__(self, get_file_stream, get_load_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Okunabilir bir akış döndüren yöntem. |
| get_load_options | `Func[LoadOptions]` | Belge yükleme seçeneklerini döndüren yöntem. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `get_load_options` None olduğunda fırlatılır. |
| `Remarks` | - GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats - .NET için GroupDocs.Viewer özellikleri hakkında daha fazla bilgi: https://docs.groupdocs.com/display/viewernet/Developer+Guide - .NET için GroupDocs.Viewer ile şifreli belgeleri yükleme ve üçüncü taraf depolardan dosyaları görüntüleme hakkında daha fazla bilgi: https://docs.groupdocs.com/display/viewernet/Loading |

### Örnek

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

Yeni bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örneği başlatır.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream, settings):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Okunabilir bir akış döndüren yöntem. |
| settings | `ViewerSettings` | Viewer ayarları. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `settings` None olduğunda. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options-settings}

Yeni bir Viewer örneği başlatır.

Daha fazla bilgi:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, get_file_stream, get_load_options, settings):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Okunabilir bir akış döndüren çağrılabilir. |
| get_load_options | `Func[LoadOptions]` | Belge yükleme seçeneklerini döndüren çağrılabilir. |
| settings | `ViewerSettings` | Viewer ayarları. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `settings` None ise. |

### Örnek

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

`[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` sınıfının yeni bir örneğini başlatır.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | `io.RawIOBase` | Dosya akışı. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `stream` None olduğunda fırlatılır. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-leave_open}

Yeni bir Viewer örneği başlatır.

Daha fazla bilgi edinin:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, leave_open):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | `io.RawIOBase` | Dosya akışı. |
| leave_open | `bool` | Viewer nesnesi yok edildiğinde akışı açık bırakmak için True; aksi takdirde False. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `stream` None ise. |

### Örnek

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

Yeni bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örneği başlatır.

Daha fazla bilgi edinin:

- More about file types supported by GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats>
- More about GroupDocs.Viewer for .NET features: <https://docs.groupdocs.com/display/viewernet/Developer+Guide>
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: <https://docs.groupdocs.com/display/viewernet/Loading>

```python
def __init__(self, stream, load_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | `io.RawIOBase` | Dosya akışı. |
| load_options | `LoadOptions` | Belge yükleme seçenekleri. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `load_options` None olduğunda. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-leave_open}

Yeni bir Viewer örneği başlatır.

```python
def __init__(self, stream, load_options, leave_open):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | `io.RawIOBase` | Dosya akışı. |
| load_options | `LoadOptions` | Belge yükleme seçenekleri. |
| leave_open | `bool` | Viewer nesnesi yok edildiğinde akışı açık bırakmak için True; aksi takdirde False. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `load_options` None olduğunda. |
| `Remarks` | - GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats> - .NET için GroupDocs.Viewer özellikleri hakkında daha fazla bilgi: <https://docs.groupdocs.com/display/viewernet/Developer+Guide> - .NET için GroupDocs.Viewer ile şifreli belgeleri yükleme ve üçüncü taraf depolardan dosyaları görüntüleme hakkında daha fazla bilgi: <https://docs.groupdocs.com/display/viewernet/Loading> |

### Örnek

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

Yeni bir Viewer örneği başlatır.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, settings):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | `io.RawIOBase` | Dosya akışı. |
| settings | `ViewerSettings` | Viewer ayarları. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `settings` None ise. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings-leave_open}

Yeni bir Viewer örneği başlatır.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

```python
def __init__(self, stream, settings, leave_open):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | `io.RawIOBase` | Dosya akışı. |
| settings | `ViewerSettings` | Viewer ayarları. |
| leave_open | `bool` | Viewer nesnesi yok edildiğinde akışı açık bırakmak için True; aksi takdirde False. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `settings` None olduğunda. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-settings}

Yeni bir Viewer örneği başlatır.

Yapıcı, bir dosya akışı (`io.RawIOBase`) gerektirir ve isteğe bağlı olarak belge yükleme seçeneklerini ve Viewer ayarlarını kabul eder.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | `io.RawIOBase` | Dosya akışı. |
| load_options | `LoadOptions` | Belge yükleme seçenekleri. |
| settings | `ViewerSettings` | Viewer ayarları. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `stream`, `load_options` veya `settings` None ise. |

### Örnek

```python
from groupdocs.viewer import Viewer

# Bir dosyayı ikili akış olarak açın ve bir Viewer oluşturun
with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream)
    # Viewer'ı kullanın, ör. HTML olarak render edin
    # ...
```

## __init__ {#stream-load_options-settings-leave_open}

Yeni bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örneği başlatır.

Daha fazla bilgi edinin:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings, leave_open):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | `io.RawIOBase` | Dosya akışı. |
| load_options | `LoadOptions` | Belge yükleme seçenekleri. |
| settings | `ViewerSettings` | Viewer ayarları. |
| leave_open | `bool` | Viewer nesnesi yok edildiğinde akışı açık bırakmak için True; aksi takdirde False. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `settings` None ise. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path}

Yeni bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) sınıfının örneğini başlatır.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Render edilecek dosyanın yolu. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `file_path` None veya boş ise. |

### Örnek

```python
from groupdocs.viewer import Viewer

# Viewer'ı bir belge yolu ile başlatın
with Viewer("./sample.docx") as viewer:
    # viewer belgeyi render etmeye hazır
    pass
```

## __init__ {#file_path-settings}

Yeni bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) sınıfı örneği başlatır.

Daha fazla bilgi edinin:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Render edilecek dosyanın yolu. |
| settings | `ViewerSettings` | Viewer ayarları. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `settings` null ise. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options}

Yeni bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örneği başlatır.

- More about file types supported by GroupDocs.Viewer: Document formats supported by GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: Developer Guide (https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: How to load and view document with GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Render edilecek dosyanın yolu. |
| load_options | `LoadOptions` | Dosyayı açmak için kullanılan seçenekler. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `load_options` None ise. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options-settings}

Yeni bir Viewer örneği başlatır.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Render edilecek dosyanın yolu. |
| load_options | `LoadOptions` | Dosyayı açmak için kullanılan seçenekler. |
| settings | `ViewerSettings` | Viewer ayarları. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `settings` None ise. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Ayrıca Bakınız
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
