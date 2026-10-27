---
title: "Seiten neu anordnen"
linkTitle: "Reorder pages"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "PDF-Seiten während der Renderung mit GroupDocs.Viewer für Python über .NET neu anordnen. Steuern Sie die Ausgabeseitenreihenfolge."
type: docs
url: /de/python-net/guides/reorder-pages/
is_root: false
weight: 100
---


GroupDocs.Viewer bewahrt die Seitenreihenfolge im Quelldokument. Stattdessen können Sie die Seiten im Ausgabedokument PDF neu anordnen.

Um Seiten neu anzuordnen, folgen Sie diesen Schritten:

1. Instanziieren Sie das [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer)-Objekt.
2. Erstellen Sie das [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions)-Objekt.
3. Rufen Sie die [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods)-Methode des [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer)-Objekts auf. Geben Sie die neue Seitenreihenfolge in den letzten Parametern an.

Das folgende Code‑Snippet zeigt, wie man Seiten neu anordnet:

{{< tabs \"example1\">}}
{{< tab \"Python\">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def reorder_pages():
    # Dokument laden
    with Viewer("sample.docx") as viewer:
        # Erstellen Sie Ansichtoptionen.
        viewOptions = PdfViewOptions("reorder_pages/reordered_pages.pdf")

        # Übergeben Sie Seitenzahlen in der Reihenfolge, in der Sie sie rendern möchten.
        viewer.view(viewOptions, [2, 1])

if __name__ == "__main__":
    reorder_pages()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/sample.docx), um sie herunterzuladen.

{{< /tab >}}
{{< tab \"reordered_pages.pdf\" >}}
```text
Binary file (PDF, 176 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/reorder_pages/reordered_pages.pdf)
{{< /tab >}}
{{< /tabs >}}
