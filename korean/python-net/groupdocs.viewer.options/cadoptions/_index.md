---
title: "CadOptions 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "CAD 도면을 렌더링하기 위한 옵션."
type: docs
url: /ko/python-net/groupdocs.viewer.options/cadoptions/
is_root: false
weight: 30
---


## CadOptions class

CAD 도면을 렌더링하기 위한 옵션.

자세한 정보와 코드 예제는 Render CAD drawings and models as HTML, PDF, and image files 및 Specify rendering options for CAD files 문서를 참조하십시오.

CadOptions 형식은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [for_rendering_by_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/#height) | 높이 기준으로 렌더링하기 위해 CadOptions 인스턴스를 초기화합니다. |
| [for_rendering_by_scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/#scale_factor) | 스케일 팩터 기준으로 렌더링하기 위해 CadOptions 인스턴스를 초기화합니다. |
| [for_rendering_by_width](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/#width) | 너비 기준으로 렌더링하기 위해 [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) 클래스의 인스턴스를 초기화합니다. |
| [for_rendering_by_width_and_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/#width-height) | 너비와 높이 기준으로 렌더링하기 위해 CadOptions 클래스의 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [background_color](/viewer/python-net/groupdocs.viewer.options/cadoptions/background_color/) | 이미지 배경 색상입니다. |
| [enable_performance_conversion_mode](/viewer/python-net/groupdocs.viewer.options/cadoptions/enable_performance_conversion_mode/) | 모든 CAD 형식에 대해 성능 중심 변환 모드를 활성화하는 플래그로, True로 설정하면 출력 품질이 감소하는 대신 변환 속도가 빨라집니다; 최대 품질을 위해 기본값은 False입니다. |
| [height](/viewer/python-net/groupdocs.viewer.options/cadoptions/height/) | 출력 결과의 높이(픽셀 단위)입니다. |
| [layers](/viewer/python-net/groupdocs.viewer.options/cadoptions/layers/) | 렌더링할 CAD 도면 레이어입니다. |
| [layout_name](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) | 렌더링할 특정 레이아웃의 이름입니다. 레이아웃 이름은 대소문자를 구분합니다. |
| [pc3_file](/viewer/python-net/groupdocs.viewer.options/cadoptions/pc3_file/) | PC3 플로터 구성 파일입니다. |
| [render_layouts](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) | CAD 문서의 레이아웃을 렌더링할지 여부를 나타내는 플래그입니다. |
| [scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/scale_factor/) | 스케일 팩터입니다. 1보다 큰 값은 출력 결과를 확대하고, 0과 1 사이의 값은 출력 결과를 축소합니다. |
| [tiles](/viewer/python-net/groupdocs.viewer.options/cadoptions/tiles/) | 렌더링할 그리기 영역. |
| [width](/viewer/python-net/groupdocs.viewer.options/cadoptions/width/) | 출력 결과의 너비(픽셀 단위). |

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
        # 너비 기준으로 렌더링하고 성능 모드를 활성화
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True

        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### 참고
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
