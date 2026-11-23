---
title: "get_file_key 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "파일을 나타내는 캐시 항목에 대한 고유 식별자를 반환합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.caching/cachekeys/get_file_key/
is_root: false
weight: 1040
---


## get_file_key {#extension}

파일을 나타내는 캐시 항목에 대한 고유 식별자를 반환합니다.

```python
def get_file_key(cls, extension):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| extension | `str` | 파일 이름 접미사(마침표 \".\" 포함) 예: \".doc\". |

**Returns:** str: Unique identifier for the cache entry that represents file.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `extension`이 None이거나 비어 있는 경우. |

### 참고
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
