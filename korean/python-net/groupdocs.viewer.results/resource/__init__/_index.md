---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "새 Resource 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/resource/__init__/
is_root: false
weight: 10
---


## __init__

새 Resource 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#file_name-nested}

새 Resource 인스턴스를 초기화합니다.

```python
def __init__(self, file_name, nested):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_name | `str` | 리소스 파일 이름. |
| nested | `bool` | 리소스가 다른 리소스 내부에 존재하는지 여부를 나타냅니다. 예: CSS 또는 SVG 리소스에 포함된 글꼴 리소스. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `file_name`이 None이거나 비어 있을 때 발생합니다. |

### 참고
* class [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/)
