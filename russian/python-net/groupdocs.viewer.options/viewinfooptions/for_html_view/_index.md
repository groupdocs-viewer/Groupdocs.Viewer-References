---
title: "Метод for_html_view"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует экземпляр ViewInfoOptions для получения информации о представлении при рендеринге в HTML."
type: docs
url: /ru/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/
is_root: false
weight: 1010
---


## for_html_view

Инициализирует экземпляр ViewInfoOptions для получения информации о представлении при рендеринге в HTML.

```python
def for_html_view(cls):
    ...
```

**Returns:** ViewInfoOptions: A new ViewInfoOptions instance.

### Пример

```python
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import ViewInfoOptions

    # Создайте параметры информации о представлении для формата HTML (одна страница)
    options = ViewInfoOptions.for_html_view(True)

    # Загрузите документ и получите информацию о представлении
    with Viewer("sample.xml") as viewer:
        info = viewer.get_view_info(options)
    ```

## for_html_view {#render_single_page}

Инициализирует экземпляр ViewInfoOptions для получения информации о представлении при рендеринге в HTML.

```python
def for_html_view(cls, render_single_page):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| render_single_page | `bool` | Включает рендеринг HTML‑контента в одну страницу. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Получить информацию о представлении для HTML с одной страницей
options = ViewInfoOptions.for_html_view(True)

with Viewer("sample.xml") as viewer:
    info = viewer.get_view_info(options)
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### См. также
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
