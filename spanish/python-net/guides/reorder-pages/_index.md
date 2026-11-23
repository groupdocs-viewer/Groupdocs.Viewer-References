---
title: "Reordenar páginas"
linkTitle: "Reorder pages"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Reordena las páginas PDF durante la renderización con GroupDocs.Viewer para Python a través de .NET. Controla la secuencia de páginas de salida."
type: docs
url: /es/python-net/guides/reorder-pages/
is_root: false
weight: 100
---


GroupDocs.Viewer conserva el orden de las páginas en el documento original. En su lugar, puedes reordenar las páginas en el documento PDF de salida.

Para reordenar páginas, siga estos pasos:

1. Instancie el objeto [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer).
2. Cree el objeto [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions).
3. Llame al método [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) del objeto [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Especifique el nuevo orden de páginas en los últimos parámetros.

El siguiente fragmento de código muestra cómo reordenar páginas:

{{< tabs \"example1\">}}
{{< tab \"Python\">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def reorder_pages():
    # Cargar documento
    with Viewer("sample.docx") as viewer:
        # Cree opciones de vista.
        viewOptions = PdfViewOptions("reorder_pages/reordered_pages.pdf")

        # Pase los números de página en el orden en que desea renderizarlos.
        viewer.view(viewOptions, [2, 1])

if __name__ == "__main__":
    reorder_pages()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` es el archivo de ejemplo utilizado en este caso. Haga clic [aquí](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/sample.docx) para descargarlo.

{{< /tab >}}
{{< tab \"reordered_pages.pdf\" >}}
```text
Binary file (PDF, 176 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/reorder_pages/reordered_pages.pdf)
{{< /tab >}}
{{< /tabs >}}
