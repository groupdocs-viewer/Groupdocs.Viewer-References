---
title: "Belgeyi yerel diskten yükle"
linkTitle: "Load from local disk"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "GroupDocs.Viewer for Python via .NET ile bir dosya yolu kullanarak yerel diskinizden belgeleri yükleyin."
type: docs
url: /tr/python-net/guides/load-document-from-local-disk/
is_root: false
weight: 50
---


Bir dosya yolunu kullanarak yerel diskten bir belge yükleyebilirsiniz. GroupDocs.Viewer dosyayı yalnızca okuma modunda açar.

Aşağıdaki kod parçacığı, yerel yol dizesi kullanarak bir belgeyi nasıl yükleyeceğinizi gösterir:

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_local_disk():
    # Belgeyi yerel diskten yükle
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_embedded_resources("load_document_from_local_disk/document_from_local_disk_{0}.html")
        viewer.view(html_options)

if __name__ == "__main__":
    load_document_from_local_disk()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-local-disk/sample.docx) tıklayın.

{{< /tab >}}
{{< tab \"load-document-from-local-disk-outputs.zip\" >}}
```text
load_document_from_local_disk/document_from_local_disk_1.html (317 KB)
load_document_from_local_disk/document_from_local_disk_2.html (149 KB)
load_document_from_local_disk/document_from_local_disk_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-local-disk/load_document_from_local_disk/load-document-from-local-disk-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
