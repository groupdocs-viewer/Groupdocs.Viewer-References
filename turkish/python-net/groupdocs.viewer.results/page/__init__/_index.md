---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Page sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.results/page/__init__/
is_root: false
weight: 10
---


## __init__

Yeni bir [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) örneği başlatır.

```python
def __init__(self):
    ...
```

## __init__ {#number-visible}

Yeni bir [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) örneği başlatır.

```python
def __init__(self, number, visible):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| number | `int` | Sayfa numarası. |
| visible | `bool` | Sayfa görünürlük göstergesi. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `number` sıfırdan küçük veya eşit olduğunda. |

## __init__ {#number-name-visible}

Yeni bir Page örneği başlatır.

```python
def __init__(self, number, name, visible):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| number | `int` | Sayfa numarası. |
| name | `str` | Çalışma sayfası veya sayfa adı. |
| visible | `bool` | Sayfa görünürlük göstergesi. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `number` sıfırdan küçük veya eşit olduğunda. |

## __init__ {#number-visible-width-height}

Yeni bir [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) örneği başlatır.

```python
def __init__(self, number, visible, width, height):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| number | `int` | Sayfa numarası. |
| visible | `bool` | Sayfa görünürlük göstergesi. |
| width | `int` | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden genişliği. |
| height | `int` | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden yüksekliği. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `height` sıfırdan küçük veya eşit olduğunda. |

## __init__ {#number-name-visible-width-height}

Yeni bir [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) örneği başlatır.

```python
def __init__(self, number, name, visible, width, height):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| number | `int` | Sayfa numarası. |
| name | `str` | Çalışma sayfası veya sayfa adı. |
| visible | `bool` | Sayfa görünürlük göstergesi. |
| width | `int` | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden genişliği. |
| height | `int` | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden yüksekliği. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `height` sıfırdan küçük veya eşit olduğunda. |

## __init__ {#number-visible-width-height-lines}

Yeni bir [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) örneği başlatır.

```python
def __init__(self, number, visible, width, height, lines):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| number | `int` | Sayfa numarası. |
| visible | `bool` | Sayfa görünürlük göstergesi. |
| width | `int` | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden genişliği. |
| height | `int` | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden yüksekliği. |
| lines | `List[Line]` | Metin Çıkarma etkinleştirildiğinde JPG veya PNG olarak görüntülendiğinde sayfada bulunan satırlar. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `lines` None ise. |

## __init__ {#number-name-visible-width-height-lines}

Yeni bir [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) örneği başlatır.

```python
def __init__(self, number, name, visible, width, height, lines):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| number | `int` | Sayfa numarası. |
| name | `str` | Çalışma sayfası veya sayfa adı. |
| visible | `bool` | Sayfa görünürlük göstergesi. |
| width | `int` | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden genişliği. |
| height | `int` | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden yüksekliği. |
| lines | `List[Line]` | Metin Çıkarma etkinleştirildiğinde JPG veya PNG olarak görüntülendiğinde sayfada bulunan satırlar. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `lines` None olduğunda. |

### Ayrıca Bakınız
* class [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)
