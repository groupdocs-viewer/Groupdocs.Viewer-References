---
title: "from_file_path 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "파일 확장자를 추출하고 파일 유형에 매핑합니다."
type: docs
url: /ko/python-net/groupdocs.viewer/filetype/from_file_path/
is_root: false
weight: 1100
---


## from_file_path {#file_path}

파일 확장자를 추출하고 파일 유형에 매핑합니다.

```python
def from_file_path(cls, file_path):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 파일 이름 또는 파일 경로입니다. |

**Returns:** FileType: The detected file type if supported; otherwise returns `FileType.unknown`.

### 참고
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
