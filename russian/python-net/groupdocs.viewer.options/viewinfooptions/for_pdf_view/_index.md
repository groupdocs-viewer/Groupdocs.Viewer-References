---
title: "метод for_pdf_view"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует экземпляр ViewInfoOptions для получения информации о представлении при рендеринге в PDF."
type: docs
url: /ru/python-net/groupdocs.viewer.options/viewinfooptions/for_pdf_view/
is_root: false
weight: 1050
---


## for_pdf_view

Инициализирует экземпляр ViewInfoOptions для получения информации о представлении при рендеринге в PDF.

```python
def for_pdf_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Пример

```python
    from groupdocs.viewer.options import ViewInfoOptions

    # Создать параметры информации о представлении для формата PDF
    view_info_options_pdf = ViewInfoOptions.for_pdf_view()
    ```

### См. также
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
