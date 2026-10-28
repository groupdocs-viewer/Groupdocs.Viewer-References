---
title: "Метод for_jpg_view"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует экземпляр ViewInfoOptions для получения информации о представлении при рендеринге в JPG."
type: docs
url: /ru/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/
is_root: false
weight: 1030
---


## for_jpg_view

Инициализирует экземпляр [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) для получения информации о представлении при рендеринге в JPG.

```python
def for_jpg_view(cls):
    ...
```

**Returns:** A new `ViewInfoOptions` instance.

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

def get_jpg_view_info():
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_jpg_view())
        print("Document type:", info.file_type)
        print("Pages count:", len(info.pages))

if __name__ == "__main__":
    get_jpg_view_info()
```

## for_jpg_view {#extract_text}

Инициализирует экземпляр ViewInfoOptions для получения информации о представлении при рендеринге в JPG.

```python
def for_jpg_view(cls, extract_text):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| extract_text | `bool` | Включает извлечение текста. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### См. также
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
