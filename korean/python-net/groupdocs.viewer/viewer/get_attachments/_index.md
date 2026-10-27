---
title: "get_attachments 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "문서에 포함된 첨부 파일을 반환합니다."
type: docs
url: /ko/python-net/groupdocs.viewer/viewer/get_attachments/
is_root: false
weight: 1030
---


## get_attachments

문서에 포함된 첨부 파일을 반환합니다.

자세히 보기:
- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def get_attachments(self):
    ...
```

**Returns:** Attachments contained by the document.

| 예외 발생 | 설명 |
| :- | :- |
| `PasswordRequiredException` | 문서를 열기 위해 비밀번호가 필요할 때 발생합니다. |
| `IncorrectPasswordException` | 지정된 비밀번호가 올바르지 않을 때 발생합니다. |

### 예시

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # 각 첨부 파일을 파일에 저장
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### 참고
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
