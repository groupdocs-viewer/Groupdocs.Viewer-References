---
title: "метод create_resource_stream"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Создаёт поток, используемый для записи данных выходных HTML‑ресурсов."
type: docs
url: /ru/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/
is_root: false
weight: 1010
---


## create_resource_stream {#page_number-resource}

Создаёт поток, используемый для записи данных выходных HTML‑ресурсов.

```python
def create_resource_stream(self, page_number, resource):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| page_number | `int` | Номер страницы. |
| resource | `Resource` | HTML‑ресурс, такой как шрифт, стиль, изображение или графика. |

**Returns:** io.RawIOBase: Stream used to write output resource data.

### Пример

```python
from groupdocs.viewer import Viewer

viewer = Viewer()
factory = viewer.resource_stream_factory

# Создать поток для CSS‑ресурса на странице 1
stream = factory.create_resource_stream(pageNumber=1, resource="style.css")
with stream:
    stream.write(b"body { font-family: Arial; }")
```

### См. также
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
