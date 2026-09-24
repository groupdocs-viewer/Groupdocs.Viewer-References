---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a new instance of Page."
type: docs
url: /python-net/groupdocs.viewer.results/page/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self):
    ...
```

## __init__ {#number-visible}

Initializes a new [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) instance.

```python
def __init__(self, number, visible):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| number | `int` | The page number. |
| visible | `bool` | The page visibility indicator. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `number` is less than or equal to zero. |

## __init__ {#number-name-visible}

Initializes a new Page instance.

```python
def __init__(self, number, name, visible):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| number | `int` | The page number. |
| name | `str` | The worksheet or page name. |
| visible | `bool` | The page visibility indicator. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `number` is less or equal to zero. |

## __init__ {#number-visible-width-height}

Initializes a new [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) instance.

```python
def __init__(self, number, visible, width, height):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| number | `int` | The page number. |
| visible | `bool` | The page visibility indicator. |
| width | `int` | The width of the page in pixels when viewing as JPG or PNG. |
| height | `int` | The height of the page in pixels when viewing as JPG or PNG. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `height` is less or equal to zero. |

## __init__ {#number-name-visible-width-height}

Initializes a new instance of [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| number | `int` | The page number. |
| name | `str` | The worksheet or page name. |
| visible | `bool` | The page visibility indicator. |
| width | `int` | The width of the page in pixels when viewing as JPG or PNG. |
| height | `int` | The height of the page in pixels when viewing as JPG or PNG. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `height` is less or equal to zero. |

## __init__ {#number-visible-width-height-lines}

Initializes a new instance of [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible, width, height, lines):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| number | `int` | The page number. |
| visible | `bool` | The page visibility indicator. |
| width | `int` | The width of the page in pixels when viewing as JPG or PNG. |
| height | `int` | The height of the page in pixels when viewing as JPG or PNG. |
| lines | `List[Line]` | The lines contained by the page when viewing as JPG or PNG with enabled Text Extraction. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `lines` is None. |

## __init__ {#number-name-visible-width-height-lines}

Initializes a new instance of [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height, lines):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| number | `int` | The page number. |
| name | `str` | The worksheet or page name. |
| visible | `bool` | The page visibility indicator. |
| width | `int` | The width of the page in pixels when viewing as JPG or PNG. |
| height | `int` | The height of the page in pixels when viewing as JPG or PNG. |
| lines | `List[Line]` | The lines contained by the page when viewing as JPG or PNG with enabled Text Extraction. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `lines` is None. |

### See Also
* class [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)
