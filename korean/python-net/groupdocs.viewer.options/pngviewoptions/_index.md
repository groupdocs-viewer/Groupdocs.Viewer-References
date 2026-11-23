---
title: "PngViewOptions 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "문서를 PNG 형식으로 렌더링하기 위한 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/pngviewoptions/
is_root: false
weight: 190
---


## PngViewOptions class

문서를 PNG 형식으로 렌더링하기 위한 옵션을 나타냅니다.

자세한 내용은 온라인 문서를 참조하십시오.

PngViewOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/__init__/#create_page_stream) | 새로운 [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/__init__/#create_page_stream-release_page_stream) | [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) 클래스의 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/__init__/#page_stream_factory) | 새로운 [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/__init__/) | PngViewOptions 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/__init__/#file_path_format) | 새로운 [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [rotate_page](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page/) | 페이지에 시계 방향 회전을 적용합니다. (상속된 [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [rotate_page_int32](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page_int32/) | (상속된 [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |

### 속성
| 속성 | 설명 |
| :- | :- |
| [extract_text](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/extract_text/) | 이 속성은 텍스트 추출을 가능하게 합니다. |
| [height](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/height/) | 출력 이미지의 높이(픽셀 단위)입니다. |
| [max_height](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/max_height/) | 출력 이미지의 최대 높이(픽셀 단위). |
| [max_width](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/max_width/) | 출력 이미지의 최대 너비(픽셀 단위). |
| [width](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/width/) | 출력 이미지의 너비(픽셀 단위). |
| [archive_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/archive_options/) | 아카이브 파일 보기 옵션. ([`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)에서 상속됨) |
| [cad_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/cad_options/) | CAD 도면 보기 옵션. ([`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)에서 상속됨) |
| [default_font_name](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/default_font_name/) | 필요한 글꼴이 없을 때 렌더링 중에 사용되는 문서의 기본 글꼴. ([`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)에서 상속됨) |
| [email_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/email_options/) | 이메일 메시지 보기 옵션. ([`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)에서 상속됨) |
| [mail_storage_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/mail_storage_options/) | 메일 저장소 데이터 파일 보기 옵션. ([`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)에서 상속됨) |
| [outlook_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/outlook_options/) | Microsoft Outlook 데이터 파일 보기 옵션. ([`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)에서 상속됨) |
| [page_rotations](/viewer/python-net/groupdocs.viewer.options/viewoptions/page_rotations/) | 페이지 회전입니다. (상속된 [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [pdf_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/pdf_options/) | PDF 문서 보기 옵션. ([`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)에서 상속됨) |
| [presentation_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/presentation_options/) | 프레젠테이션 파일 보기 옵션. ([`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)에서 상속됨) |
| [project_management_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/project_management_options/) | 프로젝트 관리 파일 보기 옵션. ([`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)에서 상속됨) |
| [remove_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/) | 이 속성은 True로 설정될 때 주석 렌더링을 비활성화합니다. 기본값은 False이며, 따라서 모든 주석이 표시됩니다. ([`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)에서 상속됨) |
| [render_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_comments/) | 이 속성은 주석 렌더링을 활성화하거나 비활성화합니다. ([`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)에서 상속됨) |
| [render_hidden_pages](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_hidden_pages/) | 이 속성은 숨겨진 페이지의 렌더링을 활성화합니다. ([`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)에서 상속됨) |
| [render_notes](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/) | 이 속성은 일부 형식에 대해 노트와 주석의 렌더링을 활성화합니다. ([`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)에서 상속됨) |
| [spreadsheet_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/spreadsheet_options/) | 스프레드시트 파일 보기 옵션. ([`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)에서 상속됨) |
| [text_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/text_options/) | 텍스트 파일 렌더링을 위한 텍스트 옵션. ([`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)에서 상속됨) |
| [visio_rendering_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/visio_rendering_options/) | Visio 파일 보기 옵션. ([`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)에서 상속됨) |
| [watermark](/viewer/python-net/groupdocs.viewer.options/viewoptions/watermark/) | 각 페이지에 적용될 텍스트 워터마크입니다. (상속된 [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [web_document_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/web_document_options/) | 웹 파일 보기 옵션. ([`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)에서 상속됨) |
| [word_processing_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/word_processing_options/) | 워드 프로세싱 파일 보기 옵션. ([`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)에서 상속됨) |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

### Guides
`PngViewOptions`를 사용하는 작업 가이드:

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)

### 참고
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
