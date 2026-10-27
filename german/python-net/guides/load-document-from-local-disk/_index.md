---
title: "Dokument von lokaler Festplatte laden"
linkTitle: "Load from local disk"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Laden Sie Dokumente von Ihrer lokalen Festplatte über einen Dateipfad mit GroupDocs.Viewer für Python via .NET."
type: docs
url: /de/python-net/guides/load-document-from-local-disk/
is_root: false
weight: 50
---


Sie können ein Dokument von einer lokalen Festplatte über einen Dateipfad laden. GroupDocs.Viewer öffnet die Datei im Nur‑Lese‑Modus.

Das folgende Code‑Snippet zeigt, wie man ein Dokument über den lokalen Pfad‑String lädt:

{{< tabs \"example1\">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_local_disk():
    # Dokument von lokaler Festplatte laden
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_embedded_resources("load_document_from_local_disk/document_from_local_disk_{0}.html")
        viewer.view(html_options)

if __name__ == "__main__":
    load_document_from_local_disk()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-local-disk/sample.docx) zum Herunterladen.

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
