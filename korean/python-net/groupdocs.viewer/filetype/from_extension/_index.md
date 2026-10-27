---
title: "from_extension 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "파일 확장자를 파일 유형에 매핑합니다."
type: docs
url: /ko/python-net/groupdocs.viewer/filetype/from_extension/
is_root: false
weight: 1090
---


## from_extension {#extension}

파일 확장자를 파일 유형에 매핑합니다.

```python
def from_extension(cls, extension):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| extension | `str` | 마침표 '.'가 있거나 없는 파일 확장자. |

**Returns:** FileType: The corresponding file type if supported; otherwise `FileType.unknown`.

### 참고
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
