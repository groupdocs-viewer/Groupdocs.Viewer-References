---
title: "PdfOptions 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "PDF 문서로 렌더링하기 위한 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/pdfoptions/
is_root: false
weight: 160
---


## PdfOptions class

PDF 문서로 렌더링하기 위한 옵션을 나타냅니다.

자세한 내용은 문서를 참조하십시오.

PdfOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptions/__init__/) | PdfOptions 클래스의 새 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [disable_chars_grouping](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/) | 이 속성은 페이지 렌더링 중 정밀한 기호 위치 지정을 위해 기호 그룹화를 비활성화합니다. |
| [disable_copy_protection](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/) | 이 속성은 HTML로 렌더링할 때 콘텐츠 복사 방지를 비활성화합니다. |
| [disable_font_license_verifications](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/) | 이 속성은 현재 XPS/OXPS 문서의 모든 글꼴에 대한 라이선스 제한을 비활성화합니다. |
| [enable_font_hinting](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_font_hinting/) | 이 속성은 폰트 힌팅을 활성화합니다. |
| [enable_layered_rendering](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/) | 이 속성은 HTML로 렌더링할 때 원본 PDF 문서의 Z-순서대로 텍스트와 그래픽을 렌더링하도록 활성화합니다. |
| [fixed_layout](/viewer/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/) | 고정 레이아웃 옵션은 PDF 및 EPUB 문서를 고정 레이아웃으로 HTML에 렌더링하도록 활성화합니다. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptions/image_quality/) | HTML로 렌더링할 때 이미지 리소스의 출력 이미지 품질입니다. 기본 품질은 `ImageQuality.LOW`입니다. |
| [render_original_page_size](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/) | 출력 페이지 크기는 소스 PDF 문서의 페이지 크기에 맞게 설정됩니다. |
| [render_text_as_image](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/) | 옵션은 PDF 파일의 텍스트를 HTML 출력에서 이미지로 렌더링하도록 합니다. |
| [wrap_images_in_svg](/viewer/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/) | 출력 HTML 문서에서 각 이미지를 SVG 태그로 감싸서 출력 품질을 향상시키는 속성입니다. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("sample.pdf") as viewer:
    view_options = PngViewOptions("output_{0}.png")
    # PDF 페이지를 이미지로 렌더링할 때 폰트 힌팅을 활성화합니다.
    view_options.pdf_options.enable_font_hinting = True
    viewer.view(view_options)
```

### 참고
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
