---
title: "PdfOptimizationOptions sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Çıktı PDF dosyasına uygulanacak PDF optimizasyon seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.viewer.options/pdfoptimizationoptions/
is_root: false
weight: 150
---


## PdfOptimizationOptions class

Çıktı PDF dosyasına uygulanacak PDF optimizasyon seçeneklerini temsil eder.

Ayrıntılar ve kod örnekleri için, belge sayfasına bakın.

PdfOptimizationOptions türü aşağıdaki üyeleri ortaya çıkar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/) | MaxResolution seçeneğinin varsayılan değerini 300'e ve ImageQuality seçeneğinin varsayılan değerini 100'e başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [compress_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images/) | Bu özellik, çıktı PDF dosyasındaki görüntülerin sıkıştırılmasını sağlar. |
| [convert_to_gray_scale](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/convert_to_gray_scale/) | Bu özellik, çıktı PDF dosyasının gri tonlamaya dönüştürülmesini sağlar. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/image_quality/) | Çıktı PDF dosyasındaki görüntü kalitesi, yüzde olarak ifade edilir. |
| [lineriaze](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/lineriaze/) | Bu özellik, çıktı PDF dosyasının web tarayıcısı ile çevrimiçi görüntülenmesi için optimize edilmesini sağlar. |
| [max_resolution](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/) | Çıktı PDF dosyasındaki maksimum çözünürlük. |
| [optimize_spreadsheets](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/optimize_spreadsheets/) | Bu özellik, PDF dosyalarındaki elektronik tabloların optimize edilmesini sağlar. |
| [remove_annotations](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_annotations/) | Bu özellik, çıktı PDF dosyasından ek açıklamaların kaldırılmasını sağlar. |
| [remove_form_fields](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_form_fields/) | Bu özellik, PDF dosyasından form alanlarının kaldırılmasını sağlar. |
| [remove_unused_objects](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/) | Bu özellik, PDF dosyasından kullanılmayan (sahipsiz) nesneleri kaldırır. |
| [remove_unused_streams](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/) | Bu özellik, sayfa kaynak sözlüğünde referans verilen ancak sayfa içeriğinde hiç kullanılmayan PDF dosyasındaki kullanılmayan (sahipsiz) akışları kaldırır. Varsayılan olarak devre dışı bırakılır (`False`); `True` olarak ayarlandığında çıktı PDF boyutu azalır. |
| [resize_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/) | Bu özellik, çıktı PDF dosyasındaki maksimum çözünürlüğün ayarlanmasını sağlar. |
| [subset_fonts](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/subset_fonts/) | Bu özellik, çıktı PDF dosyasındaki yazı tiplerini alt kümelere ayırır. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

def optimize_pdf():
    with Viewer("sample.docx") as viewer:
        view_options = PdfViewOptions("output/optimized.pdf")
        view_options.pdf_optimization_options = PdfOptimizationOptions()
        # Daha hızlı web önizlemesi için lineerleştirmeyi etkinleştir
        view_options.pdf_optimization_options.lineriaze = True
        # Boyutu azaltmak için ek açıklamaları ve form alanlarını kaldırın
        view_options.pdf_optimization_options.remove_annotations = True
        view_options.pdf_optimization_options.remove_form_fields = True

        viewer.view(view_options)
```

### Ayrıca Bakınız
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
