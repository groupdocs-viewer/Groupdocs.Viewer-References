---
title: "FileName 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "파일 이름."
type: docs
url: /ko/python-net/groupdocs.viewer.options/filename/
is_root: false
weight: 60
---


## FileName class

파일 이름.

FileName 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/filename/__init__/#file_name) | [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/) 클래스의 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.options/filename/to_string/) | 현재 객체를 나타내는 문자열을 반환합니다. |

### 필드
| 필드 | 설명 |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.options/filename/empty/) | 빈 파일 이름입니다. |
| [SOURCE](/viewer/python-net/groupdocs.viewer.options/filename/source/) | 소스 파일의 이름입니다. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, FileName

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "output/archive_{0}.html"
    )
    view_options.archive_options.file_name = FileName("Sample Files")
    viewer.view(view_options)
```

### 참고
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
