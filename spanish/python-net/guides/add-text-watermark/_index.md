---
title: "Agregar marcas de agua de texto"
linkTitle: "Add text watermarks"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Agregue marcas de agua de texto a los documentos renderizados usando GroupDocs.Viewer en sus aplicaciones Python."
type: docs
url: /es/python-net/guides/add-text-watermark/
is_root: false
weight: 80
---


Para agregar una marca de agua a la salida HTML/JPG/PNG/PDF, siga estos pasos:

1. Cree una instancia de la clase [HtmlViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) (o [PngViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pngviewoptions/), o [JpgViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/), o [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/));
2. Cree un objeto [Watermark](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/watermark/) y rellene sus propiedades;
3. Llame al método [watermark](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/viewoptions/#properties) de la clase [HtmlViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) (o [PngViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pngviewoptions/), o [JpgViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/), o [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)) y especifique el objeto creado en el paso 2;
4. Llame al método [Viewer.view()](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods).

El siguiente fragmento de código muestra cómo aplicar la marca de agua a las páginas de salida.

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # Cargar documento
    with Viewer("sample.docx") as viewer:
        # Crear un archivo HTML.
        viewOptions = HtmlViewOptions.for_embedded_resources("add_text_watermark/output-watermark.html")
        # Agregar marca de agua.
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` es el archivo de muestra utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/add-text-watermark/sample.docx) para descargarlo.

{{< /tab >}}
{{< tab \"output-watermark.html\" >}}
```text
<!DOCTYPE html><html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8" /><meta name="generator" content="Aspose.Words for .NET 26.4.0" /><title>Sample Document ver.1</title><style type="text/css">@font-face { font-family:'Calibri'; font-style:normal; font-weight:normal; src:local('☺'), url('data:application/x-font-woff;base64,d09GRgABAAAAAGlIAA0AAAAA09gAAQAAAAAAAAAAAAAAAAAAAAAAAAAAAABPUy8yAAABMAAAAGAAAABgncM96GNtYXAAAAGQAAACswAABrCp8yKHY3Z0IAAABEQAAAKEAAAFvLlw2DVmcGdtAAAGy
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/add-text-watermark/add_text_watermark/output-watermark.html)
{{< /tab >}}
{{< /tabs >}}
