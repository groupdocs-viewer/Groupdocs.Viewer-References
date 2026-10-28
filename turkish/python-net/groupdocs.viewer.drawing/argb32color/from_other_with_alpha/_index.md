---
title: "from_other_with_alpha yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Belirtilen örnekten yeni bir Argb32Color örneği oluşturur, ancak yeniden tanımlanmış bir alfa (opaklık) değeri ile."
type: docs
url: /tr/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/
is_root: false
weight: 1060
---


## from_other_with_alpha {#other-new_alpha}

Belirtilen örnekten yeni bir [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) örneği oluşturur, ancak yeniden tanımlanmış alfa (opaklık) değeriyle.

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | `Argb32Color` | Yeni örneğin oluşturulacağı diğer `Argb32Color` örneği. |
| new_alpha | `int` | Yeniden tanımlanmış alfa kanal değeri (255 - tamamen opak, 0 - tamamen şeffaf). |

**Returns:** Argb32Color: New `Argb32Color` instance.

## from_other_with_alpha {#other-new_alpha}

Belirtilen bir Rgb24Color'dan yeni bir Argb32Color örneği oluşturur, ancak belirtilen alfa (opaklık) değeriyle.

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | `Rgb24Color` | Yeni örneğin oluşturulacağı diğer Rgb24Color örneği. |
| new_alpha | `int` | Alfa kanal değeri (255 - tamamen opak, 0 - tamamen şeffaf). |

**Returns:** New Argb32Color instance.

### Ayrıca Bakınız
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
