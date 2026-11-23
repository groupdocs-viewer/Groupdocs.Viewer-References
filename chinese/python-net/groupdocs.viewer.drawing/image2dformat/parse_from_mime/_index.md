---
title: "parse_from_mime 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "返回与指定 MIME 代码对应的 Image2DFormat 值。"
type: docs
url: /zh/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_mime/
is_root: false
weight: 1060
---


## parse_from_mime {#mime_code}

返回一个 [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/) 值，该值对应于指定的 MIME 代码。

```python
def parse_from_mime(cls, mime_code):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| mime_code | `str` | 任意 MIME 代码。 |

**Returns:** Image2DFormat: `Image2DFormat` value. Returns `Image2DFormat.undefined` if the extension cannot be recognized.

### 另见
* class [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/)
