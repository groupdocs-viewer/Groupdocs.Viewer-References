---
title: "save_attachment метод"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Сохраняет файл вложения в целевой поток."
type: docs
url: /ru/python-net/groupdocs.viewer/viewer/save_attachment/
is_root: false
weight: 1070
---


## save_attachment {#attachment-destination}

Сохраняет файл вложения в поток `destination`.

- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def save_attachment(self, attachment, destination):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| attachment | `Attachment` | Вложение. |
| destination | `io.RawIOBase` | Записываемый поток. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `destination` равно None. |
| `PasswordRequiredException` | Когда для открытия документа требуется пароль. |
| `IncorrectPasswordException` | Когда указанный пароль неверен. |
| `GroupDocsViewerException` | Когда вложение не найдено. |

### Пример

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### См. также
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
