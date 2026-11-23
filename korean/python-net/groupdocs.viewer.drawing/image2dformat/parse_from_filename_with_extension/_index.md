---
title: "parse_from_filename_with_extension 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "지정된 파일 이름에서 추출한 파일 확장자에 해당하는 Image2DFormat 값을 반환합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_filename_with_extension/
is_root: false
weight: 1050
---


## parse_from_filename_with_extension {#filename}

지정된 파일 이름에서 추출한 파일 확장자에 해당하는 Image2DFormat 값을 반환합니다.

```python
def parse_from_filename_with_extension(cls, filename):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| filename | `str` | 임의의 파일 이름이며, 상대 경로나 전체 경로일 수 있습니다. |

**Returns:** Image2DFormat: Image2DFormat value. Returns `Image2DFormat.undefined` if the extension cannot be recognized.

### 참고
* class [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/)
