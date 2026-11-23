---
title: "for_external_resources yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Harici kaynaklarla HTML'ye renderlemek için HtmlViewOptions sınıfının bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/
is_root: false
weight: 1060
---


## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url}

Harici kaynaklarla HTML'ye renderlemek için [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) sınıfının bir örneğini başlatır.

Kod örneği için belgelere bakın.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Çıktı sayfa verilerini yazmak için kullanılan akışı başlatan yöntem. |
| create_resource_stream | `CreateResourceStream` | `create_page_stream` yöntemi tarafından oluşturulan akışı serbest bırakan yöntem. |
| create_resource_url | `CreateResourceUrl` | HTML kaynağı için URL oluşturan yöntem. |

**Returns:** New instance of the `HtmlViewOptions` class for rendering into HTML with external resources.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `create_resource_url` None olduğunda. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("sample.docx") as viewer:
    options = HtmlViewOptions.for_external_resources(
        "page_{0}.html",
        "page_{0}/resource_{0}_{1}",
        "page_{0}/resource_{0}_{1}"
    )
    viewer.view(options)
```

## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url-release_page_stream-release_resource_stream}

Harici kaynaklarla HTML'ye renderlemek için HtmlViewOptions sınıfının bir örneğini başlatır.

Ek kullanım örnekleri için GroupDocs Viewer belgelerine bakın.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url, release_page_stream, release_resource_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Çıktı sayfa verilerini yazmak için kullanılan bir akışı örnekleyen yöntem. |
| create_resource_stream | `CreateResourceStream` | Çıktı HTML kaynağı verilerini yazmak için kullanılan bir akışı başlatan yöntem. |
| create_resource_url | `CreateResourceUrl` | HTML kaynağı için bir URL oluşturan yöntem. |
| release_page_stream | `ReleasePageStream` | `create_page_stream` yöntemine geçirilen temsilci tarafından oluşturulan akışı serbest bırakan yöntem. |
| release_resource_stream | `ReleaseResourceStream` | `create_resource_stream` yöntemine geçirilen temsilci tarafından oluşturulan akışı serbest bırakan yöntem. |

**Returns:** HtmlViewOptions: New instance of the HtmlViewOptions class for rendering into HTML with external resources.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `release_resource_stream` None olduğunda. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_excel_to_html_external():
    # Excel elektronik tablosunu yükle
    with Viewer("invoice.xlsx") as viewer:
        # Elektronik tabloyu harici kaynaklarla HTML'ye dönüştür.
        # {0} ve {1} sırasıyla geçerli sayfa numarası ve kaynak adıyla değiştirilir.
        view_options = HtmlViewOptions.for_external_resources(
            "render_excel_to_html_external/pdf_page_{0}.html",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}"
        )
        viewer.view(view_options)

if __name__ == "__main__":
    render_excel_to_html_external()
```

## for_external_resources {#page_stream_factory-resource_stream_factory}

Harici kaynaklarla HTML'ye renderlemek için bir HtmlViewOptions örneği başlatır.

Daha fazla ayrıntı için çevrimiçi belgelere bakın.

```python
def for_external_resources(cls, page_stream_factory, resource_stream_factory):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Çıktı sayfa akışını oluşturma ve serbest bırakma yöntemlerini uygulayan fabrika. |
| resource_stream_factory | `IResourceStreamFactory` | Kaynak URL'leri oluşturma, örnekleme ve çıktı HTML kaynak akışlarını serbest bırakma için gereken yöntemleri uygulayan fabrika. |

**Returns:** HtmlViewOptions: A new HtmlViewOptions instance configured for external resources.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | Eğer `resource_stream_factory` None ise. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Her sayfa için bir HTML dosyası oluşturun ve dış kaynakları ayrı ayrı depolayın.
    # {0} ve {1} sırasıyla geçerli sayfa numarası ve kaynak adıyla değiştirilir.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

## for_external_resources

Harici kaynaklarla HTML dosyaları oluşturmak üzere yapılandırılmış bir HtmlViewOptions örneği başlatır.

Örnek, sağlanan biçim dizelerini kullanır:
- `html_file_path_format` – file path format for the output HTML files (e.g., `"page_{0}.html"`).
- `resources_path_format` – folder path format for external resource files (e.g., `"page_{0}/resource_{0}_{1}"`).
- `resources_url_format` – URL format for HTML resources (e.g., `"page_{0}/resource_{0}_{1}"`).

Çıktı dosyaları, uygulamanın geçerli çalışma dizinine yerleştirilir.

```python
def for_external_resources(cls):
    ...
```

**Returns:** HtmlViewOptions: Configured options for rendering HTML with external resources.

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html_external():
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html_external()
```

## for_external_resources {#file_path_format-resource_file_path_format-resource_url_format}

[`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) sınıfının bir örneğini başlatır.

Kod örneği için belgelere bakın.

```python
def for_external_resources(cls, file_path_format, resource_file_path_format, resource_url_format):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path_format | `str` | Dosya yolu biçimi, ör. `'page_{0}.html'`. |
| resource_file_path_format | `str` | Kaynak dosya yolu biçimi, ör. `'page_{0}/resource_{1}'`. |
| resource_url_format | `str` | Kaynak URL biçimi, ör. `'page_{0}/resource_{1}'`. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | Eğer `resource_url_format` None veya boş ise. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Bir belge yükleyin ve her sayfayı dış kaynaklarla bir HTML dosyasına render edin.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

### Ayrıca Bakınız
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
