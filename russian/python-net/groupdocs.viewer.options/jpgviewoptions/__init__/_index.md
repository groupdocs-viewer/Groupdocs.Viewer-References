---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует экземпляр класса JpgViewOptions."
type: docs
url: /ru/python-net/groupdocs.viewer.options/jpgviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Инициализирует экземпляр класса JpgViewOptions.

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

Инициализирует экземпляр класса JpgViewOptions.

Для примера кода см. документацию.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable, который создает поток, используемый для записи данных выходных страниц. |
| release_page_stream | `ReleasePageStream` | Callable, который освобождает поток, созданный методом, назначенным делегату, переданному в `create_page_stream`. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `release_page_stream` равно None. |

## __init__ {#page_stream_factory}

Инициализирует экземпляр класса [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/).

Для примера кода см. документацию по адресу https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg.

```python
def __init__(self, page_stream_factory):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Фабрика, реализующая методы создания и освобождения потока выходных страниц. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `page_stream_factory` равно None. |

## __init__

Инициализирует экземпляр JpgViewOptions.

Этот конструктор инициализирует экземпляр [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) с `\"p_{0}.jpg\"` в качестве формата пути к файлам вывода. Файлы вывода помещаются в текущий рабочий каталог приложения.

```python
def __init__(self):
    ...
```

### Пример

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

Инициализирует новый экземпляр [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/).

Для примера кода см. документацию.

```python
def __init__(self, file_path_format):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path_format | `str` | Формат пути к файлу, например `'page_{0}.jpg'`. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `file_path_format` равно None или пустой. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

def render_to_jpg():
    # Загрузите документ (например, файл Excel)
    with Viewer("invoice.xlsx") as viewer:
        # Создайте параметры просмотра JPEG с шаблоном имени файла.
        view_options = JpgViewOptions("output/excel_page_{0}.jpg")
        view_options.width = 800
        view_options.height = 900
        viewer.view(view_options)

if __name__ == "__main__":
    render_to_jpg()
```

### См. также
* class [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)
