---
title: "метод for_png_view"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует экземпляр класса ViewInfoOptions для получения информации о представлении при рендеринге в PNG."
type: docs
url: /ru/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/
is_root: false
weight: 1060
---


## for_png_view

Инициализирует экземпляр класса [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) для получения информации о представлении при рендеринге в PNG.

```python
def for_png_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the `ViewInfoOptions` class.

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Создать параметры информации о представлении для формата PNG
view_info_options_png = ViewInfoOptions.for_png_view()

# Загрузить документ и получить информацию о представлении для PNG
with Viewer("sample.xml") as viewer:
    result_png = viewer.get_view_info(view_info_options_png)
```

## for_png_view {#extract_text}

Инициализирует экземпляр класса ViewInfoOptions для получения информации о представлении при рендеринге в PNG.

```python
def for_png_view(cls, extract_text):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| extract_text | `bool` | Включает извлечение текста. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Пример

```python
from groupdocs.viewer.options import ViewInfoOptions

# Создать параметры информации о представлении для формата PNG с включенным извлечением текста
options = ViewInfoOptions.for_png_view(extractText=True)
```

### См. также
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
