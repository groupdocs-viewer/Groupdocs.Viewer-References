---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz von Page."
type: docs
url: /de/python-net/groupdocs.viewer.results/page/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz von [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self):
    ...
```

## __init__ {#number-visible}

Initialisiert eine neue [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) Instanz.

```python
def __init__(self, number, visible):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| number | `int` | Die Seitennummer. |
| visible | `bool` | Der Sichtbarkeitsindikator der Seite. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `number` kleiner oder gleich Null ist. |

## __init__ {#number-name-visible}

Initialisiert eine neue Page‑Instanz.

```python
def __init__(self, number, name, visible):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| number | `int` | Die Seitennummer. |
| name | `str` | Der Arbeitsblatt- oder Seitenname. |
| visible | `bool` | Der Sichtbarkeitsindikator der Seite. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `number` kleiner oder gleich Null ist. |

## __init__ {#number-visible-width-height}

Initialisiert eine neue [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) Instanz.

```python
def __init__(self, number, visible, width, height):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| number | `int` | Die Seitennummer. |
| visible | `bool` | Der Sichtbarkeitsindikator der Seite. |
| width | `int` | Die Breite der Seite in Pixeln, wenn sie als JPG oder PNG angezeigt wird. |
| height | `int` | Die Höhe der Seite in Pixeln beim Anzeigen als JPG oder PNG. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `height` kleiner oder gleich Null ist. |

## __init__ {#number-name-visible-width-height}

Initialisiert eine neue Instanz von [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| number | `int` | Die Seitennummer. |
| name | `str` | Der Arbeitsblatt- oder Seitenname. |
| visible | `bool` | Der Sichtbarkeitsindikator der Seite. |
| width | `int` | Die Breite der Seite in Pixeln, wenn sie als JPG oder PNG angezeigt wird. |
| height | `int` | Die Höhe der Seite in Pixeln beim Anzeigen als JPG oder PNG. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `height` kleiner oder gleich Null ist. |

## __init__ {#number-visible-width-height-lines}

Initialisiert eine neue Instanz von [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible, width, height, lines):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| number | `int` | Die Seitennummer. |
| visible | `bool` | Der Sichtbarkeitsindikator der Seite. |
| width | `int` | Die Breite der Seite in Pixeln, wenn sie als JPG oder PNG angezeigt wird. |
| height | `int` | Die Höhe der Seite in Pixeln beim Anzeigen als JPG oder PNG. |
| lines | `List[Line]` | Die Zeilen, die von der Seite enthalten sind, wenn sie als JPG oder PNG mit aktivierter Textextraktion angezeigt wird. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `lines` None ist. |

## __init__ {#number-name-visible-width-height-lines}

Initialisiert eine neue Instanz von [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height, lines):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| number | `int` | Die Seitennummer. |
| name | `str` | Der Arbeitsblatt- oder Seitenname. |
| visible | `bool` | Der Sichtbarkeitsindikator der Seite. |
| width | `int` | Die Breite der Seite in Pixeln, wenn sie als JPG oder PNG angezeigt wird. |
| height | `int` | Die Höhe der Seite in Pixeln beim Anzeigen als JPG oder PNG. |
| lines | `List[Line]` | Die Zeilen, die von der Seite enthalten sind, wenn sie als JPG oder PNG mit aktivierter Textextraktion angezeigt wird. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `lines` None ist. |

### Siehe auch
* class [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)
