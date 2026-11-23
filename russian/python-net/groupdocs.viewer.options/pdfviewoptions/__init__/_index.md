---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует экземпляр PdfViewOptions."
type: docs
url: /ru/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_file_stream}

Инициализирует экземпляр [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/).

Для примера кода см. документацию по адресу https://docs.groupdocs.com/viewer/net/rendering-to-pdf/.

```python
def __init__(self, create_file_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | Метод, который создает поток, используемый для записи данных выходного файла. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `create_file_stream` равно `None`. |

## __init__ {#create_file_stream-release_file_stream}

Инициализирует новый экземпляр PdfViewOptions.

Для примера кода см. документацию.

```python
def __init__(self, create_file_stream, release_file_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | Вызываемый объект, возвращающий поток `io.RawIOBase`, используемый для записи данных выходного файла. |
| release_file_stream | `ReleaseFileStream` | Вызываемый объект, освобождающий поток, созданный методом, назначенным `create_file_stream`. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `release_file_stream` равно None. |

## __init__ {#file_stream_factory}

Инициализирует экземпляр PdfViewOptions.

Для примера кода см. документацию: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

```python
def __init__(self, file_stream_factory):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_stream_factory | `IFileStreamFactory` | Фабрика, реализующая методы создания и освобождения потока выходного файла. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Выбрасывается, когда `file_stream_factory` равно None. |

## __init__

Инициализирует экземпляр PdfViewOptions.

Этот конструктор инициализирует PdfViewOptions с `"output.pdf"` в качестве формата пути к файлу вывода. Файл вывода будет помещён в текущий рабочий каталог приложения.

```python
def __init__(self):
    ...
```

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

## __init__ {#output_file_path}

Инициализирует экземпляр класса [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/).

Для примера кода см. документацию.

```python
def __init__(self, output_file_path):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| output_file_path | `str` | Путь к файлу PDF вывода. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `output_file_path` имеет значение None или пустой. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### См. также
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
