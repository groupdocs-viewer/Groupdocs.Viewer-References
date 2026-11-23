---
title: "wrap_images_in_svg 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "출력 HTML 문서에서 각 이미지를 SVG 태그로 감싸서 출력 품질을 향상시키는 속성입니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/
is_root: false
weight: 2100
---


## wrap_images_in_svg property

출력 HTML 문서에서 각 이미지를 SVG 태그로 감싸서 출력 품질을 향상시키는 속성입니다.

기본적으로 PDF 및 페이지 레이아웃 파일을 HTML로 렌더링할 때 모든 이미지가 하나의 PNG 이미지로 렌더링됩니다. 렌더링된 PNG 이미지는 출력 HTML 문서의 배경으로 사용됩니다.

이 옵션은 임베드 및 외부 리소스와 함께 PDF 및 페이지 레이아웃 파일 형식을 HTML로 렌더링할 때 사용할 수 있습니다. 출력 HTML 문서의 각 이미지를 SVG 태그로 감싸도록 합니다. 기본값은 False입니다.

코드 예제는 문서를 참조하십시오.

### Definition:
```python
@property
def wrap_images_in_svg(self):
    ...
@wrap_images_in_svg.setter
def wrap_images_in_svg(self, value):
    ...
```

### 참고
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
