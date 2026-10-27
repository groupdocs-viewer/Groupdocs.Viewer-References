---
title: "PresentationFontInfo 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Presentation 문서에서 로드된 Viewer 인스턴스의 글꼴에 대한 메타정보와 바이너리 데이터를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.viewer.fonts/presentationfontinfo/
is_root: false
weight: 80
---


## PresentationFontInfo class

[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스에 로드된 Presentation 문서의 글꼴에 대한 메타정보와 바이너리 데이터를 나타냅니다. 이 글꼴은 문서 내용에 사용되며 문서에 포함될 수 있거나 뷰어가 실행되는 운영 체제에 설치될 수 있습니다.

PresentationFontInfo 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/__init__/) |  |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css/#output) | 이 글꼴 정보를 @font-face 규칙으로 직렬화하고 지정된 텍스트 라이터에 씁니다. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css_text_writer/) |  |

### 속성
| 속성 | 설명 |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/content/) | 이 글꼴의 내용을 바이트 배열로 제공합니다. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/family_name/) | 스타일이 없는 글꼴의 패밀리 이름을 반환합니다; 절대 None이나 빈 문자열이 아닙니다. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/format/) | 이 글꼴의 형식입니다. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/) | 이 속성은 글꼴이 문서에 포함되어 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스에 로드되었는지(`True`), 혹은 시스템 글꼴인지(`False`)를 나타냅니다. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/style/) | 글꼴 스타일 — Regular, Bold, Italic, Bold Italic 중 하나일 수 있습니다. |

### 참고
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
