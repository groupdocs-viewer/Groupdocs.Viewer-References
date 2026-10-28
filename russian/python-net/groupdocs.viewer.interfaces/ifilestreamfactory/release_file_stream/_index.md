---
title: "метод release_file_stream"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Освобождает поток, созданный методом IFileStreamFactory.createfilestream."
type: docs
url: /ru/python-net/groupdocs.viewer.interfaces/ifilestreamfactory/release_file_stream/
is_root: false
weight: 1020
---


## release_file_stream {#file_stream}

Освобождает поток, созданный методом [`IFileStreamFactory.create_file_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ifilestreamfactory/create_file_stream/).

```python
def release_file_stream(self, file_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_stream | `io.RawIOBase` | Поток, созданный методом `IFileStreamFactory.create_file_stream`. |

**Returns:** None.

### См. также
* class [`IFileStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ifilestreamfactory/)
