---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una nueva instancia de Page."
type: docs
url: /es/python-net/groupdocs.viewer.results/page/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self):
    ...
```

## __init__ {#number-visible}

Inicializa una nueva instancia de [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| number | `int` | El número de página. |
| visible | `bool` | El indicador de visibilidad de la página. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `number` es menor o igual a cero. |

## __init__ {#number-name-visible}

Inicializa una nueva instancia de Page.

```python
def __init__(self, number, name, visible):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| number | `int` | El número de página. |
| name | `str` | El nombre de la hoja de cálculo o página. |
| visible | `bool` | El indicador de visibilidad de la página. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `number` es menor o igual a cero. |

## __init__ {#number-visible-width-height}

Inicializa una nueva instancia de [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible, width, height):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| number | `int` | El número de página. |
| visible | `bool` | El indicador de visibilidad de la página. |
| width | `int` | El ancho de la página en píxeles al verla como JPG o PNG. |
| height | `int` | La altura de la página en píxeles al verla como JPG o PNG. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `height` es menor o igual a cero. |

## __init__ {#number-name-visible-width-height}

Inicializa una nueva instancia de [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| number | `int` | El número de página. |
| name | `str` | El nombre de la hoja de cálculo o página. |
| visible | `bool` | El indicador de visibilidad de la página. |
| width | `int` | El ancho de la página en píxeles al verla como JPG o PNG. |
| height | `int` | La altura de la página en píxeles al verla como JPG o PNG. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `height` es menor o igual a cero. |

## __init__ {#number-visible-width-height-lines}

Inicializa una nueva instancia de [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible, width, height, lines):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| number | `int` | El número de página. |
| visible | `bool` | El indicador de visibilidad de la página. |
| width | `int` | El ancho de la página en píxeles al verla como JPG o PNG. |
| height | `int` | La altura de la página en píxeles al verla como JPG o PNG. |
| lines | `List[Line]` | Las líneas contenidas en la página al verla como JPG o PNG con extracción de texto habilitada. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `lines` es None. |

## __init__ {#number-name-visible-width-height-lines}

Inicializa una nueva instancia de [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height, lines):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| number | `int` | El número de página. |
| name | `str` | El nombre de la hoja de cálculo o página. |
| visible | `bool` | El indicador de visibilidad de la página. |
| width | `int` | El ancho de la página en píxeles al verla como JPG o PNG. |
| height | `int` | La altura de la página en píxeles al verla como JPG o PNG. |
| lines | `List[Line]` | Las líneas contenidas en la página al verla como JPG o PNG con extracción de texto habilitada. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `lines` es None. |

### Ver también
* class [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)
