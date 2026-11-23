---
title: "search 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "텍스트 검색을 수행하고 제공된 옵션에 따라 로드된 문서에서 찾은 텍스트를 강조 표시합니다."
type: docs
url: /ko/python-net/groupdocs.viewer/viewer/search/
is_root: false
weight: 1110
---


## search {#options}

텍스트 검색을 수행하고 제공된 옵션에 따라 로드된 문서에서 찾은 텍스트를 강조 표시합니다.

```python
def search(self, options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| options | `SearchHighlightOptions` | 검색할 텍스트 구문을 포함한 검색 및 강조 옵션. None이면 안 됩니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `options`가 None인 경우. |

### 참고
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
