---
title: "PDF-Dokument schützen"
linkTitle: "Protect PDF document"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Sichern Sie die PDF-Ausgabe mit Passwörtern und Berechtigungen beim Rendern von Dokumenten mit GroupDocs.Viewer."
type: docs
url: /de/python-net/guides/protect-pdf-document/
is_root: false
weight: 90
---


Sie können ein PDF-Dokument schützen, indem Sie die folgenden Parameter festlegen:

* permissions
* password to open document
* password to change permissions

Um ein PDF-Dokument zu schützen, folgen Sie diesen Schritten:

1. Erstellen Sie eine Instanz der Klasse [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Geben Sie den Pfad des Quelldokuments als Konstruktorparameter an.
2. Instanziieren Sie das Objekt [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security).
3. Um ein Passwort zum Öffnen des Dokuments festzulegen, setzen Sie die Eigenschaft [DocumentOpenPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties).
4. Um ein Passwort zum Ändern von Einschränkungen festzulegen, setzen Sie die Eigenschaft [PermissionsPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties).
5. Um die Dokumentberechtigungen festzulegen, setzen Sie die Eigenschaft [Permissions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/permissions).
6. Instanziieren Sie das Objekt [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions). Geben Sie das Format des Speicherpfads für das gerenderte Dokument an.
7. Initialisieren Sie die Eigenschaft [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/#properties) des Objekts [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) mit dem in den Schritten 2‑5 erstellten Objekt.
8. Rufen Sie die Methode [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) des Objekts [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) auf. Geben Sie das Objekt [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) als Parameter an.

Das folgende Code‑Snippet zeigt, wie das ausgegebene PDF‑Dokument geschützt wird:

{{< tabs \"example1\">}}
{{< tab \"Python\">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

def protect_pdf_document():
    # Dokument laden
    with Viewer("sample.docx") as viewer:
        # Geben Sie die Sicherheitseinstellungen an.
        security = Security()
        security.document_open_password = "o123"
        security.permissions_password = "p123"
        security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

        # Erstellen Sie eine PDF‑Datei.
        pdf_options = PdfViewOptions("protect_pdf_document/protected_document.pdf")

        # Wenden Sie die Sicherheitseinstellungen an
        pdf_options.security = security
        viewer.view(pdf_options)

if __name__ == "__main__":
    protect_pdf_document()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/sample.docx), um sie herunterzuladen.

{{< /tab >}}
{{< tab "protected_document.pdf" >}}
```text
Binary file (PDF, 238 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/protect_pdf_document/protected_document.pdf)
{{< /tab >}}
{{< /tabs >}}
