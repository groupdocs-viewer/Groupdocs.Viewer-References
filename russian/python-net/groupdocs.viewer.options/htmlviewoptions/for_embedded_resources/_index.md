---
title: "Метод for_embedded_resources"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует экземпляр HtmlViewOptions для рендеринга HTML с встроенными ресурсами."
type: docs
url: /ru/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/
is_root: false
weight: 1010
---


## for_embedded_resources {#create_page_stream}

Инициализирует экземпляр HtmlViewOptions для рендеринга HTML с встроенными ресурсами.

Для получения дополнительных сведений см. документацию.

```python
def for_embedded_resources(cls, create_page_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Метод, который создает поток, используемый для записи данных выходных страниц. |

**Returns:** HtmlViewOptions: New instance configured for rendering HTML with embedded resources.

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `create_page_stream` равно None. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#create_page_stream-release_page_stream}

Инициализирует экземпляр класса [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) для рендеринга в HTML с встроенными ресурсами.

```python
def for_embedded_resources(cls, create_page_stream, release_page_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Метод, который создает поток, используемый для записи данных выходных страниц. |
| release_page_stream | `ReleasePageStream` | Метод, который освобождает поток, созданный методом, назначенным параметру `create_page_stream`. |

**Returns:** HtmlViewOptions: New instance of the `HtmlViewOptions` class for rendering into HTML with embedded resources.

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `release_page_stream` равно `None`. Пример кода см. в документации. |

## for_embedded_resources {#page_stream_factory}

Инициализирует экземпляр HtmlViewOptions для рендеринга в HTML с встроенными ресурсами.

Пример кода см. в документации по адресу https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources.

```python
def for_embedded_resources(cls, page_stream_factory):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Фабрика, реализующая методы создания и освобождения потока выходных страниц. |

**Returns:** HtmlViewOptions: New instance of HtmlViewOptions for rendering into HTML with embedded resources.

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда page_stream_factory равно None. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources

Инициализирует экземпляр класса [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) со встроенными ресурсами.

Для примера кода см. документацию.

```python
def for_embedded_resources(cls):
    ...
```

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#file_path_format}

Инициализирует экземпляр HtmlViewOptions для встроенных ресурсов.

Для примера кода см. документацию.

```python
def for_embedded_resources(cls, file_path_format):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path_format | `str` | Формат пути к файлу, например 'page_{0}.html'. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `file_path_format` равно None или пустой. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### См. также
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
