---
title: "Sayfaları yeniden sırala"
linkTitle: "Reorder pages"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: ".NET üzerinden Python için GroupDocs.Viewer ile işleme sırasında PDF sayfalarını yeniden sırala. Çıktı sayfa sırasını kontrol edin."
type: docs
url: /tr/python-net/guides/reorder-pages/
is_root: false
weight: 100
---


GroupDocs.Viewer, kaynak belgedeki sayfa sırasını korur. Bunun yerine, çıktı PDF belgesindeki sayfaları yeniden sıralayabilirsiniz.

Sayfaları yeniden sıralamak için şu adımları izleyin:

1. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) nesnesini oluşturun.
2. [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) nesnesini oluşturun.
3. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) nesnesinin [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) metodunu çağırın. Yeni sayfa sırasını son parametrelerde belirtin.

Aşağıdaki kod parçacığı sayfaları nasıl yeniden sıralayacağınızı gösterir:

{{< tabs \"example1\">}}
{{< tab \"Python\">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def reorder_pages():
    # Belgeyi yükle
    with Viewer("sample.docx") as viewer:
        # Görünüm seçeneklerini oluşturun.
        viewOptions = PdfViewOptions("reorder_pages/reordered_pages.pdf")

        # Sayfa numaralarını, işlemek istediğiniz sırada geçirin.
        viewer.view(viewOptions, [2, 1])

if __name__ == "__main__":
    reorder_pages()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/sample.docx) tıklayın.

{{< /tab >}}
{{< tab \"reordered_pages.pdf\" >}}
```text
Binary file (PDF, 176 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/reorder_pages/reordered_pages.pdf)
{{< /tab >}}
{{< /tabs >}}
