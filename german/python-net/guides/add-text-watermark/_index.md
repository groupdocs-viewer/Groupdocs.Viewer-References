---
title: "Textwasserzeichen hinzufügen"
linkTitle: "Add text watermarks"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Fügen Sie Textwasserzeichen zu gerenderten Dokumenten hinzu, indem Sie GroupDocs.Viewer in Ihren Python-Anwendungen verwenden."
type: docs
url: /de/python-net/guides/add-text-watermark/
is_root: false
weight: 80
---


Um ein Wasserzeichen zur HTML/JPG/PNG/PDF-Ausgabe hinzuzufügen, führen Sie die folgenden Schritte aus:

1. Erstellen Sie eine Instanz der Klasse [HtmlViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) (oder [PngViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pngviewoptions/), oder [JpgViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/), oder [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/));
2. Erstellen Sie ein [Watermark](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/watermark/)‑Objekt und füllen Sie dessen Eigenschaften aus;
3. Rufen Sie die Methode [watermark](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/viewoptions/#properties) der Klasse [HtmlViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) (oder [PngViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pngviewoptions/), oder [JpgViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/), oder [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)) auf und geben Sie das in Schritt 2 erstellte Objekt an;
4. Rufen Sie die Methode [Viewer.view()](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) auf.

Das folgende Code‑Snippet zeigt, wie das Wasserzeichen auf die Ausgabeseiten angewendet wird.

{{< tabs \"example1\">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # Dokument laden
    with Viewer("sample.docx") as viewer:
        # Eine HTML-Datei erstellen.
        viewOptions = HtmlViewOptions.for_embedded_resources("add_text_watermark/output-watermark.html")
        # Wasserzeichen hinzufügen.
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/add-text-watermark/sample.docx), um sie herunterzuladen.

{{< /tab >}}
{{< tab \"output-watermark.html\" >}}
```text
<!DOCTYPE html><html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8" /><meta name="generator" content="Aspose.Words for .NET 26.4.0" /><title>Sample Document ver.1</title><style type="text/css">@font-face { font-family:'Calibri'; font-style:normal; font-weight:normal; src:local('☺'), url('data:application/x-font-woff;base64,d09GRgABAAAAAGlIAA0AAAAA09gAAQAAAAAAAAAAAAAAAAAAAAAAAAAAAABPUy8yAAABMAAAAGAAAABgncM96GNtYXAAAAGQAAACswAABrCp8yKHY3Z0IAAABEQAAAKEAAAFvLlw2DVmcGdtAAAGy
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/add-text-watermark/add_text_watermark/output-watermark.html)
{{< /tab >}}
{{< /tabs >}}
