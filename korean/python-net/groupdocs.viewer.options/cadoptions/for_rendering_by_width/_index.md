---
title: "for_rendering_by_width 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "너비 기반 렌더링을 위해 CadOptions 클래스의 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/
is_root: false
weight: 1030
---


## for_rendering_by_width {#width}

너비 기준으로 렌더링하기 위해 [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) 클래스의 인스턴스를 초기화합니다.

```python
def for_rendering_by_width(cls, width):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| width | `int` | 출력 결과의 너비(픽셀 단위). |

**Returns:** CadOptions: New instance of the `CadOptions` class for rendering by width.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `width`가 0 이하인 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # CAD 파일 로드
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True
        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### 참고
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
