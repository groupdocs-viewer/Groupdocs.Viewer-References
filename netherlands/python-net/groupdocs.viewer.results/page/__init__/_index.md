---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van Page."
type: docs
url: /nl/python-net/groupdocs.viewer.results/page/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self):
    ...
```

## __init__ {#number-visible}

Initialiseert een nieuw [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) exemplaar.

```python
def __init__(self, number, visible):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| number | `int` | Het paginanummer. |
| visible | `bool` | De paginazichtbaarheidsindicator. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `number` kleiner dan of gelijk aan nul is. |

## __init__ {#number-name-visible}

Initialiseert een nieuw Page-exemplaar.

```python
def __init__(self, number, name, visible):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| number | `int` | Het paginanummer. |
| name | `str` | De werkblad- of paginanaam. |
| visible | `bool` | De paginazichtbaarheidsindicator. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `number` kleiner of gelijk aan nul is. |

## __init__ {#number-visible-width-height}

Initialiseert een nieuw [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) exemplaar.

```python
def __init__(self, number, visible, width, height):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| number | `int` | Het paginanummer. |
| visible | `bool` | De paginazichtbaarheidsindicator. |
| width | `int` | De breedte van de pagina in pixels bij weergave als JPG of PNG. |
| height | `int` | De hoogte van de pagina in pixels bij weergave als JPG of PNG. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `height` kleiner of gelijk aan nul is. |

## __init__ {#number-name-visible-width-height}

Initialiseert een nieuw exemplaar van [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| number | `int` | Het paginanummer. |
| name | `str` | De werkblad- of paginanaam. |
| visible | `bool` | De paginazichtbaarheidsindicator. |
| width | `int` | De breedte van de pagina in pixels bij weergave als JPG of PNG. |
| height | `int` | De hoogte van de pagina in pixels bij weergave als JPG of PNG. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `height` kleiner of gelijk aan nul is. |

## __init__ {#number-visible-width-height-lines}

Initialiseert een nieuw exemplaar van [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible, width, height, lines):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| number | `int` | Het paginanummer. |
| visible | `bool` | De paginazichtbaarheidsindicator. |
| width | `int` | De breedte van de pagina in pixels bij weergave als JPG of PNG. |
| height | `int` | De hoogte van de pagina in pixels bij weergave als JPG of PNG. |
| lines | `List[Line]` | De regels die in de pagina staan bij weergave als JPG of PNG met ingeschakelde tekstextractie. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `lines` None is. |

## __init__ {#number-name-visible-width-height-lines}

Initialiseert een nieuw exemplaar van [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height, lines):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| number | `int` | Het paginanummer. |
| name | `str` | De werkblad- of paginanaam. |
| visible | `bool` | De paginazichtbaarheidsindicator. |
| width | `int` | De breedte van de pagina in pixels bij weergave als JPG of PNG. |
| height | `int` | De hoogte van de pagina in pixels bij weergave als JPG of PNG. |
| lines | `List[Line]` | De regels die in de pagina staan bij weergave als JPG of PNG met ingeschakelde tekstextractie. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `lines` None is. |

### Zie ook
* class [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)
