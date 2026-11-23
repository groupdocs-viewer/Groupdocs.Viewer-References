---
title: "parse_from_mime 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "지정된 MIME 코드에 해당하는 Image2DFormat 값을 반환합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_mime/
is_root: false
weight: 1060
---


## parse_from_mime {#mime_code}

지정된 MIME 코드에 해당하는 [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/) 값을 반환합니다.

```python
def parse_from_mime(cls, mime_code):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| mime_code | `str` | 임의의 MIME 코드. |

**Returns:** Image2DFormat: `Image2DFormat` value. Returns `Image2DFormat.undefined` if the extension cannot be recognized.

### 참고
* class [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/)
