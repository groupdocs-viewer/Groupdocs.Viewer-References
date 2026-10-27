---
title: "PDF-document beveiligen"
linkTitle: "Protect PDF document"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Beveilig PDF-uitvoer met wachtwoorden en permissies bij het renderen van documenten met GroupDocs.Viewer."
type: docs
url: /nl/python-net/guides/protect-pdf-document/
is_root: false
weight: 90
---


Je kunt een PDF-document beveiligen door de volgende parameters in te stellen:

* permissions
* password to open document
* password to change permissions

Om een PDF-document te beveiligen, volg deze stappen:

1. Maak een instantie van de [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) klasse. Geef het pad naar het brondocument op als constructorparameter.
2. Instantieer het [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security) object.
3. Om een wachtwoord op te geven om het document te openen, stel de eigenschap [DocumentOpenPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties) in.
4. Om een wachtwoord op te geven om beperkingen te wijzigen, stel de eigenschap [PermissionsPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties) in.
5. Om de documentrechten op te geven, stel de eigenschap [Permissions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/permissions) in.
6. Instantieer het [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) object. Geef het formaat van het opslagpad op voor het gerenderde document.
7. Initialiseert de eigenschap [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/#properties) van het [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) object met het object dat is aangemaakt in stappen 2-5.
8. Roep de methode [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) aan van het [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) object. Geef het [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) object op als parameter.

De volgende codefragment toont hoe u het uitvoer‑PDF‑document kunt beveiligen:

{{< tabs \"example1\">}}
{{< tab \"Python\">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

def protect_pdf_document():
    # Document laden
    with Viewer("sample.docx") as viewer:
        # Geef de beveiligingsinstellingen op.
        security = Security()
        security.document_open_password = "o123"
        security.permissions_password = "p123"
        security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

        # Maak een PDF‑bestand.
        pdf_options = PdfViewOptions("protect_pdf_document/protected_document.pdf")

        # Pas de beveiligingsinstellingen toe
        pdf_options.security = security
        viewer.view(pdf_options)

if __name__ == "__main__":
    protect_pdf_document()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/sample.docx) om het te downloaden.

{{< /tab >}}
{{< tab \"protected_document.pdf\" >}}
```text
Binary file (PDF, 238 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/protect_pdf_document/protected_document.pdf)
{{< /tab >}}
{{< /tabs >}}
