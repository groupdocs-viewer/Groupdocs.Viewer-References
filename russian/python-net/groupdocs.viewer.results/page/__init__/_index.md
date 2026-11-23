---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует новый экземпляр Page."
type: docs
url: /ru/python-net/groupdocs.viewer.results/page/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self):
    ...
```

## __init__ {#number-visible}

Инициализирует новый экземпляр [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| number | `int` | Номер страницы. |
| visible | `bool` | Индикатор видимости страницы. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `number` меньше или равен нулю. |

## __init__ {#number-name-visible}

Инициализирует новый экземпляр Page.

```python
def __init__(self, number, name, visible):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| number | `int` | Номер страницы. |
| name | `str` | Имя листа или страницы. |
| visible | `bool` | Индикатор видимости страницы. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `number` меньше или равен нулю. |

## __init__ {#number-visible-width-height}

Инициализирует новый экземпляр [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible, width, height):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| number | `int` | Номер страницы. |
| visible | `bool` | Индикатор видимости страницы. |
| width | `int` | Ширина страницы в пикселях при просмотре в формате JPG или PNG. |
| height | `int` | Высота страницы в пикселях при просмотре в формате JPG или PNG. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `height` меньше или равен нулю. |

## __init__ {#number-name-visible-width-height}

Инициализирует новый экземпляр [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| number | `int` | Номер страницы. |
| name | `str` | Имя листа или страницы. |
| visible | `bool` | Индикатор видимости страницы. |
| width | `int` | Ширина страницы в пикселях при просмотре в формате JPG или PNG. |
| height | `int` | Высота страницы в пикселях при просмотре в формате JPG или PNG. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `height` меньше или равен нулю. |

## __init__ {#number-visible-width-height-lines}

Инициализирует новый экземпляр [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible, width, height, lines):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| number | `int` | Номер страницы. |
| visible | `bool` | Индикатор видимости страницы. |
| width | `int` | Ширина страницы в пикселях при просмотре в формате JPG или PNG. |
| height | `int` | Высота страницы в пикселях при просмотре в формате JPG или PNG. |
| lines | `List[Line]` | Строки, содержащиеся на странице при просмотре в формате JPG или PNG с включённым извлечением текста. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `lines` равен None. |

## __init__ {#number-name-visible-width-height-lines}

Инициализирует новый экземпляр [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height, lines):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| number | `int` | Номер страницы. |
| name | `str` | Имя листа или страницы. |
| visible | `bool` | Индикатор видимости страницы. |
| width | `int` | Ширина страницы в пикселях при просмотре в формате JPG или PNG. |
| height | `int` | Высота страницы в пикселях при просмотре в формате JPG или PNG. |
| lines | `List[Line]` | Строки, содержащиеся на странице при просмотре в формате JPG или PNG с включённым извлечением текста. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `lines` равен None. |

### См. также
* class [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)
