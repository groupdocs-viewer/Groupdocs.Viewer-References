---
title: "VisioRenderingOptions 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Visio 문서 렌더링 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/visiorenderingoptions/
is_root: false
weight: 350
---


## VisioRenderingOptions class

Visio 문서 렌더링 옵션을 나타냅니다.

자세한 내용은 문서를 참조하십시오.

VisioRenderingOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/__init__/) | 다음 클래스의 인스턴스를 초기화합니다: [`VisioRenderingOptions`](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/). |

### 속성
| 속성 | 설명 |
| :- | :- |
| [figure_width](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/figure_width/) | 그림의 너비; 높이는 자동으로 계산됩니다. 기본값은 100입니다. |
| [render_figures_only](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/render_figures_only/) | 이 속성은 다이어그램이 아니라 Visio 그림만 렌더링합니다. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_visio_shapes_only():
    # Visio 문서 로드
    with Viewer("map.vsdx") as viewer:
        # Visio 파일을 PDF로 변환합니다.
        view_options = PdfViewOptions("render_visio_shapes_only/visio_shapes_only.pdf")
        # 마스터 도형만 렌더링합니다.
        view_options.visio_rendering_options.render_figures_only = True
        # 도형 너비를 픽셀 단위로 지정합니다.
        view_options.visio_rendering_options.figure_width = 200
        viewer.view(view_options)

if __name__ == "__main__":
    render_visio_shapes_only()
```

### 참고
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
