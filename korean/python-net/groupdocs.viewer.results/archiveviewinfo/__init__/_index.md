---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "ArchiveViewInfo의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

새 인스턴스 [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/)를 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

새 ArchiveViewInfo 인스턴스를 초기화합니다.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_type | `FileType` | 파일의 유형입니다. |
| pages | `List[Page]` | 볼 페이지 목록입니다. |
| folders | `List[str]` | 아카이브 파일에 포함된 폴더 목록. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `folders`가 None인 경우. |

### 참고
* class [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/)
