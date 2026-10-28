---
title: "Läs in dokument från ström"
linkTitle: "Load from stream"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Läs in dokument direkt från ett fil‑liknande objekt — öppet filhandtag, BytesIO eller någon ström — med GroupDocs.Viewer för Python via .NET."
type: docs
url: /sv/python-net/guides/load-document-from-stream/
is_root: false
weight: 60
---


Du kan läsa in ett dokument från en ström utan att spara det som en fil på en disk. Du kan använda den här funktionen för att läsa in ett dokument från olika källor som en URL, FTP och så vidare.

För att läsa in ett dokument från en ström, följ dessa steg:

1. Implementera en metod för att hämta dokumentströmmen.
2. Anropa konstruktorn för klassen [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Ange den metod som implementerades i föregående steg.

Följande kodexempel visar hur man läser in ett dokument från en ström:

{{< tabs \"example1\">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_stream():
    # Öppna dokumentström
    stream = open("sample.docx", "rb")

    # Rendera ett dokument från strömmen.
    with Viewer(stream) as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    load_document_from_stream()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-stream/sample.docx) för att ladda ner den.

{{< /tab >}}
{{< tab "load-document-from-stream-outputs.zip" >}}
```text
page_1.html (317 KB)
page_2.html (149 KB)
page_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-stream/load_document_from_stream/load-document-from-stream-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

Se även [Load document from URL]() för ett konkret exempel på hur man laddar ner ett dokument till en `BytesIO`‑ström och renderar det utan att någonsin skriva det till en disk.
