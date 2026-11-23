---
title: "Pagina's herschikken"
linkTitle: "Reorder pages"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Herschik PDF‑pagina's tijdens het renderen met GroupDocs.Viewer voor Python via .NET. Beheer de volgorde van de uitvoerpagina's."
type: docs
url: /nl/python-net/guides/reorder-pages/
is_root: false
weight: 100
---


GroupDocs.Viewer behoudt de paginavolgorde in het brondocument. In plaats daarvan kun je pagina's herschikken in het uitvoer‑PDF‑document.

Om pagina's te herschikken, volg deze stappen:

1. Maak een instantie van het [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) object.
2. Maak het [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) object.
3. Roep de [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) methode van het [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) object aan. Geef de nieuwe paginavolgorde op in de laatste parameters.

De volgende codefragment toont hoe pagina's te herschikken:

{{< tabs \"example1\">}}
{{< tab \"Python\">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def reorder_pages():
    # Document laden
    with Viewer("sample.docx") as viewer:
        # Maak view-opties aan.
        viewOptions = PdfViewOptions("reorder_pages/reordered_pages.pdf")

        # Geef paginanummers door in de volgorde waarin je ze wilt renderen.
        viewer.view(viewOptions, [2, 1])

if __name__ == "__main__":
    reorder_pages()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/sample.docx) om het te downloaden.

{{< /tab >}}
{{< tab \"reordered_pages.pdf\" >}}
```text
Binary file (PDF, 176 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/reorder_pages/reordered_pages.pdf)
{{< /tab >}}
{{< /tabs >}}
