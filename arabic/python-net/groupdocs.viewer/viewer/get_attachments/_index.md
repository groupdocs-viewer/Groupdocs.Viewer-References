---
title: "طريقة get_attachments"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يرجع المرفقات الموجودة في المستند."
type: docs
url: /ar/python-net/groupdocs.viewer/viewer/get_attachments/
is_root: false
weight: 1030
---


## get_attachments

يرجع المرفقات الموجودة في المستند.

المزيد من المعلومات:
- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def get_attachments(self):
    ...
```

**Returns:** Attachments contained by the document.

| يُثير | الوصف |
| :- | :- |
| `PasswordRequiredException` | يتم إلقاؤه عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| `IncorrectPasswordException` | يتم إلقاؤه عندما تكون كلمة المرور المحددة غير صحيحة. |

### مثال

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # احفظ كل مرفق إلى ملف
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### انظر أيضًا
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
