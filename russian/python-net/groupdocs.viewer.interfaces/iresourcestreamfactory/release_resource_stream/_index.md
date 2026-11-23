---
title: "метод release_resource_stream"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Освобождает поток, созданный методом IResourceStreamFactory.createresourcestream."
type: docs
url: /ru/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/release_resource_stream/
is_root: false
weight: 1050
---


## release_resource_stream {#page_number-resource-resource_stream}

Освобождает поток, созданный методом [`IResourceStreamFactory.create_resource_stream`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/).

```python
def release_resource_stream(self, page_number, resource, resource_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| page_number | `int` | Номер страницы. |
| resource | `Resource` | HTML‑ресурс, такой как шрифт, стиль, изображение или графика. |
| resource_stream | `io.RawIOBase` | Поток, созданный методом `IResourceStreamFactory.create_resource_stream`. |

**Returns:** None.

### См. также
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
