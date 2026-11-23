---
title: "enable_layered_rendering 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "이 속성은 HTML로 렌더링할 때 원본 PDF 문서의 Z-순서대로 텍스트와 그래픽을 렌더링하도록 활성화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/
is_root: false
weight: 2050
---


## enable_layered_rendering property

이 속성은 HTML로 렌더링할 때 원본 PDF 문서의 Z-순서대로 텍스트와 그래픽을 렌더링하도록 활성화합니다.

기본적으로 GroupDocs.Viewer는 텍스트와 그래픽을 HTML에서 단일 레이어로 렌더링합니다. 이 옵션을 사용하면 객체를 원본 파일과 동일한 순서대로 배치할 수 있습니다. 기본값은 False입니다.

코드 예제는 문서를 참조하십시오.

### Definition:
```python
@property
def enable_layered_rendering(self):
    ...
@enable_layered_rendering.setter
def enable_layered_rendering(self, value):
    ...
```

### 참고
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
