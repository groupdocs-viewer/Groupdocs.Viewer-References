---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует новый экземпляр PngViewOptions."
type: docs
url: /ru/python-net/groupdocs.viewer.options/pngviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Инициализирует новый экземпляр [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Для примера кода см. документацию.

```python
def __init__(self, create_page_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Метод, который создает поток, используемый для записи данных выходных страниц. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `create_page_stream` равно None. |

## __init__ {#create_page_stream-release_page_stream}

Инициализирует экземпляр класса [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Для примера кода см. документацию.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Метод, который создает поток, используемый для записи данных выходных страниц. |
| release_page_stream | `ReleasePageStream` | Метод, который освобождает поток, созданный методом, назначенным делегату, переданному параметру `create_page_stream`. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `release_page_stream` равно None. |

## __init__ {#page_stream_factory}

Инициализирует новый экземпляр [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Для получения дополнительной информации см. документацию.

```python
def __init__(self, page_stream_factory):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Фабрика, реализующая методы создания и освобождения потока выходных страниц. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `page_stream_factory` равно `None`. |

## __init__

Инициализирует экземпляр PngViewOptions.

Этот конструктор создает [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) с ``\"p_{0}.png\"`` в качестве формата пути к файлу по умолчанию для выходных файлов. Сгенерированные PNG‑файлы сохраняются в текущем рабочем каталоге приложения.

```python
def __init__(self):
    ...
```

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

## __init__ {#file_path_format}

Инициализирует новый экземпляр [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Для примера кода см. документацию.

```python
def __init__(self, file_path_format):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path_format | `str` | Формат пути к файлу, например `'page_{0}.png'`. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `file_path_format` равно None или пустой. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

### См. также
* class [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
