---
title: "error yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Konsola bir hata mesajı yazar."
type: docs
url: /tr/python-net/groupdocs.viewer.logging/filelogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

Konsola bir hata mesajı yazar. Hata günlük mesajları, uygulama akışındaki kurtarılamaz olaylar hakkında bilgi sağlar.

```python
def error(self, message, exception):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| message | `str` | Hata mesajı. |
| exception | `Exception` | İstisna. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `exception` None olduğunda. |

### Ayrıca Bakınız
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
