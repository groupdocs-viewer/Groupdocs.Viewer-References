---
title: "FontStyles 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "문서에서 사용되는 글꼴의 4가지 가능한 스타일을 나타냅니다: Regular, Bold, Italic, 또는 Bold Italic."
type: docs
url: /ko/python-net/groupdocs.viewer.fonts/fontstyles/
is_root: false
weight: 40
---


## FontStyles class

문서에서 사용되는 글꼴의 4가지 가능한 스타일을 나타냅니다: Regular, Bold, Italic, 또는 Bold Italic.

편리한 API와 결합 연산을 제공하는 불변 구조체입니다.

FontStyles 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/__init__/#is_bold-is_italic) | 지정된 bold 및 italic 플래그로 FontStyles 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals/#other) | 이 FontStyles 인스턴스가 지정된 인스턴스와 같은지 여부를 나타냅니다. |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals/#other) | 이 [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) 인스턴스가 지정된 형변환되지 않은 객체와 같은지 여부를 나타냅니다. |
| [equals_font_styles](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals_font_styles/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/get_hash_code/) | 이 인스턴스의 해시 코드를 반환합니다. |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/to_string/) | 이 폰트 스타일의 이름을 반환합니다. [`FontStyles.name`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/name/) 와 동일합니다. |
| [try_parse](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/#style-parsed) | 지정된 원시 문자열을 폰트 스타일 이름으로 구문 분석하려고 시도합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [is_bold](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/is_bold/) | 이 속성은 이 [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) 인스턴스에 굵게 플래그가 활성화(`True`)되어 있는지 또는 비활성화(`False`)되어 있는지를 나타냅니다. |
| [is_italic](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/is_italic/) | 이 [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) 인스턴스의 이탤릭 플래그 상태; 활성화된 경우 `True`, 비활성화된 경우 `False`. |
| [name](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/name/) | 이 폰트 스타일의 이름입니다. |

### 필드
| 필드 | 설명 |
| :- | :- |
| [REGULAR](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/) | 일반 폰트 스타일, 기본값(굵게와 이탤릭 없음) |
| [BOLD](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/bold/) | 굵게 폰트 스타일(굵게만, 이탤릭 없음) |
| [ITALIC](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/italic/) | 이탤릭 폰트 스타일(이탤릭만, 굵게 없음) |
| [BOLD_ITALIC](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/bold_italic/) | BoldItalic 폰트 스타일(굵게와 이탤릭이 함께 적용됨) |

### 참고
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
