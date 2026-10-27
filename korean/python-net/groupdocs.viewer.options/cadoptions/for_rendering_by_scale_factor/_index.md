---
title: "for_rendering_by_scale_factor 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "스케일 팩터 기준으로 렌더링하기 위해 CadOptions 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/
is_root: false
weight: 1020
---


## for_rendering_by_scale_factor {#scale_factor}

스케일 팩터 기준으로 렌더링하기 위해 CadOptions 인스턴스를 초기화합니다.

코드 예제는 문서를 참조하십시오.

```python
def for_rendering_by_scale_factor(cls, scale_factor):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| scale_factor | `float` | 값이 1보다 크면 출력 결과가 확대되고, 0과 1 사이의 값은 출력 결과를 축소합니다. |

**Returns:** CadOptions: New instance of the CadOptions class for rendering by scale factor.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `scale_factor`가 0 이하일 때 발생합니다. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def set_image_size():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("set_image_size/image_with_size_limits.pdf")
        png_options.cad_options = CadOptions.for_rendering_by_scale_factor(0.5)
        viewer.view(png_options)

if __name__ == "__main__":
    set_image_size()
```

### 참고
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
