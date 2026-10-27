---
title: "Document laden vanuit stream"
linkTitle: "Load from stream"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Laad documenten direct vanuit een bestand-achtig object — open bestandshandle, BytesIO of elke stream — met GroupDocs.Viewer voor Python via .NET."
type: docs
url: /nl/python-net/guides/load-document-from-stream/
is_root: false
weight: 60
---


U kunt een document vanuit een stream laden zonder het als bestand op schijf op te slaan. U kunt deze functie gebruiken om een document te laden vanuit verschillende bronnen, zoals een URL, FTP, enzovoort.

Om een document vanuit een stream te laden, volg deze stappen:

1. Implementeer een methode om de document‑stream op te halen.
2. Roep de [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) klasse‑constructor aan. Geef de in de vorige stap geïmplementeerde methode op.

Het volgende codefragment toont hoe een document vanuit een stream kan worden geladen:

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_stream():
    # Open document‑stream
    stream = open("sample.docx", "rb")

    # Render een document vanuit de stream.
    with Viewer(stream) as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    load_document_from_stream()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-stream/sample.docx) om het te downloaden.

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

Zie ook [Load document from URL]() voor een concreet voorbeeld van het downloaden van een document naar een `BytesIO`‑stream en het renderen ervan zonder het ooit op schijf te schrijven.
