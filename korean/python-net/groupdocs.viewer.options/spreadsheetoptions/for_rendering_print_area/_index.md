---
title: "for_rendering_print_area 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "인쇄 영역만 렌더링하도록 SpreadsheetOptions 클래스의 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/
is_root: false
weight: 1030
---


## for_rendering_print_area

인쇄 영역만 렌더링하기 위해 [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) 클래스의 인스턴스를 초기화합니다.

자세한 내용은 https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#render-a-print-area 문서를 참조하십시오.

```python
def for_rendering_print_area(cls):
    ...
```

**Returns:** SpreadsheetOptions: New instance of the `SpreadsheetOptions` class for rendering print areas only.

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def render_print_area():
    with Viewer("invoice.xlsx") as viewer:
        view_options = PdfViewOptions("render_print_area/print_area.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_print_area()
        viewer.view(view_options)
```

### 참고
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
