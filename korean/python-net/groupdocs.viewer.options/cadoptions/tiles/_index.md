---
title: "tiles 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "렌더링할 그리기 영역."
type: docs
url: /ko/python-net/groupdocs.viewer.options/cadoptions/tiles/
is_root: false
weight: 2090
---


## tiles property

렌더링할 그리기 영역.

이 옵션은 [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/) 및 [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/) 파일 형식에만 사용할 수 있습니다. [`CadOptions.render_layouts`](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) 및 [`CadOptions.layout_name`](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) 옵션은 타일로 렌더링할 때 무시됩니다.

### Definition:
```python
@property
def tiles(self):
    ...
@tiles.setter
def tiles(self, value):
    ...
```

### 참고
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
