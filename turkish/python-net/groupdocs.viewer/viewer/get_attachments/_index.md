---
title: "get_attachments yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Belge tarafından içerilen ekleri döndürür."
type: docs
url: /tr/python-net/groupdocs.viewer/viewer/get_attachments/
is_root: false
weight: 1030
---


## get_attachments

Belge tarafından içerilen ekleri döndürür.

Daha fazla bilgi edinin:
- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def get_attachments(self):
    ...
```

**Returns:** Attachments contained by the document.

| Yükseltir | Açıklama |
| :- | :- |
| `PasswordRequiredException` | Belgeyi açmak için parola gerektiğinde atılır. |
| `IncorrectPasswordException` | Belirtilen parolanın yanlış olduğu durumda atılır. |

### Örnek

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Her eki bir dosyaya kaydedin
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Ayrıca Bakınız
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
