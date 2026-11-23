---
title: "PdfOptions sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "PDF belgelerine renderlemek için seçenekleri temsil eder."
type: docs
url: /tr/python-net/groupdocs.viewer.options/pdfoptions/
is_root: false
weight: 160
---


## PdfOptions class

PDF belgelerine renderlemek için seçenekleri temsil eder.

Ayrıntılar için belgelere bakın.

PdfOptions türü aşağıdaki üyeleri ortaya çıkarır:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptions/__init__/) | PdfOptions sınıfının yeni bir örneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [disable_chars_grouping](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/) | Bu özellik, sayfa işleme sırasında hassas sembol konumlandırması için sembol gruplandırmayı devre dışı bırakır. |
| [disable_copy_protection](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/) | Bu özellik, HTML'ye işleme sırasında içerik kopyalama korumasını devre dışı bırakır. |
| [disable_font_license_verifications](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/) | Bu özellik, geçerli XPS/OXPS belgesindeki tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırakır. |
| [enable_font_hinting](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_font_hinting/) | Bu özellik, yazı tipi ipuçlarını etkinleştirir. |
| [enable_layered_rendering](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/) | Bu özellik, HTML'ye işleme sırasında orijinal PDF belgesinin z-sırasında metin ve grafikleri render etmeyi etkinleştirir. |
| [fixed_layout](/viewer/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/) | Sabit düzen seçeneği, PDF ve EPUB belgelerinin HTML'ye sabit bir düzenle render edilmesini sağlar. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptions/image_quality/) | HTML'ye işleme sırasında görüntü kaynakları için çıktı görüntü kalitesi. Varsayılan kalite `ImageQuality.LOW`'dur. |
| [render_original_page_size](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/) | Çıktı sayfa boyutu, kaynak PDF belgesinin sayfa boyutuyla eşleşecek şekilde ayarlanır. |
| [render_text_as_image](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/) | Bu seçenek, PDF dosyalarındaki metinlerin HTML çıktısında görüntü olarak render edilmesini sağlar. |
| [wrap_images_in_svg](/viewer/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/) | Bu özellik, çıktı kalitesini artırmak için çıktı HTML belgesindeki her görüntüyü bir SVG etiketi içinde sarmalamayı etkinleştirir. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("sample.pdf") as viewer:
    view_options = PngViewOptions("output_{0}.png")
    # PDF sayfalarını görüntülere render ederken yazı tipi ipuçlarını etkinleştir.
    view_options.pdf_options.enable_font_hinting = True
    viewer.view(view_options)
```

### Ayrıca Bakınız
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
