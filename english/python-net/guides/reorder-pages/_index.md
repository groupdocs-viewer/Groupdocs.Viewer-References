---
title: Reorder pages
linkTitle: "Reorder pages"
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Reorder PDF pages during rendering with GroupDocs.Viewer for Python via .NET. Control the output page sequence."
type: docs
url: /python-net/guides/reorder-pages/
is_root: false
weight: 100
---


GroupDocs.Viewer preserves the page order in the source document. Instead, you may reorder pages in the output PDF document.

To reorder pages, follow these steps:

1. Instantiate the [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) object.
2. Create the [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) object.
3. Call the [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) method of the [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) object. Specify the new page order in the last parameters.

The following code snippet shows how to reorder pages:

{{< tabs "example1">}}
{{< tab "Python">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def reorder_pages():
    # Load document
    with Viewer("sample.docx") as viewer:
        # Create view options.
        viewOptions = PdfViewOptions("reorder_pages/reordered_pages.pdf")

        # Pass page numbers in the order you want to render them.
        viewer.view(viewOptions, [2, 1])

if __name__ == "__main__":
    reorder_pages()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/sample.docx) to download it.

{{< /tab >}}
{{< tab "reordered_pages.pdf" >}}  
```text
Binary file (PDF, 176 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/reorder_pages/reordered_pages.pdf)
{{< /tab >}}
{{< /tabs >}}
