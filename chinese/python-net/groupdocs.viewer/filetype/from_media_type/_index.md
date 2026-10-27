---
title: "from_media_type 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "将文件媒体类型映射到 FileType（例如，'application/pdf' 映射到 FileType.pdf）。"
type: docs
url: /zh/python-net/groupdocs.viewer/filetype/from_media_type/
is_root: false
weight: 1110
---


## from_media_type {#media_type}

将文件媒体类型映射到 [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)（例如，'application/pdf' 映射到 [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)）。

```python
def from_media_type(cls, media_type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| media_type | `str` | 文件媒体类型，例如 ``application/pdf``。 |

**Returns:** FileType: Corresponding file type when found; otherwise returns the default `FileType.unknown`.

### 另见
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
