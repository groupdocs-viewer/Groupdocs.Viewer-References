---
title: "Muat dokumen dari disk lokal"
linkTitle: "Load from local disk"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Muat dokumen dari disk lokal Anda menggunakan jalur file dengan GroupDocs.Viewer untuk Python via .NET."
type: docs
url: /id/python-net/guides/load-document-from-local-disk/
is_root: false
weight: 50
---


Anda dapat memuat dokumen dari disk lokal menggunakan jalur ke sebuah file. GroupDocs.Viewer membuka file dalam mode hanya-baca.

Potongan kode berikut menunjukkan cara memuat dokumen menggunakan string jalur lokal:

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_local_disk():
    # Muat dokumen dari disk lokal
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_embedded_resources("load_document_from_local_disk/document_from_local_disk_{0}.html")
        viewer.view(html_options)

if __name__ == "__main__":
    load_document_from_local_disk()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-local-disk/sample.docx) untuk mengunduhnya.

{{< /tab >}}
{{< tab "load-document-from-local-disk-outputs.zip" >}}
```text
load_document_from_local_disk/document_from_local_disk_1.html (317 KB)
load_document_from_local_disk/document_from_local_disk_2.html (149 KB)
load_document_from_local_disk/document_from_local_disk_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-local-disk/load_document_from_local_disk/load-document-from-local-disk-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
