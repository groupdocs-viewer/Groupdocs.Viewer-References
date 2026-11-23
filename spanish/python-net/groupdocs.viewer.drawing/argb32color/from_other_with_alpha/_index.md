---
title: "método from_other_with_alpha"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Crea una nueva instancia Argb32Color a partir de la instancia especificada, pero con un valor alfa (opacidad) redefinido."
type: docs
url: /es/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/
is_root: false
weight: 1060
---


## from_other_with_alpha {#other-new_alpha}

Crea una nueva instancia de [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) a partir de la instancia especificada, pero con un valor alfa (opacidad) redefinido.

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | `Argb32Color` | Otra instancia `Argb32Color` a partir de la cual se creará la nueva. |
| new_alpha | `int` | Valor del canal alfa redefinido (255 - completamente opaco, 0 - completamente transparente). |

**Returns:** Argb32Color: New `Argb32Color` instance.

## from_other_with_alpha {#other-new_alpha}

Crea una nueva instancia de Argb32Color a partir de un Rgb24Color especificado, pero con un valor alfa (opacidad) especificado.

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | `Rgb24Color` | Otra instancia Rgb24Color, a partir de la cual se creará la nueva. |
| new_alpha | `int` | Valor del canal alfa (255 - totalmente opaco, 0 - totalmente transparente). |

**Returns:** New Argb32Color instance.

### Ver también
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
