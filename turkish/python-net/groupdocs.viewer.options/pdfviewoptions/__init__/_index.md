---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "PdfViewOptions sınıfının bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_file_stream}

Bir [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) örneği başlatır.

Kod örneği için https://docs.groupdocs.com/viewer/net/rendering-to-pdf/ adresindeki belgelere bakın.

```python
def __init__(self, create_file_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | Çıktı dosyası verilerini yazmak için kullanılan akışı örnekleyen yöntem. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | Eğer `create_file_stream` `None` ise. |

## __init__ {#create_file_stream-release_file_stream}

Yeni bir PdfViewOptions örneği başlatır.

Kod örneği için belgelere bakın.

```python
def __init__(self, create_file_stream, release_file_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | Çıktı dosyası verilerini yazmak için kullanılan bir `io.RawIOBase` akışı döndüren çağrılabilir. |
| release_file_stream | `ReleaseFileStream` | `create_file_stream`'a atanan yöntem tarafından oluşturulan akışı serbest bırakan çağrılabilir. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | Eğer `release_file_stream` None ise. |

## __init__ {#file_stream_factory}

Bir PdfViewOptions örneği başlatır.

Kod örneği için belgelere bakın: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

```python
def __init__(self, file_stream_factory):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_stream_factory | `IFileStreamFactory` | Çıktı dosyası akışını oluşturma ve serbest bırakma yöntemlerini uygulayan fabrika. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `file_stream_factory` None olduğunda ortaya çıkar. |

## __init__

Bir PdfViewOptions örneği başlatır.

Bu yapıcı, çıktı dosyası için dosya yolu biçimi olarak `\"output.pdf\"` kullanan bir PdfViewOptions başlatır. Çıktı dosyası uygulamanın geçerli çalışma dizinine yerleştirilecektir.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

## __init__ {#output_file_path}

Bir [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) sınıfının örneğini başlatır.

Kod örneği için belgelere bakın.

```python
def __init__(self, output_file_path):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| output_file_path | `str` | Çıktı PDF dosyasının yolu. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `output_file_path` None veya boş olduğunda. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### Ayrıca Bakınız
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
