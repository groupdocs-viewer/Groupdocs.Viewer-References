---
title: "метод create_page_stream"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Создаёт поток, используемый для записи данных выходных страниц."
type: docs
url: /ru/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/
is_root: false
weight: 1010
---


## create_page_stream {#page_number}

Создаёт поток, используемый для записи данных выходных страниц.

```python
def create_page_stream(self, page_number):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| page_number | `int` | Номер страницы. |

**Returns:** io.RawIOBase: Stream used to write output page data.

### Пример

```python
    import io
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import PngViewOptions

    page_buffers = {}

    def create_page_stream(page_number):
        buf = io.BytesIO()
        page_buffers[page_number] = buf
        return buf

    with Viewer("input.docx") as viewer:
        viewer.view(PngViewOptions(create_page_stream))
    ```

### См. также
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
