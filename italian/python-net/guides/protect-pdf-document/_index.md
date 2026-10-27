---
title: "Proteggi documento PDF"
linkTitle: "Protect PDF document"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Proteggi l'output PDF con password e permessi durante il rendering dei documenti usando GroupDocs.Viewer."
type: docs
url: /it/python-net/guides/protect-pdf-document/
is_root: false
weight: 90
---


Puoi proteggere un documento PDF impostando i seguenti parametri:

* permissions
* password to open document
* password to change permissions

Per proteggere un documento PDF, segui questi passaggi:

1. Crea un'istanza della classe [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Specifica il percorso del documento sorgente come parametro del costruttore.
2. Istanzia l'oggetto [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security).
3. Per specificare una password per aprire il documento, imposta la proprietà [DocumentOpenPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties).
4. Per specificare una password per modificare le restrizioni, imposta la proprietà [PermissionsPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties).
5. Per specificare le autorizzazioni del documento, imposta la proprietà [Permissions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/permissions).
6. Istanzia l'oggetto [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions). Specifica il formato del percorso di salvataggio per il documento renderizzato.
7. Inizializza la proprietà [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/#properties) dell'oggetto [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) con l'oggetto creato nei passaggi 2-5.
8. Chiama il metodo [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) dell'oggetto [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Specifica l'oggetto [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) come parametro.

Il seguente frammento di codice mostra come proteggere il documento PDF di output:

{{< tabs \"example1\">}}
{{< tab \"Python\">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

def protect_pdf_document():
    # Carica documento
    with Viewer("sample.docx") as viewer:
        # Specifica le impostazioni di sicurezza.
        security = Security()
        security.document_open_password = "o123"
        security.permissions_password = "p123"
        security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

        # Crea un file PDF.
        pdf_options = PdfViewOptions("protect_pdf_document/protected_document.pdf")

        # Applica le impostazioni di sicurezza
        pdf_options.security = security
        viewer.view(pdf_options)

if __name__ == "__main__":
    protect_pdf_document()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` è il file di esempio utilizzato in questo esempio. Fai clic su [qui](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/sample.docx) per scaricarlo.

{{< /tab >}}
{{< tab "protected_document.pdf" >}}
```text
Binary file (PDF, 238 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/protect_pdf_document/protected_document.pdf)
{{< /tab >}}
{{< /tabs >}}
