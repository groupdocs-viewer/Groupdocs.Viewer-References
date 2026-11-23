---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "새 PdfViewInfo 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

새 PdfViewInfo 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-printing_allowed}

새 PdfViewInfo 인스턴스를 초기화합니다.

```python
def __init__(self, file_type, pages, printing_allowed):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_type | `FileType` | 파일의 유형입니다. |
| pages | `List[Page]` | 볼 페이지 목록입니다. |
| printing_allowed | `bool` | 인쇄 권한 표시기. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `pages`가 None일 때. |

### 참고
* class [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/)
