---
title: "get_resource_filter 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Resource 객체를 나타내는 캐시 항목을 검색하기 위한 필터 문자열을 반환합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.caching/cachekeys/get_resource_filter/
is_root: false
weight: 1060
---


## get_resource_filter {#page_number}

[`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/) 객체를 나타내는 캐시 항목을 검색하기 위한 필터 문자열을 반환합니다.

```python
def get_resource_filter(cls, page_number):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| page_number | `int` | 페이지 번호. |

**Returns:** str: Filter string to search for cache entries that represent `Resource` objects.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `page_number`가 0 이하일 때. |

### 참고
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
