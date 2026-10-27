---
title: "render_header_footer_placeholders 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "이 속성은 슬라이드의 머리글 및 바닥글에 자리 표시자 렌더링을 활성화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/presentationoptions/render_header_footer_placeholders/
is_root: false
weight: 2010
---


## render_header_footer_placeholders property

이 속성은 슬라이드의 머리글 및 바닥글에 자리 표시자 렌더링을 활성화합니다.

기본적으로 비활성화됩니다 (`False`). 이 옵션은 프레젠테이션의 네 가지 렌더링 모드(HTML, PDF, PNG, JPEG) 모두에 적용됩니다. [`PresentationOptions.render_to_pure_html`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/render_to_pure_html/)을 사용하여 프레젠테이션을 순수 HTML/CSS 마크업으로 렌더링할 때는 적용되지 않습니다.

### Definition:
```python
@property
def render_header_footer_placeholders(self):
    ...
@render_header_footer_placeholders.setter
def render_header_footer_placeholders(self, value):
    ...
```

### 참고
* class [`PresentationOptions`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/)
