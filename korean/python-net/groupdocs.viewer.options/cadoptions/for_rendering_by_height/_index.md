---
title: "for_rendering_by_height 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "높이 기준으로 렌더링하기 위해 CadOptions 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/
is_root: false
weight: 1010
---


## for_rendering_by_height {#height}

높이 기준으로 렌더링하기 위해 CadOptions 인스턴스를 초기화합니다.

코드 예제는 문서를 참조하십시오.

```python
def for_rendering_by_height(cls, height):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| height | `int` | 출력 결과의 높이(픽셀 단위)입니다. |

**Returns:** CadOptions: New instance configured for rendering by height.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `height`가 0 이하일 때. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def render_by_height():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("output_by_height.png")
        png_options.cad_options = CadOptions.for_rendering_by_height(1500)
        viewer.view(png_options)
```

### 참고
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
