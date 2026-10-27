---
title: "Viewer 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "문서 렌더링 프로세스를 제어하는 주요 클래스를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.viewer/viewer/
is_root: false
weight: 100
---


## Viewer class

문서 렌더링 프로세스를 제어하는 주요 클래스를 나타냅니다.

Viewer 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream) | 새 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 클래스의 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options) | 새 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-settings) | 새 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options-settings) | 새 Viewer 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream) | 새 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 클래스의 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-leave_open) | 새 Viewer 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options) | 새 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-leave_open) | 새 Viewer 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings) | 새 Viewer 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings-leave_open) | 새 Viewer 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings) | 새 Viewer 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings-leave_open) | 새 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path) | 새 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 클래스의 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-settings) | 새 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 클래스의 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options) | 새 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options-settings) | 새 Viewer 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [dispose](/viewer/python-net/groupdocs.viewer/viewer/dispose/) | 파일 스트림과 관리되는 내부 리소스를 해제합니다. |
| [get_all_fonts](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) | 로드된 문서에서 사용된 모든 글꼴을 반환합니다. 여기에는 포함된 글꼴과 OS에 설치된 시스템 글꼴이 포함됩니다. |
| [get_attachments](/viewer/python-net/groupdocs.viewer/viewer/get_attachments/) | 문서에 포함된 첨부 파일을 반환합니다. |
| [get_file_info](/viewer/python-net/groupdocs.viewer/viewer/get_file_info/) | 파일 유형 및 파일이 암호화되었는지 여부를 나타내는 플래그와 같은 파일 정보를 반환합니다. |
| [get_view_info](/viewer/python-net/groupdocs.viewer/viewer/get_view_info/#options) | 뷰 및 문서별 정보를 반환합니다. |
| [get_view_info_view_info_options](/viewer/python-net/groupdocs.viewer/viewer/get_view_info_view_info_options/) |  |
| [save_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment/#attachment-destination) | `destination` 스트림에 첨부 파일을 저장합니다. |
| [save_attachment_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_attachment/) |  |
| [save_attachment_stream](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_stream/) |  |
| [save_attachment_streams](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_streams/) |  |
| [search](/viewer/python-net/groupdocs.viewer/viewer/search/#options) | 텍스트 검색을 수행하고 제공된 옵션에 따라 로드된 문서에서 찾은 텍스트를 강조 표시합니다. |
| [search_search_highlight_options](/viewer/python-net/groupdocs.viewer/viewer/search_search_highlight_options/) |  |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options) | 문서의 모든 페이지에 대한 뷰를 생성합니다. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-page_numbers) | 특정 문서 페이지에 대한 뷰를 생성합니다. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-cancellation_token-page_numbers) | 특정 문서 페이지에 대한 뷰를 생성합니다. |
| [view_view_options](/viewer/python-net/groupdocs.viewer/viewer/view_view_options/) |  |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, PngViewOptions

# DOCX를 HTML로 렌더링합니다.
with Viewer("./sample.docx") as viewer:
    html_opts = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(html_opts)

# PDF를 PNG로 렌더링합니다.
with Viewer("document.pdf") as viewer:
    png_opts = PngViewOptions("page_{0}.png")
    viewer.view(png_opts)
```

### Guides
`Viewer`를 사용하는 작업 가이드:

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Get Document Information](/viewer/python-net/guides/get-document-info/)
* [Load document from local disk](/viewer/python-net/guides/load-document-from-local-disk/)
* [Load document from stream](/viewer/python-net/guides/load-document-from-stream/)
* [Load document from URL](/viewer/python-net/guides/load-document-from-url/)
* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)
* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)
* [Reorder pages](/viewer/python-net/guides/reorder-pages/)
* [Save attachments](/viewer/python-net/guides/how-to-extract-and-save-attachments/)

### 참고
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
