---
title: "resize_images 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "이 속성은 출력 PDF 파일에서 최대 해상도를 설정할 수 있게 합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/
is_root: false
weight: 2110
---


## resize_images property

이 속성은 출력 PDF 파일에서 최대 해상도를 설정할 수 있게 합니다.

이 옵션을 허용하려면 [`PdfOptimizationOptions.compress_images`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images/) 속성을 `True`로 설정하십시오. 이 옵션은 [`PdfOptimizationOptions.max_resolution`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/) 속성을 설정할 수 있게 합니다.

### Definition:
```python
@property
def resize_images(self):
    ...
@resize_images.setter
def resize_images(self, value):
    ...
```

### 참고
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
