---
title: "метод get_attachments"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Возвращает вложения, содержащиеся в документе."
type: docs
url: /ru/python-net/groupdocs.viewer/viewer/get_attachments/
is_root: false
weight: 1030
---


## get_attachments

Возвращает вложения, содержащиеся в документе.

Подробнее:
- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def get_attachments(self):
    ...
```

**Returns:** Attachments contained by the document.

| Исключения | Описание |
| :- | :- |
| `PasswordRequiredException` | Выбрасывается, когда требуется пароль для открытия документа. |
| `IncorrectPasswordException` | Выбрасывается, когда указанный пароль неверен. |

### Пример

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Сохранить каждое вложение в файл
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### См. также
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
