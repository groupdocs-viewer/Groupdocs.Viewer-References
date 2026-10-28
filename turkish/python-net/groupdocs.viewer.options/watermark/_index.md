---
title: "Watermark sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Metin filigranını temsil eder."
type: docs
url: /tr/python-net/groupdocs.viewer.options/watermark/
is_root: false
weight: 360
---


## Watermark class

Metin filigranını temsil eder.

Daha fazla bilgi için çevrimiçi belgelere bakın.

Watermark türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/watermark/__init__/#text) | Bir [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/) sınıfının bir örneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [color](/viewer/python-net/groupdocs.viewer.options/watermark/color/) | Filigran rengi. Varsayılan değer `Rgb24Color.known_colors.css_level1.red`. |
| [font_name](/viewer/python-net/groupdocs.viewer.options/watermark/font_name/) | Filigran için kullanılan yazı tipi adı. |
| [position](/viewer/python-net/groupdocs.viewer.options/watermark/position/) | Filigran konumu. Varsayılan değer `Position.diagonal`. |
| [size](/viewer/python-net/groupdocs.viewer.options/watermark/size/) | Filigran boyutu. Varsayılan değer [`Size.full_size`](/viewer/python-net/groupdocs.viewer.options/size/full_size/). |
| [text](/viewer/python-net/groupdocs.viewer.options/watermark/text/) | Filigran metni. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # Belgeyi yükle
    with Viewer("sample.docx") as viewer:
        # Bir HTML dosyası oluştur.
        viewOptions = HtmlViewOptions.for_embedded_resources(
            "add_text_watermark/output-watermark.html"
        )
        # Filigran ekle.
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```

### Guides
`Watermark` kullanan görev kılavuzları:

* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)

### Ayrıca Bakınız
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
