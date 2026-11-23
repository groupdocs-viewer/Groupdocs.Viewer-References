---
title: "WordProcessingFontInfo 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Viewer 인스턴스에 로드된 WordProcessing 문서에서 글꼴의 메타 정보와 바이너리 데이터를 캡슐화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/
is_root: false
weight: 110
---


## WordProcessingFontInfo class

[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스에 로드된 WordProcessing 문서의 글꼴에 대한 메타정보와 바이너리 데이터를 캡슐화합니다.

불변 구조체입니다.

그 인스턴스는 [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 공개 API에 의해 생성 및 반환되며 일반적으로 사용자가 직접 생성해서는 안 됩니다.

자세한 내용은 문서를 참조하십시오: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

WordProcessingFontInfo 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/__init__/) |  |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css/#output) | 글꼴 정보를 @font-face 규칙으로 직렬화하고 지정된 텍스트 라이터에 씁니다. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/to_string/) | 다음 템플릿 형식으로 이 글꼴 데이터에 대한 디버그 정보를 반환합니다: "name style, embedded/system, format". |

### 속성
| 속성 | 설명 |
| :- | :- |
| [alt_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/alt_family_name/) | 글꼴의 대체 패밀리 이름입니다. 없을 경우 빈 문자열을 반환합니다. |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/charset/) | 이 글꼴의 문자 집합입니다. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/content/) | 이 글꼴의 내용을 바이트 배열로 반환합니다. 글꼴에 대한 메타 정보만 있고 바이너리 내용이 없을 경우, 해당 속성은 None을 반환합니다. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/family_name/) | 스타일이 없는 글꼴의 패밀리 이름을 반환합니다; 절대 None이나 빈 문자열이 아닙니다. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/format/) | 이 글꼴의 형식입니다. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/is_embedded/) | 이 속성은 글꼴이 문서에 포함되어 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스로 로드된 경우(`True`)인지, 시스템 글꼴인지(`False`)를 나타냅니다. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/style/) | 글꼴 스타일 — Regular, Bold, Italic, Bold Italic 중 하나일 수 있습니다. |

### 참고
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
