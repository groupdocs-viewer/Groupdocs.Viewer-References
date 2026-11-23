---
title: "error yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Konsola bir hata mesajı yazar."
type: docs
url: /tr/python-net/groupdocs.viewer.logging/consolelogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

Konsola bir hata mesajı yazar.

Error günlük mesajları, uygulama akışındaki geri döndürülemez olaylar hakkında bilgi sağlar.

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
| `ValueError` | `exception` None olduğunda fırlatılır. |

### Ayrıca Bakınız
* class [`ConsoleLogger`](/viewer/python-net/groupdocs.viewer.logging/consolelogger/)
