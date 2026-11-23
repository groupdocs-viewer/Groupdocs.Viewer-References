---
title: "WordProcessingOptions 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Word 문서 렌더링 옵션을 포함합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/wordprocessingoptions/
is_root: false
weight: 380
---


## WordProcessingOptions class

Word 문서 렌더링 옵션을 포함합니다.

자세한 내용은 https://docs.groupdocs.com/viewer/net/render-word-documents/ 에 있는 문서를 참조하십시오.

WordProcessingOptions 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/) | 워드 프로세싱 문서를 렌더링하기 위한 옵션을 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [clone](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/clone/) | 이 옵션들의 전체 깊은 복사본을 생성하여 반환합니다. |
| [equals](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals/#options) | 지정된 [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/) 인스턴스가 현재 인스턴스와 동일한지 여부를 결정합니다. |
| [equals_word_processing_options](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals_word_processing_options/) |  |

### 속성
| 속성 | 설명 |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/bottom_margin/) | 페이지의 아래쪽 여백입니다. |
| [enable_open_type_features](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/enable_open_type_features/) | 이 옵션은 아랍어, 히브리어, 인도 라틴 기반 또는 키릴 문자 기반 스크립트를 렌더링할 때 커닝 및 기타 OpenType 기능을 활성화합니다. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/) | 생성된 이미지의 인치당 도트 수(dpi) 기준 가로 해상도입니다. 이 옵션은 WordProcessing 문서를 PNG 또는 JPEG 형식으로 렌더링할 때만 사용됩니다. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/left_margin/) | 페이지의 왼쪽 여백입니다. |
| [page_number_location](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_number_location/) | 로드된 WordProcessing 문서의 페이지 번호 위치이며, 페이지 번호를 강제로 적용할 수 있습니다; 기본값은 `WordsPageNumberLocation.not_apply`이며, 문서는 그대로 유지됩니다. |
| [page_size](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/) | 출력 페이지의 크기입니다. |
| [render_tracked_changes](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/render_tracked_changes/) | 이 속성은 추적된 변경(수정) 사항의 렌더링을 활성화합니다. |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/right_margin/) | 페이지의 오른쪽 여백입니다. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/top_margin/) | 페이지의 위쪽 여백(포인트 단위)입니다. |
| [unlink_table_of_contents](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/unlink_table_of_contents/) | 이 옵션을 True로 설정하면 HTML 또는 PDF 렌더링 시 목차에서의 탐색을 비활성화합니다. |
| [update_fields](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/update_fields/) | 이 속성은 WordProcessing 문서를 HTML, PDF, PNG 또는 JPEG 형식으로 저장하기 전에 특정 유형의 필드가 업데이트되는지 여부를 결정합니다. 기본값은 True이며, 이는 필드가 업데이트됨을 의미합니다. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/) | 생성된 이미지의 인치당 도트 수(dpi) 기준 세로 해상도이며, WordProcessing 문서를 PNG 또는 JPEG 형식으로 렌더링할 때만 사용됩니다. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("with_tracked_changes.docx") as viewer:
    view_options = PdfViewOptions("output/word_with_tracked_changes.pdf")
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### 참고
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
