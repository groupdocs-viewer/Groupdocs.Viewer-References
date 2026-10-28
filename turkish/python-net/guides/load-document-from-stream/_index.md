---
title: "Akıştan belgeyi yükle"
linkTitle: "Load from stream"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "GroupDocs.Viewer for Python via .NET ile belgeleri doğrudan dosya benzeri bir nesneden — açık dosya tutamağı, BytesIO veya herhangi bir akış — yükleyin."
type: docs
url: /tr/python-net/guides/load-document-from-stream/
is_root: false
weight: 60
---


Bir belgeyi diske dosya olarak kaydetmeden akıştan yükleyebilirsiniz. Bu özelliği, belgeyi bir URL, FTP gibi farklı kaynaklardan yüklemek için kullanabilirsiniz.

Bir belgeyi akıştan yüklemek için şu adımları izleyin:

1. Belge akışını elde etmek için bir yöntem uygulayın.
2. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) sınıf yapıcısını çağırın. Önceki adımda uygulanan yöntemi belirtin.

Aşağıdaki kod parçacığı, bir belgeyi akıştan nasıl yükleyeceğinizi gösterir:

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_stream():
    # Belge akışını aç
    stream = open("sample.docx", "rb")

    # Akıştan belgeyi renderlayın.
    with Viewer(stream) as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    load_document_from_stream()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-stream/sample.docx) tıklayın.

{{< /tab >}}
{{< tab \"load-document-from-stream-outputs.zip\" >}}
```text
page_1.html (317 KB)
page_2.html (149 KB)
page_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-stream/load_document_from_stream/load-document-from-stream-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

Ayrıca, bir belgeyi `BytesIO` akışına indirip diske hiç yazmadan renderlamak için somut bir örnek olan [Load document from URL]() bölümüne bakın.
