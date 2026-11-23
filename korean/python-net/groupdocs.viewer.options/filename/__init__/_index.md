---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "FileName 클래스의 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/filename/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

[`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/) 클래스의 인스턴스를 초기화합니다.

```python
def __init__(self, file_name):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_name | `str` | 파일 이름입니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `file_name`이 None인 경우. |

### 예시

```python
from groupdocs.viewer.options import FileName

# 사용자 지정 아카이브 이름으로 FileName 인스턴스를 생성합니다.
custom_name = FileName("Sample Files")
```

### 참고
* class [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/)
