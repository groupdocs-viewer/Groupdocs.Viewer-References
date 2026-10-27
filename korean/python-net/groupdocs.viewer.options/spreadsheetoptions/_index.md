---
title: "SpreadsheetOptions 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "스프레드시트를 렌더링하기 위한 옵션."
type: docs
url: /ko/python-net/groupdocs.viewer.options/spreadsheetoptions/
is_root: false
weight: 280
---


## SpreadsheetOptions class

스프레드시트를 렌더링하기 위한 옵션.

자세한 내용은 Render spreadsheet files 주제의 하위 항목을 참조하십시오.

SpreadsheetOptions 유형은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [for_one_page_per_sheet](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_one_page_per_sheet/) | 전체 시트를 한 페이지에 렌더링하기 위해 [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) 인스턴스를 초기화합니다. |
| [for_rendering_by_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/) | 페이지 구분을 기준으로 워크시트를 페이지로 나누도록 구성된 [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) 인스턴스를 초기화합니다. |
| [for_rendering_print_area](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/) | 인쇄 영역만 렌더링하기 위해 [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) 클래스의 인스턴스를 초기화합니다. |
| [for_rendering_print_area_and_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area_and_page_breaks/) | 인쇄 영역 및 페이지 구분을 렌더링하기 위해 [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) 클래스의 인스턴스를 초기화합니다. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page) | 시트를 페이지로 렌더링하기 위해 SpreadsheetOptions 인스턴스를 초기화합니다. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page-count_columns_per_page) | 시트를 페이지로 렌더링하기 위해 SpreadsheetOptions 인스턴스를 초기화합니다. |
| [for_split_sheet_into_pages_int32](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages_int32/) |  |

### 속성
| 속성 | 설명 |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/bottom_margin/) | PDF로 변환할 때 페이지의 아래쪽 여백. |
| [count_columns_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_columns_per_page/) | 워크시트를 페이지로 나눌 때 각 페이지에 포함할 열 수. |
| [count_rows_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_rows_per_page/) | 워크시트를 페이지로 나눌 때 각 페이지에 포함할 행 수. |
| [detect_separator](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/detect_separator/) | 이 속성은 CSV/TSV 파일의 구분자를 감지하도록 합니다. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/horizontal_resolution/) | 생성된 이미지의 가로 해상도(인치당 도트 수)입니다. 이 옵션은 스프레드시트를 PNG 또는 JPEG 형식으로 렌더링할 때만 사용됩니다. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/left_margin/) | PDF로 변환할 때 페이지의 왼쪽 여백. |
| [render_grid_lines](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_grid_lines/) | 이 속성은 그리드 라인의 렌더링을 활성화합니다. |
| [render_headings](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_headings/) | 이 속성은 제목 렌더링을 활성화합니다. |
| [render_hidden_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_columns/) | 이 속성은 숨겨진 열의 렌더링을 활성화합니다. |
| [render_hidden_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_rows/) | 이 속성은 숨겨진 행의 렌더링을 활성화합니다. |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/right_margin/) | PDF로 변환할 때 페이지의 오른쪽 여백. |
| [skip_empty_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_columns/) | 이 속성은 빈 열의 렌더링을 비활성화합니다. |
| [skip_empty_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_rows/) | 이 속성은 빈 행의 렌더링을 비활성화합니다. |
| [text_overflow_mode](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/text_overflow_mode/) | 스프레드시트 문서를 HTML로 렌더링하기 위한 텍스트 오버플로 모드. 기본값은 `TextOverflowMode.OverlayIfNextIsEmpty`이며, 이는 기본 MS Excel 동작을 모방합니다. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/top_margin/) | PDF로 변환할 때 페이지의 위쪽 여백. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/) | 생성된 이미지의 세로 해상도(인치당 도트 수). 이 옵션은 스프레드시트를 PNG 또는 JPEG 형식으로 렌더링할 때만 사용됩니다. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # 스프레드시트에서 그리드 라인 렌더링을 활성화합니다.
    view_options.spreadsheet_options.render_grid_lines = True
    viewer.view(view_options)
```

### 참고
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
