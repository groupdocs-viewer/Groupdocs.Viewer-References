---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "OutlookViewInfo의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

[`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/)의 새 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

새 OutlookViewInfo 인스턴스를 초기화합니다.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_type | `FileType` | 파일의 유형입니다. |
| pages | `List[Page]` | 볼 페이지 목록입니다. |
| folders | `List[str]` | Outlook 데이터 파일에 포함된 폴더 목록입니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `folders`가 None일 때 발생합니다. |

### 참고
* class [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/)
