---
title: "set_license yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Mevcut sürece bir lisans uygula."
type: docs
url: /tr/python-net/groupdocs.viewer/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Mevcut sürece bir lisans uygula.

```python
def set_license(self, license_source):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| license_source |  | Bir ``.lic`` dosyasına giden bir dize yolu ya da lisans baytlarını sağlayan okunabilir bir dosya benzeri nesne. Dosya benzeri girdiler, köprüye iletilmeden önce geçici bir dosyaya yazılır. |

| Yükseltir | Açıklama |
| :- | :- |
| `TypeError` | ``license_source`` ne bir dize yolu ne de okunabilir bir dosya benzeri nesne ise. |

### Ayrıca Bakınız
* class [`License`](/viewer/python-net/groupdocs.viewer/license/)
