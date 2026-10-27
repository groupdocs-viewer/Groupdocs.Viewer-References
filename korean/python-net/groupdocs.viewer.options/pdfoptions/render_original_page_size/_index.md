---
title: "render_original_page_size 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "출력 페이지 크기는 소스 PDF 문서의 페이지 크기에 맞게 설정됩니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/
is_root: false
weight: 2080
---


## render_original_page_size property

출력 페이지 크기는 소스 PDF 문서의 페이지 크기에 맞게 설정됩니다.

기본적으로 GroupDocs.Viewer는 렌더링 품질을 향상시키기 위해 출력 이미지 페이지 크기를 계산합니다. 이 옵션을 활성화하면 출력 페이지가 원본 PDF 문서의 페이지 크기(픽셀)와 동일하게 유지됩니다. 기본값은 False입니다.

이 옵션은 PNG 또는 JPG 형식으로 렌더링할 때 사용할 수 있습니다.

코드 예제는 문서를 참조하십시오.

### Definition:
```python
@property
def render_original_page_size(self):
    ...
@render_original_page_size.setter
def render_original_page_size(self, value):
    ...
```

### 참고
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
