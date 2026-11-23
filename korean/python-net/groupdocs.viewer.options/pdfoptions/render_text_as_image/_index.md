---
title: "render_text_as_image 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "옵션은 PDF 파일의 텍스트를 HTML 출력에서 이미지로 렌더링하도록 합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/
is_root: false
weight: 2090
---


## render_text_as_image property

옵션은 PDF 파일의 텍스트를 HTML 출력에서 이미지로 렌더링하도록 합니다.

이 옵션을 True로 설정하면 GroupDocs.Viewer는 HTML 출력에서 텍스트를 이미지로 렌더링합니다. 이렇게 하면 텍스트를 선택할 수 없게 되고 문자 렌더링이 향상되어 HTML에서 PDF와 같은 모습을 보장합니다. 기본값은 False입니다.

이 옵션은 HTML로 렌더링할 때 사용할 수 있습니다.

코드 예제는 문서를 참조하십시오.

### Definition:
```python
@property
def render_text_as_image(self):
    ...
@render_text_as_image.setter
def render_text_as_image(self, value):
    ...
```

### 참고
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
