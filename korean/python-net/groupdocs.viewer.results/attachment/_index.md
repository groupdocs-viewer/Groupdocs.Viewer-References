---
title: "Attachment 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "이메일 메시지, 아카이브, PDF 문서 또는 Outlook 데이터 파일에 포함된 첨부 파일을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/attachment/
is_root: false
weight: 20
---


## Attachment class

이메일 메시지, 아카이브, PDF 문서 또는 Outlook 데이터 파일에 포함된 첨부 파일을 나타냅니다.

Attachment 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/) | [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/)의 새 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#file_name-file_path) | 새 Attachment 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-size) | Attachment 클래스의 새 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-file_type-size) | Attachment 클래스의 새 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/attachment/to_string/) | 현재 객체를 나타내는 문자열을 반환합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.results/attachment/file_name/) | 첨부 파일 이름입니다. |
| [file_path](/viewer/python-net/groupdocs.viewer.results/attachment/file_path/) | 첨부 파일의 상대 경로, 예: `folder/file.docx`, 또는 파일이 아카이브 루트, 이메일 메시지 또는 데이터 파일에 위치한 경우 파일 이름입니다. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/attachment/file_type/) | 첨부 파일 유형입니다. |
| [id](/viewer/python-net/groupdocs.viewer.results/attachment/id/) | 첨부 파일을 포함하는 단일 파일 컨텍스트에서 첨부 파일의 고유 식별자입니다. |
| [size](/viewer/python-net/groupdocs.viewer.results/attachment/size/) | 첨부 파일 크기(바이트)입니다. |

### 예시

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # 첨부 파일 속성에 접근합니다. 예: 파일 이름
        print(attachment.file_name)
        # 첨부 파일을 파일 경로에 저장합니다.
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### 참고
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
