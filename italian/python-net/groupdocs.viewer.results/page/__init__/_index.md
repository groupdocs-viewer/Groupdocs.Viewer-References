---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza una nuova istanza di Page."
type: docs
url: /it/python-net/groupdocs.viewer.results/page/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza di [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self):
    ...
```

## __init__ {#number-visible}

Inizializza una nuova istanza di [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| number | `int` | Il numero della pagina. |
| visible | `bool` | L'indicatore di visibilità della pagina. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `number` è minore o uguale a zero. |

## __init__ {#number-name-visible}

Inizializza una nuova istanza di Page.

```python
def __init__(self, number, name, visible):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| number | `int` | Il numero della pagina. |
| name | `str` | Il nome del foglio di lavoro o della pagina. |
| visible | `bool` | L'indicatore di visibilità della pagina. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `number` è minore o uguale a zero. |

## __init__ {#number-visible-width-height}

Inizializza una nuova istanza di [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible, width, height):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| number | `int` | Il numero della pagina. |
| visible | `bool` | L'indicatore di visibilità della pagina. |
| width | `int` | La larghezza della pagina in pixel quando visualizzata come JPG o PNG. |
| height | `int` | L'altezza della pagina in pixel quando visualizzata come JPG o PNG. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `height` è minore o uguale a zero. |

## __init__ {#number-name-visible-width-height}

Inizializza una nuova istanza di [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| number | `int` | Il numero della pagina. |
| name | `str` | Il nome del foglio di lavoro o della pagina. |
| visible | `bool` | L'indicatore di visibilità della pagina. |
| width | `int` | La larghezza della pagina in pixel quando visualizzata come JPG o PNG. |
| height | `int` | L'altezza della pagina in pixel quando visualizzata come JPG o PNG. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `height` è minore o uguale a zero. |

## __init__ {#number-visible-width-height-lines}

Inizializza una nuova istanza di [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible, width, height, lines):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| number | `int` | Il numero della pagina. |
| visible | `bool` | L'indicatore di visibilità della pagina. |
| width | `int` | La larghezza della pagina in pixel quando visualizzata come JPG o PNG. |
| height | `int` | L'altezza della pagina in pixel quando visualizzata come JPG o PNG. |
| lines | `List[Line]` | Le linee contenute nella pagina quando visualizzata come JPG o PNG con estrazione testo abilitata. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `lines` è None. |

## __init__ {#number-name-visible-width-height-lines}

Inizializza una nuova istanza di [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height, lines):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| number | `int` | Il numero della pagina. |
| name | `str` | Il nome del foglio di lavoro o della pagina. |
| visible | `bool` | L'indicatore di visibilità della pagina. |
| width | `int` | La larghezza della pagina in pixel quando visualizzata come JPG o PNG. |
| height | `int` | L'altezza della pagina in pixel quando visualizzata come JPG o PNG. |
| lines | `List[Line]` | Le linee contenute nella pagina quando visualizzata come JPG o PNG con estrazione testo abilitata. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `lines` è None. |

### Vedi anche
* class [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)
