---
title: "PDF belgesini koruyun"
linkTitle: "Protect PDF document"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "GroupDocs.Viewer kullanarak belgeleri renderlerken PDF çıktısını şifreler ve izinlerle güvenceye alın."
type: docs
url: /tr/python-net/guides/protect-pdf-document/
is_root: false
weight: 90
---


Aşağıdaki parametreleri ayarlayarak bir PDF belgesini koruyabilirsiniz:

* permissions
* password to open document
* password to change permissions

PDF belgesini korumak için şu adımları izleyin:

1. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) sınıfının bir örneğini oluşturun. Kaynak belge yolunu kurucu parametresi olarak belirtin.
2. [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security) nesnesini örnekleyin.
3. Belgeyi açmak için bir şifre belirtmek üzere, [DocumentOpenPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties) özelliğini ayarlayın.
4. Kısıtlamaları değiştirmek için bir şifre belirtmek üzere, [PermissionsPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties) özelliğini ayarlayın.
5. Belge izinlerini belirtmek için, [Permissions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/permissions) özelliğini ayarlayın.
6. [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) nesnesini örnekleyin. Oluşturulan belge için kaydetme yolu biçimini belirtin.
7. [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) nesnesinin [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/#properties) özelliğini, adım 2-5'te oluşturulan nesneyle başlatın.
8. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) nesnesinin [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) metodunu çağırın. Parametre olarak [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) nesnesini belirtin.

Aşağıdaki kod parçacığı, çıktı PDF belgesini nasıl koruyacağınızı gösterir:

{{< tabs \"example1\">}}
{{< tab \"Python\">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

def protect_pdf_document():
    # Belgeyi yükle
    with Viewer("sample.docx") as viewer:
        # Güvenlik ayarlarını belirtin.
        security = Security()
        security.document_open_password = "o123"
        security.permissions_password = "p123"
        security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

        # Bir PDF dosyası oluşturun.
        pdf_options = PdfViewOptions("protect_pdf_document/protected_document.pdf")

        # Güvenlik ayarlarını uygulayın
        pdf_options.security = security
        viewer.view(pdf_options)

if __name__ == "__main__":
    protect_pdf_document()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/sample.docx) tıklayın.

{{< /tab >}}
{{< tab \"protected_document.pdf\" >}}
```text
Binary file (PDF, 238 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/protect_pdf_document/protected_document.pdf)
{{< /tab >}}
{{< /tabs >}}
