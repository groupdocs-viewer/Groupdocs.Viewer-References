---
title: "Réorganiser les pages"
linkTitle: "Reorder pages"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Réorganisez les pages PDF lors du rendu avec GroupDocs.Viewer pour Python via .NET. Contrôlez la séquence des pages de sortie."
type: docs
url: /fr/python-net/guides/reorder-pages/
is_root: false
weight: 100
---


GroupDocs.Viewer préserve l'ordre des pages dans le document source. Vous pouvez toutefois réorganiser les pages dans le document PDF de sortie.

Pour réorganiser les pages, suivez ces étapes :

1. Instanciez l'objet [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer).
2. Créez l'objet [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions).
3. Appelez la méthode [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) de l'objet [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Spécifiez le nouvel ordre des pages dans les derniers paramètres.

Le fragment de code suivant montre comment réorganiser les pages :

{{< tabs \"example1\">}}
{{< tab \"Python\">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def reorder_pages():
    # Charger le document
    with Viewer("sample.docx") as viewer:
        # Créez les options de visualisation.
        viewOptions = PdfViewOptions("reorder_pages/reordered_pages.pdf")

        # Passez les numéros de page dans l'ordre dans lequel vous souhaitez les rendre.
        viewer.view(viewOptions, [2, 1])

if __name__ == "__main__":
    reorder_pages()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/sample.docx) pour le télécharger.

{{< /tab >}}
{{< tab \"reordered_pages.pdf\" >}}
```text
Binary file (PDF, 176 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/reorder_pages/reordered_pages.pdf)
{{< /tab >}}
{{< /tabs >}}
