---
title: "Lindungi dokumen PDF"
linkTitle: "Protect PDF document"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Amankan output PDF dengan kata sandi dan izin saat merender dokumen menggunakan GroupDocs.Viewer."
type: docs
url: /id/python-net/guides/protect-pdf-document/
is_root: false
weight: 90
---


Anda dapat melindungi dokumen PDF dengan mengatur parameter berikut:

* permissions
* password to open document
* password to change permissions

Untuk melindungi dokumen PDF, ikuti langkah-langkah berikut:

1. Buat instance kelas [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Tentukan path dokumen sumber sebagai parameter konstruktor.
2. Buat instance objek [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security).
3. Untuk menentukan kata sandi membuka dokumen, setel properti [DocumentOpenPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties).
4. Untuk menentukan kata sandi mengubah pembatasan, setel properti [PermissionsPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties).
5. Untuk menentukan izin dokumen, setel properti [Permissions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/permissions).
6. Buat instance objek [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions). Tentukan format jalur penyimpanan untuk dokumen yang dirender.
7. Inisialisasi properti [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/#properties) dari objek [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) dengan objek yang dibuat pada langkah 2-5.
8. Panggil metode [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) dari objek [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Tentukan objek [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) sebagai parameter.

Potongan kode berikut menunjukkan cara melindungi dokumen PDF output:

{{< tabs "example1">}}
{{< tab "Python">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

def protect_pdf_document():
    # Muat dokumen
    with Viewer("sample.docx") as viewer:
        # Tentukan pengaturan keamanan.
        security = Security()
        security.document_open_password = "o123"
        security.permissions_password = "p123"
        security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

        # Buat file PDF.
        pdf_options = PdfViewOptions("protect_pdf_document/protected_document.pdf")

        # Terapkan pengaturan keamanan
        pdf_options.security = security
        viewer.view(pdf_options)

if __name__ == "__main__":
    protect_pdf_document()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/sample.docx) untuk mengunduhnya.

{{< /tab >}}
{{< tab \"protected_document.pdf\" >}}
```text
Binary file (PDF, 238 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/protect_pdf_document/protected_document.pdf)
{{< /tab >}}
{{< /tabs >}}
