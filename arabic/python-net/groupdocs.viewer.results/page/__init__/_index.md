---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "ينشئ مثيلًا جديدًا من Page."
type: docs
url: /ar/python-net/groupdocs.viewer.results/page/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثيلاً جديدًا من [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self):
    ...
```

## __init__ {#number-visible}

ينشئ مثيلاً جديدًا من [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| number | `int` | رقم الصفحة. |
| visible | `bool` | مؤشر ظهور الصفحة. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما يكون `number` أقل من أو يساوي الصفر. |

## __init__ {#number-name-visible}

ينشئ مثيلاً جديدًا من Page.

```python
def __init__(self, number, name, visible):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| number | `int` | رقم الصفحة. |
| name | `str` | اسم ورقة العمل أو الصفحة. |
| visible | `bool` | مؤشر ظهور الصفحة. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما يكون `number` أقل من أو يساوي الصفر. |

## __init__ {#number-visible-width-height}

ينشئ مثيلاً جديدًا من [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible, width, height):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| number | `int` | رقم الصفحة. |
| visible | `bool` | مؤشر ظهور الصفحة. |
| width | `int` | عرض الصفحة بالبكسل عند العرض كملف JPG أو PNG. |
| height | `int` | ارتفاع الصفحة بالبكسل عند العرض كملف JPG أو PNG. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما يكون `height` أقل من أو يساوي الصفر. |

## __init__ {#number-name-visible-width-height}

ينشئ مثيلاً جديدًا من [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| number | `int` | رقم الصفحة. |
| name | `str` | اسم ورقة العمل أو الصفحة. |
| visible | `bool` | مؤشر ظهور الصفحة. |
| width | `int` | عرض الصفحة بالبكسل عند العرض كملف JPG أو PNG. |
| height | `int` | ارتفاع الصفحة بالبكسل عند العرض كملف JPG أو PNG. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما يكون `height` أقل من أو يساوي الصفر. |

## __init__ {#number-visible-width-height-lines}

ينشئ مثيلاً جديدًا من [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible, width, height, lines):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| number | `int` | رقم الصفحة. |
| visible | `bool` | مؤشر ظهور الصفحة. |
| width | `int` | عرض الصفحة بالبكسل عند العرض كملف JPG أو PNG. |
| height | `int` | ارتفاع الصفحة بالبكسل عند العرض كملف JPG أو PNG. |
| lines | `List[Line]` | السطور الموجودة في الصفحة عند العرض كملف JPG أو PNG مع تمكين استخراج النص. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `lines` يساوي None. |

## __init__ {#number-name-visible-width-height-lines}

ينشئ مثيلاً جديدًا من [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height, lines):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| number | `int` | رقم الصفحة. |
| name | `str` | اسم ورقة العمل أو الصفحة. |
| visible | `bool` | مؤشر ظهور الصفحة. |
| width | `int` | عرض الصفحة بالبكسل عند العرض كملف JPG أو PNG. |
| height | `int` | ارتفاع الصفحة بالبكسل عند العرض كملف JPG أو PNG. |
| lines | `List[Line]` | السطور الموجودة في الصفحة عند العرض كملف JPG أو PNG مع تمكين استخراج النص. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما يكون `lines` يساوي None. |

### انظر أيضًا
* class [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)
