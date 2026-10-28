---
title: "LoadOptions sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Bir dosya açmak için kullanılan seçenekler."
type: docs
url: /tr/python-net/groupdocs.viewer.options/loadoptions/
is_root: false
weight: 110
---


## LoadOptions class

Bir dosya açmak için kullanılan seçenekler.

LoadOptions türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/) | [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/) sınıfının bir örneğini başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/#file_type) | Yeni bir LoadOptions örneği başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/) | Bu özellik, [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/) ve [`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/) dosyaları için kodlama algılamayı etkinleştirir. |
| [encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/) | [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/) ve [`FileType.msg`](/viewer/python-net/groupdocs.viewer/filetype/msg/) gibi metin tabanlı dosyalar veya e-posta mesajları açılırken kullanılan kodlama. Varsayılan değer `utf-8`. |
| [file_type](/viewer/python-net/groupdocs.viewer.options/loadoptions/file_type/) | Açılacak dosyanın türü. |
| [password](/viewer/python-net/groupdocs.viewer.options/loadoptions/password/) | Şifreli bir dosyayı açmak için parola. |
| [resource_loading_timeout](/viewer/python-net/groupdocs.viewer.options/loadoptions/resource_loading_timeout/) | Harici kaynakları yüklemek için zaman aşımı. |
| [skip_external_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) | Bu özellik, [`LoadOptions.whitelisted_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) içinde listelenenler dışındaki tüm harici kaynakların (örneğin görüntüler) yüklenmesini devre dışı bırakır. |
| [try_repair](/viewer/python-net/groupdocs.viewer.options/loadoptions/try_repair/) | Bu özellik, GroupDocs.Viewer'ın PDF belgelerindeki yapısal bozulmaları onarmaya çalışmasını etkinleştirir. Varsayılan değer False'tur. |
| [whitelisted_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) | [`LoadOptions.skip_external_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) `True` olarak ayarlandığında yüklenmesi gereken harici kaynaklara karşılık gelen URL parçacıklarının listesi. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, LoadOptions

load_options = LoadOptions()
load_options.password = "12345"

with Viewer("protected.docx", load_options) as viewer:
    viewer.view(HtmlViewOptions.for_embedded_resources("page_{0}.html"))
```

### Ayrıca Bakınız
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
