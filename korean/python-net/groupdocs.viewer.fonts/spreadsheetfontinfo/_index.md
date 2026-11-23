---
title: "SpreadsheetFontInfo 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "스프레드시트 문서에서 로드된 Viewer 인스턴스의 글꼴에 대한 메타정보와 바이너리 데이터를 캡슐화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/
is_root: false
weight: 100
---


## SpreadsheetFontInfo class

[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스에 로드된 스프레드시트 문서의 글꼴에 대한 메타정보와 바이너리 데이터를 캡슐화합니다. 스프레드시트 문서는 글꼴을 포함할 수 없으므로, [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) 로 반환된 글꼴은 뷰어가 실행되는 운영 체제에 설치됩니다.

SpreadsheetFontInfo 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/__init__/) |  |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/#output) | 글꼴 정보를 @font-face 규칙으로 직렬화하고 지정된 텍스트 라이터에 씁니다. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css_text_writer/) |  |

### 속성
| 속성 | 설명 |
| :- | :- |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/charset/) | 이 글꼴의 문자 집합입니다. |
| [color](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/color/) | 이 글꼴의 색상입니다. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/content/) | 이 글꼴의 내용을 바이트 배열로 제공합니다. 글꼴에 대한 메타정보만 존재하고 바이너리 내용이 없을 경우, 이 속성은 None을 반환합니다. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/family_name/) | 스타일이 없는 글꼴의 패밀리 이름은 null이거나 빈 문자열이 절대 아닙니다. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/format/) | 이 글꼴의 형식입니다. |
| [is_strikeout](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_strikeout/) | 이 글꼴은 단일 취소선을 가집니다. |
| [is_underline](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_underline/) | 이 글꼴은 밑줄이 있습니다. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/style/) | 이 글꼴의 스타일 — Regular, Bold, Italic, 또는 Bold Italic일 수 있습니다. |

### 참고
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
