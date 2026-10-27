---
title: "PdfFontInfo 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Viewer 인스턴스에 로드된 PDF 글꼴의 메타데이터와 바이너리 데이터를 캡슐화합니다. 이 글꼴은 문서에 포함되었거나 GroupDocs.Viewer가 실행되는 운영 체제에 설치될 수 있습니다."
type: docs
url: /ko/python-net/groupdocs.viewer.fonts/pdffontinfo/
is_root: false
weight: 70
---


## PdfFontInfo class

[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스에 로드된 PDF 글꼴의 메타데이터와 바이너리 데이터를 캡슐화합니다. 이 글꼴은 문서에 포함될 수 있거나 GroupDocs.Viewer가 실행되는 운영 체제에 설치될 수 있습니다.

PdfFontInfo 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/__init__/) |  |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css/#output) | 이 글꼴 정보를 @font-face 규칙으로 직렬화하고 지정된 텍스트 라이터에 씁니다. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css_text_writer/) |  |

### 속성
| 속성 | 설명 |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/content/) | 이 글꼴의 내용을 바이트 배열로 반환합니다. 메타데이터만 제공되고 바이너리 내용이 없을 경우 None을 반환합니다. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/family_name/) | 스타일이 없는 글꼴의 패밀리 이름을 반환합니다; 절대 None이나 빈 문자열이 아닙니다. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/format/) | 이 글꼴의 형식입니다. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_embedded/) | 이 속성은 글꼴이 PDF 문서에 포함되어 Viewer 인스턴스로 로드되었는지(`True`) 여부를 나타냅니다. |
| [is_installed](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_installed/) | 이 속성은 이 글꼴이 GroupDocs.Viewer가 실행되는 운영 체제에 존재(설치)하는지 여부를 나타냅니다. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/style/) | 글꼴 스타일을 반환합니다; Regular, Bold, Italic, Bold Italic 중 하나일 수 있습니다. |

### 참고
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
