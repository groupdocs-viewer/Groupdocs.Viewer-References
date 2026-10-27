---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "LotusNotesViewInfo의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/lotusnotesviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

새 [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/) 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-notes_count}

새 [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/) 클래스 인스턴스를 초기화합니다.

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
| `ValueError` | `notes_count`가 None일 때 발생합니다. |

### 참고
* class [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/)
