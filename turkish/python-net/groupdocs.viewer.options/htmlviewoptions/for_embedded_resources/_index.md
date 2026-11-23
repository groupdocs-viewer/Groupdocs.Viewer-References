---
title: "for_embedded_resources yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Gömülü kaynaklarla HTML renderlemek için bir HtmlViewOptions örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/
is_root: false
weight: 1010
---


## for_embedded_resources {#create_page_stream}

Gömülü kaynaklarla HTML renderlemek için bir HtmlViewOptions örneği başlatır.

Daha fazla ayrıntı için belgeleri inceleyin.

```python
def for_embedded_resources(cls, create_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Çıktı sayfa verilerini yazmak için kullanılan bir akışı örnekleyen yöntem. |

**Returns:** HtmlViewOptions: New instance configured for rendering HTML with embedded resources.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | Eğer `create_page_stream` None ise. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#create_page_stream-release_page_stream}

Gömülü kaynaklarla HTML'ye renderlemek için [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) sınıfının bir örneğini başlatır.

```python
def for_embedded_resources(cls, create_page_stream, release_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Çıktı sayfa verilerini yazmak için kullanılan akışı örnekleyen yöntem. |
| release_page_stream | `ReleasePageStream` | `create_page_stream` parametresine atanan yöntem tarafından oluşturulan akışı serbest bırakan yöntem. |

**Returns:** HtmlViewOptions: New instance of the `HtmlViewOptions` class for rendering into HTML with embedded resources.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | Eğer `release_page_stream` None ise. Kod örneği için belgeleri inceleyin. |

## for_embedded_resources {#page_stream_factory}

Gömülü kaynaklarla HTML'ye renderlemek için bir HtmlViewOptions örneği başlatır.

Kod örneği için https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources adresindeki belgeleri inceleyin.

```python
def for_embedded_resources(cls, page_stream_factory):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Çıktı sayfa akışını oluşturma ve serbest bırakma yöntemlerini uygulayan fabrika. |

**Returns:** HtmlViewOptions: New instance of HtmlViewOptions for rendering into HTML with embedded resources.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | page_stream_factory None olduğunda. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources

Gömülü kaynaklarla [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) sınıfının bir örneğini başlatır.

Kod örneği için belgelere bakın.

```python
def for_embedded_resources(cls):
    ...
```

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#file_path_format}

Gömülü kaynaklar için bir HtmlViewOptions örneği başlatır.

Kod örneği için belgelere bakın.

```python
def for_embedded_resources(cls, file_path_format):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path_format | `str` | Dosya yolu biçimi örn. 'page_{0}.html'. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `file_path_format` None veya boş olduğunda. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Ayrıca Bakınız
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
