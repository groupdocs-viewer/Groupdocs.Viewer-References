---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une nouvelle instance de Page."
type: docs
url: /fr/python-net/groupdocs.viewer.results/page/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self):
    ...
```

## __init__ {#number-visible}

Initialise une nouvelle instance de [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| number | `int` | Le numéro de page. |
| visible | `bool` | L'indicateur de visibilité de la page. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `number` est inférieur ou égal à zéro. |

## __init__ {#number-name-visible}

Initialise une nouvelle instance de Page.

```python
def __init__(self, number, name, visible):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| number | `int` | Le numéro de page. |
| name | `str` | Le nom de la feuille de calcul ou de la page. |
| visible | `bool` | L'indicateur de visibilité de la page. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `number` est inférieur ou égal à zéro. |

## __init__ {#number-visible-width-height}

Initialise une nouvelle instance de [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible, width, height):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| number | `int` | Le numéro de page. |
| visible | `bool` | L'indicateur de visibilité de la page. |
| width | `int` | La largeur de la page en pixels lors de la visualisation en JPG ou PNG. |
| height | `int` | La hauteur de la page en pixels lors de la visualisation en JPG ou PNG. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `height` est inférieur ou égal à zéro. |

## __init__ {#number-name-visible-width-height}

Initialise une nouvelle instance de [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| number | `int` | Le numéro de page. |
| name | `str` | Le nom de la feuille de calcul ou de la page. |
| visible | `bool` | L'indicateur de visibilité de la page. |
| width | `int` | La largeur de la page en pixels lors de la visualisation en JPG ou PNG. |
| height | `int` | La hauteur de la page en pixels lors de la visualisation en JPG ou PNG. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `height` est inférieur ou égal à zéro. |

## __init__ {#number-visible-width-height-lines}

Initialise une nouvelle instance de [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible, width, height, lines):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| number | `int` | Le numéro de page. |
| visible | `bool` | L'indicateur de visibilité de la page. |
| width | `int` | La largeur de la page en pixels lors de la visualisation en JPG ou PNG. |
| height | `int` | La hauteur de la page en pixels lors de la visualisation en JPG ou PNG. |
| lines | `List[Line]` | Les lignes contenues dans la page lors de la visualisation en JPG ou PNG avec extraction de texte activée. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `lines` est None. |

## __init__ {#number-name-visible-width-height-lines}

Initialise une nouvelle instance de [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height, lines):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| number | `int` | Le numéro de page. |
| name | `str` | Le nom de la feuille de calcul ou de la page. |
| visible | `bool` | L'indicateur de visibilité de la page. |
| width | `int` | La largeur de la page en pixels lors de la visualisation en JPG ou PNG. |
| height | `int` | La hauteur de la page en pixels lors de la visualisation en JPG ou PNG. |
| lines | `List[Line]` | Les lignes contenues dans la page lors de la visualisation en JPG ou PNG avec extraction de texte activée. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `lines` est None. |

### Voir aussi
* class [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)
