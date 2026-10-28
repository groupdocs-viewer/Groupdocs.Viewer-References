---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Word'ın yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.results/word/__init__/
is_root: false
weight: 10
---


## __init__

Yeni bir [`Word`](/viewer/python-net/groupdocs.viewer.results/word/) örneği oluşturur.

```python
def __init__(self):
    ...
```

## __init__ {#word-x-y-width-height-characters}

Yeni bir [`Word`](/viewer/python-net/groupdocs.viewer.results/word/) örneği oluşturur.

```python
def __init__(self, word, x, y, width, height, characters):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| word | `str` | Kelime. |
| x | `float` | Kelimeyi içeren dikdörtgenin başladığı sayfa düzenindeki en üst sol noktanın X koordinatı. |
| y | `float` | Kelimeyi içeren dikdörtgenin başladığı sayfa düzenindeki en üst sol noktanın Y koordinatı. |
| width | `float` | Kelimeyi içeren dikdörtgenin genişliği. |
| height | `float` | Kelimeyi içeren dikdörtgenin yüksekliği. |
| characters | `List[Character]` | Kelimenin içerdiği karakterler. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `characters` null olduğunda. |

### Ayrıca Bakınız
* class [`Word`](/viewer/python-net/groupdocs.viewer.results/word/)
