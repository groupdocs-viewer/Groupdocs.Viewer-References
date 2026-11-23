---
title: "Carica documento dal disco locale"
linkTitle: "Load from local disk"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Carica documenti dal tuo disco locale usando un percorso file con GroupDocs.Viewer per Python via .NET."
type: docs
url: /it/python-net/guides/load-document-from-local-disk/
is_root: false
weight: 50
---


Puoi caricare un documento da un disco locale usando il percorso di un file. GroupDocs.Viewer apre il file in modalità sola lettura.

Il seguente frammento di codice mostra come caricare un documento usando la stringa del percorso locale:

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_local_disk():
    # Carica documento dal disco locale
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_embedded_resources("load_document_from_local_disk/document_from_local_disk_{0}.html")
        viewer.view(html_options)

if __name__ == "__main__":
    load_document_from_local_disk()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-local-disk/sample.docx) per scaricarlo.

{{< /tab >}}
{{< tab \"load-document-from-local-disk-outputs.zip\" >}}
```text
load_document_from_local_disk/document_from_local_disk_1.html (317 KB)
load_document_from_local_disk/document_from_local_disk_2.html (149 KB)
load_document_from_local_disk/document_from_local_disk_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-local-disk/load_document_from_local_disk/load-document-from-local-disk-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
