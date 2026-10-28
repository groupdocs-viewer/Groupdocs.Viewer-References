---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Line'ın yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.results/line/__init__/
is_root: false
weight: 10
---


## __init__

Yeni bir [`Line`](/viewer/python-net/groupdocs.viewer.results/line/) örneği oluşturur.

```python
def __init__(self):
    ...
```

## __init__ {#line-x-y-width-height-words}

Yeni bir [`Line`](/viewer/python-net/groupdocs.viewer.results/line/) sınıfı örneği oluşturur.

```python
def __init__(self, line, x, y, width, height, words):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| line | `str` | Satır. |
| x | `float` | Satırı içeren dikdörtgenin başladığı sayfa düzenindeki en üst sol noktanın X koordinatı. |
| y | `float` | Satırı içeren dikdörtgenin başladığı sayfa düzenindeki en üst sol noktanın Y koordinatı. |
| width | `float` | Satırı içeren dikdörtgenin genişliği (piksel cinsinden). |
| height | `float` | Satırı içeren dikdörtgenin yüksekliği (piksel cinsinden). |
| words | `List[Word]` | Satırın içerdiği kelimeler. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `line` null veya boş olduğunda, ya da `words` null olduğunda ortaya çıkar. |

### Ayrıca Bakınız
* class [`Line`](/viewer/python-net/groupdocs.viewer.results/line/)
