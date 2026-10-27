---
title: "from_rgb 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "지정된 빨강, 초록, 파랑 채널로부터 Argb32Color 값을 생성하고, 알파 채널은 완전 불투명으로 설정합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/
is_root: false
weight: 1090
---


## from_rgb {#red-green-blue}

지정된 빨강, 초록, 파랑 채널로부터 Argb32Color 값을 생성하고, 알파 채널은 완전 불투명으로 설정합니다.

```python
def from_rgb(cls, red, green, blue):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| red | `int` | 빨강 채널 값. |
| green | `int` | 초록 채널 값. |
| blue | `int` | 파랑 채널 값. |

**Returns:** Argb32Color: New Argb32Color value.

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.drawing import Argb32Color

with Viewer("sample.dwg") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.cad_options.background_color = Argb32Color.from_rgb(255, 255, 0)  # yellow
    viewer.view(view_options)
```

### 참고
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
