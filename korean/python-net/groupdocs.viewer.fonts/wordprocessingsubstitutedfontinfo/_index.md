---
title: "WordProcessingSubstitutedFontInfo 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "로드된 Viewer 인스턴스 문서에서 원래 사용되지 않지만 대체 글꼴로 활용되는 WordProcessing 문서의 한 글꼴에 대한 메타정보와 바이너리 데이터를 캡슐화합니다…"
type: docs
url: /ko/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
is_root: false
weight: 120
---


## WordProcessingSubstitutedFontInfo class

로드된 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스 문서에서 원래 사용되지 않았지만 대상 머신에서 찾을 수 없는 경우 대체 글꼴로 사용되는 WordProcessing 문서의 한 글꼴에 대한 메타정보와 바이너리 데이터를 캡슐화합니다. 대체 글꼴은 WordProcessing 형식군에만 존재합니다.

불변 구조체입니다. 이 인스턴스는 [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 공개 API에 의해 생성 및 반환되며 일반적으로 사용자가 직접 생성해서는 안 됩니다. 자세한 내용은 문서를 참조하십시오: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

WordProcessingSubstitutedFontInfo 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/__init__/) |  |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css/#output) | 글꼴 정보를 @font-face 규칙으로 직렬화하고 지정된 텍스트 라이터에 씁니다. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/to_string/) | 글꼴 정보를 "original-name -> substituted-name style, format" 형식의 디버그 문자열로 반환합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content/) | 대체 글꼴의 내용을 바이트 배열로 반환합니다. 절대 None이 아닙니다. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/family_name/) | 스타일이 없는 대체 글꼴의 패밀리 이름을 반환합니다. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format/) | 이 대체(원본이 아닌) 글꼴의 형식입니다. |
| [original_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/original_family_name/) | 대상 머신에서 찾을 수 없는 원본 글꼴의 패밀리 이름을 반환합니다. 스타일이 없으며 절대 null이나 빈 문자열이 아닙니다. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style/) | 원본 글꼴의 스타일을 반환합니다 — Regular, Bold, Italic, Bold Italic 중 하나일 수 있습니다. |

### 참고
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
