---
title: "ViewerSettings 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Viewer 동작을 사용자 정의하기 위한 설정을 정의합니다."
type: docs
url: /ko/python-net/groupdocs.viewer/viewersettings/
is_root: false
weight: 110
---


## ViewerSettings class

[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 동작을 사용자 정의하기 위한 설정을 정의합니다.

ViewerSettings 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache-logger) | 새 ViewerSettings 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache) | 새 ViewerSettings 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#logger) | 새 ViewerSettings 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [cache](/viewer/python-net/groupdocs.viewer/viewersettings/cache/) | 렌더링 결과를 저장하는 데 사용되는 캐시 구현입니다. |
| [logger](/viewer/python-net/groupdocs.viewer/viewersettings/logger/) | 로그(오류, 경고, 추적)를 기록하는 데 사용되는 로거 구현입니다. |

### 예시

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "example/page_{0}.html"
    )
    viewer.view(html_options)
```

### 참고
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
