---
title: "méthode from_other_with_alpha"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Crée une nouvelle instance Argb32Color à partir de l'instance spécifiée, mais avec une valeur alpha (opacité) redéfinie."
type: docs
url: /fr/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/
is_root: false
weight: 1060
---


## from_other_with_alpha {#other-new_alpha}

Crée une nouvelle instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) à partir de l'instance spécifiée, mais avec une valeur alpha (opacité) redéfinie.

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| other | `Argb32Color` | Autre instance `Argb32Color` à partir de laquelle la nouvelle sera créée. |
| new_alpha | `int` | Valeur du canal alpha redéfinie (255 - totalement opaque, 0 - totalement transparent). |

**Returns:** Argb32Color: New `Argb32Color` instance.

## from_other_with_alpha {#other-new_alpha}

Crée une nouvelle instance Argb32Color à partir d'un Rgb24Color spécifié, mais avec une valeur alpha (opacité) spécifiée.

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| other | `Rgb24Color` | Autre instance Rgb24Color, à partir de laquelle la nouvelle sera créée. |
| new_alpha | `int` | Valeur du canal alpha (255 - totalement opaque, 0 - totalement transparent). |

**Returns:** New Argb32Color instance.

### Voir aussi
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
