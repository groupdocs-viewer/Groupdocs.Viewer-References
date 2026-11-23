---
title: "Security 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "PDF 문서 보안 옵션."
type: docs
url: /ko/python-net/groupdocs.viewer.options/security/
is_root: false
weight: 260
---


## Security class

PDF 문서 보안 옵션.

자세한 내용은 문서를 참조하십시오.

Security 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/security/__init__/) | [`Security`](/viewer/python-net/groupdocs.viewer.options/security/) 클래스의 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [document_open_password](/viewer/python-net/groupdocs.viewer.options/security/document_open_password/) | PDF 문서를 열기 위해 필요한 비밀번호. |
| [permissions](/viewer/python-net/groupdocs.viewer.options/security/permissions/) | 인쇄, 수정 및 데이터 추출과 같은 PDF 문서 권한. |
| [permissions_password](/viewer/python-net/groupdocs.viewer.options/security/permissions_password/) | 권한 설정을 변경하기 위해 필요한 비밀번호. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

with Viewer("sample.docx") as viewer:
    security = Security()
    security.document_open_password = "o123"
    security.permissions_password = "p123"
    security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

    pdf_options = PdfViewOptions("protected_document.pdf")
    pdf_options.security = security
    viewer.view(pdf_options)
```

### Guides
`Security`를 사용하는 작업 가이드:

* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)

### 참고
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
