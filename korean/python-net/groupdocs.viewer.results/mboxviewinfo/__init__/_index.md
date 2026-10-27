---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "MboxViewInfo의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/mboxviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

새 [`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/) 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-notes_count}

새 [`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/) 인스턴스를 초기화합니다.

```python
def __init__(self, file_type, pages, notes_count):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_type | `FileType` | 파일의 유형입니다. |
| pages | `List[Page]` | 볼 페이지 목록입니다. |
| notes_count | `int` | Lotus 데이터베이스 저장 파일에 포함된 노트 수. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | 만약 `notes_count`가 None이면. |

### 참고
* class [`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/)
