---
title: "Ordna om sidor"
linkTitle: "Reorder pages"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Ordna om PDF-sidor under rendering med GroupDocs.Viewer för Python via .NET. Kontrollera sekvensen för utdata-sidorna."
type: docs
url: /sv/python-net/guides/reorder-pages/
is_root: false
weight: 100
---


GroupDocs.Viewer bevarar sidordningen i källdokumentet. Istället kan du ordna om sidor i utdata-PDF-dokumentet.

För att ordna om sidor, följ dessa steg:

1. Instansiera objektet [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer).
2. Skapa objektet [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions).
3. Anropa metoden [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) på objektet [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Ange den nya sidordningen i de sista parametrarna.

Följande kodsnutt visar hur man ordnar om sidor:

{{< tabs \"example1\">}}
{{< tab \"Python\">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def reorder_pages():
    # Läs in dokument
    with Viewer("sample.docx") as viewer:
        # Skapa visningsalternativ.
        viewOptions = PdfViewOptions("reorder_pages/reordered_pages.pdf")

        # Skicka sidnummer i den ordning du vill rendera dem.
        viewer.view(viewOptions, [2, 1])

if __name__ == "__main__":
    reorder_pages()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/sample.docx) för att ladda ner den.

{{< /tab >}}
{{< tab \"reordered_pages.pdf\" >}}
```text
Binary file (PDF, 176 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/reorder_pages/reordered_pages.pdf)
{{< /tab >}}
{{< /tabs >}}
