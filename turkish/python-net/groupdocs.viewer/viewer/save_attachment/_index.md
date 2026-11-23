---
title: "save_attachment yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Ek dosyasını hedef akışa kaydeder."
type: docs
url: /tr/python-net/groupdocs.viewer/viewer/save_attachment/
is_root: false
weight: 1070
---


## save_attachment {#attachment-destination}

`destination` akışına ek dosyasını kaydeder.

- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def save_attachment(self, attachment, destination):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attachment | `Attachment` | Ek. |
| destination | `io.RawIOBase` | Yazılabilir akış. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `destination` None olduğunda. |
| `PasswordRequiredException` | Belgeyi açmak için bir şifre gerektiğinde. |
| `IncorrectPasswordException` | Belirtilen şifre yanlış olduğunda. |
| `GroupDocsViewerException` | Ek bulunamadığında. |

### Örnek

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Ayrıca Bakınız
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
