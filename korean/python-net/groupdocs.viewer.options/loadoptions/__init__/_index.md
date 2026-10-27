---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "LoadOptions 클래스의 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/loadoptions/__init__/
is_root: false
weight: 10
---


## __init__

[`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/) 클래스의 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#file_type}

새 LoadOptions 인스턴스를 초기화합니다.

코드 예제는 문서를 참조하십시오.

```python
def __init__(self, file_type):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_type | `FileType` | 열 파일의 유형입니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `file_type`이 None인 경우. |

### 예시

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

load_options = LoadOptions(FileType.MD)  # specify the file type
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### 참고
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
