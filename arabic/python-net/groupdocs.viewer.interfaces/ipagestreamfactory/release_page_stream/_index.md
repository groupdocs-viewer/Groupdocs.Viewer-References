---
title: "طريقة release_page_stream"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يطلق التدفق الذي تم إنشاؤه بواسطة طريقة IPageStreamFactory.createpagestream."
type: docs
url: /ar/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream/
is_root: false
weight: 1030
---


## release_page_stream {#page_number-page_stream}

يطلق التدفق الذي تم إنشاؤه بواسطة طريقة [`IPageStreamFactory.create_page_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/).

```python
def release_page_stream(self, page_number, page_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| page_number | `int` | رقم الصفحة. |
| page_stream | `io.RawIOBase` | التدفق الذي تم إنشاؤه بواسطة طريقة `IPageStreamFactory.create_page_stream`. |

### انظر أيضًا
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
