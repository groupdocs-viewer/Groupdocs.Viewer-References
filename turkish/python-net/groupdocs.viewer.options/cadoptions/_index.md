---
title: "CadOptions sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "CAD çizimlerini renderlemek için seçenekler."
type: docs
url: /tr/python-net/groupdocs.viewer.options/cadoptions/
is_root: false
weight: 30
---


## CadOptions class

CAD çizimlerini renderlemek için seçenekler.

Daha fazla bilgi ve kod örnekleri için, Render CAD drawings and models as HTML, PDF, and image files ve Specify rendering options for CAD files belgelerine bakın.

CadOptions türü aşağıdaki üyeleri sunar:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [for_rendering_by_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/#height) | Yüksekliğe göre render etmek için bir CadOptions örneği başlatır. |
| [for_rendering_by_scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/#scale_factor) | Ölçek faktörüne göre render etmek için bir CadOptions örneği başlatır. |
| [for_rendering_by_width](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/#width) | Genişliğe göre render etmek için [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) sınıfının bir örneğini başlatır. |
| [for_rendering_by_width_and_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/#width-height) | Genişlik ve yüksekliğe göre render etmek için CadOptions sınıfının bir örneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [background_color](/viewer/python-net/groupdocs.viewer.options/cadoptions/background_color/) | Görselin arka plan rengi. |
| [enable_performance_conversion_mode](/viewer/python-net/groupdocs.viewer.options/cadoptions/enable_performance_conversion_mode/) | Tüm CAD formatları için performans odaklı bir dönüştürme modunu etkinleştiren bayrak; True olarak ayarlandığında çıktı kalitesinde azalma pahasına dönüşüm hızlanır; maksimum kalite için varsayılan değer False'tur. |
| [height](/viewer/python-net/groupdocs.viewer.options/cadoptions/height/) | Çıktı sonucunun yüksekliği (piksel cinsinden). |
| [layers](/viewer/python-net/groupdocs.viewer.options/cadoptions/layers/) | Render edilecek CAD çizim katmanları. |
| [layout_name](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) | Render edilecek belirli yerleşimin adı. Yerleşim adı büyük/küçük harfe duyarlıdır. |
| [pc3_file](/viewer/python-net/groupdocs.viewer.options/cadoptions/pc3_file/) | PC3 plotter yapılandırma dosyası. |
| [render_layouts](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) | CAD belgesindeki yerleşimlerin render edilip edilmeyeceğini belirten bayrak. |
| [scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/scale_factor/) | Ölçek faktörü. 1'den büyük değer çıktı sonucunu büyütür; 0 ile 1 arasındaki değer çıktı sonucunu küçültür. |
| [tiles](/viewer/python-net/groupdocs.viewer.options/cadoptions/tiles/) | Render edilecek çizim bölgeleri. |
| [width](/viewer/python-net/groupdocs.viewer.options/cadoptions/width/) | Çıktı sonucunun genişliği (piksel cinsinden). |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # CAD dosyasını yükle
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        # Genişliğe göre render yap ve performans modunu etkinleştir
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True

        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### Ayrıca Bakınız
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
