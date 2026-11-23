---
title: "طريقة save_attachment"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يحفظ ملف المرفق إلى تدفق الوجهة."
type: docs
url: /ar/python-net/groupdocs.viewer/viewer/save_attachment/
is_root: false
weight: 1070
---


## save_attachment {#attachment-destination}

يحفظ ملف المرفق إلى تدفق `destination`.

- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def save_attachment(self, attachment, destination):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| attachment | `Attachment` | المرفق. |
| destination | `io.RawIOBase` | دفق قابل للكتابة. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما يكون `destination` هو None. |
| `PasswordRequiredException` | عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| `IncorrectPasswordException` | عندما تكون كلمة المرور المحددة غير صحيحة. |
| `GroupDocsViewerException` | عندما لا يمكن العثور على المرفق. |

### مثال

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### انظر أيضًا
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
