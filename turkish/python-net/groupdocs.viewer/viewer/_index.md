---
title: "Viewer sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Belge renderleme sürecini kontrol eden ana sınıfı temsil eder."
type: docs
url: /tr/python-net/groupdocs.viewer/viewer/
is_root: false
weight: 100
---


## Viewer class

Belge renderleme sürecini kontrol eden ana sınıfı temsil eder.

Viewer türü aşağıdaki üyeleri ortaya çıkarır:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream) | Yeni bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) sınıfının örneğini başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options) | Yeni bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-settings) | Yeni bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options-settings) | Yeni bir Viewer örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream) | `[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` sınıfının yeni bir örneğini başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-leave_open) | Yeni bir Viewer örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options) | Yeni bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-leave_open) | Yeni bir Viewer örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings) | Yeni bir Viewer örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings-leave_open) | Yeni bir Viewer örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings) | Yeni bir Viewer örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings-leave_open) | Yeni bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path) | Yeni bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) sınıfının örneğini başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-settings) | Yeni bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) sınıfı örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options) | Yeni bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options-settings) | Yeni bir Viewer örneği başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [dispose](/viewer/python-net/groupdocs.viewer/viewer/dispose/) | Dosya akışını ve yönetilen iç kaynakları serbest bırakır. |
| [get_all_fonts](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) | Yüklenen belgede kullanılan tüm yazı tiplerini, gömülü yazı tipleri ve işletim sistemine kurulu sistem yazı tipleri dahil olmak üzere döndürür. |
| [get_attachments](/viewer/python-net/groupdocs.viewer/viewer/get_attachments/) | Belge tarafından içerilen ekleri döndürür. |
| [get_file_info](/viewer/python-net/groupdocs.viewer/viewer/get_file_info/) | Dosya türü ve dosyanın şifreli olup olmadığını gösteren bir işaret gibi dosya hakkında bilgi döndürür. |
| [get_view_info](/viewer/python-net/groupdocs.viewer/viewer/get_view_info/#options) | Görünüm ve belgeye özgü bilgileri döndürür. |
| [get_view_info_view_info_options](/viewer/python-net/groupdocs.viewer/viewer/get_view_info_view_info_options/) |  |
| [save_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment/#attachment-destination) | `destination` akışına ek dosyasını kaydeder. |
| [save_attachment_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_attachment/) |  |
| [save_attachment_stream](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_stream/) |  |
| [save_attachment_streams](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_streams/) |  |
| [search](/viewer/python-net/groupdocs.viewer/viewer/search/#options) | Metin araması gerçekleştirir ve bulunan metni, sağlanan seçeneklere göre yüklü belgede vurgular. |
| [search_search_highlight_options](/viewer/python-net/groupdocs.viewer/viewer/search_search_highlight_options/) |  |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options) | Tüm belge sayfalarının görünümünü oluşturur. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-page_numbers) | Belirli belge sayfalarının görünümünü oluşturur. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-cancellation_token-page_numbers) | Belirli belge sayfalarının görünümünü oluşturur. |
| [view_view_options](/viewer/python-net/groupdocs.viewer/viewer/view_view_options/) |  |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, PngViewOptions

# DOCX'i HTML'e dönüştürür
with Viewer("./sample.docx") as viewer:
    html_opts = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(html_opts)

# PDF'i PNG'ye dönüştürür
with Viewer("document.pdf") as viewer:
    png_opts = PngViewOptions("page_{0}.png")
    viewer.view(png_opts)
```

### Guides
`Viewer` kullanan görev kılavuzları:

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Get Document Information](/viewer/python-net/guides/get-document-info/)
* [Load document from local disk](/viewer/python-net/guides/load-document-from-local-disk/)
* [Load document from stream](/viewer/python-net/guides/load-document-from-stream/)
* [Load document from URL](/viewer/python-net/guides/load-document-from-url/)
* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)
* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)
* [Reorder pages](/viewer/python-net/guides/reorder-pages/)
* [Save attachments](/viewer/python-net/guides/how-to-extract-and-save-attachments/)

### Ayrıca Bakınız
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
