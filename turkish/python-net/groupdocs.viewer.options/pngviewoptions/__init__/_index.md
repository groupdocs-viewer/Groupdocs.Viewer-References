---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Yeni bir PngViewOptions örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/pngviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Yeni bir [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) örneği başlatır.

Kod örneği için belgelere bakın.

```python
def __init__(self, create_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Çıktı sayfa verilerini yazmak için kullanılan bir akışı örnekleyen yöntem. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `create_page_stream` None olduğunda. |

## __init__ {#create_page_stream-release_page_stream}

[`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) sınıfının bir örneğini başlatır.

Kod örneği için belgelere bakın.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Çıktı sayfa verilerini yazmak için kullanılan bir akışı örnekleyen yöntem. |
| release_page_stream | `ReleasePageStream` | `create_page_stream` parametresine geçirilen delegeye atanan yöntem tarafından oluşturulan akışı serbest bırakan yöntem. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `release_page_stream` None olduğunda. |

## __init__ {#page_stream_factory}

Yeni bir [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) örneği başlatır.

Daha fazla bilgi için belgelere bakın.

```python
def __init__(self, page_stream_factory):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Çıktı sayfa akışını oluşturma ve serbest bırakma yöntemlerini uygulayan fabrika. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `page_stream_factory` `None` ise. |

## __init__

Bir PngViewOptions örneği başlatır.

Bu yapıcı, çıktı dosyaları için varsayılan dosya yolu biçimi olarak ``\"p_{0}.png\"`` kullanan bir [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) oluşturur. Oluşturulan PNG dosyaları uygulamanın geçerli çalışma dizinine kaydedilir.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

## __init__ {#file_path_format}

Yeni bir [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) örneği başlatır.

Kod örneği için belgelere bakın.

```python
def __init__(self, file_path_format):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path_format | `str` | Dosya yolu biçimi, ör. `'page_{0}.png'`. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `file_path_format` None veya boş olduğunda. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

### Ayrıca Bakınız
* class [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
