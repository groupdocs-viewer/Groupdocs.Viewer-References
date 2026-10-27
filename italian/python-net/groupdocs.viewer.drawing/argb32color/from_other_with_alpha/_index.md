---
title: "metodo from_other_with_alpha"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Crea una nuova istanza Argb32Color dall'istanza specificata, ma con un valore alfa (opacità) ridefinito."
type: docs
url: /it/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/
is_root: false
weight: 1060
---


## from_other_with_alpha {#other-new_alpha}

Crea una nuova istanza [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) dall'istanza specificata, ma con un valore alfa (opacità) ridefinito.

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | `Argb32Color` | Altra istanza `Argb32Color` da cui verrà creata la nuova. |
| new_alpha | `int` | Valore del canale alfa ridefinito (255 - completamente opaco, 0 - completamente trasparente). |

**Returns:** Argb32Color: New `Argb32Color` instance.

## from_other_with_alpha {#other-new_alpha}

Crea una nuova istanza Argb32Color da un Rgb24Color specificato, ma con un valore alfa (opacità) specificato.

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | `Rgb24Color` | Altra istanza Rgb24Color, da cui verrà creata la nuova. |
| new_alpha | `int` | Valore del canale alfa (255 - completamente opaco, 0 - completamente trasparente). |

**Returns:** New Argb32Color instance.

### Vedi anche
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
