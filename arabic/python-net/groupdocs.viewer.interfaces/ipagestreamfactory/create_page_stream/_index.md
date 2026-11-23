---
title: "طريقة create_page_stream"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "ينشئ التدفق المستخدم لكتابة بيانات الصفحات الناتجة."
type: docs
url: /ar/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/
is_root: false
weight: 1010
---


## create_page_stream {#page_number}

ينشئ التدفق المستخدم لكتابة بيانات الصفحات الناتجة.

```python
def create_page_stream(self, page_number):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| page_number | `int` | رقم الصفحة. |

**Returns:** io.RawIOBase: Stream used to write output page data.

### مثال

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

### انظر أيضًا
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
