---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует экземпляр класса LoadOptions."
type: docs
url: /ru/python-net/groupdocs.viewer.options/loadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует экземпляр класса [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type}

Инициализирует новый экземпляр LoadOptions.

Для примера кода см. документацию.

```python
def __init__(self, file_type):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_type | `FileType` | Тип открываемого файла. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `file_type` равно None. |

### Пример

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

load_options = LoadOptions(FileType.MD)  # specify the file type
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### См. также
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
