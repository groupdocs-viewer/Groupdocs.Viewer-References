---
title: "Document laden vanaf lokale schijf"
linkTitle: "Load from local disk"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Laad documenten vanaf uw lokale schijf met een bestandspad met GroupDocs.Viewer voor Python via .NET."
type: docs
url: /nl/python-net/guides/load-document-from-local-disk/
is_root: false
weight: 50
---


U kunt een document vanaf een lokale schijf laden met een pad naar een bestand. GroupDocs.Viewer opent het bestand in de alleen-lezen modus.

De volgende codefragment toont hoe een document te laden met de lokale pad‑string:

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_local_disk():
    # Document laden vanaf lokale schijf
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_embedded_resources("load_document_from_local_disk/document_from_local_disk_{0}.html")
        viewer.view(html_options)

if __name__ == "__main__":
    load_document_from_local_disk()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-local-disk/sample.docx) om het te downloaden.

{{< /tab >}}
{{< tab "load-document-from-local-disk-outputs.zip" >}}
```text
load_document_from_local_disk/document_from_local_disk_1.html (317 KB)
load_document_from_local_disk/document_from_local_disk_2.html (149 KB)
load_document_from_local_disk/document_from_local_disk_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-local-disk/load_document_from_local_disk/load-document-from-local-disk-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
