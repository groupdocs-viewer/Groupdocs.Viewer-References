---
title: "Метод from_media_type"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Отображает тип медиа файла на FileType (например, 'application/pdf' отображается в FileType.pdf)."
type: docs
url: /ru/python-net/groupdocs.viewer/filetype/from_media_type/
is_root: false
weight: 1110
---


## from_media_type {#media_type}

Отображает тип медиа файла в [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) (например, 'application/pdf' отображается в [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)).

```python
def from_media_type(cls, media_type):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| media_type | `str` | Тип медиа файла, например, ``application/pdf``. |

**Returns:** FileType: Corresponding file type when found; otherwise returns the default `FileType.unknown`.

### См. также
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
