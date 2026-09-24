---
title: from_other_with_alpha method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Creates a new Argb32Color instance from the specified instance, but with a redefined alpha (opacity) value."
type: docs
url: /python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/
is_root: false
weight: 1060
---


## from_other_with_alpha {#other-new_alpha}

Creates a new [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance from the specified instance, but with a redefined alpha (opacity) value.

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| other | `Argb32Color` | Other `Argb32Color` instance from which the new one will be created. |
| new_alpha | `int` | Re-defined alpha channel value (255 - fully opaque, 0 - fully transparent). |

**Returns:** Argb32Color: New `Argb32Color` instance.

## from_other_with_alpha {#other-new_alpha}

Creates a new Argb32Color instance from a specified Rgb24Color, but with a specified alpha (opacity) value.

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| other | `Rgb24Color` | Other Rgb24Color instance, from which the new one will be created. |
| new_alpha | `int` | Alpha channel value (255 - fully opaque, 0 - fully transparent). |

**Returns:** New Argb32Color instance.

### See Also
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
