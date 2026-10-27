---
title: "PdfOptimizationOptions 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "출력 PDF 파일에 적용할 PDF 최적화 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/pdfoptimizationoptions/
is_root: false
weight: 150
---


## PdfOptimizationOptions class

출력 PDF 파일에 적용할 PDF 최적화 옵션을 나타냅니다.

자세한 내용과 코드 샘플은 문서 페이지를 참조하십시오.

PdfOptimizationOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/) | MaxResolution 옵션의 기본값을 300으로, ImageQuality 옵션의 기본값을 100으로 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [compress_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images/) | 이 속성은 출력 PDF 파일에서 이미지를 압축하도록 합니다. |
| [convert_to_gray_scale](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/convert_to_gray_scale/) | 이 속성은 출력 PDF 파일을 그레이스케일로 변환하도록 합니다. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/image_quality/) | 출력 PDF 파일의 이미지 품질, 백분율로 표시됩니다. |
| [lineriaze](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/lineriaze/) | 이 속성은 웹 브라우저를 통한 온라인 보기용으로 출력 PDF 파일을 최적화하도록 합니다. |
| [max_resolution](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/) | 출력 PDF 파일의 최대 해상도. |
| [optimize_spreadsheets](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/optimize_spreadsheets/) | PDF 파일에서 스프레드시트를 최적화하도록 하는 속성. |
| [remove_annotations](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_annotations/) | 이 속성은 출력 PDF 파일에서 주석을 제거하도록 합니다. |
| [remove_form_fields](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_form_fields/) | 이 속성은 PDF 파일에서 양식 필드를 제거하도록 합니다. |
| [remove_unused_objects](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/) | 이 속성은 PDF 파일에서 사용되지 않는(고아) 객체를 제거합니다. |
| [remove_unused_streams](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/) | 이 속성은 페이지 리소스 사전에서 참조되지만 페이지 내용에서는 사용되지 않은 PDF 파일의 사용되지 않는(고아) 스트림을 제거합니다. 기본적으로 비활성화(`False`)되어 있으며, `True`로 설정하면 출력 PDF 크기가 감소합니다. |
| [resize_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/) | 이 속성은 출력 PDF 파일에서 최대 해상도를 설정할 수 있게 합니다. |
| [subset_fonts](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/subset_fonts/) | 이 속성은 출력 PDF 파일에서 글꼴을 부분집합으로 포함합니다. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

def optimize_pdf():
    with Viewer("sample.docx") as viewer:
        view_options = PdfViewOptions("output/optimized.pdf")
        view_options.pdf_optimization_options = PdfOptimizationOptions()
        # 웹 미리보기를 빠르게 하기 위해 선형화를 활성화합니다.
        view_options.pdf_optimization_options.lineriaze = True
        # 크기를 줄이기 위해 주석 및 양식 필드를 제거합니다.
        view_options.pdf_optimization_options.remove_annotations = True
        view_options.pdf_optimization_options.remove_form_fields = True

        viewer.view(view_options)
```

### 참고
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
