---
title: "Dokument aus Stream laden"
linkTitle: "Load from stream"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Laden Sie Dokumente direkt aus einem dateiähnlichen Objekt — geöffneten Dateihandle, BytesIO oder einem beliebigen Stream — mit GroupDocs.Viewer für Python über .NET."
type: docs
url: /de/python-net/guides/load-document-from-stream/
is_root: false
weight: 60
---


Sie können ein Dokument aus einem Stream laden, ohne es als Datei auf der Festplatte zu speichern. Diese Funktion können Sie nutzen, um ein Dokument aus verschiedenen Quellen wie einer URL, FTP usw. zu laden.

Um ein Dokument aus einem Stream zu laden, folgen Sie diesen Schritten:

1. Implementieren Sie eine Methode, um den Dokumenten‑Stream zu erhalten.
2. Rufen Sie den Konstruktor der Klasse [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) auf. Geben Sie die im vorherigen Schritt implementierte Methode an.

Das folgende Code‑Snippet zeigt, wie man ein Dokument aus einem Stream lädt:

{{< tabs \"example1\">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_stream():
    # Dokumentstream öffnen
    stream = open("sample.docx", "rb")

    # Ein Dokument aus dem Stream rendern.
    with Viewer(stream) as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    load_document_from_stream()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-stream/sample.docx) zum Herunterladen.

{{< /tab >}}
{{< tab \"load-document-from-stream-outputs.zip\" >}}
```text
page_1.html (317 KB)
page_2.html (149 KB)
page_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-stream/load_document_from_stream/load-document-from-stream-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

Siehe auch [Load document from URL](), für ein konkretes Beispiel, wie ein Dokument in einen `BytesIO`‑Stream heruntergeladen und gerendert wird, ohne es jemals auf die Festplatte zu schreiben.
