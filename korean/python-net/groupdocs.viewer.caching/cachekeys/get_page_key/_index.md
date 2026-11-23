---
title: "get_page_key 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "페이지 파일을 나타내는 캐시 항목에 대한 고유 식별자를 반환합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.caching/cachekeys/get_page_key/
is_root: false
weight: 1050
---


## get_page_key {#page_number-extension}

페이지 파일을 나타내는 캐시 항목에 대한 고유 식별자를 반환합니다.

```python
def get_page_key(cls, page_number, extension):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| page_number | `int` | 페이지 번호. |
| extension | `str` | 파일 이름 접미사(마침표 \".\" 포함) 예: \".doc\". |

**Returns:** str: Unique identifier for the cache entry that represents page file.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `extension`이 None이거나 비어 있을 때. |

### 참고
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
