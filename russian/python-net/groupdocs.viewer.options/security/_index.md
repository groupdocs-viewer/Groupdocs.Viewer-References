---
title: "Класс Security"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Опции безопасности PDF‑документа."
type: docs
url: /ru/python-net/groupdocs.viewer.options/security/
is_root: false
weight: 260
---


## Security class

Опции безопасности PDF‑документа.

Для подробностей см. документацию.

Тип Security раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/security/__init__/) | Инициализирует экземпляр класса [`Security`](/viewer/python-net/groupdocs.viewer.options/security/). |

### Свойства
| Свойство | Описание |
| :- | :- |
| [document_open_password](/viewer/python-net/groupdocs.viewer.options/security/document_open_password/) | Пароль, необходимый для открытия PDF‑документа. |
| [permissions](/viewer/python-net/groupdocs.viewer.options/security/permissions/) | Разрешения PDF‑документа, такие как печать, изменение и извлечение данных. |
| [permissions_password](/viewer/python-net/groupdocs.viewer.options/security/permissions_password/) | Пароль, необходимый для изменения настроек разрешений. |

### Пример

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
Руководства задач, использующие `Security`:

* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)

### См. также
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
