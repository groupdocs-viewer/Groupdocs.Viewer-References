---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ny instans av Page."
type: docs
url: /sv/python-net/groupdocs.viewer.results/page/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self):
    ...
```

## __init__ {#number-visible}

Initierar en ny [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) instans.

```python
def __init__(self, number, visible):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| number | `int` | Sidnumret. |
| visible | `bool` | Sidans synlighetsindikator. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `number` är mindre än eller lika med noll. |

## __init__ {#number-name-visible}

Initierar en ny Page-instans.

```python
def __init__(self, number, name, visible):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| number | `int` | Sidnumret. |
| name | `str` | Arbetsbladets eller sidans namn. |
| visible | `bool` | Sidans synlighetsindikator. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `number` är mindre eller lika med noll. |

## __init__ {#number-visible-width-height}

Initierar en ny [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) instans.

```python
def __init__(self, number, visible, width, height):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| number | `int` | Sidnumret. |
| visible | `bool` | Sidans synlighetsindikator. |
| width | `int` | Bredden på sidan i pixlar vid visning som JPG eller PNG. |
| height | `int` | Höjden på sidan i pixlar vid visning som JPG eller PNG. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `height` är mindre eller lika med noll. |

## __init__ {#number-name-visible-width-height}

Initierar en ny instans av [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| number | `int` | Sidnumret. |
| name | `str` | Arbetsbladets eller sidans namn. |
| visible | `bool` | Sidans synlighetsindikator. |
| width | `int` | Bredden på sidan i pixlar vid visning som JPG eller PNG. |
| height | `int` | Höjden på sidan i pixlar vid visning som JPG eller PNG. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `height` är mindre eller lika med noll. |

## __init__ {#number-visible-width-height-lines}

Initierar en ny instans av [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible, width, height, lines):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| number | `int` | Sidnumret. |
| visible | `bool` | Sidans synlighetsindikator. |
| width | `int` | Bredden på sidan i pixlar vid visning som JPG eller PNG. |
| height | `int` | Höjden på sidan i pixlar vid visning som JPG eller PNG. |
| lines | `List[Line]` | Raderna som sidan innehåller vid visning som JPG eller PNG med aktiverad textutvinning. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `lines` är None. |

## __init__ {#number-name-visible-width-height-lines}

Initierar en ny instans av [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height, lines):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| number | `int` | Sidnumret. |
| name | `str` | Arbetsbladets eller sidans namn. |
| visible | `bool` | Sidans synlighetsindikator. |
| width | `int` | Bredden på sidan i pixlar vid visning som JPG eller PNG. |
| height | `int` | Höjden på sidan i pixlar vid visning som JPG eller PNG. |
| lines | `List[Line]` | Raderna som sidan innehåller vid visning som JPG eller PNG med aktiverad textutvinning. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `lines` är None. |

### Se även
* class [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)
