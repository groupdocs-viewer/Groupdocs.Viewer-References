---
title: "Urutkan ulang halaman"
linkTitle: "Reorder pages"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Urutkan ulang halaman PDF selama proses rendering dengan GroupDocs.Viewer untuk Python via .NET. Kendalikan urutan halaman output."
type: docs
url: /id/python-net/guides/reorder-pages/
is_root: false
weight: 100
---


GroupDocs.Viewer mempertahankan urutan halaman dalam dokumen sumber. Sebagai gantinya, Anda dapat mengurutkan ulang halaman dalam dokumen PDF output.

Untuk mengubah urutan halaman, ikuti langkah-langkah berikut:

1. Buat instance objek [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer).
2. Buat objek [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions).
3. Panggil metode [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) dari objek [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Tentukan urutan halaman baru pada parameter terakhir.

Potongan kode berikut menunjukkan cara mengubah urutan halaman:

{{< tabs "example1">}}
{{< tab "Python">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def reorder_pages():
    # Muat dokumen
    with Viewer("sample.docx") as viewer:
        # Buat opsi tampilan.
        viewOptions = PdfViewOptions("reorder_pages/reordered_pages.pdf")

        # Berikan nomor halaman dalam urutan yang ingin Anda render.
        viewer.view(viewOptions, [2, 1])

if __name__ == "__main__":
    reorder_pages()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/sample.docx) untuk mengunduhnya.

{{< /tab >}}
{{< tab "reordered_pages.pdf" >}}
```text
Binary file (PDF, 176 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/reorder_pages/reordered_pages.pdf)
{{< /tab >}}
{{< /tabs >}}
