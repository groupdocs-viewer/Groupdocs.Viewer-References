---
title: "render_layouts 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "CAD 문서의 레이아웃을 렌더링할지 여부를 나타내는 플래그입니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/cadoptions/render_layouts/
is_root: false
weight: 2070
---


## render_layouts property

CAD 문서의 레이아웃을 렌더링할지 여부를 나타내는 플래그입니다.

이 옵션은 레이아웃을 지원하는 CAD 도면에만 사용할 수 있습니다 [`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/), [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/), [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/), [`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/), 및 [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/). 기본적으로 모델만 렌더링됩니다.

### Definition:
```python
@property
def render_layouts(self):
    ...
@render_layouts.setter
def render_layouts(self, value):
    ...
```

### 참고
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
