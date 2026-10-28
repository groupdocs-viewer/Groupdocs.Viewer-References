---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "JpgViewOptions sınıfının bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/jpgviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

JpgViewOptions sınıfının bir örneğini başlatır.

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

JpgViewOptions sınıfının bir örneğini başlatır.

Kod örneği için belgelere bakın.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Çıktı sayfa verilerini yazmak için kullanılan bir akışı örnekleyen çağrılabilir. |
| release_page_stream | `ReleasePageStream` | `create_page_stream`'e geçirilen temsilciye atanan yöntemin oluşturduğu akışı serbest bırakan çağrılabilir. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `release_page_stream` None ise. |

## __init__ {#page_stream_factory}

[`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) sınıfının bir örneğini başlatır.

Kod örneği için https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg adresindeki belgelere bakın.

```python
def __init__(self, page_stream_factory):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Çıktı sayfa akışını oluşturma ve serbest bırakma yöntemlerini uygulayan fabrika. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `page_stream_factory` None olduğunda. |

## __init__

Bir JpgViewOptions örneğini başlatır.

Bu yapıcı, çıktı dosyaları için dosya yolu biçimi olarak `\"p_{0}.jpg\"` kullanarak [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) sınıfının bir örneğini başlatır. Çıktı dosyaları uygulamanın geçerli çalışma dizinine yerleştirilir.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = JpgViewOptions("render_excel_to_jpg/excel_to_jpg_{0}.jpg")
    view_options.width = 800
    view_options.height = 900
    viewer.view(view_options)
```

## __init__ {#file_path_format}

[`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) yeni bir örneğini başlatır.

Kod örneği için belgelere bakın.

```python
def __init__(self, file_path_format):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path_format | `str` | Dosya yolu biçimi, ör. `'page_{0}.jpg'`. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `file_path_format` None veya boş ise. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

def render_to_jpg():
    # Bir belge yükleyin (ör. bir Excel dosyası)
    with Viewer("invoice.xlsx") as viewer:
        # Bir dosya adı deseniyle JPEG görüntü seçenekleri oluşturun.
        view_options = JpgViewOptions("output/excel_page_{0}.jpg")
        view_options.width = 800
        view_options.height = 900
        viewer.view(view_options)

if __name__ == "__main__":
    render_to_jpg()
```

### Ayrıca Bakınız
* class [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)
