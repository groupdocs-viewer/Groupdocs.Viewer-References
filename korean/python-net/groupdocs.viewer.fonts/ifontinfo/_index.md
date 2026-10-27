---
title: "IFontInfo 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "PDF, WordProcessing, Spreadsheet, Presentation 등 지원되는 모든 문서 형식군에서 추출할 수 있는 모든 글꼴에 대한 공통 인터페이스를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.viewer.fonts/ifontinfo/
is_root: false
weight: 50
---


## IFontInfo class

PDF, WordProcessing, Spreadsheet, Presentation 등 지원되는 모든 문서 형식군에서 추출할 수 있는 모든 글꼴에 대한 공통 인터페이스를 나타냅니다.

IFontInfo 유형은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css/#output) | 이 글꼴 정보를 @font-face 규칙으로 직렬화하고 지정된 텍스트 라이터에 씁니다. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css_text_writer/) |  |

### 속성
| 속성 | 설명 |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/content/) | 글꼴의 바이너리 내용을 바이트 배열로 제공되면 반환하고, 그렇지 않으면 None을 반환합니다. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/family_name/) | 글꼴의 패밀리 이름을 문자열로 반환합니다. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/format/) | 이 글꼴의 형식을 열거형으로 반환합니다 — TrueType, TrueType Collection, OpenType, Embedded OpenType, 또는 `FontFormat.unknown`. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/style/) | 글꼴 스타일을 열거형(Regular, Bold, Italic, Bold Italic)으로 반환합니다; 일부 문서 형식은 [`FontStyles.regular`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/)만 지원할 수 있습니다. |

### 참고
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
