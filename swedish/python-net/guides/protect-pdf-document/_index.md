---
title: "Skydda PDF-dokument"
linkTitle: "Protect PDF document"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Säkra PDF-utdata med lösenord och behörigheter när du renderar dokument med GroupDocs.Viewer."
type: docs
url: /sv/python-net/guides/protect-pdf-document/
is_root: false
weight: 90
---


Du kan skydda ett PDF-dokument genom att ange följande parametrar:

* permissions
* password to open document
* password to change permissions

För att skydda ett PDF-dokument, följ dessa steg:

1. Skapa en instans av klassen [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Ange källdokumentets sökväg som en konstruktorparameter.
2. Instansiera objektet [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security).
3. För att ange ett lösenord för att öppna dokumentet, sätt egenskapen [DocumentOpenPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties).
4. För att ange ett lösenord för att ändra begränsningar, sätt egenskapen [PermissionsPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties).
5. För att ange dokumentbehörigheterna, sätt egenskapen [Permissions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/permissions).
6. Instansiera objektet [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions). Ange formatet för sparvägen för det renderade dokumentet.
7. Initiera egenskapen [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/#properties) i objektet [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) med objektet som skapades i steg 2‑5.
8. Anropa metoden [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) i objektet [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Ange objektet [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) som parameter.

Följande kodsnutt visar hur man skyddar den genererade PDF-dokumentet:

{{< tabs \"example1\">}}
{{< tab \"Python\">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

def protect_pdf_document():
    # Läs in dokument
    with Viewer("sample.docx") as viewer:
        # Ange säkerhetsinställningarna.
        security = Security()
        security.document_open_password = "o123"
        security.permissions_password = "p123"
        security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

        # Skapa en PDF-fil.
        pdf_options = PdfViewOptions("protect_pdf_document/protected_document.pdf")

        # Tillämpa säkerhetsinställningarna
        pdf_options.security = security
        viewer.view(pdf_options)

if __name__ == "__main__":
    protect_pdf_document()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/sample.docx) för att ladda ner den.

{{< /tab >}}
{{< tab "protected_document.pdf" >}}
```text
Binary file (PDF, 238 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/protect_pdf_document/protected_document.pdf)
{{< /tab >}}
{{< /tabs >}}
