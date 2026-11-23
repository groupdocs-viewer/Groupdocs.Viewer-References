---
title: "Класс Attachment"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет файл вложения, содержащийся в электронном письме, архиве, PDF‑документе или файле данных Outlook."
type: docs
url: /ru/python-net/groupdocs.viewer.results/attachment/
is_root: false
weight: 20
---


## Attachment class

Представляет файл вложения, содержащийся в электронном письме, архиве, PDF‑документе или файле данных Outlook.

Тип Attachment раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/) | Инициализирует новый экземпляр [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#file_name-file_path) | Инициализирует новый экземпляр Attachment. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-size) | Инициализирует новый экземпляр класса Attachment. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-file_type-size) | Инициализирует новый экземпляр класса Attachment. |

### Методы
| Метод | Описание |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/attachment/to_string/) | Возвращает строку, представляющую текущий объект. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.results/attachment/file_name/) | Имя файла вложения. |
| [file_path](/viewer/python-net/groupdocs.viewer.results/attachment/file_path/) | Относительный путь к вложению, например `folder/file.docx`, или имя файла, когда файл находится в корне архива, в электронном письме или в файле данных. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/attachment/file_type/) | Тип файла вложения. |
| [id](/viewer/python-net/groupdocs.viewer.results/attachment/id/) | Уникальный идентификатор вложения в контексте одного файла, содержащего это вложение. |
| [size](/viewer/python-net/groupdocs.viewer.results/attachment/size/) | Размер файла вложения в байтах. |

### Пример

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Доступ к свойствам вложения, например, имени файла
        print(attachment.file_name)
        # Сохранить вложение по пути к файлу
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### См. также
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
