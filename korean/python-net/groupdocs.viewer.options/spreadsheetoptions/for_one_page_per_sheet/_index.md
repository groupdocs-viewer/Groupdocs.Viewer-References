---
title: "for_one_page_per_sheet 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "전체 시트를 한 페이지로 렌더링하기 위해 SpreadsheetOptions 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/spreadsheetoptions/for_one_page_per_sheet/
is_root: false
weight: 1010
---


## for_one_page_per_sheet

전체 시트를 한 페이지에 렌더링하기 위해 [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) 인스턴스를 초기화합니다.

자세한 내용은 문서를 참조하십시오.

```python
def for_one_page_per_sheet(cls):
    ...
```

**Returns:** `SpreadsheetOptions`: A new instance configured to render the whole sheet into one page.

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def render_one_page_per_sheet():
    # 스프레드시트 로드
    with Viewer("products.xlsx") as viewer:
        view_options = PdfViewOptions("render_one_page_per_sheet/one_page_per_sheet.pdf")
        # 각 워크시트를 한 페이지로 렌더링합니다.
        view_options.spreadsheet_options = SpreadsheetOptions.for_one_page_per_sheet()
        viewer.view(view_options)

if __name__ == "__main__":
    render_one_page_per_sheet()
```

### 참고
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
