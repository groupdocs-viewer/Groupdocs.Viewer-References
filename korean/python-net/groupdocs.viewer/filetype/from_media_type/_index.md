---
title: "from_media_type 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "파일 미디어 유형을 FileType에 매핑합니다 (예: 'application/pdf'는 FileType.pdf에 매핑됩니다)."
type: docs
url: /ko/python-net/groupdocs.viewer/filetype/from_media_type/
is_root: false
weight: 1110
---


## from_media_type {#media_type}

파일 미디어 유형을 [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)에 매핑합니다(예: 'application/pdf'는 [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)에 매핑됩니다).

```python
def from_media_type(cls, media_type):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| media_type | `str` | 파일 미디어 유형, 예: ``application/pdf``. |

**Returns:** FileType: Corresponding file type when found; otherwise returns the default `FileType.unknown`.

### 참고
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
