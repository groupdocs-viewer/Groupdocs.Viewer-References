---
title: "render_to_pure_html 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "이 속성은 Presentation 문서에 대한 새로운 HTML 렌더링 모드를 활성화합니다 — 이 모드에서는 파일이 SVG 이미지 없이 순수 HTML/CSS 마크업으로 렌더링됩니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/presentationoptions/render_to_pure_html/
is_root: false
weight: 2020
---


## render_to_pure_html property

이 속성은 프레젠테이션 문서에 대한 새로운 HTML 렌더링 모드를 활성화합니다 — 이 모드에서는 파일이 SVG 이미지 없이 순수 HTML/CSS 마크업으로 렌더링됩니다. 기본적으로 비활성화(`False`)되어 있으며, 기존 SVG 기반 HTML 렌더러가 사용됩니다.

코드 예제는 https://docs.groupdocs.com/viewer/net/render-presentations/#generate-pure-htmlcss-markup 에 있는 문서를 참조하세요.

### Definition:
```python
@property
def render_to_pure_html(self):
    ...
@render_to_pure_html.setter
def render_to_pure_html(self, value):
    ...
```

### 참고
* class [`PresentationOptions`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/)
