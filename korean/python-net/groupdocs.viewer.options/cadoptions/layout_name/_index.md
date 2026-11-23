---
title: "layout_name 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "렌더링할 특정 레이아웃의 이름입니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/cadoptions/layout_name/
is_root: false
weight: 2050
---


## layout_name property

렌더링할 특정 레이아웃의 이름입니다. 레이아웃 이름은 대소문자를 구분합니다.

이 옵션은 레이아웃을 지원하는 CAD 도면에만 사용할 수 있습니다: [`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/), [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/), [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/), [`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/), 및 [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/); 기본적으로 모델만 렌더링됩니다.

### Definition:
```python
@property
def layout_name(self):
    ...
@layout_name.setter
def layout_name(self, value):
    ...
```

### 참고
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
