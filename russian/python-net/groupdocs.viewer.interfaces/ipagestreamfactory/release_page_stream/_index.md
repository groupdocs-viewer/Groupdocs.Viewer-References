---
title: "метод release_page_stream"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Освобождает поток, созданный методом IPageStreamFactory.createpagestream."
type: docs
url: /ru/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream/
is_root: false
weight: 1030
---


## release_page_stream {#page_number-page_stream}

Освобождает поток, созданный методом [`IPageStreamFactory.create_page_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/).

```python
def release_page_stream(self, page_number, page_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| page_number | `int` | Номер страницы. |
| page_stream | `io.RawIOBase` | Поток, созданный методом `IPageStreamFactory.create_page_stream`. |

### См. также
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
