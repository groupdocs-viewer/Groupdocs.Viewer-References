---
title: "for_split_sheet_into_pages 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "시트를 페이지로 렌더링하기 위해 SpreadsheetOptions 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/
is_root: false
weight: 1050
---


## for_split_sheet_into_pages {#count_rows_per_page}

시트를 페이지로 렌더링하기 위해 SpreadsheetOptions 인스턴스를 초기화합니다.

자세한 내용은 https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows 문서를 참조하십시오.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| count_rows_per_page | `int` | 각 페이지에 포함할 행 수. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering sheet into pages.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `count_rows_per_page`가 0 이하인 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows():
    # 스프레드시트 로드
    with Viewer("two-pages.xlsx") as viewer:
        rows_per_page = 15
        view_options = PdfViewOptions("split_by_rows/by_rows.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(rows_per_page)
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows()
```

## for_split_sheet_into_pages {#count_rows_per_page-count_columns_per_page}

시트를 페이지로 렌더링하기 위해 SpreadsheetOptions 인스턴스를 초기화합니다.

자세한 내용은 https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns 문서를 참조하십시오.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page, count_columns_per_page):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| count_rows_per_page | `int` | 각 페이지에 포함할 행 수. |
| count_columns_per_page | `int` | 각 페이지에 포함할 열 수. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering a sheet into pages.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `count_columns_per_page`가 0 이하인 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows_and_columns():
    # 스프레드시트 로드
    with Viewer("four-pages.xlsx") as viewer:
        rows_per_page = 15
        columns_per_page = 7
        # 스프레드시트를 PDF로 변환합니다.
        view_options = PdfViewOptions("split_by_rows_and_columns/by_rows_and_columns.pdf")
        # 행 및 열 수에 따라 분할합니다.
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(
            rows_per_page, columns_per_page
        )
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows_and_columns()
```

### 참고
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
