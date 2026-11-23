---
title: "metode from_other_with_alpha"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Membuat instance Argb32Color baru dari instance yang ditentukan, tetapi dengan nilai alpha (opasitas) yang didefinisikan ulang."
type: docs
url: /id/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/
is_root: false
weight: 1060
---


## from_other_with_alpha {#other-new_alpha}

Membuat instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) baru dari instance yang ditentukan, tetapi dengan nilai alpha (opasitas) yang didefinisikan ulang.

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | `Argb32Color` | Instance `Argb32Color` lain yang akan menjadi sumber pembuatan yang baru. |
| new_alpha | `int` | Nilai saluran alpha yang didefinisikan ulang (255 - sepenuhnya opak, 0 - sepenuhnya transparan). |

**Returns:** Argb32Color: New `Argb32Color` instance.

## from_other_with_alpha {#other-new_alpha}

Membuat instance Argb32Color baru dari Rgb24Color yang ditentukan, tetapi dengan nilai alpha (opasitas) yang ditentukan.

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | `Rgb24Color` | Instance Rgb24Color lain, yang akan menjadi sumber pembuatan yang baru. |
| new_alpha | `int` | Nilai saluran alfa (255 - sepenuhnya tidak tembus, 0 - sepenuhnya tembus). |

**Returns:** New Argb32Color instance.

### Lihat Juga
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
