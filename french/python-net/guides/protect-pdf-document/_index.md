---
title: "Protéger le document PDF"
linkTitle: "Protect PDF document"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Sécurisez la sortie PDF avec des mots de passe et des autorisations lors du rendu de documents avec GroupDocs.Viewer."
type: docs
url: /fr/python-net/guides/protect-pdf-document/
is_root: false
weight: 90
---


Vous pouvez protéger un document PDF en définissant les paramètres suivants :

* permissions
* password to open document
* password to change permissions

Pour protéger un document PDF, suivez ces étapes :

1. Créez une instance de la classe [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Spécifiez le chemin du document source comme paramètre du constructeur.
2. Instanciez l'objet [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security).
3. Pour spécifier un mot de passe afin d'ouvrir le document, définissez la propriété [DocumentOpenPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties).
4. Pour spécifier un mot de passe afin de modifier les restrictions, définissez la propriété [PermissionsPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties).
5. Pour spécifier les autorisations du document, définissez la propriété [Permissions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/permissions).
6. Instanciez l'objet [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions). Spécifiez le format du chemin de sauvegarde pour le document rendu.
7. Initialisez la propriété [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/#properties) de l'objet [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) avec l'objet créé aux étapes 2 à 5.
8. Appelez la méthode [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) de l'objet [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Spécifiez l'objet [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) comme paramètre.

Le fragment de code suivant montre comment protéger le document PDF de sortie:

{{< tabs \"example1\">}}
{{< tab \"Python\">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

def protect_pdf_document():
    # Charger le document
    with Viewer("sample.docx") as viewer:
        # Spécifiez les paramètres de sécurité.
        security = Security()
        security.document_open_password = "o123"
        security.permissions_password = "p123"
        security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

        # Créez un fichier PDF.
        pdf_options = PdfViewOptions("protect_pdf_document/protected_document.pdf")

        # Appliquez les paramètres de sécurité
        pdf_options.security = security
        viewer.view(pdf_options)

if __name__ == "__main__":
    protect_pdf_document()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` est le fichier d'exemple utilisé dans cet exemple. Cliquez sur [ici](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/sample.docx) pour le télécharger.

{{< /tab >}}
{{< tab \"protected_document.pdf\" >}}
```text
Binary file (PDF, 238 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/protect_pdf_document/protected_document.pdf)
{{< /tab >}}
{{< /tabs >}}
