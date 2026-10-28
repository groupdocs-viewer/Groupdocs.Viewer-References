---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует новый экземпляр класса Viewer."
type: docs
url: /ru/python-net/groupdocs.viewer/viewer/__init__/
is_root: false
weight: 10
---


## __init__ {#get_file_stream}

Инициализирует новый экземпляр класса [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Подробнее

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Метод, возвращающий поток для чтения. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Вызывается, когда `get_file_stream` равно None. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options}

Инициализирует новый экземпляр [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

```python
def __init__(self, get_file_stream, get_load_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Метод, возвращающий поток для чтения. |
| get_load_options | `Func[LoadOptions]` | Метод, возвращающий параметры загрузки документа. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Выбрасывается, когда `get_load_options` равно None. |
| `Remarks` | - Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats - Подробнее о возможностях GroupDocs.Viewer для .NET: https://docs.groupdocs.com/display/viewernet/Developer+Guide - Подробнее о загрузке зашифрованных документов и просмотре файлов из сторонних хранилищ с GroupDocs.Viewer для .NET: https://docs.groupdocs.com/display/viewernet/Loading |

### Пример

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

Инициализирует новый экземпляр [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream, settings):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Метод, возвращающий поток для чтения. |
| settings | `ViewerSettings` | Настройки Viewer. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `settings` равно None. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options-settings}

Инициализирует новый экземпляр Viewer.

Дополнительная информация:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, get_file_stream, get_load_options, settings):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Вызываемый объект, возвращающий поток для чтения. |
| get_load_options | `Func[LoadOptions]` | Вызываемый объект, возвращающий параметры загрузки документа. |
| settings | `ViewerSettings` | Настройки Viewer. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `settings` равно None. |

### Пример

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

Инициализирует новый экземпляр класса [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | `io.RawIOBase` | Поток файла. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Вызывается, когда `stream` равно None. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-leave_open}

Инициализирует новый экземпляр Viewer.

Подробнее:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, leave_open):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | `io.RawIOBase` | Поток файла. |
| leave_open | `bool` | True, чтобы оставить поток открытым после освобождения объекта Viewer; иначе False. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `stream` равно None. |

### Пример

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

Инициализирует новый экземпляр [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Подробнее:

- More about file types supported by GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats>
- More about GroupDocs.Viewer for .NET features: <https://docs.groupdocs.com/display/viewernet/Developer+Guide>
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: <https://docs.groupdocs.com/display/viewernet/Loading>

```python
def __init__(self, stream, load_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | `io.RawIOBase` | Поток файла. |
| load_options | `LoadOptions` | Параметры загрузки документа. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `load_options` равно None. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-leave_open}

Инициализирует новый экземпляр Viewer.

```python
def __init__(self, stream, load_options, leave_open):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | `io.RawIOBase` | Поток файла. |
| load_options | `LoadOptions` | Параметры загрузки документа. |
| leave_open | `bool` | True, чтобы оставить поток открытым после освобождения объекта Viewer; иначе False. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `load_options` равно None. |
| `Remarks` | - Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats> - Подробнее о возможностях GroupDocs.Viewer для .NET: <https://docs.groupdocs.com/display/viewernet/Developer+Guide> - Подробнее о загрузке зашифрованных документов и просмотре файлов из сторонних хранилищ с GroupDocs.Viewer для .NET: <https://docs.groupdocs.com/display/viewernet/Loading> |

### Пример

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

Инициализирует новый экземпляр Viewer.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, settings):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | `io.RawIOBase` | Поток файла. |
| settings | `ViewerSettings` | Настройки Viewer. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `settings` равно None. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings-leave_open}

Инициализирует новый экземпляр Viewer.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

```python
def __init__(self, stream, settings, leave_open):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | `io.RawIOBase` | Поток файла. |
| settings | `ViewerSettings` | Настройки Viewer. |
| leave_open | `bool` | True, чтобы оставить поток открытым после освобождения объекта Viewer; иначе False. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `settings` равно None. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-settings}

Инициализирует новый экземпляр Viewer.

Конструктор требует файловый поток (`io.RawIOBase`) и опционально принимает параметры загрузки документа и настройки Viewer.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | `io.RawIOBase` | Поток файла. |
| load_options | `LoadOptions` | Параметры загрузки документа. |
| settings | `ViewerSettings` | Настройки Viewer. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `stream`, `load_options` или `settings` равно None. |

### Пример

```python
from groupdocs.viewer import Viewer

# Откройте файл как бинарный поток и создайте Viewer
with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream)
    # Используйте viewer, например, отрисуйте в HTML
    # ...
```

## __init__ {#stream-load_options-settings-leave_open}

Инициализирует новый экземпляр [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Подробнее:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings, leave_open):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | `io.RawIOBase` | Поток файла. |
| load_options | `LoadOptions` | Параметры загрузки документа. |
| settings | `ViewerSettings` | Настройки Viewer. |
| leave_open | `bool` | True, чтобы оставить поток открытым после освобождения объекта Viewer; иначе False. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `settings` равно None. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path}

Инициализирует новый экземпляр класса [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к файлу для рендеринга. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `file_path` равно `None` или пустой. |

### Пример

```python
from groupdocs.viewer import Viewer

# Инициализируйте viewer с путем к документу
with Viewer("./sample.docx") as viewer:
    # viewer готов к рендерингу документа
    pass
```

## __init__ {#file_path-settings}

Инициализирует новый экземпляр класса [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Подробнее:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к файлу для рендеринга. |
| settings | `ViewerSettings` | Настройки Viewer. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `settings` равно null. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options}

Инициализирует новый экземпляр [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: Document formats supported by GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: Developer Guide (https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: How to load and view document with GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к файлу для рендеринга. |
| load_options | `LoadOptions` | Параметры, используемые для открытия файла. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `load_options` равно None. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options-settings}

Инициализирует новый экземпляр Viewer.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к файлу для рендеринга. |
| load_options | `LoadOptions` | Параметры, используемые для открытия файла. |
| settings | `ViewerSettings` | Настройки Viewer. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `settings` равно None. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### См. также
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
