---
title: "Riordina le pagine"
linkTitle: "Reorder pages"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Riordina le pagine PDF durante il rendering con GroupDocs.Viewer per Python tramite .NET. Controlla la sequenza delle pagine di output."
type: docs
url: /it/python-net/guides/reorder-pages/
is_root: false
weight: 100
---


GroupDocs.Viewer conserva l'ordine delle pagine nel documento di origine. In alternativa, puoi riordinare le pagine nel documento PDF di output.

Per riordinare le pagine, segui questi passaggi:

1. Istanzia l'oggetto [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer).
2. Crea l'oggetto [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions).
3. Chiama il metodo [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) dell'oggetto [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Specifica il nuovo ordine delle pagine negli ultimi parametri.

Il seguente frammento di codice mostra come riordinare le pagine:

{{< tabs \"example1\">}}
{{< tab \"Python\">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def reorder_pages():
    # Carica documento
    with Viewer("sample.docx") as viewer:
        # Crea le opzioni di visualizzazione.
        viewOptions = PdfViewOptions("reorder_pages/reordered_pages.pdf")

        # Passa i numeri di pagina nell'ordine in cui desideri renderizzarli.
        viewer.view(viewOptions, [2, 1])

if __name__ == "__main__":
    reorder_pages()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/sample.docx) per scaricarlo.

{{< /tab >}}
{{< tab \"reordered_pages.pdf\" >}}
```text
Binary file (PDF, 176 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/reorder_pages/reordered_pages.pdf)
{{< /tab >}}
{{< /tabs >}}
