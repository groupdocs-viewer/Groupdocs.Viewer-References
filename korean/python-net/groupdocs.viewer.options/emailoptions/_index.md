---
title: "EmailOptions 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "이메일 메시지를 렌더링하기 위한 옵션을 포함합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/emailoptions/
is_root: false
weight: 40
---


## EmailOptions class

이메일 메시지를 렌더링하기 위한 옵션을 포함합니다.

GroupDocs.Viewer는 이메일 메시지를 렌더링하기 위한 다양한 옵션을 지정할 수 있는 EmailOptions 클래스를 지원합니다. 원하는 출력 형식에 따라 다음 보기 옵션 클래스 중 하나에서 EmailOptions 속성을 사용하여 이러한 옵션에 접근하십시오:

- [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
- [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
- [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
- [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)

EmailOptions 타입은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/emailoptions/__init__/) | [`EmailOptions`](/viewer/python-net/groupdocs.viewer.options/emailoptions/) 클래스의 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [date_time_format](/viewer/python-net/groupdocs.viewer.options/emailoptions/date_time_format/) | 시간 형식 (TimeZone을 포함할 수 있음). 설정되지 않은 경우 현재 시스템 형식이 사용됩니다. |
| [field_text_map](/viewer/python-net/groupdocs.viewer.options/emailoptions/field_text_map/) | 이메일 메시지 [`Field`](/viewer/python-net/groupdocs.viewer.options/field/)와 필드 텍스트 표현 사이의 매핑입니다. |
| [page_size](/viewer/python-net/groupdocs.viewer.options/emailoptions/page_size/) | 출력 페이지의 크기입니다. |
| [time_zone_offset](/viewer/python-net/groupdocs.viewer.options/emailoptions/time_zone_offset/) | 메시지 시간대 오프셋입니다. |

### 참고
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
