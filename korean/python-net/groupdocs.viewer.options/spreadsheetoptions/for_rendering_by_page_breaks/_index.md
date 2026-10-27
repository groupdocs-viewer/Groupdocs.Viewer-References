---
title: "for_rendering_by_page_breaks 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "SpreadsheetOptions 인스턴스를 초기화합니다. 이 인스턴스는 페이지 구분을 사용하여 워크시트를 페이지로 분할하도록 구성됩니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/
is_root: false
weight: 1020
---


## for_rendering_by_page_breaks

페이지 구분을 기준으로 워크시트를 페이지로 나누도록 구성된 [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) 인스턴스를 초기화합니다.

자세한 내용은 문서를 참조하십시오.

```python
def for_rendering_by_page_breaks(cls):
    ...
```

**Returns:** New `SpreadsheetOptions` instance for splitting to pages by page breaks. The behavior is similar to printing in Excel.

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_page_breaks():
    # 스프레드시트 로드
    with Viewer("products.xlsx") as viewer:
        # 스프레드시트를 PDF로 변환합니다.
        view_options = PdfViewOptions("split_by_page_breaks/by_page_breaks.pdf")
        # 페이지 구분을 사용하여 분할합니다.
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_by_page_breaks()
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_page_breaks()
```

### 참고
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
