---
title: "Muat dokumen dari aliran"
linkTitle: "Load from stream"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Muat dokumen secara langsung dari objek mirip file — handle file terbuka, BytesIO, atau aliran apa pun — dengan GroupDocs.Viewer untuk Python via .NET."
type: docs
url: /id/python-net/guides/load-document-from-stream/
is_root: false
weight: 60
---


Anda dapat memuat dokumen dari aliran tanpa menyimpannya sebagai file di disk. Anda dapat menggunakan fitur ini untuk memuat dokumen dari berbagai sumber seperti URL, FTP, dan sebagainya.

Untuk memuat dokumen dari aliran, ikuti langkah-langkah berikut:

1. Implementasikan metode untuk mendapatkan aliran dokumen.
2. Panggil konstruktor kelas [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Tentukan metode yang diimplementasikan pada langkah sebelumnya.

Potongan kode berikut menunjukkan cara memuat dokumen dari aliran:

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_stream():
    # Buka aliran dokumen
    stream = open("sample.docx", "rb")

    # Render sebuah dokumen dari aliran.
    with Viewer(stream) as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    load_document_from_stream()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-stream/sample.docx) untuk mengunduhnya.

{{< /tab >}}
{{< tab "load-document-from-stream-outputs.zip" >}}
```text
page_1.html (317 KB)
page_2.html (149 KB)
page_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-stream/load_document_from_stream/load-document-from-stream-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

Lihat juga [Load document from URL]() untuk contoh konkret mengunduh dokumen ke dalam aliran `BytesIO` dan merendernya tanpa pernah menulis ke disk.
