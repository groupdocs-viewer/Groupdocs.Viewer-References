---
title: "from_html_view_options 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "HtmlViewOptions 객체를 기반으로 ViewInfoOptions 클래스의 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/
is_root: false
weight: 1080
---


## from_html_view_options {#options}

HtmlViewOptions 객체를 기반으로 ViewInfoOptions 클래스의 인스턴스를 초기화합니다.

```python
def from_html_view_options(cls, options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| options | `HtmlViewOptions` | HTML 보기 옵션. |

**Returns:** A new ViewInfoOptions instance.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `options`가 None인 경우. |

### 예시

```python
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions

html_opts = HtmlViewOptions()
view_info_opts = ViewInfoOptions.from_html_view_options(html_opts)
```

### 참고
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
