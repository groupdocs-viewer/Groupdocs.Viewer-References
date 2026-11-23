---
title: "ArchiveOptions sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Arşiv dosyalarını renderlemek için seçenekleri içerir."
type: docs
url: /tr/python-net/groupdocs.viewer.options/archiveoptions/
is_root: false
weight: 10
---


## ArchiveOptions class

Arşiv dosyalarını renderlemek için seçenekleri içerir.

ArchiveOptions türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/archiveoptions/__init__/) | Bir [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/) sınıfının örneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.options/archiveoptions/file_name/) | Görüntülenen arşiv dosya adı. |
| [folder](/viewer/python-net/groupdocs.viewer.options/archiveoptions/folder/) | Render edilecek klasör. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "render_specific_archive_folder/specific_archive_folder.html"
    )
    view_options.archive_options.folder = "first_folder"
    viewer.view(view_options)
```

### Ayrıca Bakınız
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
