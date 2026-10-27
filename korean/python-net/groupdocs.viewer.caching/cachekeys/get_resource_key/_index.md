---
title: "get_resource_key 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Resource 객체를 나타내는 캐시 항목에 대한 고유 식별자를 반환합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.caching/cachekeys/get_resource_key/
is_root: false
weight: 1070
---


## get_resource_key {#page_number-resource}

[`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/) 객체를 나타내는 캐시 항목에 대한 고유 식별자를 반환합니다.

```python
def get_resource_key(cls, page_number, resource):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| page_number | `int` | 페이지 번호. |
| resource | `Resource` | HTML 리소스. |

**Returns:** str: Unique identifier for the cache entry that represents `Resource` object.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `page_number`가 0 이하이거나 `resource`가 None인 경우. |

### 참고
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
