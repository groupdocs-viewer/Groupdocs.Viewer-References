---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "MaxResolution 옵션의 기본값을 300으로, ImageQuality 옵션의 기본값을 100으로 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/
is_root: false
weight: 10
---


## __init__

MaxResolution 옵션의 기본값을 300으로, ImageQuality 옵션의 기본값을 100으로 초기화합니다.

자세한 내용 및 코드 샘플은 https://docs.groupdocs.com/viewer/net/optimization-pdf-options/ 및 해당 하위 페이지를 참조하십시오.

```python
def __init__(self):
    ...
```

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

with Viewer("sample.docx") as viewer:
    view_options = PdfViewOptions("optimized.pdf")
    view_options.pdf_optimization_options = PdfOptimizationOptions()
    viewer.view(view_options)
```

### 참고
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
