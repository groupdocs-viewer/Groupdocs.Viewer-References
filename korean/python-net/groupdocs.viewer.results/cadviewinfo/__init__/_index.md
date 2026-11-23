---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "새 CadViewInfo 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/cadviewinfo/__init__/
is_root: false
weight: 10
---


## __init__ {#file_type-pages-layers-layouts}

새 CadViewInfo 인스턴스를 초기화합니다.

```python
def __init__(self, file_type, pages, layers, layouts):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_type | `FileType` | 파일의 유형입니다. |
| pages | `List[Page]` | 볼 페이지 목록입니다. |
| layers | `List[Layer]` | CAD 도면에 포함된 레이어 목록입니다. |
| layouts | `List[Layout]` | CAD 도면에 포함된 레이어 목록입니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `layouts`가 None일 때 발생합니다. |

### 참고
* class [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/)
