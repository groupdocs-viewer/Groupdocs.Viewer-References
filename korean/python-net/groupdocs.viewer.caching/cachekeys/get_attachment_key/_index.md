---
title: "get_attachment_key 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "첨부 파일을 나타내는 캐시 항목에 대한 고유 식별자를 반환합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.caching/cachekeys/get_attachment_key/
is_root: false
weight: 1010
---


## get_attachment_key {#attachment_id}

첨부 파일을 나타내는 캐시 항목에 대한 고유 식별자를 반환합니다.

```python
def get_attachment_key(cls, attachment_id):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attachment_id | `str` | 첨부 파일의 고유 식별자(단일 파일 컨텍스트에서). |

**Returns:** str: Unique identifier for the cache entry that represents attachment file.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `attachment_id`가 null이거나 비어 있을 때 발생합니다. |

### 참고
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
