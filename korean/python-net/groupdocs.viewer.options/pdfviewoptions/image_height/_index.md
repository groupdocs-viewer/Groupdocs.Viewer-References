---
title: "image_height 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "출력 이미지의 높이(픽셀 단위)입니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/pdfviewoptions/image_height/
is_root: false
weight: 2010
---


## image_height property

출력 이미지의 높이(픽셀 단위)입니다.

이 속성을 사용하여 출력 이미지 높이(픽셀 단위)를 설정합니다. GroupDocs.Viewer는 단일 이미지를 HTML로만 렌더링할 때 이 속성을 적용합니다. 자세한 내용은 https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/ 의 문서를 참조하십시오.

이 속성을 설정하면, [`PdfViewOptions.ImageMaxHeight`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_height/) 속성이 무시됩니다.

### Definition:
```python
@property
def image_height(self):
    ...
@image_height.setter
def image_height(self, value):
    ...
```

### 참고
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
