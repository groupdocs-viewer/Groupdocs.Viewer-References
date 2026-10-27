---
title: "워터마크 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "텍스트 워터마크를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/watermark/
is_root: false
weight: 360
---


## Watermark class

텍스트 워터마크를 나타냅니다.

자세한 내용은 온라인 문서를 참조하십시오.

Watermark 유형은 다음 멤버를 제공합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/watermark/__init__/#text) | [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/) 클래스의 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [color](/viewer/python-net/groupdocs.viewer.options/watermark/color/) | 워터마크 색상. 기본값은 `Rgb24Color.known_colors.css_level1.red`입니다. |
| [font_name](/viewer/python-net/groupdocs.viewer.options/watermark/font_name/) | 워터마크에 사용되는 글꼴 이름. |
| [position](/viewer/python-net/groupdocs.viewer.options/watermark/position/) | 워터마크 위치. 기본값은 `Position.diagonal`입니다. |
| [size](/viewer/python-net/groupdocs.viewer.options/watermark/size/) | 워터마크 크기. 기본값은 [`Size.full_size`](/viewer/python-net/groupdocs.viewer.options/size/full_size/)입니다. |
| [text](/viewer/python-net/groupdocs.viewer.options/watermark/text/) | 워터마크 텍스트. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # 문서 로드
    with Viewer("sample.docx") as viewer:
        # HTML 파일을 생성합니다.
        viewOptions = HtmlViewOptions.for_embedded_resources(
            "add_text_watermark/output-watermark.html"
        )
        # 워터마크를 추가합니다.
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```

### Guides
`Watermark`를 사용하는 작업 가이드:

* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)

### 참고
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
