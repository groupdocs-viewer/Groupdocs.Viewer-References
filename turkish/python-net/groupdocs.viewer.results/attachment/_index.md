---
title: "Attachment sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "E-posta mesajı, arşiv, PDF belgesi veya Outlook veri dosyası içinde bulunan bir ek dosyasını temsil eder."
type: docs
url: /tr/python-net/groupdocs.viewer.results/attachment/
is_root: false
weight: 20
---


## Attachment class

E-posta mesajı, arşiv, PDF belgesi veya Outlook veri dosyası içinde bulunan bir ek dosyasını temsil eder.

Attachment türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/) | Yeni bir [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/) örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#file_name-file_path) | Yeni bir Attachment örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-size) | Attachment sınıfının yeni bir örneğini başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-file_type-size) | Attachment sınıfının yeni bir örneğini başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/attachment/to_string/) | Mevcut nesneyi temsil eden bir dize döndürür. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.results/attachment/file_name/) | Ek dosya adı. |
| [file_path](/viewer/python-net/groupdocs.viewer.results/attachment/file_path/) | Ek'in göreli yolu, ör. `folder/file.docx`, ya da dosya bir arşivin kökünde, bir e‑mail mesajında veya bir veri dosyasında bulunduğunda dosya adı. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/attachment/file_type/) | Ek dosya türü. |
| [id](/viewer/python-net/groupdocs.viewer.results/attachment/id/) | Bu eki içeren tek bir dosya bağlamında ekin benzersiz tanımlayıcısı. |
| [size](/viewer/python-net/groupdocs.viewer.results/attachment/size/) | Ek dosyasının bayt cinsinden boyutu. |

### Örnek

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Ek özelliklerine erişin, ör. dosya adı
        print(attachment.file_name)
        # Ek'i bir dosya yoluna kaydedin
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Ayrıca Bakınız
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
