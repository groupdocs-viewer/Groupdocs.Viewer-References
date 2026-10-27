---
title: "save_attachment 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "첨부 파일을 대상 스트림에 저장합니다."
type: docs
url: /ko/python-net/groupdocs.viewer/viewer/save_attachment/
is_root: false
weight: 1070
---


## save_attachment {#attachment-destination}

`destination` 스트림에 첨부 파일을 저장합니다.

- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def save_attachment(self, attachment, destination):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attachment | `Attachment` | 첨부 파일. |
| destination | `io.RawIOBase` | 쓰기 가능한 스트림. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `destination`가 None일 때. |
| `PasswordRequiredException` | 문서를 열기 위해 비밀번호가 필요한 경우. |
| `IncorrectPasswordException` | 지정된 비밀번호가 올바르지 않을 때. |
| `GroupDocsViewerException` | 첨부 파일을 찾을 수 없을 때. |

### 예시

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### 참고
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
