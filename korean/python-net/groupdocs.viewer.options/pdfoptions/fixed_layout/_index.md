---
title: "fixed_layout 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "고정 레이아웃 옵션은 PDF 및 EPUB 문서를 고정 레이아웃으로 HTML에 렌더링하도록 활성화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/
is_root: false
weight: 2060
---


## fixed_layout property

고정 레이아웃 옵션은 PDF 및 EPUB 문서를 고정 레이아웃으로 HTML에 렌더링하도록 활성화합니다.

PDF 및 EPUB 문서는 원본 문서의 모양을 유지하기 위해 처음에 고정 레이아웃으로 HTML에 렌더링됩니다. 이 고정 레이아웃은 모든 HTML 요소가 지정된 크기의 컨테이너 내에서 정확한 위치를 갖는다는 의미입니다. 브라우저 창 크기를 조정해도 문서 내 요소의 위치와 크기는 영향을 받지 않습니다.

이 옵션은 HTML로 렌더링할 때만 사용할 수 있습니다. 기본값은 `True`입니다. 유동 레이아웃으로 렌더링하려면 이 속성을 `False`로 설정하십시오.

유동 레이아웃으로 렌더링할 때는 이미지가 건너뛰어집니다. 텍스트 콘텐츠가 있는 PDF 문서를 렌더링할 때 유동 레이아웃을 사용하십시오.

코드 예제는 문서를 참조하십시오.

### Definition:
```python
@property
def fixed_layout(self):
    ...
@fixed_layout.setter
def fixed_layout(self, value):
    ...
```

### 참고
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
